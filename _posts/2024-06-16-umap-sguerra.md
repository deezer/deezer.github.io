---
layout: post
title: "Uncertainty in Repeated Implicit Feedback as a Measure of Reliability"
date: 2025-06-16 10:00:00 +0200
category: Publication
author: bmassonisguerra
readtime: 6
people:
 - bmassonisguerra
 - vatran
 - rhennequin
 - mmoussallam
publication_type: conference
publication_title: "Uncertainty in Repeated Implicit Feedback as a Measure of Reliability"
publication_year: 2025
publication_authors: B. Sguerra, V. Tran, R. Hennequin, M. Moussallam
publication_conference: "UMAP"
publication_code: "https://github.com/deezer/uncertainty_feedback"
publication_preprint: "https://arxiv.org/pdf/2505.02492"
domains: 
domains: 
 - RECSYS
---

In recommender systems, feedback usually comes in two forms. Explicit feedback is when users directly state their preferences, for example through ratings or reviews. Implicit feedback is inferred from their actions. At Deezer, most of the feedback users leave behind is implicit: listening to a song counts as positive, while skipping it counts as negative. A skip usually means dropping the track before the 30-second mark. The challenge is that implicit feedback is noisy, which makes it harder to build accurate models of user preferences.

One particularity about music consumption is repetition: people repeat songs a lot. Compared to other media like movies or books, repetition in music is off the charts. And every time we hit replay, different things can happen in our brains. Sometimes a few listens are enough to make a track "click". Psychologists call this the mere exposure effect, the idea that familiarity makes us like something more. That is why a song you hear in a TikTok or at the supermarket can suddenly become your new favorite. But there is also a downside: play a song too much and you eventually get bored and start dropping it.

This brings us to the main idea of our work: can these repetitive listening patterns help us measure uncertainty in user feedback? In other words, can these patterns reveal which actions reflect real interest and which are just noise?

When we look at how people repeat songs, both in terms of the number of times they listen (play count) and the time between listens, we start to see some trends. For example, the likelihood of replaying a song (that someone ends up enjoying it) grows up to around ten plays, then slowly drops as overexposure sets in. Timing matters too: after about a day, people are very likely to replay the same track, often because they are in the same context as the day before, such as working, commuting, or doing sports. These patterns create areas in the play count x time interval space where listening behavior is more predictable than in others.

To capture this, we use a simple Bayesian model that quantifies uncertainty in user feedback. Each interaction is represented by a pair (play count x time interval), and the listening tendency is modeled with a Beta distribution. The Bayesian approach has two big advantages: it allows us to incorporate prior beliefs and it naturally provides a measure of uncertainty after updating with data.

As we collect more interactions for a given pair, the prior distribution gets updated into a posterior distribution. This posterior reflects both prior knowledge and the observed data. From it, we can estimate how likely users are to listen, and just as importantly, how confident we are in that estimate. We use the highest density interval (HDI) to capture the range where most of the probability mass lies, giving us a direct measure of certainty.

<div class="publication-illustration">
    <img
        style="width: 95%;"
        src="{{ '/static/images/publis/sguerra25umap/uncertainty1.jpg' | prepend: site.url }}"
        alt="Overview of the methodology."/>
</div>

Practically, we split the space into discrete play count x time interval bins, each starting with a weak prior. As user data comes in, we update these priors to get posterior distributions across the whole space. 

<div class="publication-illustration">
    <img
        style="width: 95%;"
        src="{{ '/static/images/publis/sguerra25umap/uncertainty2.jpg' | prepend: site.url }}"
        alt="Overview of the methodology."/>
</div>

The results are intuitive. For example a user replaying a track for the ninth time with a one-day gap shows a strong, repeatable pattern, while listening to a track forty times with very long gaps is much less consistent. The posteriors capture this difference, allowing us to pinpoint reliable signals from noisy outliers.

<div class="publication-illustration">
    <img
        style="width: 95%;"
        src="{{ '/static/images/publis/sguerra25umap/uncertainty3.jpg' | prepend: site.url }}"
        alt="Overview of the methodology."/>
</div>

By weighting interactions according to their uncertainty, we can downplay the noisy ones and let the recommender system focus on the interactions that really matter. In practice, this means paying more attention to reliable signals and less to noisy ones. And when we tested this approach on two different datasets, the outcome was clear: explicitly modeling uncertainty in feedback led to better recommendation performance.
 
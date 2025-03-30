---
layout: post
title: "Post II"
description: "My new blog"
date: 2025-03-30
categories: blog
theme: "jekyll-theme-minima"
url: "https://kirstinbosch.github.io/data_snoop"
baseurl: "/data_snoop"

---
Micro-goal: 3 hours of statistics a day for 30 days
terms: sample space, element, outcome, event (set), union, intersection, special events (null event/empty set, whole sample space, probability measure, axioms of probability, mutually exclusive events, independent events, classical (frequentist) approach, bayesian approach

![Alt text](/_images/inclusion_exclusion.png)

Example: Music Recommendation System with Collaborative Filtering

collaborative filtering - make recommendations based on user behavior and preferences

Objective is to predict the probability of a user liking a specific song or artists, given that they already like another artist or genre. inclusion-exclusion used principle used to refine this probability

P(A): 0.8 probability that a user likes a particular artist (based on listening habits)
P(B): 0.7 probability that the same user likes a particular genre
P(A n B): 0.5 probability that a user likes both a particular artist and genre. (overlapping of preferences)
Then P(A u B) = 0.8 + 0.7 - 0.5 = 1.0
Therefore, there is 100% chance that the user will like either the artist or the genre, or both, based on their history
Then --> P(A n B) + P(A u B) = P(A) + P(B)
0.5 + 1.0 = 0.8 + 0.7
1.5 = 1.5






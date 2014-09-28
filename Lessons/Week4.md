---
layout: default
title: Week 4: Questionnaire Design I
ghurl: https://github.com/leeper/surveycourse/tree/gh-pages
---

# Questionnaire Design I #

## Outline ##

  - Continue stratified sampling from last week

  - Cluster sampling (equal cluster sizes)
     - Why do we cluster sample?
       - Cost/feasibility
       - Not able to enumerate the actual units we care about
         - Example: We can enumerate blocks but not households or classrooms but not students
       - Population is structured in clusters
         - Example: students in classrooms in teachers in schools
         - Depending on research question, this also gives us nice estimates for each cluster (e.g., municipality-level opinion)
     - Examples:
       - Random sample of population of South Sudan (most people do not have telephones or computers)
       - Random sample of municipality politicians in face-to-face interviews
       - Random sample of population of Champions League football players (clustered within teams)
     - Design effect
       - Definition: ratio of the sampling for a statistic computed on this design divided by sampling variance obtained from an SRS of the same sample size ($n_SRS$).
       - How much are we inflating our uncertainty due to choosing an easier-to-conduct study?
       - Trade-off: we can change the design, but cost considerations weigh against design effect
     - Design effect depends on cluster homogeneity and within-cluster sample size
       - Within-cluster sample size (when clusters are heterogeneous) exacerbates heterogeneity
       - Examples:
         - Students are ability grouped in classrooms, not random draws from the whole population
         - Municipalities have different partisan/ideological compositions, so not representative
       - $\roh$
       - Effective sample size: $\frac{n}{d^2}$
     - Variation in cluster size
       - Examples:
         - Classrooms vary slightly in size (even if there's a minimum or maximum class size)
         - Municipalities vary in population
         - A residential street varies in housing units depending on housing type (apartment, houses, etc.)
       - Variation in cluster size can create problems
         - Unequal probabilities of selection if a fixed "second-stage" fraction is used (thus raw sample is not representative)
         - If variance in cluster size is large, a fixed "second-stage" sampling fraction can produce vastly different sample sizes (and associated costs and variances)
  - Combining stratified and cluster sampling
    - Example: Population of Denmark, stratified by region, and clustered samples w/in region
  - Discuss Burnham et al. article
  - Questionnaire Design
    - Opinion questions
    - Activity: designing opinion questions
  - Preview of next week: Questionnaire Design II
    - Assignment
      - What are the concepts/constructs you need to measure in your survey?
    - New topics
      - Truth/validity
      - Sensitive questions
      - Memory
      - Social desirability

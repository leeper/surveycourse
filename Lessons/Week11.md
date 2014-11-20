---
layout: default
title: Week 11: Data Management
ghurl: https://github.com/leeper/surveycourse/tree/gh-pages
---

# Data Management #

## Outline ##

 - Missing data
   - Sources
     - Nonresponse
     - Attrition
     - Data loss
   - Impacts
     - Effective sample size and sampling variance
     - Scale construction
     - Bias
   
 - Missing data imputation
   - Why imputation?
     - Casewise deletion results in huge loss of information due to small missingness
     - 
   - Assumptions
     - Missing completely at random
     - Missing at random
     - Missing not at random
   - Single imputation
     - Mean imputation (grand mean, subgroup mean, interpolation in a panel)
     - Top or bottom category imputation
     - Random imputation
     - Hot deck imputation
   - Multiple imputation
   
 - Weighting
   - Sampling designs assign different selection probabilities to different units
     - Self-weighting samples are nice because the analysis is simple
     - SRS, proportional allocation stratified sampling, opt-in samples
   - Disproportionate, cluster, and multi-stage sampling produce varying selection probabilities
     - Analysis has to involve weighted data
     - 
   - Sampling design is not the only reason to weight
     - Undercoverage in our sampling frame
     - Intentional oversamples of particular subpopulations
     - Missing data (unit nonresponse, item nonresponse, breakoff, attrition)
     - Nonprobability sample is not descriptively representative
   - Kinds of weighting
     - Ratio adjustment
     - Selection probabilities (i.e., sampling design)
     - Nonresponse
     - Poststratification
   - Weighting for nonresponse
     - Requires missing at random assumption
     - Similar to mean or random imputation of missing data
   
 - Coding
   - Types
     - Open-ended responses
     - Summary categories
     - Scaling
   - How to code
     - Mutually exclusive categories
     - Exhaustive/comprehensive categories
     - Label
     - Numeric value
       - Missing data (Item nonresponse; DK; breakoff; not asked; inapplicable)
       - Number of digits
       - Are categories nominal, ordinal, or interval
   - Editing
     - Not a huge problem with digital modes
     - Software handles a lot of coding and checks
     - May still need to identify problematic data points
   - Creating codebooks
     - Complete record of survey interview
     - Contents
       - Question wording
       - Details of questionnaire structure (order, randomization, etc.)
       - Exact response categories
       - Question type (open, closed, multiple response, etc.)
       - Mode
       - Numerical categories/codes
       - Missing data information
       - Optional
         - Data type
         - Data source (unit, household, registry, etc.)
         - Frequencies
         - Metadata
         - Interviewer instructions
         - Details of automatic and manual editing (e.g., constrained responses)
   - Activities
     - Activity I: Analyze a codebook
     - Activity II: Create a codebook
       - Code open-ended responses
       - Create summary item
       - Multiple choice and multiple response
       - Numeric
 
 - Anonymizing data
   - Reasons to anonymize
   - What counts as anonymity?
 
 - Data formats and file sharing
   - Open versus proprietary formats
   - What data are contained in a file format
     - Codes
     - Response labels
     - Variable labels
     - Variable names
     - Missing data categories
     - Data types
   - Metadata
     - Dublin Core
        Title
        Creator
        Subject
        Description
        Publisher
        Contributor
        Date
        Type
        Format
        Identifier
        Source
        Language
        Relation
        Coverage
        Rights
     - Data Documentation Initiative
        

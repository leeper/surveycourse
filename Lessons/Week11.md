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
     - Retain design-based sampling variances
   - Assumptions
     - Missing completely at random
     - Missing at random
     - Missing not at random
   - Single imputation
     - Mean imputation (grand mean, subgroup mean, interpolation in a panel)
     - Top or bottom category imputation
     - Random imputation
     - Hot deck imputation
     - Regression imputation
   - Multiple imputation
     - Advantages
       - Account for uncertainty due to missingness
     - Challenges
       - A bit analytically complex
       - Many different approaches
     
   - Should we impute missing data?
   
 - Weighting
   - Sampling designs assign different selection probabilities to different units
     - Self-weighting samples are nice because the analysis is simple
     - SRS, proportional allocation stratified sampling, opt-in samples
   - Disproportionate, cluster, and multi-stage sampling produce varying selection probabilities
     - Analysis has to involve weighted data
   - Sampling design is not the only reason to weight
     - Undercoverage in our sampling frame
     - Intentional oversamples of particular subpopulations
     - Missing data (unit nonresponse, item nonresponse, breakoff, attrition)
     - Nonprobability sample is not descriptively representative
   - Kinds of weighting
     - Selection probabilities (i.e., sampling design)
     - Nonresponse
     - Poststratification
   - Weighting for nonresponse
     - Requirements
       - Missing at random assumption
       - Some information about nonrespondents
     - Similar in some sense to mean or random imputation of missing data
     - Two methods
       - "Weighting classes"
       - "Propensity subclassification"
   - Poststratification weights
     - Like stratification in a sampling design
     - Identify strata and weight observations within each strata so sample matches population
     - Basis for inference in non-probability samples
       - Because selection probabilities are unknown, can only weight for nonresponse and poststratification
       - This makes a face-value representative dataset
     - Limitations
       - What features do we know about the population as a whole? Can only poststratify if variables in population and sample
       - Only weights for representativeness on specified variables
   - Consequences
     - Weighting can affect sampling variances (and thus Standard Errors)
     - Size of effect depends on data, but one can assume that variance increases with weighting
     
   - Adaptive design
     - Monitor response rates during data collection
     - Adapt data collection efforts to minimize sampling variances accordingly
     - That may require weighting calculations at intermediate stages of data collection
   
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
     - "Statistically identifiable"
 
 - Data formats and file sharing
   - Open versus proprietary formats
   - What data are contained in a file format
     - Codes
     - Response labels
     - Variable labels
     - Variable names
     - Missing data categories
     - Imputation information
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
        
 - Total Survey Error
   - Design-related errors
     - Coverage error
     - Sampling error
     - Nonresponse error
     - Adjustment error
   - Measurement errors
     - Construct validity
     - Measurement error and response biases
     - Processing error
     
   - Our goal as survey researchers is to minimize errors of all kinds
     - Achieving this goal requires trade-offs
     - Some trade-offs involve time, money, and resources
     - Other trade-offs are substantive (e.g., question wordings; sampling design)
     - Always think about errors and their impact on data quality

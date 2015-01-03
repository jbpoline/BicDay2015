
#The question of reproducibility in brain imaging {.step data-scale=10}


## Jean-Baptiste Poline  

Brain Imaging Center, Helen Wills Neuroscience Institute, UC Berkeley


# Outline
> * Science Reproducibility crisis evidence
> * Causes and Impact
> * What about brain imaging ? Some - but few - facts
> * What shall we do about it 

# Science finding Reproducibility crisis evidence

## Preclinical oncology
> * Begley C.G. & Ellis L. Nature, (2012): "6 out of 53 key findings could not be replicated"

## Epidemiology
> * Ioannidis 2011: “The FP/FN Ratio in Epidemiologic Studies:” 

## In social sciences and in psychology
> * Reproducibility Project: Psychology (open science foundation)
> * Simmons, et al. “... Undisclosed Flexibility ... Allows Presenting Anything as Significant.” 2011. 
> * In cognitive neuroscience
    - Barch, Deanna M., and Tal Yarkoni. “Special Issue on Reliability and Replication in Cognitive and Affective Neuroscience Research.”  2013.

---------------

## Genetics
> * Ionannidis 2007: 16 SNPs hypothesized, check on 12-32k cancer/control: "... results are largely null." 
> * The concept of endophenotype
> * Many references and warning: eg:"Drinking from the fire hose ..." by Hunter and Kraft, 2007.

## Neuroscience
> * Button et al., 2013

## In general: Editorials / high profile journals
* In general: Nature, "Reducing our irreproducibility", 2013.
    - New mechanism for independently replicating needed 
    - Easy to misinterpret artefacts as biologically important
    - Too many sloppy mistakes 
    - Revised standard for statistical evidence (PNAS 2013)

# Causes and Impact

# What about brain imaging ? Some - but few - facts

# What shall we do about it 





==========================================================

# Data and code sharing : the neuroimaging situation

## Data
> * In brain imaging, only few % of data shared
> * Highly visible large datasets: the tip of the iceberg
> * Resistance to sharing data is very high
> * Sharing against authorship against ICMJE recommendations

## Code 
> * Most software are free and code is open source (Licenses vary)
> * Almost none of the analysis code is shared - highly specific - multiple languages

# Repeatability, Replicability & Reproducibility : the situation in brain mapping

> * Repeatable: in general very poor (within laboratories)
> * Replicability: hardly exists
> * Method reporting: extremely poor
    - J. Carp, 2012
> * Reproducibility: suspected to be very poor
> * Reproducibility: confirmed to be very poor by some 
    - Boekel, W., et al. (2013). A purely confirmatory replication study of
      structural brain-behavior correlations. Journal of Neuroscience 12,
      4745–4765.

# Etiology: why is research sick ?

> * The statistical causes
> * The computational causes
> * The sociological / meta causes

# Statistical causes of irreproducibility

> * Ionnadis 2005
> * Small N/power problem: Button et al., 2012
> * P-hacking: Simmons et al. 2011, Simmonshon et al., 2014 
> * File drawer problem: emmergence of complex H0/H1

# Computational causes of irreproducibility

> * Meta data capture and curation (parameters and process of data generation)
> * Associated data capture and curation 
> * Bugs in code are ubiquitous (cf Donoho's quote)
> * Computational environment packaging not used enough (cf Neurodebian)
> * Some specific situations (PI protection, large computing power needed, etc)

# Sociological causes

## Reward system / The incentives

> * Highly competitive environment
> * The incentive: the high impact factor journal paper

## Consequences

> * keep data if they are a competitive advantage
> * At the detriment of 
    - economy / most efficient use of research funds
    - science: aggregate data, converging evidence
    - ethic: patient population

# The incentive problem 

> * Data paper ? Stars on publication where code is provided ? 
> * Incentives seem to work in the short run, it is a strategy that ultimately fails and even does lasting harm.
> * People actually do inferior work when they are enticed with money, grades, or other incentives.
> * We lost some of the principles on which our work should be based.


# Punish by reward 

> * The main issue: when internal motivation is turned into external motivation
> * ![Punish by Reward!](./img/punish_by_reward_80.jpg)

# What are the solutions 

## Learning the right computing and statistical tools: 

> * How can I check my code ? How can I go back to a certain state ? (learn git/mercurial, learn git Annex or others)
> * How can others check my analyses? Learn the emerging social open science frameworks
> * Statistical issues
> * Learn "one layer below" (A. Martelli)

## Remind ourselves of what is our job

> * Our job is to advance knowledge - not our carreer 
> * What do we do when the right thing to do is against our personal interest? 

# Change our reward system 

> * Ioannidis, J.  (2014). How to Make More Published Research True. PLoS Medicine 11.
> * attribute impact on papers when they are reproduced
> * review code and data generated and their use

# Acknowledgement & Conclusion 

* My colleagues in UCB (M. Brett, J. Millman, F. Perez)
* My colleagues at INCF (Mathew Abrams, Linda Layon)
* My colleagues of Nidash (David Kennedy, Satra Ghosh, Chris Gorgowleski, Nolan Nichols, Dave Keator, Camille Maumet, Guillaume Flandin, Tom Nichols, Russ Poldrack, etc)

![Titus Brown future past](./img/titus_brown.pdf)





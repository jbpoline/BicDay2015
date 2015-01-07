
#The question of reproducibility in brain imaging {.step data-scale=10}


## Jean-Baptiste Poline  

Brain Imaging Center, Helen Wills Neuroscience Institute, UC Berkeley


# Outline
>     
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
> * In cognitive neuroscience:  Barch, Deanna M., and Tal Yarkoni. “Special Issue on Reliability and Replication in Cognitive and Affective Neuroscience Research.”  2013.

---------------

## Genetics

> * Ionannidis 2007: 16 SNPs hypothesized, check on 12-32k cancer/control: "... results are largely null." 
> * The concept of endophenotype
> * Many references and warning: eg:"Drinking from the fire hose ..." by Hunter and Kraft, 2007.

## Neuroscience

> * Button et al., 2013

## In general: Editorials in high profile journals

> * In general: Nature, "Reducing our irreproducibility", 2013.
    - New mechanism for independently replicating needed 
    - Easy to misinterpret artefacts as biologically important
    - Too many sloppy mistakes 

---------------

# What about brain imaging ? Some - _but few_ - facts

> * Jossua Carp (2013): report does not allow replication or to find methodological issues

   For example, while Brown and Braver (2005) claimed that activation in the
   anterior cingulate cortex (ACC) is sensitive to the likelihood of committing
   an error, Nieuwenhuis, Tanja, Mars, Botvinick, and Hajcak (2007) reported no
   relationship between ACC activation and error likelihood."

> * Reproducibility: confirmed to be very poor by some 
    - Boekel, W., et al. (J. Neuroscience 2013) : replication study of structural brain-behavior correlations.
    - 5 studies, 17 findings: Bayesian analysis favored null hypothesis
    - But: only 36 subjects, while most original studies were better powered

> * The Autism example: Toro et al., Corpus callosum size example.

> * Analysis of large databases showing low concordance of small sample group analysis (Thirion et al., 2007)

<div class="notes">

R Toro: 
    We conducted a meta-analysis of the literature which suggested a
    statistically significant difference. However, the studies included were
    heavily underpowered: on average only 20% power to detect differences of
    0.3 standard deviations, which makes it difficult to establish the reality
    of such a difference. We therefore studied the size of the corpus callosum
    among 694 subjects (328 patients, 366 controls) from the Abide cohort.
    Despite having achieved 99% power to detect statistically significant
    differences of 0.3 standard deviations, we did not observe any.
</div>

# Causes and Impact

## Statistical 
## Computational 
## Social 

----------------------------

## Statistical causes:(1)

> * Lack of understanding of statistical issues and Power computation
> * The usual issues apply:
>       - low power studies (Button et al, 2013)
>       - P-hacking: Simmons et al. 2011, Simmonshon et al., 2014

## Example  

> * From imaging genetics:
> * ![Molendijk, 2012](./img/molendijk_2012_f4.pdf) 

----------------------------

## Statistical causes:(2)

> * P value evil: will we eventually turn to Bayesian evidence?
> * No good understanding of the necessity to report null results 
   - File drawer problem (Rosenthal, 1979)
   - Emmergence of complex H0/H1, A. Afraz, 2014. 

## And if we stick to p-values: 

> * Which one to pick: Revised standard for statistical evidence (PNAS Johnson 2013)
> * ![Johnson 2013, Significance](./img/Johnson_significance.pdf) 


<div class="notes">

    For instance, H1 “neurons in brain area X encode visual memories” can be
    contrasted against H0 “neurons in brain area X does not encode visual
    memories”. Even if H1 is not true, if only positive results get published,
    after a few years there will be plenty of published papers showing that
    neurons in brain area X encode visual memories. Then, some scientists might
    hypothesize a more complex H1: “neurons in area X encode visual memories by
    synchronization of their electrical activity”, now the null hypothesis
    would be “neurons in area X encode visual memories without synchronization
    of their activity”.  In this new null hypothesis, involvement of area X
    neurons in memory encoding is already assumed. This second null hypothesis
    can be falsely rejected again in contrast to an even more complex
    scientific model, creating an even more complex set of default beliefs and
    null hypotheses. 
</div>
----------------------------

## Computational causes:

> * Biologists and MDs are rarely well trained in computation - but most brain imaging findings rely heavily on computations
> * Claerbout's """An article about computational science in a scientific
   publication is not the scholarship itself, it is merely advertising of the
   scholarship. The actual scholarship is the complete software development
   environment and the complete set of instructions which generated the
   figures.""""
   (Truer for applied math field, but also valid in Brain Imaging)
> * Meta data capture and curation not implemented (parameters and process of data generation), no standards for meta data
> * Computational environment packaging not used (Neurodebian IMI, Docker, ...)

----------------------------

## Social causes

> * Publication based reward system (career, grants, fame, etc) is in general not working
    towards good science:
    - favors speed over careful, __re-usable__, reproduced studies
    - favors high risk and rapid publications
    - impeeds data and code sharing even for publicly funded research
> * High pressure for publication in competitive environment makes this a serious problem
> * Positive finding publication bias and the file drawer problem 
   - how this can delay scientific revolution (A. Afraz, 'We could all be astronomers')

----------------------------

## Impact

> * Large amount of resource wasted (talent, money, time)  
> * Discredit from the public and governments
> * Slows down scientific and medical progress
> * Impact on the type of work that can be started (counter example: biobank, bavarian cohorts).
> * Increase young generation cynicism 

# Conclusion: What shall we do about it 

> * Adopt more stringent and better statistical and computational standards 
> * Augment the awareness of these issues, advocate for data and code sharing as the standard in our field
> * Adopt genetic research standards: every result should be replicated 
> * Adopt clinical trial standards and pre-registration
> * Train the new generation of scientist in computation, statistics

# Acknowledgement 

* My colleagues at Berkeley  (M. Brett, J. Millman, F. Perez, the Simpace group: Dan, Courtney, Arielle, Katy, Kay, ...)
* My colleagues at INCF (Mathew Abrams, Linda Layon)
* My colleagues of Nidash (David Kennedy, Satra Ghosh, Chris Gorgowleski, Nolan Nichols, Dave Keator, Camille Maumet, Guillaume Flandin, Tom Nichols, Russ Poldrack, etc)






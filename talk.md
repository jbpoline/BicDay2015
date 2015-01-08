
#The question of reproducibility in brain imaging {.step data-scale=10}


## Jean-Baptiste Poline  

Brain Imaging Center, Helen Wills Neuroscience Institute, UC Berkeley


# Outline
>     
> * Evidence for a crisis in reproducibility  
> * What about brain imaging ? 
> * Causes  
> * Impact
> * What shall we do about it 

> * Mesh terms "reproducibility of results" (100 in 2010) ![Mesh terms 2012](./img/mesh_term_reproducibility_results.pdf)

# Science finding Reproducibility crisis evidence

## Preclinical oncology

> * Begley C.G. & Ellis L. Nature, (2012): "Only 6 out of 53 key findings in pre-clinical oncology could be fully replicated"

## Epidemiology

> * Reproducible Epidemiologic Research, Peng et al, 2006.
> * “High FP/FN Ratio in Epidemiologic Studies”, Ioannidis, 2011. 

## Genetics

> * Ionannidis 2007: 16 SNPs hypothesized, check on 12-32k cancer/control: "... results are largely null." 
> * The failing concept of endophenotype (Iacono, Psychophysiology, 2014)
> * Many references and warnings: eg:"Drinking from the fire hose ..." by Hunter and Kraft, 2007.

---------------

## In social sciences, psychology, cognitive neuroscience

> * Reproducibility Project in Psychology  (Open Science Framework)
> * Simonshon et al. "P-curve", “Evaluating Replication Results” 2014, 2013. 
> * Special Issue on “Reliability and Replication in Cognitive and Affective Neuroscience Research.” Barch, Deanna, and Yarkoni, Cogn Affect Behav Neurosci, 2013.

## Neuroscience

> * Button et al., Nature Neuroscience, 2013

## In general: Editorials in high profile journals

> * Nature, "Reducing our irreproducibility", 2013.
    - New mechanism for independently replicating needed 
    - Easy to misinterpret artefacts as biologically important
    - Too many sloppy mistakes
> * NIH plans to enhance reproducibility. Collins and Tabak, Nature, 2014.

---------------

# What about brain imaging ? Some - _but few_ - facts


> * Publication does not allow replication or to find methodological issues (J. Carp Cogn Affect Behav Neurosci, 2013): 

  "For example, while Brown and Braver (2005) claimed that activation in the
  anterior cingulate cortex (ACC) is sensitive to the likelihood of committing
  an error, Nieuwenhuis, Tanja, Mars, Botvinick, and Hajcak (2007) reported no
  relationship between ACC activation and error likelihood."

> * When attempted, replication is poor:  
    - Boekel, W., et al. (Cortex 2013) : replication study of structural brain-behavior correlations.
    - 5 studies, 17 findings: Bayesian analysis favored null hypothesis
    - But: only 36 subjects, while most original studies were better powered

> * Autism example: Toro et al., Corpus callosum size example. S. Bookheimer's examples (cereb. size, FFA, FC). 


<div class="notes">
 * Analysis of large databases showing low concordance of small sample group analysis (Thirion et al., 2007)

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

> * Lack of understanding of statistical issues and power computation
> * The usual issues:
>       - low power studies (Button et al, 2013)
>       - P-hacking: Simmons et al. 2011, Simmonshon et al., 2014

## Example  

> * From imaging genetics (BDNF - Hippocampus volume):
> * ![Molendijk, 2012](./img/molendijk_2012_f4.pdf) 

----------------------------

## Statistical causes:(2)

> * P value evil: will we eventually turn to Bayesian evidence? How ?
> * No good understanding of the necessity to report null results -> File drawer problem (Rosenthal, 1979)  
   - Emmergence of complex H0/H1, A. Afraz, 2014. 

## And if we stick to p-values: 

> * Which one to pick: Revised standard for statistical evidence (PNAS Johnson 2013) : 0.05 <=> BF$\in{[3,5]}$
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
> * Meta data capture and curation not implemented (parameters and process of data generation), no standards for meta data
> * Computational environment packaging not used (Neurodebian VM, Docker, ...)

----------------------------

## Social/systemic causes

> * Publication based reward system (career, grants, fame, etc) + hyper competitive environment is in general not working towards good science:
    - favors speed over careful, __re-usable__, reproduced studies
    - favors high risk and rapid publications
    - impeeds data and code sharing even for publicly funded research
> * Positive finding publication bias and the file drawer problem 
    - how this can delay scientific revolution (A. Afraz, 'We could all be astronomers')
    - is science always self-correcting ? 

----------------------------

## Impact

> * Large amount of resource wasted (talent, money, time) 
> * Discredit from the public and governments
> * Slows down scientific and medical progress
> * Impact on the type of work that can be started (counter example: UK biobank, Bavarian cohorts).
> * The system may select the most "productive" scientists - not necessarily the best

# Conclusion: What shall we do about it 

> * Adopt more stringent and better statistical and computational standards 
> * Adopt genetic research standards for replication 
> * Adopt clinical trial standards and pre-registration
> * Augment the awareness of these issues, adopt data and code sharing as the standard in our field

----------------------------

# Conclusion: What shall we do about it 

> * Train the new generation of scientist in computation, statistics
> * NIH answers: 
    - Data Discovery Index, checklists 
    - online forum for open discussions, 
    - change in funding and bio, anonymize peer review, etc. 
> * Work with journals and editors to accept well powered null findings
> * OSF, many lab and community based projects, METRICS (Meta-Research) institutes
> * Reward people who produce re-usable science

# Acknowledgement 

* At Berkeley: M. Brett, J. Millman, F. Perez; Simpace interest group:  D. Sheltraw, C. Gallen, A. Tambini, K. K. Hwang; B. Inglis, M. D'Esposito. 
* At INCF: Mathew Abrams, Linda Layon, Roman Valls
* Nidash: David Kennedy, Satra Ghosh, Chris Gorgowleski, Nolan Nichols, Dave Keator, Camille Maumet, Guillaume Flandin, Tom Nichols, Russ Poldrack, etc
* At Pasteur, Neurospin, MNI.




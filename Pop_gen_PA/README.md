## Site Frequency Spectrum

In this directory we rely Markov Chains to model allele frequency  evolution. 

Our practical objective is to estimate the expected number of segregating variants in samples of modern day haplotypes. 

One way to do this is to estimate what the frequency distribution of these alleles is in populations of interest. 

**setup**
We are interested only in alleles up to a certain age, and we know the rate at which new alleles rise in time. Under neutral conditions this is a relation between the mutation rate *per* base pair *per* generation and the effective size of the population. 

The problem comes in describing the likely frequency of each new variant in the present. Luckily, the jump in frequency of one allele from one generation to the next can be moddelled as a transition matrix.

Visit the [notebook]() for more.


**example**

Frequency probability if segregating alleles of different ages for example species:


![image](Figures/schweinfurthii/N1000/schweinfurthii_SFSbins.png)

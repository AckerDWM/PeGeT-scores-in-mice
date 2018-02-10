# PeGeT-scores-in-mice
Quantification of Schizophrenia-associated gene enrichment in mice near the time of peak transcriptomic change

Skene, Roy, and Grant (2017) quantified gene expression across the lifespan. They found that Schizophrenia-associated genes were enriched for turning points around the time of peak genetic change in humans. This was quantified using a novel metric called the PeGeT score. I am interested in whether the PeGeT scores of the mouse homologs of these Schizophrenia-associated genes are enriched as well. To test this, I will use a resampling proceedure in which PeGeT scores for Schizophrenia-associated genes are paired with random PeGeT scores. Both random and observed score lists will be sorted so that the quantiles of the two lists are aligned. Based on the following preliminary analysis, PeGeT scores of Schizophrenia-associated genes in two orthogonal gene lists appear to be enriched in the mouse. Future analysis will include controls for transcript length.

The R notebook file can be seen ![here](http://htmlpreview.github.com/?https://github.com/AckerDWM/PeGeT-scores-in-mice/blob/master/mouse-schizo-peget.html)

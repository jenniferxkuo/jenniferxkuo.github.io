---
title: Comparing k-means and OPTICS clustering algorithms for identifying vowel categories
collection: publications
category: published
permalink: /publications/2023-plsa-vowel-clustering
paperurl: 'http://jenniferxkuo.github.io/files/publications/2023_grabowski_kuo_PLSA_vowels.pdf'
citation: 'Grabowski, Emily and <b>Kuo, Jennifer</b>. (2023). Comparing k-means and OPTICS clustering algorithms for identifying vowel categories. <i>Proceedings of the LSA 2023, (8)</i>1, 5488.https://doi.org/10.3765/plsa.v8i1.5488.'
abstract: 'The K-means algorithm is the most commonly used clustering method for phonetic vowel description but has some properties that may be sub-optimal for rep- resenting phonetic data. This study compares K-means with an alternative algorithm, OPTICS, in two speech styles (lab vs. conversational) in English to test whether OP- TICS is a viable alternative to K-means for characterizing vowel spaces. We find that with noisier data, OPTICS identifies clusters that more accurately represent the underlying data. Our results highlight the importance of choosing an algorithm whose assumptions are in line with the phonetic data being considered.'
---

**Try it out!** You can visit our [interactive shiny app](https://www.kuojennifer.com/vowel-clustering/) to test out K-means and OPTICS on different parameter settings. 


**Preview of the results:** The figure below visualizes the distribution of cardinal in conversational speech data (Buckeye Corpus; Pitt et al. 2005). The lefthand figure shows hand-labeled vowel categories, while the middle and righthand figures show clusters found by K-means and OPTICS respectively. Visual inspection of these figures suggest that K-means tends to partition the data into evenly sized clusters. In contrasts, OPTICS finds more meaningful generalizations in the data; it also excludes many points as noise, which may or may not be beneficial depending on the analyst's goals. 

<br>
<img src="https://www.kuojennifer.com/images/results-cardinal-comp.png" style="display: block; margin: auto;" />

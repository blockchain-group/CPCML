# *CPCML* - a Data-Driven Consensus Protocol Classification using Machine Learning.


## Goal of this repository

The diversity and distinct characteristics of consensus protocols employed in DLT have sparked extensive debates regarding their classification in response to the rapidly evolving landscape of this field over the past decade.

This repository provides a quantitative data-driven classification methodology that leverages machine learning, specifically clustering, to achieve an unbiased grouping of analyzed DLT platforms.


## The data sets for the classification process

- [Raw data set](Data/data_raw.md)

  The raw data set was developed to aid the classification process of consensus protocols. 

  Currently, the data set consists of categorized quantitative and qualitative data reflecting 19 state-of-the-art DLT platforms and layer-two solutions aggregated from various sources and also considering (Filatovas et al., 2022).

  The most popular platforms have been selected in order to span the most implementations of consensus protocols used in DLT. We identify the criteria corresponding to the collected features and metrics. 

- [Processed data set](Data/data_processed.md)

  Together with the collected raw data, we provide the processed data set ready to use by various clustering methods. The collected data was processed converting qualitative units to quantitative ones, then the data was scaled to have zero mean and variance equal to one.

- [PCA data set](Data/data_pca.md)

  The data sets provided are highly multi-dimensional, therefore, a simple downside is that it is impossible to graphically represent the data points contained.

  For this reason, in this repository it is also presented the data coming from the Principal Component Analysis (PCA) performed on the processed data set. There are included the first two components of the PCA, such that the data set can be plotted on a 2-dimensional graph.

## Contribution to the *CPCML*

We welcome contributions and corrections to this resource either way:

- **common way** - send us your comments, corrections or suggestions by email: [marco.marcozzi@mif.vu.lt](mailto:marco.marcozzi@mif.vu.lt), [ernestas.filatovas@mif.vu.lt](mailto:ernestas.filatovas@mif.vu.lt),
[linas.stripinis@mif.vu.lt](mailto:linas.stripinis@mif.vu.lt), 
[remigijus.paulavicius@mif.vu.lt](mailto:remigijus.paulavicius@mif.vu.lt)
- **modern way** - [fork](https://help.github.com/articles/fork-a-repo/) github repository, add new information & correct existing, then create a [pull request](https://help.github.com/articles/creating-a-pull-request-from-a-fork/) and  we gratefully incorporate your contribution!

## References

- F. Aponte, L. Gutierrez, M. Pineda, I. Merino, A. Salazar, P. Wightman, (2021). Cluster-Based Classification of Blockchain Consensus Algorithms. *IEEE Latin America Transactions* 19 (4), 688–696. https://doi.org/doi:10.1109/TLA.2021.9448552
- E. Filatovas, M. Marcozzi, L. Mostarda, R. Paulavičius. (2022). A MCDM-based framework for blockchain consensus protocol selection. *Expert Systems with Applications*, 204 , 117609. https://doi.org/doi:10.1016/j.eswa.2022.117609
- R. Xu, D. Wunsch, (2005). Survey of clustering algorithms. *IEEE Transactions on neural networks* 16 (3), 645–678. https://doi.org/doi:10.1109/TNN.2005.845141
- D. Xu, Y. Tian, (2015). A comprehensive survey of clustering algorithms. *Annals of Data Science* 2, 165–193. https://doi.org/doi:10.1007/s40745-015-0040-1

## Acknowledgment

- This research has been supported by a Grant (No. S-MIP-21-53) from the Research Council of Lithuania.

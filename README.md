[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.878944.svg)](https://doi.org/10.5281/zenodo.878944) 
![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.png?v=103)
[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.png?v=103)](https://github.com/sepehrband/Mining_NeuroAnat/blob/master/LICENSE)
[![LONI](https://github.com/sepehrband/Mining_NeuroAnat/blob/master/files/loni.png)](http://loni.usc.edu)

# Neuroanatomical Morphometric Characterization of Sex Differences
This repository accompanies below paper: 

><span style="color:gray">F. Sepehrband, K.M. Lynch, R.P. Cabeen, C. Gonzalez-Zacarias, L. Zhao, M. D'Arcy, C. Kesselman, M.M. Herting, I.D. Dinov, A.W. Toga, K.A. Clark,   
**Neuroanatomical Morphometric Characterization of Sex Differences in Youth Using Multivariate Statistical Learning**,  
*NeuroImage*,   
submitted September 2017</span>.

## Source codes
* `NeuroAnat_SexDiff/code` contains source codes
* `NeuroAnat_SexDiff/demo` contains .html files of the same codes (compiled and static presentation)

## Source codes include:
* Explatory analysis
* Linear regression
  * Ordinary least square implementation
  * Robust linear modeling with Huber's loss function using least trimmed squares estimator
* Non-parameteric correlation analysis
  * Spearman's rank correlation 
* Multivariate logistic regression
* Statistical learning
  * Support vector machine
* Inferential analysis
  * Mapping between-group differences
  * Plotting statistical summeries 

## Raw data and preparation
* Strucutral MRI of the [PNC study](http://www.med.upenn.edu/bbl/philadelphianeurodevelopmentalcohort.html ) were used for this study.  
* Morphological features of the strucutral images were derived using [FreeSurfer](http://freesurfer.net) toolkit.  
* FreeSurfer analysis was performed using [LONI pipeline](http://pipeline.loni.usc.edu) on high performance computing of <font color='red'>**USC**</font> Mark and Mary Stevens Neuroimaging and Informatics [Institute](http://www.ini.usc.edu), Keck school of Medicine of <font color='red'>**USC**</font>. The outputs were QC'ed and used in this study.  
* **Data is available upon request and approval. See LICENSE for more information.**

__________________________________________________________________
author:  
Farshid Sepehrband,   
*Laboratory of Neuro Imaging,  
Mark and Mary Stevens Neuroimaging and Informatics Institute,  
Keck School of Medicine,  
University of Southern California, Los Angeles, CA, USA*  
<farshid.sepehrband@loni.usc.edu>  
@fsepehrband


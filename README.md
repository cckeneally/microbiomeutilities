
<br> 

[![Build Status](https://travis-ci.org/microsud/microbiomeutilities.svg?branch=master)](https://travis-ci.org/microsud/microbiomeutilities)   

<br>  

# About  
The **microbiomeutilities** is a supporting R package for the parent [microbiome](http://microbiome.github.com/microbiome) R/BioC package. This utility tool includes functions for formatting and visualization of [phyloseq](https://github.com/joey711/phyloseq) object. The package has a function `microbiome_pipeline`, which generates an _HTML_ report with infromation on preliminary QC, Alpha Diversity, Ordination and Composition analysis of OTU tables. The _HTML_ report can be convenient for having prelimanry insights into the data.    

[Package website and online documentation](https://microsud.github.io/microbiomeutilities/)  
 
Example output of the `microbiome_pipeline`: [here](https://microsud.github.io/microbiomeutilities/index.html).  

The package provides access to a subset of studies included in the [MicrobiomeHD](https://zenodo.org/record/840333#.WuYuDoiFM2w) database from Duvallet et al 2017: [Meta-analysis of gut microbiome studies identifies disease-specific and shared responses. Nature communications](https://www.nature.com/articles/s41467-017-01973-8). These datasets are converted to phyloseq objects and can be directly used in R environment.  

## Install microbiomeutilities    

```
install.packages("devtools")
devtools::install_github("microsud/microbiomeutilities")

```  
**Citation:**  Sudarshan A. Shetty, & Leo Lahti. (2018, October 25). microbiomeutilities: An R package for utilities to guide in-depth marker gene amplicon data analysis (Version 0.99.00). Zenodo. [![DOI](https://zenodo.org/badge/99698135.svg)](http://doi.org/10.5281/zenodo.1471685)   

## Direction for this package   
Depending on the real world usefulness, practicality and success, we plan to include complete or parts of this package in the Microbiome R package.  
"Leo Lahti, Sudarshan Shetty [et al.](https://github.com/microbiome/microbiome/graphs/contributors) ([Bioconductor, 2017](https://bioconductor.org/packages/devel/bioc/html/microbiome.html)). Tools for microbiome analysis in R.   

The microbiome R package relies on the independently developed   
[phyloseq](https://github.com/joey711/phyloseq) package and data structures for R-based microbiome analysis developed by Paul McMurdie and Susan Holmes.  
[ggplot2](http://ggplot2.org/) H. Wickham. ggplot2: Elegant Graphics for Data Analysis. Springer-Verlag New York, 2009.  
[tidyverse packages](https://www.tidyverse.org/).  

**Microbiome package website with step-wise tutorials**:  
URL: [http://microbiome.github.com/microbiome](http://microbiome.github.com/microbiome).  

**Tutorials**  
* [Microbiome R package tutorials](http://microbiome.github.io/microbiome/)  
* [Open and reproducible spring school 2018](https://mibwurrepo.github.io/Microbial-bioinformatics-introductory-course-Material-2018/introduction.html)   
* [Tools Microbiome Anlaysis](https://microsud.github.io/Tools-Microbiome-Analysis/)   
 
### More useful resources:  
1. [Ben J. Callahan and Colleagues: Bioconductor Workflow for Microbiome Data Analysis: from raw reads to community analyses](https://f1000research.com/articles/5-1492/v2).   
2. [Comeau AM and Colleagues: Microbiome Helper: a Custom and Streamlined Workflow for Microbiome Research](http://msystems.asm.org/content/2/1/e00127-16)  
3.	MicrobiomeHD	[A standardized database of human gut microbiome studies in health and disease *Case-Control*](http://www.biorxiv.org/content/early/2017/05/08/134031)   
4.	Rhea	[A pipeline with modular R scripts](https://peerj.com/articles/2836/)  
5.	Phyloseq	[Import, share, and analyze microbiome census data using R](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0061217) 

### About the Author   
* [Web CV](https://microsud.github.io/gutmicrobe_webpage.io/)  
* [twitter](https://twitter.com/gutmicrobe)   
* [googlescholar](https://scholar.google.nl/citations?hl=en&user=Vahc6LUAAAAJ&view_op=list_works&sortby=pubdate)  
* [ORCID ID: 0000-0001-7280-9915](http://orcid.org/0000-0001-7280-9915)   

### References:
1. Callahan, B. J., McMurdie, P. J. & Holmes, S. P. (2017). Exact sequence variants should replace operational taxonomic units in marker gene data analysis. bioRxiv, 113597.  
2. Callahan, B. J., McMurdie, P. J., Rosen, M. J., Han, A. W., Johnson, A. J. A. & Holmes, S. P. (2016). DADA2: high-resolution sample inference from Illumina amplicon data. Nature methods 13, 581-583.  
3. Caporaso, J. G., Kuczynski, J., Stombaugh, J., Bittinger, K., Bushman, F. D., Costello, E. K., Fierer, N., Peña, A. G., Goodrich, J. K. & Gordon, J. I. (2010). QIIME allows analysis of high-throughput community sequencing data. Nature methods 7, 335-336.  
4. Schloss, P. D., Westcott, S. L., Ryabin, T., Hall, J. R., Hartmann, M., Hollister, E. B., Lesniewski, R. A., Oakley, B. B., Parks, D. H. & Robinson, C. J. (2009). Introducing mothur: open-source, platform-independent, community-supported software for describing and comparing microbial communities. Applied and environmental microbiology 75, 7537-7541.  
Team, R. C. (2000). R language definition. Vienna, Austria: R foundation for statistical computing.  

### Datasets from:  
* Duvallet, Claire, et al. "Meta-analysis of gut microbiome studies identifies disease-specific and shared responses." Nature communications 8.1 (2017): 1784.   
* Son, J. et al. Comparison of fecal microbiota in children with autism spectrum disorders and neurotypical siblings in the simons simplex collection. PLoS ONE 10, e0137725 (2015).  
* Kang, D. W. et al. Reduced incidence of Prevotella and other fermenters in intestinal microflora of autistic children. PLoS ONE8, e68322 (2013).  
* Schubert, A. M. et al. Microbiome data distinguish patients with clostridium difficile infection and non-c. difficile-associated diarrhea from healthy controls. mBio 5, e01021–14–e01021–14 (2014).  
* Youngster, I. et al. Fecal microbiota transplant for relapsing clostridium difficile infection using a frozen inoculum from unrelated donors: a randomized, open-label, controlled pilot study. Clin. Infect. Dis. 58, 1515–1522 (2014).  
* Baxter, N. T., Ruffin, M. T., Rogers, M. A. & Schloss, P. D. Microbiota-based model improves the sensitivity of fecal immunochemical test for detecting colonic lesions. Genome Med. 8, 37 (2016).  
* Zackular, Joseph P., et al. "The gut microbiome modulates colon tumorigenesis." MBio 4.6 (2013): e00692-13.
* Zeller, G. et al. Potential of fecal microbiota for early-stage detection of colorectal cancer. Mol. Syst. Biol. 10, 766–766 (2014).
* Singh, P. et al. Intestinal microbial communities associated with acute enteric infections and disease recovery. Microbiome 3, 45 (2015).  
* Noguera-Julian, M. et al. Gut microbiota linked to sexual preference and hiv infection. EBioMedicine 5, 135–146 (2016).
Dinh, D. M. et al. Intestinal microbiota, microbial translocation, and systemic inflammation in chronic HIV infection. J. Infect. Dis. 211, 19–27 (2014).  
* Lozupone, C. A. et al. Alterations in the gut microbiota associated with hiv-1 infection. Cell Host Microbe 14, 329–339 (2013).
* Gevers, D. et al. The treatment-naive microbiome in new-onset crohn’s disease. Cell Host Microbe 15, 382–392 (2014).
* Zhang, Z. et al Large-scale survey of gut microbiota associated with MHE via 16s rRNA-based pyrosequencing. Am. J. Gastroenterol. 108, 1601–1611 (2013).  
* Wong, J. M. W., Souza, R. De, Kendall, C. W. C., Emam, A. & Jenkins, D. J. A. Colonic health: fermentation and short chain fatty acids. J. Clin. Gastroenterol. 40, 235–243 (2006).  
* Ross, M. C. et al. 16s gut community of the cameron county hispanic cohort. Microbiome 3, 7 (2015).
* Zupancic, M. L. et al. Analysis of the gut microbiota in the old order Amish and its relation to the metabolic syndrome. PLoS ONE 7, e43052 (2012).  
* Scher, J. U. et al. Expansion of intestinal prevotella copri correlates with enhanced susceptibility to arthritis. eLife 2, e01202 (2013).  
* Alkanani, A. K. et al. Alterations in intestinal microbiota correlate with susceptibility to type 1 diabetes. Diabetes 64, 3510–3520 (2015).  
* Scheperjans, F. et al Gut microbiota are related to parkinson’s disease and clinical phenotype. Mov. Disord. 30, 350–358 (2014).

**NOTE:**  
The aim of this package is not to replace any of the other tools mentioned on this site. Instead this package is useful for a quick and (not so) dirty analysis of the OTU tables/biom files generated by tools such as QIIME (the newer QIIME2) (Caporaso, Kuczynski, Stombaugh et al., 2010), Mothur (Schloss, Westcott, Ryabin et al., 2009), DADA2 (Callahan, McMurdie, Rosen et al., 2016). Using the _HTML_ report as a reference for more thorough analysis.  



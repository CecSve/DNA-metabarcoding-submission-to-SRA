# DNA metabarcoding submission to the Sequence Read Archive (SRA)
[to be updated]
Documentation on how DNA metabarcoding sequencing data was submitted to SRA using [the submission portal](https://www.ncbi.nlm.nih.gov/sra/docs/submitportal/).

## 1. Submit a BioProject
First step is to create a BioProject.

#### Submitter
Enter submitter information, in this case info about me :bowtie:.

#### Project type
For this information, I found a project that sounded [sort of similar](https://www.ncbi.nlm.nih.gov/bioproject/688294?log$=activity) and filled out the information based on what they had done. 
* _Project data type_: Targeted loci environmental
* _Sample scope_: Environment

#### Target
My attempt of the most descriptive title possible.
* _Environmental sample name_: Arthropod CO1 DNA metabarcoding of flying insect bulk samples

#### General info

* _When should this submission be released to the public?_: Release on specified date
* _Public description_: The goal of this study was to characterize flying insect diversity using DNA metabarcoding (targeting the cytochrome c oxidase subunit 1 mitochondrial gene (COI)) of bulk insect samples collected with rooftop mounted car nets that sampled >250 five km routes in Denmark and Germany in June and July 2018 and 2019. DNA extracted from dried bulk insect samples were amplified with two COI primer pairs, fwhF2+ fwhR2n (Vamos, Elbrecht and Leese, 2017) and ZBJ-ArtF1c + ZBJ-ArtR2c (Zeale et al., 2011) and a 16S marker, Inse01 (Taberlet et al., 2018), for the purpose of comparing the efficacy of these primer sets used individually and in combination. 
* _Relevance_: Environmental

Before submitting, I added an external link to project webpage, mentioned Aage V. Jensens Naturfond as funding organisation and added a link to a published paper using some of the data. 

## 2. Submit BioSamples ([batch sample submission](https://www.ncbi.nlm.nih.gov/biosample/docs/submission/batch/))
### BioSample type
I am not completely sure which [BioSample template](https://submit.ncbi.nlm.nih.gov/biosample/template/) to choose. For the BioProjects and associated BioSamples I found on SRA, it seems like people use _Metagenome or environmental; version 1.0_. Since I will submit to SRA, I will go with that package as well. 

It seems there are a limited amount of columns that needs to be uploaded for most of the templates: _sample_name_, _organism_, _collection_date_, _geo_loc_name_, _Lat_lon_. There is a good general guide and webinar from [NCBI](https://www.ncbi.nlm.nih.gov/biosample/docs/submission/faq/) that explains the data types etc. 

The data compiling is documented in script XX.

### BioSample attributes
**Check**: should _organism_ be Arthropoda environmental sample [Taxonomy ID: 260574](https://www.ncbi.nlm.nih.gov/Taxonomy/Browser/wwwtax.cgi?mode=Info&id=260574&lvl=3&lin=f&keep=1&srchmode=1&unlock)? It seems other submission with similar data have used that organism disclaimer.

## 3. Submit [metadata](https://www.ncbi.nlm.nih.gov/sra/docs/submitmeta/) 

### References
* Vamos E, Elbrecht V, Leese F (2017) Short COI markers for freshwater macroinvertebrate metabarcoding. Metabarcoding and Metagenomics 1: e14625. https://doi.org/10.3897/mbmg.1.14625
* Zeale, M. R., Butlin, R. K., Barker, G. L., Lees, D. C., & Jones, G. (2011). Taxon‐specific PCR for DNA barcoding arthropod prey in bat faeces. Molecular ecology resources, 11(2), 236-244. https://doi.org/10.1111/j.1755-0998.2010.02920.x
* Taberlet, P., Bonin, A., Zinger, L., & Coissac, E. (2018). Environmental DNA: For biodiversity research and monitoring. Oxford University Press.

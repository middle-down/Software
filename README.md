### Software for middle-down Proteomics
Welcome to the webpage of the middle-down Proteomics software tools.
The page currently contains Histone Coder and isoScale, two software produced to validate MS/MS spectra and quantify identified polypeptides by Mascot (Matrix Science, UK) database searching engine.

Below you can find the first software tools made in collaboration between the [University of Southern Denmark](www.sdu.dk) and the [University of Pennsylvania](http://www.upenn.edu/)


If you want to access our data repository, please visit the [Cross-talk database](http://crosstalkdb.bmb.sdu.dk/)



If you're using the GitHub for Mac, simply sync your repository and you'll see the new branch.

 
### Histone Coder - [Download](http://bioinformatics.sdu.dk/Simone/Histone Coder.jar)
Histone Coder counts the number of MS/MS ions in a given spectrum to determine the unambiguous localization of a post-translational modification (PTM). The software lists number and type of site determining ions found between the assigned PTM localization by Mascot (Matrix Science) and the closest other amino acids which can host the modification. The PTMs included in the script are phosphorylation (S,T,Y), acetylation (K), mono- and dimethylation (K,R) and trimethylation (K). From the interface it is possible to select filters for spectrum score, fragment ion types and MS/MS tolerance for the search. As additional feature, Histone Coder converts the Mascot output to the standard Brno nomenclature for PTMs (e.g. K4me3K14ac). 

Requirements: The software activates with Java. The input is Mascot output in .xml extension. 

 
### isoScale - [Download]( http://bioinformatics.sdu.dk/Simone/isoScale)
isoScale is a proteomics software to quantify peptides based on the total ion intensity of the MS/MS spectra. The software provides also relative quantification of isobaric peptides co-fragmented in MS/MS spectra which share the same sequence but have distinct localizations of post-translational modifications (PTMs). The principle of the quantification is described in Pesavento et al. (Analytical Chemistry, 2006). We recommend the use of the software for middle-down or top-down analyses, as it is suitable for direct comparison of single sequences with scrambled combinatorial PTMs. The user interface provides a choice for CID/HCD or ETD fragmentation. It is suitable for high and low resolution data, as it allows the choice of MS/MS ion tolerance for searching the fragment ions required to calculate the fragment ion relative ratio of isobaric peptides (FIRR). 

Requirements: The software requires Java. It processes Mascot output files in .csv extension. The software input is the result file, which is the output format of Histone Coder, and a data file, which is the Mascot .csv output 

 
### Reference
If using Histone Coder or isoScale please cite the paper: Hybrid chromatography/hybrid tandem mass spectrometry and computational tools for middle-down characterization and quantification of co-existing post-translational modifications in histone proteins (Proteomics, 2014)

Authors:
Simone Sidoli, Veit Schwämmle, Chrystian Ruminowicz, Thomas A. Hansen, Xudong Wu, Kristian Helin and Ole N. Jensen


 
### Contacts
If having troubles in using the software, or any kind of help, please contact
Simone Sidoli: simone.sidoli@gmail.com

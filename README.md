# Automate your genome downloads from NCBI Datasets using Python 🐍

In this project, I harness the use of the Python language to programatically download whole genome assemblies from NCBI genome database.
I demonstrate in detail my methodology in:
1. Shortlisting a list of genome accessions from the taxonomic family of interest
2. Filtering this list against a specified set of conditions
3. Validating this list to retain only validly published organisms
4. Automating the download of whole genome assemblies

My complete workflow is documented in a single Jupyter Notebook; check it out [here](ncbi_datasets.ipynb)!

The genome dataset showcased here is used in my description of a marine bacteria (**TLL-SE01**) from a novel genus, [***Parasalinivibrio***](https://lpsn.dsmz.de/genus/parasalinivibrio), which I isolated from the intestinal contents of a farmed Asian Seabass (*Lates calcarifer*). I used this dataset in my downstream phylogenetic and taxonogenomic analysis of **TLL-SE01** together with all valid species from the family *Vibrionaceae*. 

P.S. you can easily tweak the code and some of the methods used to suit your needs (eg. different genome quality filter, different taxonomic family)!


Read more about ***Parasalinivibrio latis* TLL-SE01** here[^1]:
> [**Er S., Soh M., Low A., Seedorf H.** Parasalinivibrio latis gen. nov., sp. nov., isolated from the distal gut of healthy farmed Asian Seabass (Lates calcarifer). Antonie van Leeuwenhoek 118, 25 (2025).](https://doi.org/10.1007/s10482-024-02036-x)

[^1]: [Full-text available on ResearchGate](https://www.researchgate.net/publication/385683854_Parasalinivibrio_latis_gen_nov_sp_nov_isolated_from_the_distal_gut_of_healthy_farmed_Asian_Seabass_Lates_calcarifer#fullTextFileContent)
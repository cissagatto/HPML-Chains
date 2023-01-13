# HPML-Set-Up-7
This is the seven set-up experiment for HPML - Hybrid Partition for Multi-Label Classification.

## Enviroments to run experiments
Click here to download 

### Conda
You can run this experiment in Conda Environment. The name is "AmbienteTeste". To be able to use this env you must first install conda in your computer or server and then install the environment using the following command: *conda env create --file AmbienteTeste.yaml*

### Singularity
You can also run this experiment in a singularity container. Download the recipes and follow this tutorial (in portuguese): https://prensa.li/@cissa.gatto/tutorial-como-criar-um-container-singularity-para-executar-scripts-r-com-java-e-rclone

## Code

### Step 1

Pre-processing

10-Fold Cross Validation: https://github.com/cissagatto/CrossValidationMultiLabel

### Step 2 and 3

Modeling the correlations between the labels and choosing the best dendrogram to generate the hybrid partitions.

https://github.com/cissagatto/jaccard

### Step 4, 5 and 6

Building and validating all generated hybrid partitions with the silhouette coefficient. The hybrid partition with the highiest silhouet coefficient is chosen to be tested.

https://github.com/cissagatto/Best-Partition-Silhouette

### Step 7

Building and testing the best chosen hybrid partition

https://github.com/cissagatto/Chains-Hybrid-Partition/blob/main/README.md


## Global Partitions
https://github.com/cissagatto/Global-ECC

## Local Partitions
https://github.com/cissagatto/Local-ECC


## Download Results
- [Original Multi-Label Datasets](https://cometa.ujaen.es/datasets/)
- [10-Fold Cross Validation Multi-Label Datasets](https://www.4shared.com/s/dYpGZWzjQ)
- [Jaccard Best Dendrograms](https://www.4shared.com/folder/wVsBXIT5/1-Jaccard-Best-Dendrograms.html)
- [Best Partitions from Silhouette Coefficient](https://www.4shared.com/folder/ucwVLJIg/2-Best-Partitions-Silhouette.html)
- Test

## Metodology Flow


## Acknowledgment
This study is financed in part by the Conselho Nacional de Desenvolvimento Científico e Tecnológico - Brasil (CNPQ) - Process number 200371/2022-3.

## Links

| [Site](https://sites.google.com/view/professor-cissa-gatto) | | [Post-Graduate Program in Computer Science](http://ppgcc.dc.ufscar.br/pt-br) | [Computer Department](https://site.dc.ufscar.br/) |  [Biomal](http://www.biomal.ufscar.br/) | [CNPQ](https://www.gov.br/cnpq/pt-br) | [Ku Leuven](https://kulak.kuleuven.be/) | [Embarcados](https://www.embarcados.com.br/author/cissa/) | [Read Prensa](https://prensa.li/@cissa.gatto/) | [Linkedin Company](https://www.linkedin.com/company/27241216) | [Linkedin Profile](https://www.linkedin.com/in/elainececiliagatto/) | [Instagram](https://www.instagram.com/cissagatto) | [Facebook](https://www.facebook.com/cissagatto) | [Twitter](https://twitter.com/cissagatto) | [Twitch](https://www.twitch.tv/cissagatto) | [Youtube](https://www.youtube.com/CissaGatto) |

## Report Error
Please contact me: elainececiliagatto@gmail.com

## HPML Schematic
<img src="https://github.com/cissagatto/HPML-Set-Up-7/blob/main/HPML-ALL-VERSIONS.png" width="700">

# Thanks

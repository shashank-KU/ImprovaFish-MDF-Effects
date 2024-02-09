# The need for high-resolution gut microbiome characterization to design efficient strategies for sustainable aquaculture production
Microbiome-directed dietary interventions such as microbiota-directed fibers (MDFs) have a proven track record in eliciting responses in beneficial gut microbes and are increasingly being promoted as an effective strategy to improve animal production systems. Here we used initial metataxonomic data on fish gut microbiomes as well as a wealth of a priori mammalian microbiome knowledge on β-mannan-derived MDFs to study effects of such feed supplements in Atlantic salmon (Salmo salar) and their hitherto poorly characterized gut microbiomes. Our multi-omic analysis revealed that the investigated MDFs, at a dose of 0.2%, had negligible effects on both host gene expression, and gut microbiome structure and function under studied conditions.While a high dosage β-mannan (4%) trial significantly shifted the gut microbiome composition, there were still no biologically relevant effects on salmon metabolism and physiology. Only a single Burkholderia-Caballeronia-Paraburkholderia (BCP) population demonstrated consistent and significant abundance shifts across both feeding trials, although with no evidence of β-mannan utilization capabilities or of associated gene transcripts for producing metabolites beneficial to the host. In light of these findings we revisited our omics data to predict and outline novel and potentially beneficial endogenous lactic acid bacteria that should be targeted with future, conceivably more suitable, MDF strategies for salmon.

## Overview of the data generated in this study
<img width="960" alt="ImprovAFish" src="https://user-images.githubusercontent.com/30895959/213148498-c9ec83fc-ee0d-4e58-9a79-520b1748db95.png">

##  Getting Started
### Step 1. Package dependencies
Installing R packages can be done through various sources such as GitHub, the Comprehensive R Archive Network (CRAN), or by following the official website of the package.

To install a package from GitHub, use the devtools package and the install_github() function. For example, to install the "ggplot2" package from GitHub, run the following code:
```{r
library(devtools)
install_github("ggplot2")
```

To install a package from CRAN, use the install.packages() function. For example, to install the "dplyr" package from CRAN, run the following code:
```{r
install.packages("dplyr")
```

It is recommended to regularly update the installed packages to ensure compatibility and to benefit from new features and bug fixes. We require following packages-

```{r
library("ranacapa")
library("phyloseq")
library("ggplot2")
library("stringr")
library("plyr")
library("reshape2")
library("reshape")
library("dplyr")
library("tidyr")
library("doBy")
library("plyr")
library("microbiome")
library("ggpubr")
library("vegan")
library("tidyverse")
library("magrittr")
library("cowplot")
library("dendextend")
library("WGCNA")
library("metagenomeSeq")
library("decontam")
library("RColorBrewer")
library("ampvis2")
library("DT)
library("png")
```

### Step 2. Low dosage MDF trial
We investigated the effects of a low dosage trial of beta-mannan supplementation on Atlantic salmon (Salmo salar) and their gut microbiomes. The trial, conducted in accordance with European Union and Norwegian Ministry guidelines, involved fish randomly distributed into 12 tanks supplied with freshwater. The experimental diets included a standard commercial diet (CTR) and the same diet supplemented with 0.2% w/w beta-mannan from different sources (MC1, MC2, and MN3 diets).

Over a 110-day period, fish were subjected to continuous feeding, and samples were collected at various time points for analysis. The results indicated that the 0.2% beta-mannan supplementation had negligible effects on host gene expression, gut microbiome structure, and function. Biometric traits, fish welfare indicators, and gut tissue samples were examined, revealing no significant changes in salmon health or performance. Additionally, the microbial community profiling through 16S rRNA gene sequencing showed limited alterations in bacterial composition.

Steps used for low dosage of MDF trial mentioned [here](https://shashank-ku.github.io/ImprovaFish-MDF-Effects/Low_dosage_MDF_trial.html)

### Step 3. High dosage MDF trial
This part explores the impact of a high-dose beta-mannan supplementation trial on Atlantic salmon (Salmo salar) and their gut microbiomes. The trial involved fish acclimatized in recirculated freshwater tanks. The experimental diets included a control diet (CTR) and an experimental diet supplemented with 4% beta-mannan derived from Norway Spruce wood (4%MN3).

Over a 28-day period, fish were fed 4% beta-mannan diet, and samples were collected for analysis. The results revealed that the 4% beta-mannan supplementation significantly altered the gut microbiome composition. Despite these changes, no discernible effects on salmon metabolism or physiology were observed.

Biometric traits, fish welfare indicators, and various tissue samples were examined, indicating no significant changes in salmon health or overall performance. Additionally, the microbial community profiling through 16S rRNA gene sequencing showed substantial shifts in bacterial composition, with specific attention to a Burkholderia-Caballeronia-Paraburkholderia (BCP) population consistently shifting in abundance.

Host transcriptomic analysis using RNA extraction, library preparation, and sequencing revealed limited differential expression in response to the high-dose beta-mannan supplementation. The metatranscriptomic analysis of microbial RNA extraction demonstrated notable changes in the expression of genes from the Salmon Microbiome Genome Atlas (SMGA).

Steps used for low dosage of MDF trial mentioned [here](https://shashank-ku.github.io/ImprovaFish-MDF-Effects/High_dosage_MDF_trial.html)



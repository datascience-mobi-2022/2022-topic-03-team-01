# Proteome-wide Screen for RNA-dependent Proteins in Non-Synchronized HeLa cells - Data analysis project

## 2022-topic-03-team-01

Cancer, neurological diseases and muscular atrophy - What do these diseases have in common? 
All of them include RNA-binding proteins. RNA-binding proteins (RBP) are proteins that bind RNA and form ribonucleoprotein particles. 
They are involved in a number of processes like translation, alternative splicing, RNA editing and chemical modification as well as protein modification.
RBPs belong to the RNA-dependent proteins (RDP) together with RBP-binding proteins. These RBP-binding proteins bind RBPs when they assemble with RNA.
Their complex interactions are crucial for cellular functions and therefore it is of importance to identify RDPs.

The data about Non-Synchronized HeLa cells was provided by our supervisor Dr. Maïwen Caudron-Herger. To generate the data the following steps have been taken.
To identify RDPs a proteome-wide screen was conducted with mass-spectrometry. HeLa S3 cells in different cell cycle stages were lysed (Figure 1). 
The cell lysate was split into a control and an RNase group. The RNase group was treated with RNase which causes the degradation of RNA. 
RBPs can no longer bind to RNA and RBP-binding proteins to RBPs. The control group did not receive any further treatment and therefore all RNA and RDPs interact.
The cell lysate was transferred onto a sucrose density gradient. After ultracentrifugation the RNA-protein complexes or proteins alone will end up in one of 25 fractions depending on their molecular weight.
A heavy RNA-protein complex will travel further and land in a higher fraction than a single protein from the RNase treatment. This would create a left shift and is expected to happen for RDPs.

All our analysis steps can be found in the document *BioinfoCode.Rmd*. After installing all the packages mentioned at the top of the document the code can be run to perform the analysis steps.
Our project was divided into the following 5 main steps:
1. Data Clean-Up and Normalization
2. Identification of global maxima
3. Identification and application of selection criteria
4. Protein shift identification
5. Protein data bases as comparison and linear regression


The report which accurately explains all of the aforementioned steps of our analysis is called *Topic003_Team001.pdf*. The accompanying code for the report is stored in the folder "Report" and is called "Topic003_Team001.Rmd. Our code for the entire project is stored under "Topic003_Team001_Code.Rmd".
Furthermore our GitHub contains folders with our *project proposal*, *final presentation* as well as a folder containing all the pictures we have used throughout our report.

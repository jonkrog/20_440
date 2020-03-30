# 20_440 - COVID Protein-Protein Network Analysis

Overview:
This analysis was conducted using data from the paper titled "A SARS-CoV-2 Human Protein-Protein Interaction Map Reveals Drug Targets and Potential Drug-Repurposing" by David Gorden et al. Here we are looking to better understand the protein-protein interactions of Ofr3, Orf8 and Orf10 of the SARS-CoV-2 and their effect on the endogenous protein networks. To do so, we began by just plotting the network for all three of these proteins together in one plot which can be found under the figures section.

Data:
The data that we are using is affinity-purification mass spectrometry data for the different viral protein when expressed on plasmids that were trasnfected into HEK293T cells. This was provided in a excel spreadsheet that details the viral protein - host protein interactions and different metrics such as MIST score, fold change and Saint Score. This data for the combined cross section of Orf3b, Orf8, Orf 10 as well as their individual interaction maps can be found in the data section of this page.

Folder Structure:
You can find the folders for Data, Figure and Code above. 

Installation:
The provided code is a jupyter notebook that can be run in python 3. It has all of the requirements as imports at the start of the code and should be able to be run smoothly without the need for additional packages. You will need to have the code and the data files in the same folder when running. Successful running of the code blocks in jupyter notebook will result in the recreation of the figure.

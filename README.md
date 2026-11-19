# DSA495 - Constitutional Respect and Supreme Court Open-Ended Response Analysis
Alexus Livesey

## Project Purpose
This project will analyze open-ended survey responses from a political science public opinion survey administered during Spring 2026.
The survey examines respondents' attitudes toward a bipartisan term limit bill for Supreme Court justices. The open-ended response
questions ask why respondents approve or disapprove of the term limit bill. This analysis will examine topics generated from the 
open-ended questions. Specifically, the data will be analyzed based on survey treatment. The survey included two treatments: 
constitutional amendment and ordinary legislation. Each treatment asked the same open-ended question. 

## Repository Structure
- Google Colab Folder: This folder includes the code for the two topic models required for the present analysis. 
- Data Folder: This folder contains the two CSV files required for the present analysis. 
- Topic Brief: This file was the project's origin and brainstorming. It can be used to identify how the project has evolved. 
- README.md: This document contains rerun instructions and an analysis guide. 

## Documentation needed for Reproducibility
- ConstitutionalTopicModel.ipynb: topic model code for constitutional treatment data.
- LegislationTreatmentTopicModel.ipynb: topic model code for legislative treatment data. 
- con.csv: open-ended survey responses for respondents in constitutional treatment. 
- leg.csv: open-ended survey responses for respondents in legislative treatment.

The Google Colab notebook provides the code for the entire analysis. 

## How to Run the Analysis
Step-by-step rerun instructions for the Constitutional Amendment Treatment: 
1. Open ConstitutionalTopicModel.ipynb in Google Colab.
2. Select Runtime → Change runtime type → T4 GPU.
3. Run the install Bertopic cell first
4. Download the con.csv data to your own Google Drive folder. Change DATA_DIR to your drive path
   where the data is stored.
5. Run remaining cells in order; do not rerun installation in the restarted session.

Step-by-step rerun instructions for the Ordinary Legislation Treatment: 
1. Open LegislationTreatment_TopicModel.ipynb in Google Colab.
2. Select Runtime → Change runtime type → T4 GPU.
3. Run the install Bertopic cell first
4. Download the leg.csv data to your own Google Drive folder. Change DATA_DIR to your drive path
   where the data is stored.
5. Run remaining cells in order; do not rerun installation in the restarted session.


## Recommended Starting Point 
For reproducibility, analysis can begin with either the constitutional amendment topic model or 
the legislation topic model; the starting model does not influence results and the code/analysis
is the same. 







## AI Use Statement 
-  Umap
-  stop words
-  keywords do not overlap on bar chart

# Prototype Data Dictionary: Small Ruminants

## Overview
This document accompanies the prototype data dictionary for small ruminants, part of the larger effort to develop a comprehensive data dictionary for the Global Burden of Animal Diseases (GBADs) programme. The prototype focuses on essential parameters and data elements related to small ruminants as used in the GBADs Dynamic Population Model (DPM). It provides an initial framework for organizing and standardizing the data necessary for estimating animal disease burdens using GBADs methods.
The full data dictionary will be uploaded in due course, expanding on this prototype with additional parameters and species coverage.
Structure of the Prototype Data Dictionary

The data dictionary is organized by several key fields, described below:
* Parameter: The specific data element or variable being defined (e.g., "Cull age", "Dry matter content").
* Data Categories A, B, C: Hierarchical categories that organize the data into broad groups, subgroups, and specific contexts (e.g., "System characteristics", "Inputs").
* Relationship to Dynamic Population Model: This indicates how the parameter interacts with or supports the GBADs Dynamic Population Model.
* Definition: A detailed description of the parameter.
* Definition Notes: Additional notes or clarifications related to the parameter's definition.
* Stratification: Any stratifications (e.g., by sex, breed, or production system) applicable to the parameter.
* DataType: The type of data represented (e.g., "Floating number").
* Calculations: Describes any calculations related to the parameter.
* Related Parameters: Lists any parameters related to the one in question.
* Species_Sheep & Species_Goats: These columns indicate if the parameter applies to sheep or goats (1 = Yes, 0 = No).
* DPM (Dynamic Population Model) Codes: These are specific codes used within versions 1.0 and 2.0 of the GBADs Dynamic Population Model.
* Modeling Notes: Notes on how the parameter is used within the modeling process.
* AHLE (Animal Health Loss Estimate) Fields: These columns show how the parameter is used in the current and ideal estimates of Animal Health Loss.
  * AHLE current: How this parameter is parameterised in the current health scenario - "Fixed" parameters are predefined; "current estimate" parameters require values to be assigned derived from data/literature etc
  * AHLE ideal: How parameterised in the ideal health scenario - "Fixed" parameters are predefined; "as current" parameters are assumed to be the same under current and ideal health; "Derived from current" parameters are adjusted for ideal health in relation to their estimate under surrent health; "ideal estimate" parameters require an estimate to be defined specifically for the ideal health scenario.
    
## How to Use this Data Dictionary
1.	Data Organization: The parameters are grouped by categories and subcategories, allowing for easy navigation through the data.
2.	Parameter Definitions: Each parameter includes a clear definition to ensure consistent interpretation and application.
3.	Modeling Insights: Some parameters include notes on their relevance to the GBADs dynamic population model or the AHLE estimation process, which can help with understanding their role in disease burden estimation.
   
## Future Updates
This prototype will be expanded to include additional species, parameters, and more detailed metadata. Updates will also refine the structure and the inclusion of new calculation methods relevant to GBADs analyses.

## Relationship to GBADs Dynamic Population Models
This data dictionary is linked to parameters related to small ruminants in the GBADs Dynamic Population Models, which can be found in the GBADs Informatics GitHub repository:

GBADsDPM.R GitHub Repository.

The data dictionary also supports the analyses across the wider GBADs framework as described in the GBADs Technical Guide, which can be downloaded here, https://animalhealthmetrics.org/gbads-technical-guide/, as well as other GBADs methods publications such as those outlined below: 

* Jemberu WT, Li Y, Asfaw W, Mayberry D, Schrobback P, Rushton J, Knight-Jones TJD. Population, biomass, and economic value of small ruminants in Ethiopia. Front Vet Sci. 2022 Oct 13;9:972887. doi: 10.3389/fvets.2022.972887. PMID: 36311678; PMCID: PMC9608676.
* Li Y, Mayberry D, Rushton J. Estimating livestock biomass across diverse populations and data ecosystems. Rev Sci Tech. 2024 Aug;43:23-29. English. doi: 10.20506/rst.43.3514. PMID: 39222115.
* Schrobback P, Dennis G, Li Y, Mayberry D, Shaw A, Knight-Jones T, Marsh TL, Pendell DL, Torgerson PR, Gilbert W, Huntington B, Raymond K, Stacey DA, Bernardo T, Bruce M, McIntyre KM, Rushton J, Herrero M. Approximating the global economic (market) value of farmed animals. Glob Food Sec. 2023 Dec;39:100722. doi: 10.1016/j.gfs.2023.100722. PMID: 38093782; PMCID: PMC10714036.
  
Other information about GBADs publications and the programme in general can be found on the website: https://animalhealthmetrics.org/


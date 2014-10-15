# BIOMD0000000286: BIOMD0000000462

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000286.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000286.git@20140916`


# Model Notes


This is the model described the article:  
**GSK3 and p53 - is there a link in Alzheimer's disease?**   
Carole J Proctor and Douglas A Gray _Molecular Neurodegeneration_ 2010, 5:7;
doi: [10.1186/1750-1326-5-7](http: //dx.doi.org/10.1186/1750-1326-5-7)  
**Abstract:**   
**Background:** Recent evidence suggests that glycogen synthase kinase-3beta (GSK3beta) is implicated in both sporadic and familial forms of Alzheimer's disease. The transcription factor, p53 also plays a role and has been linked to an increase in tau hyperphosphorylation although the effect is indirect. There is also evidence that GSK3beta and p53 interact and that the activity of both proteins is increased as a result of this interaction. Under normal cellular conditions, p53 is kept at low levels by Mdm2 but when cells are stressed, p53 is stabilised and may then interact with GSK3beta. We propose that this interaction has an important contribution to cellular outcomes and to test this hypothesis we developed a stochastic simulation model.   
**Results:** The model predicts that high levels of DNA damage leads to increased activity of p53 and GSK3beta and low levels of aggregation but if DNA damage is repaired, the aggregates are eventually cleared. The model also shows that over long periods of time, aggregates may start to form due to stochastic events leading to increased levels of ROS and damaged DNA. This is followed by increased activity of p53 and GSK3beta and a vicious cycle ensues.   
**Conclusions:** Since p53 and GSK3beta are both involved in the apoptotic pathway, and GSK3beta overactivity leads to increased levels of plaques and tangles, our model might explain the link between protein aggregation and neuronal loss in neurodegeneration. 

  

**Notes:** The original model submitted by the author had events in it. Since, this model is intended for Stochastic Simulation run and Copasi cannot handle events in Stochastic run, I have replaced the events with piecewise assignment rule. -Viji 

This model is an extension of Proctor_p53_Mdm2_ATM (
[BIOMD0000000188](http://www.ebi.ac.uk/biomodels-main/BIOMD0000000188) ).

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2010 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)



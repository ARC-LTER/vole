# VOLE Model

A simple coupled biogeochemical model to examine recovery of terrestrial ecosystems from disturbances that remove vegetation, e.g. voles.  The model is complex enough to represent the interactions between C and N and between vegetation and soil-microbial processes that are important to the questions we address, but still simple enough to be broadly illustrative of terrestrial ecosystems and easily implemented and analyzed. The model is based on five mass balance equations representing changes in C and N in vegetation biomass (BC and BN), C and N in soil organic matter and associated microbes and fauna (DC and DN), and inorganic N (N). The model is driven by atmospheric CO2 concentration, air temperature, vole density and inorganic nitrogen inputs .The model incorporates the temperature sensitivity of six metabolic processes (photosynthesis, autotrophic and heterotrophic respiration, plant and microbial N uptake, and N mineralization) and the effects of voles on the transfer of C and N from vegetation to soil organic matter and the transfer of N in urine from vegetation to inorganic N (although not all N in urine is inorganic, it is labile, and we treat it as inorganic). 

The full VOLE model is desribed in the file, Model descriptionVole V4.txt. 

--------------------------------------------------------------------------

The vole model is written for modelshell, a model develepment package, which is written in Lazarus/Free Pascal. Modelshell allows the user to create a model by making creating a plain text file description of the model. Modelshell provides a GUI interface, an integrator, file IO, and a simple graph. All output files created by modelshell are comma delimited text files.

Detailed instructions for compiling and running the model are in "Install and Run VOLE.docx"

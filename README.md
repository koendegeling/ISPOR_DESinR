# ISPOR Discrete Event Simulation Short Course

This is the repository for the short course on "Learning and Applying Discrete Event Simulation" by Hendrik Koffijberg (University of Twente, the Netherlands) and Koen Degeling (GSK, the Netherlands) for the Professional Society for Health Economics and Outcomes Research (ISPOR).

The repository contains three important files that are used in demonstrating on how a discrete event simulation can be implemented and analyzed for the case study:

* `1_basic_structure.R`: script that defines the basic structure for the discrete event simulation
* `2_health_economics.R`: script that demonstrates how the basic structure can be expanded to generate health and economic outcomes for two treatment strategies
* `3_probabilistic_analysis.R`: scripts that illustrates how a probabilistic analysis of a discrete event simulation can be implemented 
* `out_probabilistic 500runs 50000individuals.RDS`: matrix with the output of a probabilistic analysis of 500 runs and 50,000 individuals per run, which can be used to analyze the results without the need to run the analysis yourself
* `slides_illustration.pdf`: slides that provide the introduction to the case study and overview of the `simmer` package and its functions that are used to implement the discrete event simulation (will be added closer to the course date)
* `slides_theory.pdf`: slides that were presented on several methodological aspects of applying discrete event simulation (will be added closer to the course date)

We recommend to save all these files, or simply the whole repository, in a single folder, and use the `ISPOR_DESinR.Rproj` to open R Studio, which ensures the working directly is set automatically. We also recommend to ensure that you install all the packages required to run the scripts before the live short course session. Given that all scripts should run without error, you can verify whether the packages have been properly installed by running, for example, the `1_basic_structure.R` script.

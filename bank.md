# Biochar Properties Prediction Model Development

Julius Choi
April 17th, 2019

# I. Definition
## Project Overview

Biochar is a porous carbon-rich material produced from biomass-waste such as agricultural waste, wood waste or food waste through a thermochemical process like gasification or pyrolysis[1]. 
Biochar has potential applications in waste-water treatment, catalysts, electrodes, carbon sequestration agents, soil amendment agents and solid fuels[2]. 

Designing and producing the biochar for its specific application is highly dependent on its physicochemical properties. 
For example, the surface area, yield and molar composition are critical properties for its application as an adsorbent in waste-water treatment[1]. 
The properties are determined by production conditions (e.g., temperature, pressure, heating rate and residence time) and intrinsic properties of starting materials (e.g., element composition)[2]. 
Understanding the relation between those process parameters and the properties of the biochar would be beneficial for screening the process method and determining possible applications of the products.  
Also, it can proceed to develop a model that predicts the potential application from the measurable parameters, saving experimental time and cost and increasing the success of the product's commercialization.  

In this project, the correlation between production conditions and properties of the final product was investigated using a dataset collected from the literature [2-7]. Then, the model that predicts the properties of biochar was developed as a function of production conditions such as temperature, heating rate and residence time and feedstock elemental composition such as carbon, oxygen, nitrogen and hydrogen. 
Then, ANN, multitarget regresser and GradientBoostingRegressor were implemented for the model development.

# II. Analysis
## Data Exploration

[Raw data](/files/data2.csv)

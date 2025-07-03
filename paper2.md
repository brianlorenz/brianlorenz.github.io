## Stacking and Analyzing MOSDEF Galaxies by Spectral Types: Implications for Dust Geometry and Galaxy Evolution

[Link to published paper](https://iopscience.iop.org/article/10.3847/1538-4357/ad7de8/pdf)

**Project Description:** My previous project found that galaxy inclination does not have a strong affect on the observed dustribution. Building off of this work, I can make an even more finely-tuned splitting of galaxy groups. This time, I intend to observe what galaxy properties are most important in predicting the dust content of distant galaxies. 

### 1. Forming Groups Algorithmically

Individual galaxies do not have strong enough signal to make a reliable dust measurement - instead, I form groups of galaxies and combine their data. In order to determine which property is most important, I want to find groups of galaxies that are as similar to each other as possible, while being different than other groups. Galaxies with similar properties tend to have similar distributions of light. I cross-correlated the light distribution of each of the 500 galaxies to each other, and constructed a similarity matrix of these values. I then use a spectral clustering algoithm to group the galaxies. Examples of the groups are shown below. 

<img src="images/paper2/Example_Group.png?raw=true"/>

We can see that the algorithm did a reasonable job - the selected galaxies (black dots) occupy similar regions of the parameter spaces shown in the rightmost three plots.

### 2. Fitting a Model

I fit each of the 20 groups with the *prospector* stellar population synthesis code. These models take the light distriubtions of individual stars and combine them to try to predict what combination of stars make up the light of an observed galaxy. These models have a wide range of possible parameters and priors, so I spent significant time optimizing their fits. As seen in the imagine below, the models (gray line) ended up doing a great job of reproducing the data (circles).  

<img src="images/paper2/Model_Fits.png?raw=true"/>


### 3. Assessing Model Fits

While they visually look like reasonable fits ot the data, I want to verify that the models are accurately reproducing the galaxy properties. Here, I test a direct measure of the star formation rate (SFR) from emission lines (y-axis) against the model prediction of the star formation rate (x-axis). I find reasonable agreement, with the models slightly under-predicting the SFR. This under-prediction may be evidence of other sources contributing to the observed emission lines that the models are not currently accounting for. 

<img src="images/paper2/Model_Assessed.png?raw=true"/>

### 4. Resulting Properties

Finally, I show the wide variety of properties captured by our groups below. They have a range of different masses and star formation rates, which allows this to be a very exciting data set that can capture many stages of how galaxies evolve. 

<img src="images/paper2/Sample_Props.png?raw=true"/>

I then measured the dust properties of these galaxies and correlated them with mass and star formation rate. The results of this project broadly agreed with my first paper, finding that the dust distriubtion is likely clumpy and irregular. There was strong evidence for extra dust near regions where new stars are being formed. 




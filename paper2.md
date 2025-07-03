## Stacking and Analyzing MOSDEF Galaxies by Spectral Types: Implications for Dust Geometry and Galaxy Evolution

[Link to published paper](https://iopscience.iop.org/article/10.3847/1538-4357/ad7de8/pdf)

**Project description:** My previous project found that galaxy inclination does not have a strong affect on the observed dustribution. Building off of this work, I can make an even more finely-tuned splitting of galaxy groups. This time, I intend to observe what galaxy properties are most important in predicting the dust content of distant galaxies. 

### 1. Forming Groups Algorithmically

Individual galaxies do not have strong enough signal to make a reliable dust measurement - instead, I form groups of galaxies and combine their data. In order to determine which property is most important, I want to find groups of galaxies that are as similar to each other as possible, while being different than other groups. Galaxies with similar properties tend to have similar distributions of light. I cross-correlated the light distribution of each of the 500 galaxies to each other, and constructed a similarity matrix of these values. I then use a spectral clustering algoithm to group the galaxies. Examples of the groups are shown below. 

<img src="images/paper2/Example_Group.png?raw=true"/>

We can see that the algorithm did a reasonable job - the selected galaxies (black dots) occupy similar regions of the parameter spaces shown in the rightmost three plots.

### 2. Assessing Model Fits

Text

<img src="images/paper2/Model_Fits.png?raw=true"/>


### 3. Header

Text

<img src="images/paper2/Model_Assessed.png?raw=true"/>

### 4. Header

<img src="images/paper2/Sample_Props.png?raw=true"/>

Text


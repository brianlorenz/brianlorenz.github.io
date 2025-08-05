## Evidence for Shallow Nebular Attenuation Curves and Patchy Dust Geometry at z~2 with Paβ/Hα from JWST-MegaScience Medium Band Photometry

**Project Description:** In my previous paper, I developed and demonstrated a technique to measure emission line strengths from image data, allowing us to measure emission lines five times faster. Here, I implement the technique on a dataset of over 70,000 objects. 

### 1. Sample Selection

First, I slice the 70,000 objects to select galaxies where we can make the emission line measurements. Then, following the process of my previous work, I require that the line strength is strong enough to make a reliable measurement (signal-to-noise ratio > 3), that the targets are not too close to the bright cluster galaxies (which would contaminate the data), and that the data are consistent with our models. This selection process results in a set of 66 galaxies, as shown below.

<img src="images/paper4/Sample_Selection.png?raw=true"/>

### 2. Measuring Emission Line Fluxes

Then, for each galaxy, we run the mathematical analysis to make emission line and dust measurements. We correlate the measured Paβ/Hα ratios with galaxy mass and star formation rate (SFR). We analyze the strength of these correlations with linear regression, finding a statistically significant trend with mass, but not with SFR. These results are consistent with the popuar theory that higher mass galaxies retain more dust.

<img src="images/paper4/Dust_Mass_SFR.png?raw=true"/>


### 3. Evidence for a Shallow Attenuation Curve

We are able to test one of the most important assumptions in observational astronomy - the dust attenuation curve. When astronomers measure galaxy mass or SFR, they have to correct for the presence of dust using the attenuation curve. Typically, the Cardelli curve is assumed for these galaxies. To assess the curve, I match our observations to measurements from anotehr dataset. Then, with two line ratio measurements, we plot our data against possible attenuation curves below. We see that, surprisingly, the Cardelli curve is not consistent with our observations, and that the Reddy curve better describes the data

<img src="images/paper4/Neb_Curve.png?raw=true"/>


### 4. Comparison to Prior Datasets

To quantify the difference between these attenuation curve, I compare our measurements to past data using the typical Cardelli curve (left) and more shallow Reddy curve (right).

<img src="images/paper4/AV_Compare.png?raw=true"/>

We see that our measurements are much more consistent using the Reddy curve (0.75mag offset compared to 0.11mag offset). Assuming the wrong attenuation curve can affect the dust measurement by 0.5mag, and over 1mag for the highest mass galaxies, which can cause dramatically wrong mass and SFR measurements. 

Putting all of the results together, I describe the possible distribution of dust within galaxies that could produce these data. I suggest that we require dust only around star-forming regions, and that not all of these regions are fully covered with dust. 

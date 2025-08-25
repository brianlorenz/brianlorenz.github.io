## Evidence for Shallow Nebular Attenuation Curves and Patchy Dust Geometry at z~2 with Paβ/Hα from JWST-MegaScience Medium Band Photometry

**Project Description:** In my previous paper, I developed and demonstrated a technique to measure emission line strengths from image data, enabling measurements up to five times faster. Here, I apply that technique to a dataset of over 70,000 objects. 

### 1. Sample Selection

First, I slice the 70,000 objects to select galaxies where we can make the emission line measurements. Following the process of my previous work, I require that the emission line signal-to-noise ratio exceeds 3, that the targets are not too close to the bright cluster galaxies (to avoid contamination), and that the data are consistent with our models. This selection process results in a set of 66 galaxies, as shown below.

<img src="images/paper4/Sample_Selection.png?raw=true"/>

### 2. Measuring Emission Line Fluxes

Then, for each galaxy, we run the mathematical analysis to make emission line and dust measurements. We correlate the measured Paβ/Hα ratios with galaxy mass and star formation rate (SFR). Using linear regression, we find a statistically significant correlation with mass, but not with SFR. These results are consistent with the prevailing theory that higher mass galaxies retain more dust.

<img src="images/paper4/Dust_Mass_SFR.png?raw=true"/>


### 3. Evidence for a Shallow Attenuation Curve

We are able to test one of the most important assumptions in observational astronomy - the dust attenuation curve. When astronomers measure galaxy mass or SFR, they have to correct for the presence of dust using the attenuation curve. Typically, the Cardelli curve is assumed for these galaxies. 

To evaluate this assumption, I match our observations to measurements from another dataset. With two line ratio measurements, we plot our data against possible attenuation curves (see below). Surprisingly, the Cardelli curve is not consistent with our observations, but the shallower Reddy curve provides a better fit.

<img src="images/paper4/Neb_Curve.png?raw=true"/>


### 4. Comparison to Prior Datasets

To quantify the difference between these attenuation curve, I compare our measurements with previous datasets using the typical Cardelli curve (left) and more shallow Reddy curve (right).

<img src="images/paper4/AV_Compare.png?raw=true"/>

We find that our measurements are much more consistent using the Reddy curve (0.75mag offset with Cardelli vs. 0.11mag with Reddy). Assuming the wrong attenuation curve can affect the dust measurement by 0.5mag, and over 1mag for the highest mass galaxies, which can cause dramatically wrong mass and SFR measurements. 

Putting all of the results together, I describe the possible distribution of dust within galaxies that could produce these data. I suggest that we require dust only around star-forming regions, and that not all of these regions are fully covered with dust. 

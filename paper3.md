## Measuring Emission Lines with JWST-MegaScience Medium-Bands: A New Window into Dust and Star Formation at Cosmic Noon

[Link to published paper](https://arxiv.org/pdf/2505.10632)

**Project Description:** A wide variety of galaxy properties can be determined by measuring the strength of emission lines. Typically, astronomers require spectroscopic observations to measure these lines, which need specialized instruments and long observation time. However, I have implemented a novel technique to measure emission lines directly from images, which takes far less observation time. I verify the accuracy of this technique by comparing the new "photometric" measurements to the standard "spectroscopic" measurements, and then apply this technique to dataset of over 70,000 galaixes. 

### 1. Sample Selection

About 700 galaxies in the UNCOVER survey have spectroscopic observations, out of a total of 70,000. Through careful consideration, I have selected 14 galaxies that meet the criteria for this project. The selection process entailed assessing the quality and location of the emission lines for each galaxy. Here, I show the selected targets compared to the full 70,000 galaxies.

<img src="images/paper3/Sample_Selection.png?raw=true"/>

### 2. Compare the "Photometric" and "Spectroscopic" Measurements

I then perform the mathematical analysis required to measure both the typical "spectroscopic" emission lines directly, as well as my new technique of "photometric" emission lines measurements. I then compare the two measurements below, and statistically analyze the quality of the comparison. The technique appears to work very well, with the slight scatter being attributed to the difference in light collection methods by the telescope. 

<img src="images/paper3/Flux_Compare.png?raw=true"/>


### 3. Science Results from Emission Line Measurements

One additional upside of measureing emission lines directly from images ("photometric") is that we can make 2D maps of the strongest emission. I generate maps of the measured emission lines, and consider what these imply about the galaxies. The particular emission line shown here traces star formation, so we can see where galaxies were forming stars 10 billions years in the past. 

<img src="images/paper3/Ha_Maps.png?raw=true"/>

A second emission line can be used to determine the locations of dust in these galaxies, which has been the focus of my thesis. From all of this work, I conclude that these galaxies have clumpy dust and star formation - these galaxies are messy, with no uniform pattern to dust distribution and star formation. These findings have implications for how galaxies grow and evolve into what we see in the universe today, including our own Milky Way Galaxy.  

### 4. Broadening otheur View to 70,000 Galaxies

After verifying the power of this technique with the smaller sample, I now broaden the project to include galaxies that don't have spectroscopic observations. I considered a number of factors in selecting this sample: galaxy distances need to be known to a high enough degree of accuracy such that their emission lines will be detectable. Furthermore, the lines need to be strong enough to have a reliable measurement. The results of this careful selection are shown below. 

<img src="images/paper3/Select_Phot_Sample.png?raw=true"/>
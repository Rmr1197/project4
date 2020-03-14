# Project 4: Hydrophone Project
Robert Reiten 

11 March 2020

Hydrophone Project

Code Link
https://github.c

## Problem Statement

#### Part 1 Wind and Rain Noise

We are to answer questions that involve hydrophone data

7) In each site and for each category that you identified in step 3, plot 𝑃𝑆𝐷𝑑𝐵 vs frequency 

8) Compare the spectral levels and answer these questions:

a) What is the effect of wind and rain on underwater noise? Explain any behavior you observe in your result.

b) Which one has the highest impact? Rain or wind?

c) What are the main reasons for observing different spectral levels in Oregon shelf compared to Oregon offshore?

#### Part 2 Airgun, Marine Mammals, Earthquake/Volcano Noise

In this part, data can be at any time from any location listed in this link.

1) Find a short time period that there is a marine mammal vocalization in recorded data and plot its spectrogram.

2) Find a short time period that there is an airgun noise in recorded data and plot its spectrogram.

3) Find a short time period that there is an earthquake or a volcano eruption in recorded data and plot its spectrogram.

4) Compare the bandwidth of these three signals. Are they consistent with what is shown in the Wenz curve?

## Solution - Part 1

### 7) In each site and for each category that you identified in step 3, plot 𝑃𝑆𝐷𝑑𝐵 vs frequency

<img src="https://github.com/Rmr1197/project4/blob/master/Images/1.PNG" height="250" width="350">

		Figure 1: 𝑃𝑆𝐷𝑑𝐵 vs Frequency - Oregon Shelf - No wind and no rain - March 13 2019
		
<img src="https://github.com/Rmr1197/project4/blob/master/Images/2.PNG" height="250" width="350">

		Figure 2: 𝑃𝑆𝐷𝑑𝐵 vs Frequency - Oregon Shelf - Wind and No Rain - January 20 2019
		
<img src="https://github.com/Rmr1197/project4/blob/master/Images/3.PNG" height="250" width="350">

		Figure 3: 𝑃𝑆𝐷𝑑𝐵 vs Frequency - Oregon Shelf - Rain and No Wind - January 7 2019
		
<img src="https://github.com/Rmr1197/project4/blob/master/Images/4.PNG" height="250" width="350">

		Figure 4: 𝑃𝑆𝐷𝑑𝐵 vs Frequency - Oregon Shelf - Wind and Rain - January 1 2019
		
<img src="https://github.com/Rmr1197/project4/blob/master/Images/5.PNG" height="250" width="350">

		Figure 5: 𝑃𝑆𝐷𝑑𝐵 vs Frequency - Oregon Offshore -No wind and no rain - January 13 2019
		
<img src="https://github.com/Rmr1197/project4/blob/master/Images/6.PNG" height="250" width="350">

		Figure 6: 𝑃𝑆𝐷𝑑𝐵 vs Frequency - Oregon Offshore - Wind and No Rain - January 6 2019
		
<img src="https://github.com/Rmr1197/project4/blob/master/Images/7.PNG" height="250" width="350">

		Figure 7: 𝑃𝑆𝐷𝑑𝐵 vs Frequency - Oregon Offshore - Rain and No Wind - January 19 2019
		
<img src="https://github.com/Rmr1197/project4/blob/master/Images/8.PNG" height="250" width="350">

		Figure 8: 𝑃𝑆𝐷𝑑𝐵 vs Frequency - Oregon Offshore - Wind and Rain - January 1 2019

### 8) Compare the spectral levels and answer these questions:


		
### a) What is the effect of wind and rain on underwater noise? Explain any behavior you observe in your result.

Looking at the Oregon Shelf site, we can see that there are lower spectral levels at lower frequencies in cases where there is only rain or only wind. Looking at figures 10 and 11, we observe the range only going up to 108, instead of 120 where it does in the cases of either both wind and rain, or neither of the two, in figures 9 and 12. In a case of no wind and no rain, figure 9, we see that higher frequencies have a higher spectrum level, indicated by the brighter color.

### b) Which one has the highest impact? Rain or wind?

In the Oregon Offshore site, during a period of wind and no rain, figure 15, we see the highest spectrum level for frequencies than any other site at any other period. We also notice that in figure 14, the lack of rain also shows a brighter color representing  higher spectral level. Cases of wind and rain, and no wind and no rain both look very similar in terms of spectral level at this site. 

### c) What are the main reasons for observing different spectral levels in Oregon shelf compared to Oregon offshore?

The offshore site, as the name implies, is offshore. Sites further out can have deeper depths, and cause the sound to reflect less than sites further inshore. 

## Solution - Part 2

In this part, data can be at any time from any location listed in this link.

### 1) Find a short time period that there is a marine mammal vocalization in recorded data and plot its spectrogram.

<img src="https://github.com/Rmr1197/project4/blob/master/Images/17.PNG" height="250" width="350">

		Figure 10: Spectrogram Data for Period of Mammal Vocalization
		
### 2) Find a short time period that there is an airgun noise in recorded data and plot its spectrogram.

<img src="https://github.com/Rmr1197/project4/blob/master/Images/18.PNG" height="250" width="350">

		Figure 11: Spectrogram Data for Period of Airgun Noise
		
### 3) Find a short time period that there is an earthquake or a volcano eruption in recorded data and plot its spectrogram.

<img src="https://github.com/Rmr1197/project4/blob/master/Images/19.PNG" height="250" width="350">

		Figure 12: Spectrogram Data for Period of Earthquake
		
### 4) Compare the bandwidth of these three signals. Are they consistent with what is shown in the Wenz curve?

The Wenz curve here is taken from Ocean Noise and Marine Mammals:

<img src="https://github.com/Rmr1197/project4/blob/master/Images/20.PNG" height="350" width="250">

		Figure 9: Wenz Curve from Ocean Noise and Marine Mammals

1) In the data marine mammal vocalization we notice a range of frequencies of about 200 Hz in the upper 1000 and 800 Hz frequencies that show higher relative spectral levels, around 70. This is consistent with Sperm Whale vocalization found on the spectrogram data below. These whales have a large frequency range around 1000 Hz at spectral levels of 55-65. Biologic noise on the Wenz curve shows a very large range of frequency at high spectral level. The frequency may be consistent, but based just on the Wenz curve, we cannot make a conclusion.

<img src="https://github.com/Rmr1197/project4/blob/master/Images/21.PNG" height="250" width="350">

		Figure 13: Spectrogram Data for Period of Earthquake from Ocean Noise and Marine Mammals

2) According to nih.gov, airguns can produce a wide range of frequencies. Due to this, it is hard to pinpoint specific cases of airgun noise. The data I have found contains small patterns which may indicate the repetitive nature of airguns. They are in a higher frequency range, around 0-1000 at the 14 second mark. The closest we can trace airgun noise to on the Wenz curve would be ships/industrial/activity, which confirms our findings, coming in at anywhere from 10-10000 Hz, with high spectral density.

3) When looking at Earthquakes we refer to the Wenz curve. Earthquakes range from 0-100 Hz frequency and have a higher spectrum level around 150. Looking at our data we can see that there is some seismic activity at the 17 second mark, that shows frequencies of around 20-70 Hz. The spectrum level may confirm our findings, although coming in at a lower level, it still shows relatively higher levels than ambient levels. We know that this higher spectral density at lower frequency is a good case for seismic activity. 

## References

L. Hermannsen, J. Tougaard, K. Beedholm, J. Nabe-Nielsen, and P. T. Madsen, “Characteristics and Propagation of Airgun Pulses in Shallow Water with Implications for Effects on Small Marine Mammals,” PloS one, 27-Jul-2015. [Online]. Available: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4516352/. [Accessed: 14-Mar-2020].

Ocean noise and marine mammals. Washington, D.C.: National Academic Press, 2003.

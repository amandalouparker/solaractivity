## Solar activity and UFO reports
This project explores whether solar activity (sunspot observations) can predict UFO reports or other light/percpetual phenomena as it does the aurora. 

#### About

There is reason to believe that UFO reports can be attributed to natural phenomena. 

* Numerous pop culture articles on the internet link UFO reports to activity from the sun. The visual appearance of sunspots shares similarities with sun-linked UFO reports (for example seeing a number of black disks 'fly' across the sun).

* The academic literature contains some references to a correlation between solar activity and UFO reports, but there is sparse recent research.  

* Atmospheric and solar conditions are linked to unusual light phenomena like lightning balls and the aurora, which may be reported as UFOs. 

This analysis revisits the link between solar activity and UFO reports with more recent (and larger) UFO data set than used previosuly along with sunspot observation data from the Royal Observatory of Belgium website http://sidc.oma.be/silso/. The UFO data analysed was mostly collected through an online reporting database NUFORC.org and covers the period of the internet (1996-onwards) increasing report rates. Data older than the nuforc.org website registration in 2001 was presumably added manually.


#### Details

Compares monthly UFO signtings and sunspot activity (sunspot observations) data from 1997 - 2016 

Sunspot data: http://sidc.oma.be/silso/newdataset source: (SILSO data/image, Royal Observatory of Belgium, Brussels)

UFO data: http://www.nuforc.org/webreports.html 

![image](https://raw.githubusercontent.com/amandalouparker/solaractivity/master/imgs/UFOsunspots_1997-2016.png "UFO and sunspots 1997-2016")

** Signal coherence **
Test coherence between the UFO and sunspot observations at diff. frequencies

![image](https://raw.githubusercontent.com/amandalouparker/solaractivity/master/imgs/UFOsunspots_freqCoherence.png "UFO and sunspots signal coherence")

** Granger test of causality**
Granger test if historical sunspot counts can predict UFO sightings

![image](https://raw.githubusercontent.com/amandalouparker/solaractivity/master/imgs/UFOsunspots_granger_pvals.png "UFO and sunspots granger p values")

**Time series decomposition**
Decompose timeseries into seasonal, trend and residual components. 
![image](https://raw.githubusercontent.com/amandalouparker/solaractivity/master/imgs/UFOsunspots_timeseries.png)

** Auto correlation **
Test patterns within UFO and sunspot time series with auto-correlation

#### Results
Granger tests of the total sunspot number to predict UFO report frequency were not significant. However, the count of sunspot obersvations (shown in graphs) did appear to significantly predict UFO reports at lags of 1-12 months. This is consistent with the signal coherence result and points to a seasonal trend. UFO reports over time appears relate to sunspot report count, but not total sunspots recorded.

The time series decomposition shows seasonal trends in both data sets, testing significant with the Granger test. When the seasonal component was removed, only the seasonal and residual components alone remained significantly in sync - the time series with the seasonal component removed and the trend component alone did not significanty correlate across the two report sets. It's possible that seasonal variations in human behavior (reporting the observations) or atmospheric conditions that effect visibility are involved. These questions can be explored with intersecting data sets. 


#### Further questions
* Does UFO sighting duration vary in any systematic way?
* Likewise the shape of the reported UFO
* Location: does longitude/lattitude of UFO report shift with solar activity?
* Effect of internet on increase in UFO reports
* Add aurora activity/sightings data

#### References
Geophysical Variables and Human Behavior: XVIII. Expected Perceptual Characteristics and Local Distributions of Close UFO Reports
M. A. Persinger, June 1, 1984 Perceptual and Motor Skills, Vol 58, Issue 3, 1984 (& 1983 article same Author/Journal)
http://journals.sagepub.com/doi/abs/10.2466/pms.1984.58.3.951

Data Analysis of Anomalous Luminous Phenomena in Hessdale. Massimo Teodorani & Erling P Strand, 2001. European Journal of UFO and Abduction Studies, Vol 1(2) pp 64-82
http://www.itacomm.net/ph/hess_e.pdf

Monthly sunspot number time series analysis and its modeling through autoregressive artificial neural network

http://www.rense.com/general3/sunufo.htm

http://www.nuforc.org/webreports.html 

Sunspot data: http://sidc.oma.be/silso/newdataset source: (SILSO data/image, Royal Observatory of Belgium, Brussels)

Pop culture:

http://www.express.co.uk/news/nature/576454/UFO-monster-ship-draining-solar-power-Sun-NASA-footage

http://www.dailymail.co.uk/sciencetech/article-3477355/Aliens-controlling-SUN-UFO-hunters-claims-spotted-strange-ships-near-solar-surface.html

http://www.livescience.com/19024-refueling-ufo-solar-prominence.html



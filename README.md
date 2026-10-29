# DreamTeam_AcousticSensor

## Variables
* Signal Length 
* Sampling Frequency (# of samples a second)
* n from 0 to sample length -1, incremented by 1

## Functions 
* Gave the program a discrete time vector and plotted the given signal in time domain. If we're sampling, we'll be using discrete time signals rather than continuous. 

* Gave the program a discrete time vector, used a Fourier Fast Transform to give signal in freq domain and plotted it. 

* Used a bandpass to attenuate all frequencies outside of 3000 & 4000 Hz. Line 20 accounts for negative frequency pairs, which would fall OUT of our desired range, thus should be accounted for in Filter

## Plots
* Used subplot function to get all desired plots in one tab. Original signal on top, following DFT spectrum and lastly our filtered signal. 

* There is only one magnitude above 0 which is the only datapoint within our desired range.
   * All other frequencies have been successfully attenuated.   :) 

   

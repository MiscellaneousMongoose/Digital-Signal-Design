check powerpoint "week 10 powerpoint" on page 4 for Butterworth Filter

note: Butterworth Filter 16th order fcs at 135 and 180 meet at height 0.01
## List of Things to Figure Out

1. type of filter to use, the current likely canidate is the Butterworth Filter
2. what order filter will be used, this will be based on things like the type of filter and the delay
3. how much delay should be allowed and how to decrease it, delay from my memory will increase with the order of the filter and we need to 
determine how much will result from an increase in filter order and how much we should allow before the game starts to feel off
4. what cut off frequency should be used for the filter, I found that The voiced speech of a typical adult male will have a fundamental 
frequency from 85 to 155 Hz, and that of a typical adult female from 165 to 255 Hz so in desmos graphing calculator I used an fc = 155
5. Should a modulator be used to square the filter output or something else

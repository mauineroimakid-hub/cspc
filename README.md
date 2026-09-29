hey
 for pw1 A 
Pure-Python loop: 3.9602 seconds
NumPy version:     0.0003 seconds
NumPy is 12278.57 times faster

for pw1 B 
The observed data followed the same general value as the analytical decay law although the measured points didnt match the theoretical curve exactly

The Snakemake pipeline uses decay_observed.csv as input and runs plot.py to automatically generate figure.png

for PW2 labA while calculation mean value of acceleration we expected value around -9.8 but got -6.5 I ve checked the code and freefall.csv file and didnt noticed anything wrong so its probably related with the fact that derivative works not with value itself but at the rate of them.(gradient part)I mean differentation amplifies the noise.Standard deviation: 30.908825280977943
The noisy acceleration was integrated twice to recover velocity and position. The recovered position differed from the original by a maximum of 0.785 m, showing that integration suppresses random noise.

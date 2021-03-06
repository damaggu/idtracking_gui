# Idtracking GUI accompanying SIPEC

## usage

start the gui by simply running
```
  python gui.py
```

in bash current steps taken are displayed until the gui pops up.
Now basically everything is controlled in the keyboard.

The first image is the first mask, which is indicated as a green rectangle.
So the ID needs to be determined for that individual.
To go forward or backward in the video press
```
  n - for next frame (hold to see video)
  p - for previous frame
```

Now, to label the id use the numbers 1 to 4, which should be tied to the identity
of the primates (i.e. 1 - Bob, 2 - John, ...)
So after identifying the animal press Numbers 1 to 4.
If you are unsure follow the rule: in doubt - leave it out! and press
```
  d - for doubt
```
Then the program will just skip to the next mask.


## installation

create a fresh python environment (conda installed previously) with:
```
conda create -n idtracker python=3.6
```
afterwards install necessary packages from requirements file
```
pip install -r requirements.txt 
```
and Done!


## Cite:

If you use any part of this code for your work, please cite the following:

  ```
  SIPEC: the deep-learning Swiss knife for behavioral data analysis
  Markus Marks, Jin Qiuhan, Oliver Sturman, Lukas von Ziegler, Sepp Kollmorgen, Wolfger von der Behrens, Valerio Mante, Johannes Bohacek, Mehmet Fatih Yanik
  bioRxiv 2020.10.26.355115; doi: https://doi.org/10.1101/2020.10.26.355115
  ```

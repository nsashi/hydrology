#Hydrology

##My Hydrology  repository
I use Python and R for managing my workflow in hydrological modelling. This repository is a collection of those codes. You are welcome to use and modify it for your purpose. See [Licence](../master/LICENSE) for terms and conditions.
My contact details are at the bottom of this page.

### Markov chain Monte Carlo(MCMC) estimation of missing wind speed
Use of MCMC to fill missing wind speed values in weather data. [MCMC](../master/wind_speed_had_mcmc.py) 

### Modflow using flopy in linux
#### Modflow Compilation instructions for linux
In makefile, use F90= gfortran .
In openspec.inc
change DATA ACCESS/'SEQUENTIAL'/ to DATA ACCESS/'STREAM'/
change DATA FORM/'BINARY'/ to DATA FORM/'UNFORMATTED'/
#### Simple tutorial for modflow model using flopy
[Flopy tutorial](../master/gw.tut.py)

###Tutorial for stage volume
See the [Stage - Volume Tutorial](../master/stage_volume_tutorial.py).
Check out the comments.  

###3D plotting
For 3D plotting of interpolated stream profile  [Profile Creator](../master/profile_creator.py).

###591 Check dam profile
#### Stage - Surface Area relationship
The stage(water height) vs water surface area relationship is calculated in this file [591 Check Dam](../master/profile_creator_591.py).
This file does following functions:
 1. Fills in between profiles.
 2. Creates x,y,z grid from profile.
 3. Creates interpolation of uniform grid.
 4. Creates a contour and 3D surface plot from the interpolated data.
 5. Calculates the contour area for given elevation levels.
 6. Plot of surface area vs stage.

###Contact
For related queries please mail: haran.kiruba@gmail.com

<a href="http://stackoverflow.com/users/2632856/kirubaharan-j">
<img src="http://stackoverflow.com/users/flair/2632856.png" width="208" height="58" alt="profile for Kirubaharan J at Stack Overflow, Q&amp;A for professional and enthusiast programmers" title="profile for Kirubaharan J at Stack Overflow, Q&amp;A for professional and enthusiast programmers">
</a>

![Contact](http://i.imgur.com/C9rENMG.png)
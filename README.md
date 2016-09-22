# Chevalier
Two profiles after the model of [Chevalier 1982](http://adsabs.harvard.edu/full/1982ApJ...259L..85C). The first is a 1.4 solar mass Type Ia model (no circumstellar medium) and the other is a 15 solar mass Type II model (circumstellar medium with power-law index of -2). You can view these plots with [`gnuplot`](http://www.gnuplot.info/) (or something similar). It'd be useful to chage the y-axis to be log-scale.

These were generated with a numerical model heavily based on work by several others, so I do not really intend on storing the code for it since it's not really mine. If you really want a specific model, send me an email with the following specs:

 - adiabatic index
 - age of remnant (in years)
 - Energy of blast (in foe)
 - mass of initial star
 - power law index of SNR
 - power law index of ambient medium (usually 0 for no medium and -2 for circumstellar medium)
 - density of ambient medium (typically this the data is scaled such that this is 1)
 - temperature of SNR
 - temperature of ambient

Hopefully I will be able to email you back within a couple days (but no promises, as I'm not an active astrophysicist anymore).

-------
This work was part of my dissertation on particle acceleration in supernova remnant environments. I mapped the 1D solutions to a 2D grid and allowed the hydrodynamic solver to evolve these forward in time.

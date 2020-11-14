# PHON
Program to compute phonons 

INSTALLATION PROCEDURE

* copy incs/make.inc.$system in make.inc. Systems available at present are
  g95, linux_ifort, sun, sgi, linux_pg, ibm. I have only tested g95, linux_ifort
  and sun. 

* type make 

* it has been reported that on some system the gfortran or the g95 compiler may 
  have problems compiling the code or cause it to hang at execution time. If this
  happens, try to remove the optimisation flags in the make.inc file and recompile

* Please send me a message with your e-mail, so that I can inform you of updates
  and bug fixes.

* If you use this code to publish scientific results please include the following citation: 

D. Alfe`, "PHON: A program to calculate phonons using the small displacement method",
Computer Physics Communications, Vol. 180, No. 12, pp. 2622-2633 (2009) 
doi:10.1016/j.cpc.2009.03.010; Program available at http://chianti.geol.ucl.ac.uk/~dario

* For installation simplicity, the distribution includes BLAS and LAPACK routines, which are 
released under their own licence.

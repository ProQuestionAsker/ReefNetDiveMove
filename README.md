# ReefNetDiveMove
For use with the ReefNet Sensus Ultra dive tags and the DiveMove package within the R environment


This code was written to analyze the data collected from ReefNet Sensus Ultra dive tags, which were deployed on harbor seal pups in an rehabilitation center.  It utilizes the diveMove package (version 1.3.5) within the R environment. 

diveMove Package: https://github.com/spluque/divemove or http://cran.r-project.org/web/packages/diveMove/index.html

This code defines a "dive" as a period of time spent below 0.3 m.

It returns dive stats which include daily statistics: 
  Beginning and ending times of each day
  Duration of dive
  Post-dive duration (i.e. the time spent between one dive and the next)
  Maximum depth
  The number of dives detected within that day
  Wet phases (i.e. the number of time periods throughout the day that the animal spent making consecutive dives     without spending time outside of its pool.)
  
  
  All other terms follow the same nomenclature as described by the diveMove package.  

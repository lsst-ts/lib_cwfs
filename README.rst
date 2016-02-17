===============================
Curvature Wavefront Sensing Algorithm
===============================

.. image:: https://img.shields.io/travis/lsst-ts/cwfs.svg
        :target: https://travis-ci.org/lsst-ts/cwfs

.. image:: https://img.shields.io/pypi/v/cwfs.svg
        :target: https://pypi.python.org/pypi/cwfs


-----------------------------------------------------------
Curvature Wavefront Sensing (CWFS) Software v1.0
------------------------------------------------------------

    This software package consists of a set of Python codes that take a pair of defocused star images equally spaced on both sides of the optical focus, and calculate the incoming wavefront. The underlying baseline algorithms implemented are the iterative FFT method by the Roddiers and the series expansion based method by Gureyev and Nugent. We have made several modifications to make them work for LSST, to overcome challenges including a highly obscured pupil, the fast f-number, pupil distortion and vignetting at the field corners, and variation of the wavefront over the area covered by the split-sensors.
	    
    Please reference Xin et al., Appl. Opt. 54, 9045-9054 (2015). 

    Note that the off-axis corrections and pupil geometry as functions of field position are specific to each telescope. We have modelled these for LSST. The data can be found in data/lsst/. It may require some additional work to model these properly for your application.
	
    Authors:    Bo Xin, Chuck Claver
Large Synoptic Survey Telescope (LSST)

We'd like to thank Andy Connolly and Michael Reuter for the help with Python programming.



.. image:: /images/stsci_pri_combo_mark_white_bkgd.png
   :align: center
   :scale: 8

|
|
|

===================================
The STAK Project
===================================
Space Telescope Astronomy Kit (STAK), a resource for Python astronomy software and tutorial materials.

The new and improved Python version
===================================
The `Space Telescope Science Data Analysis System (STSDAS) <http://www.stsci.edu/institute/software_hardware/stsdas>`_ was a software package for reducing and analyzing astronomical data, layered on top of IRAF. The Space Telescope Science Institute has begun the effort to transition critical and requested parts of the STSDAS package, along with other IRAf libraries, into python.  Although the name will stay the same, the STAK package will *not* be a direct copy of the STSDAS package, but instead will work to use the improved techniques and algorithms that exists in the astronomy Python ecosystem, relying heavily on the use of the Astropy project.  In addition to writing replacement functionality where needed, we are also providing the community with short tutorials on how to translate a large portion of IRAF tasks into Python through the format of Jupyter Notebooks.

**Important Note: The HST and JWST pipelines will NOT be part of this package, unlike the IRAF STSDAS package.**

|

We want your input
==================
We would love to hear feedback from the community, included but not limited to:

* What IRAF tasks do you use the most?
* Which IRAF tasks have you had trouble finding a Python equivalent for?
* What do you miss most about IRAF when not using it?
* What do you feel is missing from the Python ecosystem that might help astronomers transition from IRAF to Python?

You can send us any comments or questions at our **echo page**
  
|

STAK Package Documentation
============================

.. toctree::
  :maxdepth: 2

  stak/index.rst
  notebooks/index.rst

DES_phosim
==========

This repo host code and files to run the LSST phosim as DES... 

Code for LSST phosim can be found here: https://dev.lsstcorp.org/cgit/LSST/sims/phosim.git/

One will need to install LSST phosim and put the directory des/ 
under data/ in the LSST phosim master directory. Then to run LSST 
phosim as DES, try:

phosim -i des

The files in this repo include...

PhoSim required:
- focalplanelayout.txt
- segmentation.txt
- filter_X.txt (X=0,1...4)
- optics_X.txt (X=0,1...4)
- lenses.txt
- mirror.txt
- detectorar.txt
- spider.txt

Original documents:
- ZEMAX files
- orientation document
- Antonik et al 2012
- DECam overview paper


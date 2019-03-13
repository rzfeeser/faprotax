# faprotax

### Visit the project homepage @ http://www.zoology.ubc.ca/louca/FAPROTAX/lib/php/index.php?section=Home

### Summary

One of my nerd buddies asked me to help her get the "Functional Annotation of Prokaryotic Taxa (FAPROTAX)" working on her system. Below are my notes on getting the project working.

Ubuntu 18.04 LTS installation instructions:

  - `sudo apt install python3-pip`
  - `python3 -m pip install numpy`
  - `python3 -m pip install biom-format`
  - `python3 -m pip install h5py`
  - `vim` 
  - Copy & paste in
  - Save & exit with `:wq`
  - `python3 .py`

Bug Fixes:
  - Removed mix of spaces and tabs (all tabs)
  - Updated print statements to functions (py2 to py3 fix)
  - tested on python 3.7

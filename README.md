# faprotax

### Summary

One of my nature nerd buddies asked for help using the, "Functional Annotation of Prokaryotic Taxa (FAPROTAX)". Below are my notes on getting the project working on Ubuntu 18.04, Windows 10, and one of those fancy silver machines made by Tim Apple.

I've made a few bug fixes thus far, and ensuring it can now run in Python 3.x so I suppose this is my own tiny fork of the FAPROTAX project.

Start with a review the FAPROTAX homepage @ http://www.zoology.ubc.ca/louca/FAPROTAX/lib/php/index.php?section=Home I'm not sure if the project is currently maintained, as it references, "...maybe working on Python 3...".

**Ubuntu 18.04 LTS installation instructions:**
  - `sudo apt install python3-pip`
  - `python3 -m pip install numpy`
  - `python3 -m pip install biom-format`
  - `python3 -m pip install h5py`
  - `python3 collapse_table.py` (avail in my repo)


**Windows 10 installation instructions (not yet working):**
  - goto python.org and install python 3.7
  - google pycharm and install pycharm community edition
  - install microsoft visual studio https://visualstudio.microsoft.com/thank-you.../... run the executable and select / install the "top left one" (it'll make sense when you run it). I think its' called "build tools c++ 2017". My brain is telling me It's about 4.5ish gigs. Then on the right, ALSO click "VC++ 2015 v14.0blablablabla". I think this will add another 4 or so gigs to the install. 
  - Run pycharm / start a new project --> save it as, "biggulpshuh"
  - CLICK: File > new python file > name it "alpastor_is_the_best_taco_tables.py"
  - CLICK: File > Settings > Project: biggulpshuh > Project Interpreter > click the "+" and search for the following
  - numpy (press INSTALL button)
  - biom-format (press INSTALL buttom) **breakdown in install here... thoughts on moving forward... try Ubuntu shell for windows?**

**Bug Fixes:**
  - Removed mix of spaces and tabs (all tabs)
  - Updated print statements to functions (py2 to py3 fix)
  - tested on python 3.7

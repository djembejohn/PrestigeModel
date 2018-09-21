# PrestigeModel

There are currently two versions, when I get a moment I'll split them
out into a library.

Both require Python 3

**PrestigeModelSimple.py**

Requires numpy and matplotlib as well. To recreate the results from the paper, try

python PrestigeModelSimple.py -q 0.5 --plot

python PrestigeModelSimple.py -q 0.53 --plot

python PrestigeModelSimple.py -q 0.54 --plot

**PrestigeModel.py**

This also needs graph-tool. https://graph-tool.skewed.de/ It can need a lot of time/memory to compile and install.

Software is copyright to John Bryden under GPL 3. Please don't publish any results generated using this code, or the underlying model, without John's permission.

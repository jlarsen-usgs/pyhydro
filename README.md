D-Any
-----
"D-Any" is a python package that performs hydrologic conditioning, 
flow accumulation, and stream network creation on structured (rectilinear) and 
unstructured grids

"D-Any" is compatible with `FloPy` and uses FloPy's grid objects for mapping
grid networks. Compatibility patches are also included with "D-Any" for use
with pyGSFLOW's model builder methods. 

Installation
------------
In a command prompt/terminal window run

```commandline
pip install https://github.com/jlarsen-usgs/pyhydro/archive/refs/heads/main.zip
```


Importing and using "D-Any"
---------------------------
```python
from dany import fill_sinks, FlowDirections, PrmsStreams, Sfr6, Sfr2005
```

For the time being, please refer to the python scripts in the development 
folder for `dany` usage. The `sagehen_unstructured.py` script is a complete
example from DEM to a hand calibrated PRMS model.

Full example notebooks are coming soon

Development Status
------------------
Development is ongoing for the first release of "D-Any", current development
plans include:
   - autotesting infrastructure
   - example notebooks
   - pypi / conda release


Disclaimer
----------
This software is preliminary or provisional and is subject to revision. It is 
being provided to meet the need for timely best science. This software is 
provided "as is" and "as-available", and makes no representations or warranties 
of any kind concerning the software, whether express, implied, statutory, or 
other. This includes, without limitation, warranties of title, 
merchantability, fitness for a particular purpose, non-infringement, absence 
of latent or other defects, accuracy, or the presence or absence of errors, 
whether or not known or discoverable.
# BIOMD0000000172: Pritchard2002_glycolysis

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000172.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000172.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000172 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


from:  
**Schemes of fluc control in a model of _Saccharomyces cerevisiae_ glycolysis **

**Pritchard, L and Kell, DB** _Eur. J. Biochem._ 269(2002), 3894-3904.   
It represents a modified version of **Teusink et al.** _Eur. J. Biochem._
267(2000), 5313-5329.  
The model is a translation from the GEPASI file encoded by Leighton Pritchard.  
This version uses the Vmaxes found by the best fit (R1) of Table 1 of the
Pritchard and Kell paper and simulates a decrease of external glucose
concentration from 100 to 2 mM.  
To reproduce the values in table 2 of the publication, set _GLCo_ to 50 mM and
compute the steady state.

  

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not.

  

To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)



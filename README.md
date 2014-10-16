# MODEL1006230001: Fallon2000_IL2dynamics

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1006230001.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1006230001.git@20140916`

## Usage

Importing the model package.

`import MODEL1006230001 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Computational model for effects of ligand/receptor binding properties on interleukin-2 trafficking dynamics and T cell proliferation response.**   
Fallon EM, Lauffenburger DA. _Biotechnol Prog_ 2000 Sep-Oct;16(5):905-16
[11027188](http://www.ncbi.nlm.nih.gov/pubmed/11027188) ,  
**Abstract:**   
Multisubunit cytokine receptors such as the heterotrimeric receptor for
interleukin-2 (IL-2) are ubiquitous in hematopoeitic cell types of importance
in biotechnology and are crucial regulators of cell proliferation and
differentiation behavior. Dynamics of cytokine/receptor endocytic trafficking
can significantly impact cell responses through effects of receptor down-
regulation and ligand depletion, and in turn are governed by ligand/receptor
binding properties. We describe here a computational model for trafficking
dynamics of the IL-2 receptor (IL-2R) system, which is able to predict T cell
proliferation responses to IL-2. This model comprises kinetic equations
describing binding, internalization, and postendocytic sorting of IL-2 and IL-
2R, including an experimentally derived dependence of cell proliferation rate
on these properties. Computational results from this model predict that IL-2
depletion can be reduced by decreasing its binding affinity for the IL-2R
betagamma subunit relative to the alpha subunit at endosomal pH, as a result
of enhanced ligand sorting to recycling vis-a-vis degradation, and that an
IL-2 analogue with such altered binding properties should exhibit increased
potency for stimulating the T cell proliferation response. These results are
in agreement with our recent experimental findings for the IL-2 analogue
termed 2D1 [Fallon, E. M. et al. J. Biol. Chem. 2000, 275, 6790-6797]. Thus,
this type of model may enable prediction of beneficial cytokine/receptor
binding properties to aid development of molecular design criteria for
improvements in applications such as in vivo cytokine therapies and in vitro
hematopoietic cell bioreactors.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Fallon EM, Lauffenburger DA. (2000) -
version=1.0**
](http://models.cellml.org/exposure/eac0440dc434d67337eb835402f5ab5f)  
The original CellML model was created by:  
**Catherine Lloyd**   
c.lloyd@auckland.ac.nz  
The University of Auckland  

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)



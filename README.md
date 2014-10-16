# MODEL1308080003: MODEL1308080003

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1308080003.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1308080003.git@20140916`

## Usage

Importing the model package.

`import MODEL1308080003 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes
References: 1\. Xiaomei Zhu, Lan Yin, Leroy Hood, David Galas and Ping Ao,
Efficiency, Robustness and Stochasticity of Gene Regulatory networks in
Systems biology: Lambda switch as a working example, 2006. 2\. Adam Arkin,
John Ross and Harley H. McAdams, Stochastic kinetic analysis of developmental
pathway bifurcation in phage lambda-infected Escherichia coli cells, 1998,
Genetics, 149: 1633-1648. 3\. GenBank sequence: NC_001416 is the whole genome
sequence of phage lambda.



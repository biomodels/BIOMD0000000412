# BIOMD0000000412: Model_1

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000412.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000412.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000412 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
**The clock gene circuit in Arabidopsis includes a repressilator with additional feedback loops**   
Pokhilko A, Fernández AP, Edwards KD, Southern MM, Halliday KJ, Millar AJ.
_Mol Syst Biol._ 2012 Mar 6;8:574.
[22395476](http://www.ncbi.nlm.nih.gov/pubmed/22395476) ,  
**Abstract:**   
Circadian clocks synchronise biological processes with the day/night cycle,
using molecular mechanisms that include interlocked, transcriptional feedback
loops. Recent experiments identified the evening complex (EC) as a repressor
that can be essential for gene expression rhythms in plants. Integrating the
EC components in this role significantly alters our mechanistic, mathematical
model of the clock gene circuit. Negative autoregulation of the EC genes
constitutes the clock's evening loop, replacing the hypothetical component Y.
The EC explains our earlier conjecture that the morning gene PSEUDO-RESPONSE
REGULATOR 9 was repressed by an evening gene, previously identified with
TIMING OF CAB EXPRESSION1 (TOC1). Our computational analysis suggests that
TOC1 is a repressor of the morning genes LATE ELONGATED HYPOCOTYL and
CIRCADIAN CLOCK ASSOCIATED1 rather than an activator as first conceived. This
removes the necessity for the unknown component X (or TOC1mod) from previous
clock models. As well as matching timeseries and phase-response data, the
model provides a new conceptual framework for the plant clock that includes a
three-component repressilator circuit in its complex structure.



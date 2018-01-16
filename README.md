# Cross-referencing Boston Police Department's spending against the Surveillance Industry Index

This project cross-references Boston Police Department's spending, sourced from [Boston's Checkbook Explorer](https://spending.data.boston.gov), against companies listed on the [Surveillance Industry Index](https://sii.transparencytoolkit.org/).

The code is written in a [Jupyter](http://jupyter.org/) notebook and should hopefully be self-explanatory. A standard IPython 2.7 data analysis stack (including pandas) should be all that's necessary. The dependency on pandas can be eliminated with little effort.

Included in the repo:

* `ledger.csv`, a download of the Checkbook Explorer spreadsheet taken 2018-01-07;
* `sii.html`, a copy of the Surveillance Industry Index's homepage saved 2018-01-07;
* `bpd_sii.ipynb`, the actual code;
* `purchases.csv`, a list of BPD purchases matching vendors listed on the Surveillance Industry Index, from the above two source files.

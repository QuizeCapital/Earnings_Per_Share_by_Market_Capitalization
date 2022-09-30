# Quantitative Investment Research (Smart Factor) : Earnings Per Share (EPS) by Market Value (MV)

## Overview
This repository is home to files used in conducting a 5 level Quintile Research where i try to determine the relationships between the Earnings per share growth and Market Value of specific quintiles. Quintiles here is defined by splitting relevant data (first factor) eg. market value, free cash flow per share, earnings per share etc. into a number of portfolios which is used as reference for our second factor.

## How to Replicate the Research
1. Download and Edit the dataset paths as needed
2. Download and Edit the modules path as needed
3. Run the main python file (stated below)

> ......../EPS/templates/Market Value by Earnings per Share.py

Alternatively, you can clone the repository and restructure as necessary. Via 
the command line,

```
> git clone git@github.com:QuizeCapital/EPS 
```
## Layout

The repository is split into five main directories,which may/may not have subdirectories. This structure has been designed to be easily navigable by humans and computers alike, allowing for rapid location of specific files and instructions. Within each directory is a `README.md` file which summarizes the purpose of that directory as well as some examples where necessary. Each section is briefly described below. 

<!--  * **`exploratory`**: A sandbox where you keep a record of your different approaches to transformation, interpretation, cleaning, or generation of data.
 * **`figures`**: Any code used to generate figures for your finished work, presentations, or for any other use. -->

### **`data`** 
This directory houses all small (< 100 MB) data sets that are a result of API downloads from different sources. All datasets are mostly sourced from https://site.financialmodelingprep.com/developer/docs/. 
### **`miscellaneous`** 
Files that may not be code, but are important for reproducibility of this project's findings.

### **`Results and Tests`** 
Summary of Results and tests suites for the code. 

### **`Code`** 
Custom code  written that is executed directly and some code that is called from files in the other directories. 

### Required Files
These are files considered to be mandatory for this project.

1. **`LICENSE`**: A legal protection of your work. *It is important to think deeply about the licensing of your work, and is not a decision to be made lightly. See [this useful site](https://choosealicense.com/) for more information about licensing and choosing the correct license for your project.*

2. **`README.md`**: A descriptive yet succinct description of your research project and information regarding the structure outlined below.

# License Information

<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <a rel="dct:publisher"
     href="github.com/gchure/reproducible_research">
    <span property="dct:title">Griffin Chure</span></a>
  has waived all copyright and related or neighboring rights to
  <span property="dct:title">A template for using git as a platform for reproducible scientific research</span>.
This work is published from:
<span property="vcard:Country" datatype="dct:ISO3166"
      content="US" about="github.com/gchure/reproducible_research">
  United States</span>.
</p>
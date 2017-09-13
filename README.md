# mgc
R package for MGC code


## Installation:

The following installation has been checked on a fresh Ubuntu 16.04 instance with R version 3.4.1 installed.

### Set up `devtools` package for R:

From an R terminal (or GUI such as RStudio), type:

```
install.packages('devtools')
```

Optionally, set up the `fmriutils` package (required for several tutorials) following the [fmriutils-repo](https://github.com/neurodata/fmriutils) install instructions.

### Install the `MGC` package:

Still from your R terminal (or GUI such as RStudio), type:

```
require(devtools)
install.packages(c('ggplot2', 'reshape2', 'Rmisc'))
install_github('ebridge2/mgc')
```

## Demo

### Discriminability

```
library(MGC)
```

Check out our demo tutorial for applying discriminability to fMRI data at [discriminability-mri analysis](http://neurodata.io/mgc/discriminability_brains.html).

### MGC
Into your R console, type the following:

```
library(MGC)
run_demo()  # runs the MGC demo
```
which takes < 10 seconds to run, which shows the actual MGC and p-value for testing on linear and quadratic data.

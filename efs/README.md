# edl3.0 - a better way to predict student loan default rate

Welcome to edl3.0

This file introduces you to edl3.0 R package. This package is used for the easy to use functions that predicts the student loan default rate.

## Package information

**Package Name**: edl3.0

**Title**: edl3.0 - predict student loan default rate

**Version** : 3.0

**Author**: Sanatan Das

**Description**: The edl3.0 package is used to predict the student loan default rate.

**Depends**: R (>= 3.4.3)

**License**: GPL

**Encoding**: UTF-8


## Pre-requisites

You should have the below packages installed in your R environment to install the edl3.0 package as it has dependencies on these packages.

* tidyverse
* readxl
* broom
* knitr
* earth
* devtools

## Installation

    install_github('sanatanonline/edl3.0')
    library('edl3.0')
	
After you have successfully installed you can call the predict default rate function passing the test data as input. You can see the help for more details using the below command.

    ?predict_default_rate

## Test Data

You have to use the following columns to create a test data frame.

* OPEID - Office of Postsecondary Education Identifier
* Name - Institution's Name

You can pass the test data as a data frame with following information.

For more details about edl3.0, see https://github.com/sanatanonline/csx415-project/tree/master/efs

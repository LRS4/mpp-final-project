## Feature Engineering

A key step in order to boost the accuracy of the model was to understand the lender acceptance rate (%) i.e. proportionately how many people each lender had accepted or declined. In order to do this:

* I created a pivot table in 'train_X' to calculate accepted vs declined and calculate that as a percentage.
* Used those calculations to form a lookup table
* Applied the lookup table to each 400,000 observations using a VLOOKUP function.

Within 'train_X' worksheet (not csv) this can be viewed in tab 1.
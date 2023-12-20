# Toy-Calib

## Study 1: LR calibration to 

Building up a soltuion... there's q a bit of duplicated code, just b/c I was trying to cross check each step

- `Calib-LR-no-pT.ipynb` : LR for 1d SF
- `Calib-LR-no-pT-bkg.ipynb`: Adding in a bkg component, which we subtract off in the LR calculation
- `Calib-LR-with-pT-and-bkg.ipynb` : Now 2d, pT and Dbb

Note, this last nb is still pretty messy b/c there are some cross checks, esp with the analytical formula for the SF that I'm still working on, but I think the ML solutions are right, b/c the tests I'm doing checking the phase space at the sampling and histogramizing level seem to be passing.

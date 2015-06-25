# higgs_spin

Author: Jeff Picard
August 2013

H->gamma gamma spin analysis code
This program analyzes the expected sensitivity to the Higgs
spin measurement.


To run the code:
make
./runMC          (must be run from t3-higgs) (~5 minutes) (writes files in ./tempData )
./runToys        (can take an hour) (writes files in ./tempData )
./runPlots       (instant) (plots are saved in ./plots by default)


Options:
There are no arguments. Edit config.cfg to specify various
options described there.


# Data archive

**Content**: data archive for the result presented in the following paper (submitted):

_On the stability of planetary orbits in binary star systems I. The S-type orbits_

**Authors**: G. De Cesare, R. Capuzzo-Dolcetta

**Contact email**: giovanni.decesare@inaf.it

This repository contains the results for a test particle (_massEqZero_ directory), a Jupiter-mass (_massEqMj_ directory), and 30 Jupiter mass planets (_massEq30Mj_ directory).

The data are published for any binary mass ratio and eccentricity, apllying a common naming scheme. For example, the _csv_ file:

_massEqZero/mu_0.5/e_0.5/0/index_a.csv_

contains the data for a test particle in a binary with a mass ration $\mu = 0.5$ and an eccentricity $e = 0.5$ with binary initially at apoapse (see Table 1 in the paper), at the first initial longitude. Note that the data are defined by the _path_ not by the file name, that is the same for any configuration.

In the _csv_ file the _stability_ flag can have one of the following values:

- _ST_: stable orbit
- _CA_: the planet collides with the primary star after a given (_t_stop_) time
- _CB_: the planet collides with the secondary star
- _EJ_: ejection

**Note:** The repository does not contains the raw file with orbits. Please, ask to the authors if you are also interested to these data.

## How to use the archive

First clone the repository, then use _python_ to read and process the _csv_ files.

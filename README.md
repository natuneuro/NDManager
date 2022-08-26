# NDManager
NDManager (Neurophysiological Data Manager) is a simple graphical application designed to help neurophysiologists manage their experimental recording parameters (e.g., number of channels and sampling rate of the acquisition system) and process their data (data filtering, spike extraction, PCA, etc.)

NDManager was developed by Lynn Hazan in G. Buzsáki's lab (CMBN, Rutgers Newark, USA), and distributed under the GNU Public License v2.

Software compile on Ubuntu 20.04

## Documentation
For more information about this software please read:

- [NDManager handbook](http://ndmanager.sourceforge.net/UserManual/index.html)


## Compile guide

  1. Install [Libneurosuite](https://github.com/natuneuro/neurosuite) and [LibKlustersShared](https://github.com/natuneuro/LibKlustersShared) before compilling NDManager
  
  2. Go to `/NDManager` directory and type:
  ```
  mkdir build
  cd build
  cmake ..
  make
  sudo make install
  ```


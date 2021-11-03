# OpenMX-deb

``` bash
sudo apt install ./openmx_3.9.9-1_amd64.deb ./openmx-data_20211103-1_amd64.deb ./openmx-work_20211103-1_amd64.deb
```

## openmx_3.9.9-1_amd64.deb

A deb file is to install OpenMX 3.9.9.
The default value for a input keyword of `DATA.PATH` is changed to `/usr/share/openmx/DFT_DATA19`.

## openmx-data_20211103-1_amd64.deb

A deb file is to install a database in 2019 of fully relativistic pseudopotentials (VPS) and pseudo-atomic orbitals (PAO), which could be an input data of `openmx`.
It is installed on `/usr/share/openmx/DFT_DATA19`.

## openmx-work_20211103-1_amd64.deb

A deb file is to install a directory containing examples of inputs and computational results.
It is installed on `/usr/share/openmx/work`.
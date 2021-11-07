# OpenMX-deb

1. Download a `deb` file of OpenMX from [v3.9.9-2](https://github.com/Ncmexp2717/OpenMX-deb/releases/tag/v3.9.9-2).
2. Install them with `apt` or `dpkg`.

``` bash
sudo apt install ./openmx_3.9.9-2_amd64.deb
```

## openmx_3.9.9-2_amd64.deb

This is a `deb` file to install OpenMX 3.9.9.
The default value for a input keyword of `DATA.PATH` is changed to `/usr/share/openmx/DFT_DATA19`.

- This `deb` file includes a database in 2019 of fully relativistic pseudopotentials (VPS) and pseudo-atomic orbitals (PAO), which could be an input data of `openmx`.
It is installed on `/usr/share/openmx/DFT_DATA19`.
- Examples of inputs and computational results are also contained.
They are installed on `/usr/share/openmx/work`.

### Others

The `deb` file was prepared on Debian 11 (bullseye).

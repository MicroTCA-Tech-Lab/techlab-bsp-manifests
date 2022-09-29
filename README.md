# Repo manifest for DESY TechLab Boards

Based on [Xilinx Yocto manifests](https://github.com/Xilinx/yocto-manifests)

* Manifests for different Yocto / Vivado releases are on separate branches
* Manifests for different repository servers are in separate .xml files

## TechLab Yocto Layers included here

| Layer Name           | Description                                  |
|----------------------|----------------------------------------------|
| `meta-techlab-utils` | Common, hardware-independent utilities       |
| `meta-techlab-bsp`   | Machine definitions & board support packages |
| `meta-techlab-demo`  | Demo applications & FPGA bitstreams          |

## Supported hardware

Currently supported boards:

| Product Name         | Revision                 | Yocto `MACHINE` name    |
|----------------------|--------------------------|-------------------------|
| DAMC-FMC1Z7IO        | Rev. A                   | `damc-fmc1z7io-rev-a`   |
| DAMC-FMC1Z7IO        | Rev. B                   | `damc-fmc1z7io`         |
| DAMC-FMC2ZUP         | Rev. A, B                | `damc-fmc2zup`          |

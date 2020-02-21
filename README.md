# Leiden Tools

Tools used by LevyLab to interact with Leiden Temperature Control (TC) and Front Panel (FP).

## Installation

Unless otherwise noted, all software is written with LabVIEW. Please install using the [VI Package Manager](https://vipm.jki.net/)

## Usage

[FP to DSC]
- Add FP_to_DSC.vi to the FP.vi source code to write data to the DSC. Works for CF or MNK.

[TC to DSC]
- Add TC_to_DSC.vi to the TC.vi source code to write data to the DSC. Works for CF or MNK.

[Instrument.MNK_TC.lvclass]
- API that overrides the "Get Temperature.vi" method defined by Instrument.Cryostat.lvclass

## Contributing

Please contact [Patrick Irvin](p.irvin@levylab.org)

## License

[BSD-3](https://opensource.org/licenses/BSD-3-Clause)
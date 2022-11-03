# Generic Klipper configuration

This is a global generic Klipper config dedicated to be used on CoreXY printers (and perhaps others with some minor modifications). It's currently used on all my own machines: a Voron V2.4 (V2.1237), a Voron Trident, a custom TriZero, and a heavily modified Prusa i3 MK3s. Other Voron owners have also reported using this config as-is without any problems.

Please keep in mind this is a WIP and the files are beeing updated frequently with new custom features, PRs merged from users or just if I want to. **Do not** take it as a fully compliant config for every machines: look, think, understand and adapt it to your own.

You can reach out in the Voron Discord: i'm **Frix_x#0161**.


## Features

This config is designed to be generic. You can use it on a lot of machines by selecting and enabling the hardware options you need. This also activate automatically the associated macros and process under the hood.

I also tried, when possible, to put all the print settings directly in the Klipper config. My utlimate goal would be to be able to use the same Gcode file (sliced generically) with multiple materials or even share it across multiple printers. That's why I'm use and set firmware retraction in the macros, set pressure advance in the macros, etc...

This config is also known for the **adaptive bed mesh** functionnality that I wrote some time ago, the **custom calibrations macros** for pressure advance, the flow, etc..., the **automated input shaper workflow**, and the **vibrations measurements** macros and scripts.

You can find a [complete list and descriptions of all the features](./doc/features.md) in the doc folder.


## Installation

There is mainly two steps to install this config:
  1. Configure the printer.cfg file to suit the hardware of your machine
  2. Modify and adapt the variables to suit the configuration of your machine

You will find the [complete detailed installation procedure](./doc/install.md) in the doc folder.


## Sponsor the work

I try to stay open to any user needs if it suit and fit this config design. Please open an issue or a PR if you want a specific hardware device or new functionnalities to be supported.

Also, feel free to buy me a coffee or help me buy new hardware to support them in this config :)

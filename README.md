This repository contains pre-build Plasma Mobile packages for the [postmarketOS](https://postmarketos.github.io/) project. It serves as a temporary file host till the official postmarketOS binary repo is setup.

### Installation

Clone the contents of this repository to `~/.local/var/pmbootstrap/packages/`. Afterwards run `./pmbootstrap.py index` from the root of your pmbootstrap installation.

To install the packages into your phone run `./pmbootstrap.py install --add plasma-mobile,plasma-phone-components`.

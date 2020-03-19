[![Bare Conductive](http://bareconductive.com/assets/images/LOGO_256x106.png)](http://www.bareconductive.com/)

# Bare Conductive Keyboard Emulation

Code for the  [Bare Conductive Pi Cap](http://www.bareconductive.com/shop/pi-cap/). Allows you to emulate a keyboard and map keyboard strokes to the Pi Cap's electrodes.

## Requirements
* Requires [python-dev](https://www.python.org/) (`apt-get install python-dev`)
* Requires [WiringPi](http://wiringpi.com/) (`apt-get install wiringpi`)
* Requires [phue](https://github.com/studioimaginaire/phue) (`sudo pip install phue`)
* Requires [Bare Conductive's MPR121 libary for WiringPi](https://github.com/BareConductive/wiringpi-mpr121)

## Install / Build

* Clone the repository and follow the usage instructions.

## Usage

First, find you your [Hue IP](https://www.meethue.com/api/nupnp). Change the IP in the code under `bridgeip`. Make sure you the lamp that you use has the same in the code `light`.
# StarlinkYacht
Notes on how we setup Starlink to operate on our Yacht 

## Yacht Installation

* Starlink Dishy
* Boondocker Power/Ethernet interface
* Router
* Raspberry Pi (BoatPi)

## Shore based setup 

* VDSL Connection to Internet
* Rasperry Pi (ShorePi)

## VPN setup
A VPN is necessary as Starlink does not accept incoming connections

* Wireguard installed on both BoatPi and ShorePi
* ShorePi has Dynamic DNS client (updating ShorePi.southsky.com.au)
* BoatPi initiates VPN connection to ShipPi

  ![ship to shore starlink_1](https://github.com/smr547/StarlinkYacht/assets/4327895/e025d3e8-a7fe-4066-87e4-8c36c33a84c0)

## Experimental setup

![IMG_0813](https://github.com/smr547/StarlinkYacht/assets/4327895/31baf2b5-f973-4af2-9755-d354c4b63cdf)
![IMG_0814](https://github.com/smr547/StarlinkYacht/assets/4327895/cc0ddcbf-9e76-4414-b047-b978a65cebc0)

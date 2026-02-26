# CryMine Dashboard

CryMine is a dashboard designed to centralize the monitoring of a variety of low-powered crypto mining devices, commonly referred to as "lotto" miners, or "home" miners. With a wide number of devices available, and each with their own native interface and varying abilities to monitor the devices themselves, the CryMine dashboard aims to simplify this by creating one interface capable of monitoring these unique devices.

Traditionally, these devices also have very limited storage for performance metrics over time, monitoring of health and functionality, as well as alerts or notifications for notable events. CryMine introduces the ability to store historical data from these devices for time-based comparisons, configuring alerts for notable events, and perhaps, in the future, the ability to interface with home automation to trigger events such as cycling a smart plug to restart a device, or taking devices offline during peak power grid utilization hours.

## Architecture

It is my intention to support a variety of deployment models, from running a Docker container, or a service on a Docker Swarm, to a standalone implementation on a Raspberry Pi or other SBC variants running Ubuntu or Debian.

The first deployment model on the roadmap is Docker support due to it's ability to be deployed on Windows, Mac, and Linux computers, including cheap thin clients like Dell Wyse systems.

The second deployment model will be standalone SBC deployments for devices like the Radxa Rock 4D or Raspberry Pi 4/5, primarily targeting Debian based OSes.


## Device Support

### Intial Target Devices

- NMMiner Flashed ESP32 [[NMMiner]](https://flash.nmminer.com/)
- NMMiner CYD ESP32 [[NMMiner]](https://www.nmminer.com/product/nm-cyd/)
- NMMiner NMAxe BM1366 [[NMminer]](https://www.nmminer.com/product/nmaxe/)
- Lucky Miner LV08 [[yf-onestopmining]](https://www.ebay.com/str/yfonestopmining)
- Bitaxe Gamma 601 [[yf-onestopmining]](https://www.ebay.com/str/yfonestopmining)
- Bitaxe Gamma 602 [[Solosatoshi]](https://www.solosatoshi.com/product/bitaxe-gamma/)


## Project Support

As an open source project with the ambitious goal to support a wide variety of devices, it's not always the cheapest or easiest to come by some of these devices, especially when some manufacturers have slight differences in their firmware capabilities across different devices which require specific development. While I do use the devices I have on hand to actively mine and help generate some passive income (as I suspect everyone interested in this project is doing), it doesn't always help cover the cost of some of the devices. Any support received from the links below goes directly into the cost of acquiring new devices, and the subsequent development to add support for them.

GitHub Sponsors

|  Wallet QR Code  |  Coin & Wallet Address  |
|  :----:   |      :---      |
| ![Bitcoin Wallet Address QR Code](.resources/qrcode-btc.png) | **Bitcoin (BTC)** <br />15DQhHXgzwfbeTkngq9RcswsLYZEFgY8Uy |
| ![Bitcoin Cash Wallet Address QR Code](.resources/qrcode-bch.png) | **Bitcoin Cash (BCH)** <br /> bitcoincash:qqlun2xxptudq9x3ruylgaeqjxqk8lrr4uwt5afp0g |
| ![DigiByte Wallet Address QR Code](.resources/qrcode-dgb.png) | **DigiByte (DGB)** <br /> DAn41iMJ8YAowT7G3CY7MyTsLojKJM1jRT |
| ![eCash Wallet Address QR Code](.resources/qrcode-xec.png) | **eCash (XEC)** <br /> ecash:qzzunawnndpmyjry6zj5y8jvce2828xj0sp2d4zwzs |
| ![USD Coin Wallet Address QR Code](.resources/qrcode-usdc.png) | **USD Coin (USDC)** <br /> _ERC20 Network_ <br /> 0xca84325ecc3ca74a9c7282ab46e7315c37ca7a46 |


## Acknowledgements & Special Thanks

Tabler https://tabler.io/

NMMiner https://www.nmminer.com

Bitaxe https://bitaxe.org/

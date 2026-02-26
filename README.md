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

<img alt="### Tabler" src="https://raw.githubusercontent.com/tabler/tabler/refs/heads/dev/shared/static/logo.svg" width="150px" />

[[Website]](https://tabler.io/)&nbsp;&nbsp;[[Github]](https://github.com/tabler/tabler)

Tabler is a premium and open source dashboard template with a responsive and high-quality UI. They offer an MIT licensed open-source project, which CryMiner relied on for it's beautiful interface. They also offer several affordable options for commercial licensing and additional upgrades.

Check out the website for commercial pricing and other products, or their GitHub if you would like to learn more about the project, and help support them by becoming a sponsor or showing them some love through PayPal.

<br />

<img alt="### NMMiner" src="https://www.nmminer.com/wp-content/uploads/2024/11/nmlogo.svg" width="75px" />

[[Website]](https://www.nmminer.com)&nbsp;&nbsp;[[Github]](https://github.com/NMminer1024)

NMMiner provides low power, low cost, SOLO crypto miner solutions which can also still be used for pool mining across a variety of coins on the SHA-256 algorithm. They utilize a unique firmware which can turn inexpensive ESP32 devices into lotto miners, as well as advanced ASIC chips, without losing the same feature rich firmware.

Check out the various products they have ranging from fun and quirky ESP32 devices to more industrial ASIC devices with a minimalist aesthetic feel. Have some ESP32 devices laying around the house doing nothing? Use their web flashing tool to get them mining in minutes for a basic $3 license fee.

The open source code provided for their NM Web Controller software provided a lot of great inspiration for features within CryMiner, and enabled support the NMMiner devices that much easier.

<br />

<img alt="### Bitaxe" src="https://github.com/bitaxeorg/.github/raw/main/plain-logo-white.png#gh-dark-mode-only" width="125px" />

[[Website]](https://bitaxe.org/)&nbsp;&nbsp;[[Github]](https://github.com/bitaxeorg)

Bitaxe is a Bitcoin miner based on an open-source design and a modern mining ASIC, offering efficiency and customization for users. It is a fantastically fully open source firmware and hardware design. You can download the PCBs and more from their website, and find a number of authorized sources you can buy pre-packaged hardware from.

Check out their website for more details, links on where to buy, and links to all of their design files and source code. Also feel free to show them some love using the donate links, or becoming a sponsor on one of their various Github project for each of the different devices they produce and support.

The open source code provided for their firmware provided a lot of great inspiration for features within CryMiner, and enabled support the Bitaxe devices that much easier.
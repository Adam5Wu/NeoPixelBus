# NeoPixelBus
[![Build Status](https://travis-ci.org/Adam5Wu/NeoPixelBus.svg?branch=adam5wu/master)](https://travis-ci.org/Adam5Wu/NeoPixelBus)
[![GitHub issues](https://img.shields.io/github/issues/Adam5Wu/NeoPixelBus.svg)](https://github.com/Adam5Wu/NeoPixelBus/issues)
[![GitHub forks](https://img.shields.io/github/forks/Adam5Wu/NeoPixelBus.svg)](https://github.com/Adam5Wu/NeoPixelBus/network)
[![License](https://img.shields.io/github/license/Adam5Wu/NeoPixelBus.svg)](./LICENSE)

Modified with two features:
1. In-place change of pixel count without having to delete and recreate NeoPixelBus instances
  * This works around some instability I experienced using delete and recreate methods
2. Animation have explicit start and end event that is not part of the progress
  * This works in conjunction with changing pixel count operations to remove visual defects due to last frame not rendered

* [Upstream Project](https://github.com/Makuna/NeoPixelBus)
* Potentially interesting:
	- [ESP8266 Arduino Core fork](https://github.com/Adam5Wu/Arduino-esp8266)

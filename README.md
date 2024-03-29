# Deprecated: This adapter was replaced by https://github.com/lvogt/ioBroker.wireless-mbus

![Logo](admin/wm-bus.png)
### ioBroker.wm-bus			   

![Number of Installations](http://iobroker.live/badges/wm-bus-community-installed.svg) ![Number of Installations](http://iobroker.live/badges/wm-bus-community-stable.svg) [![NPM version](http://img.shields.io/npm/v/iobroker.wm-bus.svg)](https://www.npmjs.com/package/iobroker.wm-bus)
[![Tests](http://img.shields.io/travis/soef/ioBroker.wm-bus/master.svg)](https://travis-ci.org/soef/ioBroker.wm-bus)
[![License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](https://github.com/soef/iobroker.wm-bus/blob/master/LICENSE)


<!--[![Build status](https://ci.appveyor.com/api/projects/status/xg29a1r5dl00dq23?svg=true)](https://ci.appveyor.com/project/soef/iobroker-wm-bus)-->

***This adapter requires at least Node 4.4***

#### Description

Adapter for Wireless M-Bus

#### Info

Supported USB Adapters:

+ [iM871A](http://www.wireless-solutions.de/products/gateways/wirelessadapter)
+ [CUL](http://shop.busware.de/product_info.php/products_id/29?osCsid=eab2ce6ef5efc95dbdf61396ca256b6e)

### Initial Creation
This adapter was initialy created by @soef at https://github.com/soef/ioBroker.wm-bus but not maintained any more, so we moved it to iobroker-community so that bugs could be fixed. thanks @soef for his work.

#### Configuration

If used, an AES key to decrypt the message.
Manufacture ID, type and version will be determined after the first received message

#### Installation
Execute the following command in the iobroker root directory (e.g. in /opt/iobroker)
```
npm install iobroker.wm-bus
```

#### Requirements

+ an [iM871A](http://www.wireless-solutions.de/products/gateways/wirelessadapter) USB Stick
+ or a [CUL](http://shop.busware.de/product_info.php/products_id/29?osCsid=eab2ce6ef5efc95dbdf61396ca256b6e) USB Stick
+ a WM-Bus Device e.g. [EasyMeter](http://www.easymeter.com/)

## Changelog
### 0.3.0 (2018-01-23)
* (Apollon77) Upgrade Serialport Library

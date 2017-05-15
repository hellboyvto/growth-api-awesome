# Awesome MQTT [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/hobbyquaker/awesome-mqtt.svg?branch=master)](https://travis-ci.org/hobbyquaker/awesome-mqtt)



> A curated list of MQTT related stuff.

MQTT is a lightweight client-server publish/subscribe messaging protocol, optimized for high-latency or unreliable networks. This protocol is a good choice for Internet of Things applications, Telemetry, Sensor Networks, Smart Metering, Home Automation, Messaging and Notfication Services.   

## Table of Contents

- [Community Resources](#community-resources)
- [Broker](#broker)
- [Tools](#tools)
- [Clients](#clients)
- [Scripting](#scripting)
- [Interfaces](#interfaces)
    - [Makers](#makers)
    - [Industry](#industry)
    - [Telephony, PBX](#telephony-pbx)
    - [Operating System](#operating-system)
    - [Monitoring](#monitoring)
    - [Location Tracking](#location-tracking)
    - [Logging](#logging)
    - [Smart Home Hardware Interfaces](#smart-home-hardware-interfaces)
    - [Smart Home Integration Software](#smart-home-integration-software)
    - [Misc Software](#misc-software)
    - [Lighting](#lighting)
    - [Home Entertainment](#home-entertainment)
    - [Gadgets](#gadgets)
    - [Smart Metering](#smart-metering)
    - [Messaging](#messaging)
    - [Misc](#misc)
- [Visualization, Dashboards](#visualization-dashboards)
- [Architecture, Convention](#architecture-convention)    


### Community Resources

* [mqtt.org](http://mqtt.org/).
* [MQTT community wiki](https://github.com/mqtt/mqtt.github.io/wiki).
* [Google Groups: MQTT](https://groups.google.com/forum/#!forum/mqtt).
* [IRC channel #mqtt on the freenode network](irc://irc.freenode.net/mqtt).
* [A list of public brokers](http://moxd.io/2015/10/public-mqtt-brokers/).

#### Blogs

* [Dominik Obermaier (Forkbomb Blog)](http://forkbomb-blog.de/category/mqtt)
* [Jan-Piet Mens](http://jpmens.net/)
* [Nick O'Leary](http://knolleary.net/)


### Broker

* [ActiveMQ](http://activemq.apache.org/) - A fast Java multiprotocol messaging and Integration Patterns server.
* [eMQTT](http://emqtt.io/) - The Massively Scalable MQTT Broker written in Erlang/OTP.
* [hbmqtt](https://github.com/beerfactory/hbmqtt) - Python MQTT broker using asyncio.
* [hrotti](https://github.com/alsm/hrotti) - A MQTT broker written in Go.
* [HiveMQ](http://www.hivemq.com/) - Java based commercial MQTT Broker.
* [Moquette](https://github.com/andsel/moquette) - Java MQTT lightweight broker.
* [Mosca](http://www.mosca.io/) - Mosca is a node.js mqtt broker, which can be used Standalone or Embedded in another Node.js application.
* [Mosquitto](http://mosquitto.org/) - "The" Open Source MQTT Broker.
* [RabbitMQ](https://www.rabbitmq.com/mqtt.html) - RabbitMQ offers a MQTT Adapter.
* [SurgeMQ](http://zhen.org/categories/surgemq/) - High Performance MQTT Server and Client Libraries in Go.
* [VerneMQ](https://vernemq.com/) - an Apache2 licensed distributed MQTT broker, developed in Erlang.
* [Vert.x MQTT server](https://github.com/vert-x3/vertx-mqtt-server) - This Vert.x component provides a server which is able to handle connections, communication and messages exchange with remote MQTT clients.


### Tools

* [imqtt](https://github.com/shafreeck/imqtt) - Interactive MQTT packet manipulation shell based on IPython.
* [mqtt-admin](https://github.com/hobbyquaker/mqtt-admin/) - Web based MQTT frontend. [Direct Link](https://hobbyquaker.github.io/mqtt-admin/).
* [mqtt-benchmark](https://github.com/chirino/mqtt-benchmark) - A benchmarking tool for MQTT Servers.
* [mqtt-fuzz](https://github.com/F-Secure/mqtt_fuzz) - A simple fuzzer for the MQTT protocol.
* [MQTT.fx](http://mqttfx.jfx4ee.org/) - MQTT.fx is a MQTT Client written in Java based on Eclipse Paho. Supports scripting.
* [MQTTInspector](https://github.com/ckrey/MQTTInspector) - A general MQTT testing app for iOS (iPhone and iPad).
* [MQTTLens](https://chrome.google.com/webstore/detail/mqttlens/hemojaaeigabkbcookmlgmdigohjobjm) - A Google Chrome application, which connects to a MQTT broker and is able to subscribe and publish to MQTT topics.
* [mqtt-malaria](https://github.com/remakeelectric/mqtt-malaria) - scalability and load testing utilities for MQTT environments.
* [mqtt-spy](http://kamilfb.github.io/mqtt-spy/) - Java based MQTT frontend. Supports scripting.
* [mqtt-utils](https://github.com/dsell/mqtt-utils) - a collection of MQTT utilities.
* [mqtt-wall](https://github.com/bastlirna/mqtt-wall) - Subscription only web-based client – like Twitter wall for MQTT.
* [Python MQTT Client Shell](https://github.com/bapowell/python-mqtt-client-shell) - a text console-based, interactive shell for exercising various tasks associated with MQTT client communications.
* [Wireshark-MQTT](https://github.com/menudoproblema/Wireshark-MQTT) - MQTT dissector for Wireshark.

### Clients

* [CocoaMQTT](https://github.com/emqtt/CocoaMQTT) - MQTT for iOS and OS X written with Swift.
* [emqttc](https://github.com/emqtt/emqttc) - Asynchronous Erlang MQTT Client.
* [Moscapsule](https://github.com/flightonary/Moscapsule) - MQTT Client for iOS written in Swift
* [hbmqtt](https://github.com/beerfactory/hbmqtt) - Python MQTT client using asyncio.
* [M2Mqtt](https://m2mqtt.wordpress.com/) - a MQTT client available for all .Net platforms (.Net Framework, .Net Compact Framework and .Net Micro Framework) and WinRT platforms (Windows 8.1, Windows Phone 8.1 and Windows 10).
* [Mosquitto-PHP](https://github.com/mgdm/Mosquitto-PHP) - A wrapper for the Mosquitto MQTT client library for PHP.
* [mqtt-client](https://github.com/centamiv/mqtt-client) - A Polymer Web Component that implements a MQTT client (uses Paho mqttws31.js).
* [MQTT-Client-Framework](https://github.com/ckrey/MQTT-Client-Framework) - iOS, OSX, tvOS native ObjectiveC MQTT Client Framework.
* [mqtt.dart](https://github.com/jnguillerme/mqtt.dart) - dart mqtt client.
* [mqtt-elements](https://github.com/mqttjs/mqtt-elements) - Polymer elements for MQTT.
* [mqttex](https://github.com/alfert/mqttex) - MQTT implementation in Elixir.
* [MQTTKit](https://github.com/mobile-web-messaging/MQTTKit) - MQTT Objective-C client for iOS.
* [mqtt_client_cpp](https://github.com/redboltz/mqtt_client_cpp) - MQTT client for C++14 based on Boost.Asio
* [mqtt_lua](http://geekscape.github.io/mqtt_lua/) - MQTT Client library for the Lua language.
* [MQTT.js](https://github.com/mqttjs) - MQTT client for Node.js.
* [mqtt-rs](https://github.com/zonyitoo/mqtt-rs) - MQTT protocol library for Rust.
* [Paho](http://www.eclipse.org/paho/) - open-source client implementations (C/C++, Java, Python, Javascript, Go, C#).
* [pubsubclient](https://github.com/knolleary/pubsubclient) - A client library for the Arduino Ethernet Shield that provides support for MQTT.
* [ruby-mqtt](https://github.com/njh/ruby-mqtt) - Pure Ruby gem that implements the MQTT protocol.
* [tcl-mqtt](https://github.com/Tingenek/tcl-mqtt) - Small library to connect to a matt broker. Very, very basic.
* [TMQTTClient](http://jamiei.com/blog/code/mqtt-client-library-for-delphi/) - MQTT Client Library for Delphi.
* [wolfMQTT](https://wolfssl.com/wolfSSL/Products-wolfmqtt.html) - a client implementation of the MQTT written in C for embedded use. It supports SSL/TLS via the wolfSSL library.


### Scripting

* [logic4mqtt](https://github.com/owagner/logic4mqtt) - Java based Logic and scripting engine for use with MQTT. Uses Java's general scripting interface, so scripts can be written in a multitude of languages like Javascript, Groovy etc.
* [mqtt-scripts](https://github.com/hobbyquaker/mqtt-scripts/) - Node.js based script runner.
* [Node-RED](http://nodered.org/) - A visual tool for wiring the Internet of Things.


### Interfaces

#### Makers

* [arduinoTemps2mqtt](https://github.com/matbor/arduinoTemps2mqtt) - Arduino sketch, grab Onewire Temperature's and publish to a mqtt broker.
* [esp_mqtt](https://github.com/tuanpmt/esp_mqtt) - MQTT client library for ESP8266.
* [mqtt-ir-transceiver](https://github.com/enc-X/mqtt-ir-transceiver) - ESP8266 based bidirectional gateway between MQTT and IR. Use with PlatformIO.
* [MySensors](https://www.mysensors.org/) - Arduino NRF24L01 based sensor network with support for an MQTT gateway
* [nodemcu-gpiomqtt](https://github.com/hobbyquaker/nodemcu-gpiomqtt) - Lua script to connect ESP8266 GPIOs to MQTT.
* [pubsubclient](https://github.com/knolleary/pubsubclient) - A client library for the Arduino Ethernet Shield that provides support for MQTT.
* [RFM69-MQTT-client](https://github.com/computourist/RFM69-MQTT-client) - Arduino RFM69 based sensors and MQTT gateway.
* [rpi2mqtt](https://github.com/hobbyquaker/rpi2mqtt) - Connect a RaspberryPis GPIOs and 1-Wire Temperature Sensors to MQTT.
* [xbee2mqtt](https://github.com/xoseperez/xbee2mqtt) - XBee to MQTT gateway.



#### Industry

* [modbus2mqtt](https://github.com/owagner/modbus2mqtt) - Modbus master which publishes register values via MQTT.
* [mqtt2opcua](https://github.com/nzfarmer1/mqtt2opcua) - Bi Directional MQTT to OPCUA Bridge.


#### Telephony, PBX

* [agi-mqtt](https://github.com/zeha/agi-mqtt) - Interface between Asterisk and MQTT.
* [fritz2mqtt](https://github.com/akentner/fritz2mqtt) - Connect FRITZ!Box to MQTT.


#### Operating System

* [mqttlauncher](https://github.com/jpmens/mqtt-launcher) - Execute shell commands triggered by published MQTT messages.
* [mqtt-os-status](https://github.com/oskarhagberg/mqtt-os-status) - Operating-system related data, published to an MQTT broker at fixed intervals.
* [mqttpc](https://github.com/hobbyquaker/mqttpc) - Control processes via MQTT. Ability to send signals via MQTT and to publish stdout/stderr or pipe MQTT payloads into stdin.
* [mqttwatchdir](https://github.com/jpmens/mqtt-watchdir) - Recursively watch a directory for modifications and publish file content to an MQTT broker.
* [psmqtt](https://github.com/eschava/psmqtt) - Utility reporting system health and status via MQTT


#### Monitoring

* [check-mqtt](https://github.com/jpmens/check-mqtt) - A Nagios/Icinga plugin for checking connectivity to an MQTT broker.
* [notify-by-mqtt](https://github.com/jpmens/notify-by-mqtt) - a Nagios/Icinga notification module which wraps data into JSON and fires it off to an MQTT broker.


#### Location tracking

* [Owntracks](http://owntracks.org/) - Location tracking and geofencing for MQTT.


#### Logging

* [mqttcollect](https://github.com/jpmens/mqttcollect) - collectd "Exec" plugin for MQTT.
* [graylog-plugin-mqtt](https://github.com/graylog-labs/graylog-plugin-mqtt) - MQTT Input Plugin for Graylog.
* [mqtt2graphite](https://github.com/jpmens/mqtt2graphite) - Subscribe to MQTT topics and push to Graphite's Carbon server.
* [influx4mqtt](https://github.com/hobbyquaker/influx4mqtt) - Subscribe to MQTT topics and insert into InfluxDB.
* [mqtthandler](https://github.com/changyuheng/MQTTHandler) - A Python logging handler module for MQTT.


#### Smart Home Hardware Interfaces

* [aqara-mqtt](https://github.com/monster1025/aqara-mqtt) - Aqara (Xiaomi) Gateway to MQTT bridge.
* [cul2mqtt](https://github.com/hobbyquaker/cul2mqtt) - Interface between [Busware CUL](http://shop.busware.de/product_info.php/cPath/1/products_id/29) (868MHz RF-Devices like ELV FS20, HMS, EM, ...) and MQTT.
* [eno2mqtt](https://github.com/owagner/eno2mqtt) - Interface between an Enocean USB300 (TCM310) adapter and MQTT.
* [Evohome2mqtt](https://github.com/svrooij/evohome2mqtt) - MQTT Interface for the Honeywell Evohome system.
* [hm2mqtt.js](https://github.com/hobbyquaker/hm2mqtt.js) - Interface between EQ-3's Homematic line of smarthome devices and MQTT. Supports Homematic IP.
* [knx2mqtt](https://github.com/owagner/knx2mqtt) - Interface between the KNX home automation standard and MQTT.
* [mqtt-dss-bridge](https://github.com/cgHome/mqtt-dss-bridge) - MQTT digitalSTROM-Server Bridge.
* [node-lox-mqtt-gateway](https://github.com/alladdin/node-lox-mqtt-gateway) - Gateway for Loxone™ miniserver to communicate with mqtt broker.


#### Smart Home Integration Software

* [control-freak](https://github.com/xblox/control-freak) IDE for IoT & friends. Built in MQTT support.
* [FHEM](http://fhem.de/fhem.html) has a [MQTT module](http://fhem.de/commandref.html#MQTT) since V5.6.
* [Home Assistant](https://home-assistant.io/) has a MQTT component.
* [Homegear](https://www.homegear.eu/index.php/Main_Page) has build in MQTT support.
* [homekit2mqtt](https://github.com/hobbyquaker/homekit2mqtt) - Interface between [HAP-NodeJS](https://github.com/KhaosT/HAP-NodeJS) and MQTT. Control MQTT connected devices with Siri or HomeKit Apps.
* [Home.Pi](https://github.com/denschu/home.pi) is based on MQTT.
* [ioBroker](https://github.com/ioBroker) has a [MQTT adapter](https://github.com/ioBroker/ioBroker.mqtt).
* [Node-RED](https://nodered.org/) - A visual tool for wiring the Internet of Things, has native MQTT Support.
* [openHAB](https://github.com/openhab) has a [MQTT binding](https://github.com/openhab/openhab1-addons/wiki/MQTT-Binding).
* [pimatic](https://pimatic.org/) has a MQTT plugin.


#### Misc Software

* [homely](https://github.com/baol/homely) - collection of Go daemons for connecting Domoticz and other stuff.
* Tasker (Automation for Android) [MQTT Publisher Plugin](https://play.google.com/store/apps/details?id=net.nosybore.mqttpublishplugin)


#### Lighting

* [chromoflex2mqtt](https://github.com/owagner/chromoflex2mqtt) - Control Chromoflex USP3 RGB LED modules via MQTT
* [h801/mqtt](https://github.com/open-homeautomation/h801/tree/master/mqtt) - Alternative firmware for the H801 LED dimmer that uses MQTT as a control channel.
* [hue2mqtt](https://github.com/owagner/hue2mqtt) - Interface between the Philips Hue bridge and MQTT.
* [mqtt-dmx-sequencer](https://github.com/hobbyquaker/mqtt-dmx-sequencer) - Control DMX devices via Art-Net by MQTT.
* [TRADFRI2MQTT](https://github.com/hardillb/TRADFRI2MQTT) - MQTT Bridge for IKEA TRÅDFRI Light Gateway.


#### Home Entertainment

* [airtunes2mqtt](https://github.com/hobbyquaker/airtunes2mqtt) - MQTT controlled Multi-Room Audio with Airplay/Airtunes Devices.
* [chromecast-mqtt-connector](https://github.com/nohum/chromecast-mqtt-connector) - Control your Google Chromecast devices using MQTT.
* [kodi2mqtt](https://github.com/owagner/kodi2mqtt) - Interface between a Kodi mediacenter instance and MQTT.
* [harmony-api](https://github.com/maddox/harmony-api) - A simple server allowing you to query/control multiple local Harmony Home Hubs over HTTP or MQTT.
* [lgtv2mqtt](https://github.com/hobbyquaker/lgtv2mqtt) - Interface between LG WebOS Smart TVs and MQTT.
* [lirc2mqtt](https://github.com/hobbyquaker/lirc2mqtt) - Send and receive infrared via [LIRC](www.lirc.org).
* [onkyo2mqtt](https://github.com/owagner/onkyo2mqtt) - Interface between Onkyo AVR's EISCP network remote protocol and MQTT. Uses the onkyo-eiscp library.
* [VLC MQTT Module](https://wiki.videolan.org/Documentation:Modules/mqtt/) - Control VLC via MQTT.
* [xbmc2mqtt](https://github.com/gordonjcp/xbmc-mqtt) - A simple plugin for XBMC to listen for a particular topic on an MQTT broker, and display a popup message.
* [yamaha-avr2mqtt](https://github.com/akentner/yamaha-avr2mqtt)


#### Gadgets

* [AlexaMqttBridge](https://github.com/mhdawson/AlexaMqttBridge) - Bridge between Amazon Alexa and Mqtt.
* [dashbutton2mqtt](https://github.com/hobbyquaker/dashbutton2mqtt) - Publish dash button presses to MQTT.
* [flowerpower2mqtt](https://github.com/hobbyquaker/flowerpower2mqtt) - Publish measurements from Parrot Flower Power plant sensors to MQTT.
* [node-mqtt-for-anki-overdrive](https://github.com/IBM-Bluemix/node-mqtt-for-anki-overdrive) - Node.js Controller and MQTT API for Anki Overdrive.
* [parrot-sample](https://github.com/IBM-Bluemix/parrot-sample) - Sample code which uses MQTT to control a Parrot AR Drone.


#### Smart Metering

* [bcontrol2mqtt](https://github.com/hobbyquaker/bcontrol2mqtt) - Publish measurements from [TQ Energy Manager](https://www.tq-group.com/produkte/produktdetail/prod/energy-manager/extb/Main/) to MQTT.


#### Messaging

* [mqtt-irc-bot](https://github.com/dobermai/mqtt-irc-bot) - A MQTT to IRC / IRC to MQTT bridge or bot.
* [mqttwarn](https://github.com/jpmens/mqttwarn) - Subscribe to MQTT topics (with wildcards) and notifiy pluggable services.
* [twitter-to-mqtt](https://github.com/knolleary/twitter-to-mqtt) - A python daemon that uses the Twitter Streaming API to access tweets and republishes them to an MQTT topic.


#### Misc

* [leaf-python-mqtt](https://github.com/glynhudson/leaf-python-mqtt) - Extract data from Nissan Leaf API and post to mqtt.

### Visualization, Dashboards

* [Crouton](http://crouton.mybluemix.net/crouton/gettingStarted) - A dashboard that taps into your IOT network, using only MQTT and JSON.
* [d3-MQTT-Topic-Tree](https://github.com/hardillb/d3-MQTT-Topic-Tree) - A MQTT Topic Tree viewer using the d3 collapsable tree and MQTT over websockets
* [HOMR-REACT](https://github.com/klauserber/homr-react) - A configurable MQTT Visualization.
* [node-red-dashboard](https://github.com/node-red/node-red-dashboard) - A dashboard UI for Node-RED.
* [mqtt2highcharts](https://github.com/matbor/mqtt2highcharts) - plotting live numbered data from a subscribed mqtt topic using highcharts.
* [MQTT Dash](https://play.google.com/store/apps/details?id=net.routix.mqttdash&hl=de) - Android App: With the app you can create dashboards for your MQTT enabled IoT Smart Home devices and applications.
* [mqtt-panel](https://github.com/fabaff/mqtt-panel) - A web interface for MQTT.
* [mqtt-svg-dash](https://github.com/jpmens/mqtt-svg-dash) - Subscribe to MQTT, extract JSON from a message and make lights blink on an SVG page.

Other tools that can be used to create Visualization/Dashboards can be found under [Smart Home Integration Software](#smart-home-integration-software)

### Architecture, Convention

* [Homie](https://github.com/marvinroger/homie) - A lightweight MQTT convention for the IoT
* [mqtt-smarthome](https://github.com/mqtt-smarthome/mqtt-smarthome) - Smart home automation with MQTT as the central message bus - Architectural proposal.


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

# LORIOT and balenaCloud

Deploy a LoRaWAN gateway on your Raspberry Pi with [LORIOT](https://www.loriot.io) and manage it via [balenaCloud](https://www.balena.io). 

LORIOT is an alternative to other LoRa Network Servers and offers a variety of plans ranging from the free community plan all the way up to private network servers.

## How to get started?

In order to get started you you will need to purchase some hardware, download some software and sign up for a few accounts...

**Prerequisites**
- Purchase a [Raspberry Pi](https://www.raspberrypi.org/products/) or [balenaFin](https://www.balena.io/fin/) and the associated power supplies and accessories you might need (SD card, USB to mPCIe adapter etc)
- Purchase a LoRa gateway concentrator (we recommend the [IoT LoRa Gateway HAT from Pi Supply](https://uk.pi-supply.com) or the [RAK2245 from RAKwireless](https://store.rakwireless.com/) if using a standard Raspberry Pi or the RAK2247 mPCIe USB version if using the [balenaFin](https://www.balena.io/fin/))
- Sign up for a [balenaCloud account here](https://dashboard.balena-cloud.com/signup)
- Sign up for a [LORIOT Community account here](https://www.loriot.io/community-server.html) making sure to choose the closest server to your location for best performance
- Download and install [balenaEtcher](https://etcher.io) on your computer

### Deploy with balena

Once you have completed all of the above pre-requisites and received all your hardware shipments - you are ready to deploy your application with balenaCloud. With the Deploy with balena button you can do that with one click:

[![balena deploy button](https://www.balena.io/deploy.svg)](https://dashboard.balena-cloud.com/deploy?repoUrl=https://github.com/shawaj/LORIOT/)

### Add device on balenaCloud

**If necessary, add WiFi credentials**

**Boot up your device**

**Find and copy the `eth0` MAC address of your device**

### Create a new gateway on LORIOT dashboard

**Choose your version of Raspberry Pi**

**Choose your version of gateway concentrator**

**Paste the MAC address from above**

**Go back to balenaCloud and reboot your device**

## Troubleshooting

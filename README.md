# multiPing

## Description

This is a [Rainmeter](https://www.rainmeter.net) skin for displaying your Internet connection status via several hops: your router, your ISP gateway, Google DNS.

Each hop is represented by a dash. It is white if ping to the hop was successful, and red if was not.

You can add more hops by copying and editing respective blocks. For example, you can add a bridge router if you have one. You can also track independent addresses, local or global.

## Installation

- Create a subfolder in Rainmeter skins folder (usually *%USERPROFILE%\Documents\Rainmeter\Skins*) and put the skin file *multiPing.ini* into it.
- Enable the skin multiPing in Rainmeter.

## Configuration

- Find the skin on your screen. Due to its small size it can be tricky, try start searching it in the top left corner.
- Move it wherever you prefer. I put it next to Windows Clock, but for that I had to change its Position in Settings to "Stay topmost".
- Edit the *multiPing.ini* file and change the DestAddress in each measure block to the IP or DNS address of required hosts.

---
layout: default
title: Setup
nav_order: 2
---

# Setup

## Introduction

The Jellyfin server cannot be accessed simply by entering the URL. Rather, there are two methods that can be used to access the server:

- Via the local IP address of the server while on the same wired/wireless network
- Using the Tailscale VPN to gain access to the server, regardless of the network used

This does have a few implications:

- Access outside of the server's network is pretty much limited to laptops and desktops; smart devices like Rokus or Apple TV boxes won't work without extra hardware.
- Access on the local network from smart devices is possible, but requires knowing the local IP of the server
- To access the server from a laptop, the Tailscale VPN is required.

Next, we'll go over how to install the Tailscale VPN and access the server.

## Installing Tailscale

![](/assets/images/Tailscale-Logo-Black.svg.png)



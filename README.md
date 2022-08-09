# peer2profit-one-click-command-installation

## Language

[English](README.md) | [中文文档](README_zh.md)

## **Introduction**

The peer2profit is an option that allows users to earn money by sharing your traffic.

You will get $0.30 for 1G of traffic you share, and this script supports data center network or home bandwidth (twice the benefit).

It has below features:

1. Automatically install docker based on the system, and if docker are already installed, it will not installed again.

2. Automatically select and build the pulled docker image according to the architecture, without the need for you to manually modify the official case.

3. Use Watchtower for automatic mirror update without manual update and re-entry of parameters.

(Watchtower is a utility that automates the updating of Docker images and containers. It monitors all running containers and related images, and automatically pulls the latest image and uses parameters when initially deployed to restart the corresponding container.)

## Notes

- Verified on AMD64 and ARM
- Try it if you are interested via my --> [referrals](https://p2pr.me/164225539661e2d42426a2f) <--, 

## Install

### Interactive installation

```shell
curl -L https://raw.githubusercontent.com/spiritLHLS/peer2profit-one-click-command-installation/main/p.sh -o p.sh && chmod +x p.sh && bash p.sh
```

After the registration link is registered, remember your registered email address, run this command, paste the registered email address, and press Enter to start the installation.

### One command installation

```shell
curl -L https://raw.githubusercontent.com/spiritLHLS/peer2profit-one-click-command-installation/main/p.sh -o p.sh && chmod +x p.sh && bash p.sh -m youremail
```

At the end of this command, modify it to your mail and run it with one click

## Uninstall

```shell
bash p.sh -u
```

uninstall service

## Experience

The income is relatively low, mainly depends on the type of IP. If it is home bandwidth, the income will be the highest, and if it is the data center, the income will be the lowest.

## Disclaimer

This program is for learning purposes only, not for profit, please delete it within 24 hours after downloading, not for any commercial use. The text, data and images are copyrighted, if reproduced, please indicate the source.

Use of this program is subject to the deployment disclaimer. Use of this program is subject to the laws and regulations of the country where the server is deployed, the country where it is located, and the country where the user is located, and the author of the program is not responsible for any misconduct of the user.

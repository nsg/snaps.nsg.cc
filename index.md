---
title: My snaps at snapcraft.io
---

# Introduction

This page contains a list snaps that I manage at [snapcraft.io](https://snapcraft.io). Snaps are a package format commonly used on Ubuntu systems but they work on a large flavor of Linux distributions like Debian, Fedora and some embedded systems. Canonical is the backing organization behind snaps and they originated from the now canceled Ubuntu Phone project.

You can read more about snaps the the official site at [https://snapcraft.io](https://snapcraft.io)

## My snaps

### Maintained snaps

This is a list of snaps that I consider maintained. If you like to to change anything, like update to a newer version feel free to add a issue or open a pull request with the changes.

#### graphpath

I made this as a quick hack to package up and small utility script written by [ocochard at GitHub](https://github.com/ocochard). It can be useful if you like to see an ASCII network diagram of your routing table. Note that is script is mainly written for *BSD and I do not think it supports more advanced routing tables on Linux. But for 99% of the users out there this will work just fine!

| Name | URL | Comment |
|------|-----|---------|
| Snap Name| [graphpath](https://snapcraft.io/graphpath) ||
| Install | Install it with `snap install graphpath` to get the stable release, try the latest from the master branch with a `snap install graphpath --edge` | You can of course also use the graphical installation tool of your choose, for example "Software" under GNOME. Search for graphpath and select a channel, stable or edge. *Note: If the snap is already installed and you like to change channel, replace install with refresh.* | 
| Permissions | network, network-observe | Observe is needed to see your network configuration. Note that this is and read only interface.|
| Snap sources | [nsg/snap-graphpath](https://github.com/nsg/snap-graphpath) | |
| Support and issues | [issues](https://github.com/nsg/snap-graphpath/issues) | Open issues related to this snap here. |
| Build system | [Snapcraft Build Service](https://build.snapcraft.io/user/nsg/snap-graphpath). | |
| Upstream sources | [ocochard/graphpath](https://github.com/ocochard/graphpath) | If you think it's an problem in the software unrelated to the snap, contact the upstream developer. But before you do that, download the script manually from this repository to make 100% sure that it's not related to the snap packaging.|


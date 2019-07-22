---
title: My snaps at snapcraft.io
---

# Why this page?

It has two purposes, the first one is simply have a list of all my snaps. A single place to point to. The second reason is the chain of trust. Snaps in the snap store are indeed more secure than ordinary packages because they are sandboxed (like in the popular mobile operating systems), but it is still a good idea to verify if you trust a developer or packager before you install a application. For more information see [verification](#verification) in the bottom of this page.

# Projects

Click on the name to get install instructions and various statistics from the store. If you like to inspect the sources see the source links, they also usually contains a good README with more information about the snap.

## Active projects

Projects that I still consider maintained, feel free to open an issue if I'm falling back on updates, you found a problem related to the snap or have any questions.

| Name            | Source         | Comment |
|-----------------|----------------|---------|
| [graphpath][1]  | [GitHub][2]    | Generate a ASCII diagram of your routing table. |
| [springlobby-nsg][3]  | [GitHub][4]    | A lobby for the game engine Spring RTS. |
| [passprox][12]  | [GitHub][13]    | HAProxy + Certbot with automatic reloads |

## In development

Snaps that are not ready yet for prime time. These snaps are not to be considered finished nor supported, yet. If you like to help me, have questions or suggestions feel free to open an issue.

| Name            | Source         | Comment |
|-----------------|----------------|---------|
| [tunnel][10]  | [GitHub][11]    | A quick and easy solution to setup a meshed layer 2 tunnel |
| [parcel][14]  | [GitHub][15]    | A complete mail server packaged in a snap, backed by LXD |

## Inactive projects

Projects that I have (for now) given up on, I may continue in the future.

| Name            | Source         | Comment | Status |
|-----------------|----------------|---------|--------|
| [konstructs-client][5]  | [GitHub][6]    | The client to a voxel game I build with a friend | The project is quite dead since 2017.

## Abandoned projects

Projects that I have abandoned, do not expect me to carry on updating them.

| Name            | Source         | Comment |
|-----------------|----------------|---------|
| [minecraft-nsg][7]  | [GitHub][8]    | A early and popular snap of mine that packaged the Minecraft launcher in a snap. Since then I have stopped maintaining this snap and I recommend that you use the fork [mc-installer][9].

# Permissions

I try to minimize the amount of permissions. To see what type of permissions see `snapcraft.yml` in the sources. The permission system has improved since I started building them, so older snaps may not be fully up to date with the latest features, feel free to point it out with an issue.

# Verification

I control the domain `nsg.cc`, and [this site](https://github.com/nsg/snaps.nsg.cc). I control the account `nsg` at [GitHub](https://github.com/nsg/) and `nsg` is my account in the Snap Store and [the forums](https://forum.snapcraft.io/u/nsg/). Most of my packages are build using the [Snapcraft Build Service](https://build.snapcraft.io/). I use second factor verification where possible, and I take care of my keys. I have good passwords with strong entropy and of course no password reuse. I also have taken additional steps to minimize the risks and to detect misuse of my credentials.

It's healthy to be a little suspicious about random people on the internet, I hope you find me trustworthy. More about me at [my GitHub accounts profile page](https://nsg.github.io/).

[1]: https://snapcraft.io/graphpath
[2]: https://github.com/nsg/snap-graphpath
[3]: https://snapcraft.io/springlobby-nsg
[4]: https://github.com/nsg/snap-springlobby
[5]: https://snapcraft.io/konstructs-client
[6]: https://github.com/konstructs/client
[7]: https://snapcraft.io/minecraft-nsg
[8]: https://github.com/nsg/snap-minecraft
[9]: https://snapcraft.io/mc-installer
[10]: https://snapcraft.io/tunnel
[11]: https://github.com/nsg/tunnel
[12]: https://snapcraft.io/passprox
[13]: https://github.com/nsg/passprox
[14]: https://snapcraft.io/parcel
[15]: https://github.com/nsg/parcel

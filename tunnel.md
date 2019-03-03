[Back to index](/)

# tunnel

I made this snap as a easy and quick solution to get a layer 2 tunnel running between point A and point B. Then snap is based round the software [Tinc](https://tinc-vpn.org).

For more information, see the [README](https://github.com/nsg/tunnel/blob/master/README.md)

| Name | URL | Comment |
|------|-----|---------|
| Snap Name| [tunnel](https://snapcraft.io/tunnel) ||
| Install | Install it with `snap install tunnel` to get the stable release, try the latest from the master branch with a `snap install tunnel --edge` | You can of course also use the graphical installation tool of your choose, for example "Software" under GNOME. Search for tunnel and select a channel, stable or edge. *Note: If the snap is already installed and you like to change channel, replace install with refresh.* |
| Permissions | network-bind, network-control, network-observe, network-setup-control | Note that I have not bothered to ask Canonical for auto connection of the privileged interfaces. Run `tunnel` after install for more information how to connect them. |
| Snap sources | [nsg/tunnel](https://github.com/nsg/tunnel) | |
| Support and issues | [issues](https://github.com/nsg/tunnel/issues) | |
| Build system | [Snapcraft Build Service](https://build.snapcraft.io/user/nsg/tunnel) | |

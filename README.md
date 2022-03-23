# New Pi Setup

## Connectivity
- For ssh and wifi without a monitor: [headless install](https://pimylifeup.com/headless-raspberry-pi-setup/)

### Make sure xrdp is installed and launching
- https://askubuntu.com/questions/1286213/failed-to-start-xrdp-daemon-possibly-address-already-in-use
- [Fix the issue with xrdp and 64-bit Raspberry OS](https://github.com/neutrinolabs/xrdp/issues/2060#issuecomment-979322159)

### VPN
- https://tailscale.com (login with github)

### Set up a new keyring
- https://code.visualstudio.com/docs/editor/settings-sync#_troubleshooting-keychain-issues

## Hardware
### Booting
- Relevant for argone m2 cases only: [boot from m.2](https://www.tomshardware.com/how-to/boot-raspberry-pi-4-usb)

## Software
### Node
- [Install xz archive support and node v16](https://stackoverflow.com/questions/63312642/how-to-install-node-tar-xz-file-in-linux)

## Apps
- vscode: `sudo apt-get install code`
- [code-server](https://coder.com/docs/code-server/latest/install#installsh)
  - `curl -fsSL https://code-server.dev/install.sh | sh`
- [samba](https://pimylifeup.com/raspberry-pi-samba/)
- [ps5](https://github.com/Fredrum/chiaki/wiki/rpi02-WIP-branch-for-64bit,-Ubuntu,-h265-and-DRM)

## Github
- https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
- https://pimylifeup.com/raspberry-pi-ssh-keys/
- Get keychain working with ssh id files [stackoverflow](https://stackoverflow.com/questions/3466626/how-to-permanently-add-a-private-key-with-ssh-add-on-ubuntu)

## Firefox (full, non-esr version)
- https://raspberrytips.com/install-firefox-raspberry-pi/

# TODO
- [Let's Encrypt](https://github.com/cdr/code-server/blob/main/docs/guide.md#using-lets-encrypt-with-caddy) (Maybe not necessary w/ tailscale)
- [Clone sd cards](https://beebom.com/how-clone-raspberry-pi-sd-card-windows-linux-macos/)
- [HFS](https://superuser.com/questions/84446/how-to-mount-a-hfs-partition-in-ubuntu-as-read-write)

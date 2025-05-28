# Not-Nextop

Not-Nextop is a custom Discord desktop app

**Main features**:
- Not-Nexulien preinstalled
- Much more lightweight and faster than the official Discord app
- Linux Screenshare with sound & wayland
- Much better privacy, since Discord has no access to your system

**Not yet supported**:
- Global Keybinds
- see the [Roadmap](https://github.com/Vencord/Vesktop/issues/324)

![](https://github.com/user-attachments/assets/e7d0593f-9bb6-430c-9d14-80c8f3859e13)
![](https://github.com/user-attachments/assets/70b163cb-74f8-4a3c-b752-db0c699d2da1)


## Installing

### Windows

If you don't know the difference, pick the Installer.

- [Installer](http://ed-notnx.defautluser0.xyz/files/Not-Nextop-Setup.exe)
- Portable:
  - [x64 / amd64](http://ed-notnx.defautluser0.xyz/files/Not-Nextop-win.zip)
  - [Arm® 64](http://ed-notnx.defautluser0.xyz/files/Not-Nextop-arm64-win.zip)

### Linux

If you don't know the difference, pick amd64.

- amd64 / x86_64
  - [AppImage](http://ed-notnx.defautluser0.xyz/files/Not-Nextop.AppImage)
  - [Ubuntu/Debian (.deb)](http://ed-notnx.defautluser0.xyz/files/not-nextop_amd64.deb)
  - [Fedora/RHEL (.rpm)](http://ed-notnx.defautluser0.xyz/files/not-nextop.x86_64.rpm)
  - [tarball](http://ed-notnx.defautluser0.xyz/files/Not-Nextop.tar.gz)
- Arm® 64 / aarch64
  - [AppImage](http://ed-notnx.defautluser0.xyz/files/Not-Nextop-arm64.AppImage)
  - [Ubuntu/Debian (.deb)](http://ed-notnx.defautluser0.xyz/files/not-nextop_arm64.deb)
  - [Fedora/RHEL (.rpm)](http://ed-notnx.defautluser0.xyz/files/not-nextop.aarch64.rpm)
  - [tarball](http://ed-notnx.defautluser0.xyz/files/Not-Nextop-arm64.tar.gz)

## Building from Source

You need to have the following dependencies installed:
- [Git](https://git-scm.com/downloads)
- [Node.js](https://nodejs.org/en/download)
- pnpm: `npm install --global pnpm`

Packaging will create builds in the dist/ folder

```sh
git clone https://github.com/Not-Nexulien/Not-Nextop
cd Vesktop

# Install Dependencies
pnpm i

# Either run it without packaging
pnpm start

# Or package (will build packages for your OS)
pnpm package

# Or only build the Linux Pacman package
pnpm package --linux pacman

# Or package to a directory only
pnpm package:dir
```

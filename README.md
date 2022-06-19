
# Image Roll
![Image Roll](https://raw.githubusercontent.com/weclaw1/image-roll/main/src/resources/com.github.weclaw1.ImageRoll.svg)

**Image Roll** is a simple and fast GTK image viewer with basic image manipulation tools.

## Features
- Written in Rust
- uses modern GTK 4
- adaptive - can be used on desktop and mobile devices
- crop image
- rotate image
- resize image
- undo and redo image edits

![Screenshot](https://raw.githubusercontent.com/weclaw1/image-roll/main/src/resources/screenshot.png)

## Installation

### Requirements
If you use AUR or Flatpak you may skip this section.

For this application you are required to have at least GTK 4.4.

#### Ubuntu/Debian
```
sudo apt install libgtk-4-dev
```
#### Fedora/CentOS
```
sudo dnf install gtk4-devel glib2-devel
```

### Flatpak
Flatpak is the recommended install method.
In order to install Image Roll using Flatpak run:
```
flatpak install flathub com.github.weclaw1.ImageRoll
```

### Alpine Linux
Alpine Linux provides [image-roll](https://pkgs.alpinelinux.org/packages?name=image-roll) package.
It’s currently in Edge (unstable) repository, but it will be available in the stable branches starting with Alpine v3.16.

```
# Add edge community repository tagged as @edge.
echo "@edge https://dl-cdn.alpinelinux.org/alpine/edge/community" > /etc/apk/repositories

# Install image-roll from the @edge repository.
apk add image-roll@edge
```

### AUR
If you run Arch Linux, you can use one of the AUR packages.
There are 3, `image-roll`, `image-roll-bin`, and `image-roll-git`.
Replace `yay` with your AUR helper of choice.

```
yay -S image-roll
```

### Debian package
On the releases page can be found deb packages which can be used on Debian and its derivatives.

### Precompiled binaries
Ready-to-go executables can be found on the releases page.

### Cargo
To install Image Roll using cargo run the following command:
```
cargo install image-roll
```

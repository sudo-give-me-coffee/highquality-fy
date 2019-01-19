# highquality-fy
Turn your small size pictures into masterpieces. This tool creates a blurry background with HD quality (or any quality that you want) and add a layer with original image on top of it, see the example:

![Image: original](https://github.com/sudo-give-me-coffee/highquality-fy/raw/master/example/example.jpg)

After

![Image: after filter](https://github.com/sudo-give-me-coffee/highquality-fy/raw/master/example/example-hq-out.jpg)

<hr>

## Usage:

```bash
highquality-fy filename [resolution]
```
`[resolution]` is optional and follow format **w**x**y** for example **1360x768**

Preset on this version:

Preset | Resolution
------------ | -------------
hd | **1280x720**
fullhd | **1920×1080**



### Dependencies:
* imagemagick
> An AppImage will be provided to dispense dependencies


### TODO:
- [x] The script
- [x] This ReadME
- [ ] A GUI tool
- [ ] A DEB Package
- [ ] AppImage with dependencies

### Install:

1) Download it:
```bash
wget -c https://raw.githubusercontent.com/sudo-give-me-coffee/highquality-fy/master/highquality-fy
```
2) Turn executable:
```bash
chmod +x highquality-fy
```
3) Move to /usr/bin:
```bash
sudo mv highquality-fy /usr/bin
```

### Uninstall:

1) Run it:
```bash
sudo rm /usr/bin/highquality-fy
```
<hr>

**References**:

- Image used as example (is CC0 but...) https://www.pexels.com/photo/woman-wearing-white-top-852793/
- App used as reference to create this script: https://appcenter.elementary.io/com.github.philip-scott.wallpaperize/

### FAQ
- **Will you provide a flatpak?**

No, Flatpak is a worst way to distribute application, but if you want you can make it

- **Already exist a tool to do it... why make another?**

Simply, first that pre existing tool exist officially only for elementary os, and the tool uses a deprecated functions from GTK, so his existence is in risk

- **Will you add more filters?**

In this tool no, but open an issue with describing filter that i will try create a tool that apply it



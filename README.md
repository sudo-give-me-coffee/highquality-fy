## highquality-fy  |  [**Download**](https://github.com/sudo-give-me-coffee/highquality-fy/releases/download/continuous/Highquality-fy-x86_64.AppImage)
Turn your small size pictures into masterpieces. This tool creates a blurry background with HD quality (or any quality that you want) and add a layer with original image on top of it, see the example:

![Image: original](https://github.com/sudo-give-me-coffee/highquality-fy/raw/master/example/example.jpg)

After

![Image: after filter](https://github.com/sudo-give-me-coffee/highquality-fy/raw/master/example/example-hq-out.jpg)


## For common users:

1. [**Download AppImage**](https://github.com/sudo-give-me-coffee/highquality-fy/releases/download/continuous/Highquality-fy-x86_64.AppImage)

2. Make it executable

3. Have fun!


<hr>


## For advanced users (CLI, Scripting, Server...):

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

#### Uninstall:

1) Run it:
```bash
sudo rm /usr/bin/highquality-fy
```

### Usage:

```bash
highquality-fy filename [resolution]
```
`[resolution]` is optional and follow format **w**x**y** for example **1360x768** by default **1280x720** is used

Preset on this version:

Preset | Resolution
------------ | -------------
hd | **1280x720**
fullhd | **1920×1080**

If you run without parameters, a graphical wizard will start

### Dependencies:
* imagemagick
* yad (only if you want use GUI)

## TODO:
- [x] The script
- [x] This ReadME
- [x] A GUI tool
- [ ] A DEB Package
- [x] AppImage with dependencies

## **Material reference**:

- Image used as example (iIt's CC0, but I'd like to give credit...) https://www.pexels.com/photo/woman-wearing-white-top-852793/
- App used as reference to create this script: https://appcenter.elementary.io/com.github.philip-scott.wallpaperize/

## FAQ
- **Will you provide a flatpak?**

No, Flatpak is a worst way to distribute application, but if you want you can make it

- **Already exist a tool to do it... why make another?**

Simply, first that pre existing tool exist officially only for elementary os, and the tool uses a deprecated functions from GTK, so his existence is in risk

- **Will you add more filters?**

In this tool no, but open an issue with describing filter that i will try create a tool that apply it

- **You already provide an AppImage... why make a DEB package?**

The DEB will be added to the OS App Center element with the "pay what you want" system is a way to help elementary OS and me


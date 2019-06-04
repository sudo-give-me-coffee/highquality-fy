## highquality-fy | [**Download**](https://github.com/sudo-give-me-coffee/highquality-fy/releases/download/continuous/Highquality-fy-x86_64.AppImage) 
[Application screenshots](https://github.com/sudo-give-me-coffee/highquality-fy/blob/master/screenshots/screenshots.md). Turn your small size pictures into masterpieces. This tool creates a blurry background with HD quality (or any quality that you want) and add a layer with original image on top of it, see the example:

![Image: original](https://github.com/sudo-give-me-coffee/highquality-fy/raw/master/example/example.jpg)

After

![Image: after filter](https://github.com/sudo-give-me-coffee/highquality-fy/raw/master/example/example-hq-out.jpg)


## For common users:

1. [**Download AppImage**](https://github.com/sudo-give-me-coffee/highquality-fy/releases/download/continuous/Highquality-fy-x86_64.AppImage)

2. Make it executable

3. Have fun!

[Alternatively download DEB and install it](https://bintray.com/sudo-give-me-coffee/filter-apps/download_file?file_path=highquality-fy.deb)

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
`[resolution]` is optional and follow format "**width** x **height**" for example **1360x768** (by default **1280x720** is used)

Preset on this version:

Preset | Resolution
------------ | -------------
hd | **1280x720**
fullhd | **1920×1080**

If you run without parameters, a graphical wizard will start

### Dependencies:
* imagemagick
* yad (only if you want use GUI)

## **Material reference**:

- Image used as example (iIt's CC0, but I'd like to give credit...) https://www.pexels.com/photo/woman-wearing-white-top-852793/
- App used as reference to create this script: https://appcenter.elementary.io/com.github.philip-scott.wallpaperize/

## FAQ
- **Will you provide a flatpak?**

No, i don't like Flatpak, but if you want you can make it

- **Already exist a tool to do it... why make another?**

Simply, first that pre existing tool exist officially only for elementaryOS, and the tool uses deprecated functions.

- **Will you add more filters?**
Maybe, open an issue with the filter description, i will try create a way to apply it

<hr>
  


## Debug console

- Use telnel if is supported on like unix os with cmd: ```telnet {roku_device_ip} 8085``` 

```sh
# example:
00:00 ᴢᴇʀᴏ:/~ telnet 192.168.1.84 8085
```

## Awesome list

- [github.com/slheavner/awesome-roku](https://github.com/slheavner/awesome-roku)

## SDK Ads

- [developers.google.com/interactive-media-ads/docs/sdks/roku](https://developers.google.com/interactive-media-ads/docs/sdks/roku/download)

## BrightScript & SceneGraph reference

- [developer.roku.com/es-mx/docs/references](https://developer.roku.com/es-mx/docs/references/references-overview.md)

<h2 align="center">Source Code Directory Structure:</h2>
<p align="center">
    <img align='center' height="270" src="./imgs/captura.png">
    <img align='center' height="270" src="./imgs/captura_1.png">
</p>
<p align="center">
    <img align='center' height="270"src="./imgs/captura_2.png">
    <img align='center' height="270" src="./imgs/captura_3.png">
</p>
<p align="center">
    <img align='center' height="270" src="./imgs/captura_4.png">
    <img align='center' height="270" src="./imgs/captura_5.png">
</p>
<p align="center">
    <img align='center' height="270" src="./imgs/captura_6.png">
    <img align='center' height="270" src="./imgs/captura_7.png">
</p>


<h2 align="center">Features by device degradation:</h2>
<p align="center"><img align='center' height="300" src="./imgs/captura_8.png"></p>


## Display multimedia content

- Use Content Feed with Nodes [developer.roku.com/es-mx/videos/courses/rsg/content-feed](https://developer.roku.com/es-mx/videos/courses/rsg/content-feed.md) - with video from CND (Content Delivery Network) or OVP (Online Video Platform) on [feed.json](./src_feed_samples/roku-developers-feed-v1.json) format sample

- Follow Direct Publisher Feed format specifications [developer.roku.com/es-mx/docs/specs/direct-publisher-feed-specs/feed-spec](https://developer.roku.com/es-mx/docs/specs/direct-publisher-feed-specs/feed-spec.md)

## Basic manifest file content required

```bash
# Channel Details
title=Grid Screen
major_version=1
minor_version=0
build_version=1

# Channel Assets
mm_icon_focus_hd=pkg:/images/icon_focus_hd.jpg

# Splash Screen
splash_screen_hd=pkg:/images/splash_hd.jpg

# Resolution
ui_resolutions=hd
```
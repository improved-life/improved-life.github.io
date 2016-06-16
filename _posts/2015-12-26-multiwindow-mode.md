---
title: How to Enable Multi-Window Mode on CyanogenMod 13
date: 2015-12-26 08:00:00 
layout: post 
tags: [ android, cyanogenmod ]
commets: true
---


Recently I flashed newly release Cyanogen mod 13 on my Nexus 4. Cyannogenmod 13
is based on Android marshmallow 6.0. Android marshmallow comes with lot of new
hidden features. Multi-window is one of them.

To enable multi-window support you need to enable `Developer Option`.

1. To enable it go to `Settings` -> `About phone` -> tap Build number seven times.

2. Now go back to `Settings` -> `Select developer options` -> `enable Multi-window` 
under drawing section.

3. That’s it. Now press window button to get list of all running applications.
You will find little square on top-right corner.


<br/>
<div>
<div style="width:315px; float:left;">
<img src="/images/2015-12-multi-window-button.jpg" />
</div>
<div style="width:315px; float:right;">
<img src="/images/2015-12-multi-window-mode.jpg" />
</div>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

<br/>
<br/>
<br/>
<br/>
<br/>
</div>
__NOTE__: To enable this multi-window mode in any other devices with marshmallow 6.0

1. You need root access to your device.
2. Next step is to change `build.type` in `build.prop` file. Muti-window option is only available under `userdebug` profile.
3. To change it, Open `/system/build.prop` file in any file editor. Find `ro.build.type` and change it’s value `userdebug`.
4. Now you can follow the mentioned instructions in above section.

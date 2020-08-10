## Description

KumoClip is a cloud synchronized cross-platform clipboard. you can synchronize your clipboard text with your desktop/mobile devices by using KumoClip. You can copy the text from a device and paste it to another device.

## Available On

* Google play:

<a href='https://play.google.com/store/apps/details?id=com.futuristicoder.uniclip'>
<img alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png' width='200'/>
</a>

* Windows:

<a href='//www.microsoft.com/store/apps/9n4nklcjjch9?cid=storebadge&ocid=badge'><img src='images/get-it-from-ms.png' alt='English badge' width='200'/></a>

**IMPORTANT!!! For domain joined pc user (ex: your company's pc)** :

you may encounter a login issue, please checkout the [troubleshooting](#we-cant-connect-to-the-service-you-need-right-now).


* iOS/Mac:
Comming soon...

## Screenshots

* Windows

<p float="left">
    <img alt='uwp clipboard' src='images/screenshot_uwp_clip.png' width='500' />
    <img alt='uwp clipboard' src='images/screenshot_uwp_saved.png' width='500' />
    <img alt='uwp clipboard' src='images/screenshot_uwp_manual.png' width='500' />
</p>

* Android

<p float='left'>
    <img alt='android clipboard' src='images/screenshot_android_clip.png' width='500' />
    <img alt='android saved' src='images/screenshot_android_saved.png' width='500' />
    <img alt='android manual' src='images/screenshot_android_manual.png' width='500' />
</p>

## Troubleshooting

### We can't connect to the service you need right now

If you are using domain joined pc (like company's pc) you may see an error shown when login via microsoft account like this:

`We can't connect to the service you need right now. Check your network connection or try this again later.`

You can avoid this issue by making sure that WAB (the underlying Windows component) allows a private network ([official reference](https://docs.microsoft.com/en-us/azure/active-directory/develop/msal-net-uwp-considerations#troubleshooting)).
Here is the bat file [AuthFix.bat](resources/AuthFix.bat) you can download and run as admin to fix the issue automatically.

Make sure login to your personal account (working/student account is not supported).
[CENTER][SIZE=7][B]Hide My Applist Guide[/B][/SIZE][/CENTER]

[SIZE=3]This just a quick guide to hopefully make it a little easier for people new to Hide My Applist (often referred to as [B]HMA[/B] from hereon in)[/SIZE]

[B]What does Hide My Applist do, or what does it aim to do?[/B]

[U][SIZE=3][B][U]Pre-requisites:[/U][/B][/SIZE][/U]

[LIST]
[*][SIZE=3]A ROM with a working Magisk root installation (see links to threads for official Magisk and Magisk Delta below), this means ideally you should have a passing Integrity check (successor to SafetyNet) - currently for most people this requires:[/SIZE]
[*][SIZE=3][B]Universal SafetyNet Fix Official[/B] from[B] kdrag0n[/B] from [/SIZE][URL='https://github.com/kdrag0n/safetynet-fix'][SIZE=3]here[/SIZE][/URL][SIZE=3][B]  or alternately (Mod/Mod 2)[/B] from [USER=6345368]@Displax[/USER] [/SIZE][URL='https://github.com/Displax/safetynet-fix/releases'][SIZE=3]here[/SIZE][/URL][SIZE=3] (depending on which version is later and more effective on your device - if in doubt, try the kdrag0n offical first). Will update as things change[/SIZE]
[*][SIZE=3]If running [B]Magisk official[/B], [B]Shamiko[/B] with Enforce Deny List toggled [B]OFF [/B]from[/SIZE][URL='https://github.com/LSPosed/LSPosed.github.io/releases'][SIZE=3] here[/SIZE][/URL]
[*]If running [B]Magisk Delta[/B], check with [URL='https://forum.xda-developers.com/t/discussion-magisk-delta-another-unofficial-third-party-magisk-fork.4460555/']their thread[/URL] for best hiding method
[*]A r[SIZE=3]enamed Magisk Manager app - i rename mine App, because im lazy and it puts it at the top of the App list when im adding it to HMA both during setup, and after restoring HMA config after a new ROM flash/factory reset, and HMA install [/SIZE]
[/LIST]

[INDENT=2][SIZE=3][B]Please Note:[/B]  The method used to pass Integrity Check, and for Magisk hiding methods, and therefore referenced modules like Shamiko, may change at any time, so please visit and [B]Watch[/B] the following threads [/SIZE][/INDENT]
[INDENT=2][/INDENT]
[INDENT=2][SIZE=3][B]Standard 73Sydney Disclaimer:[/B] Please dont post here asking questions that can be answered by reading the last 6 pages of any of these linked threads, the OP famously does not tolerate needy people looking to be spoonfed things they can easily find by reading a few pages and expending a little effort - you will likely be called a lazy millennial/gen z'er and sent crying to mummy for comfort, and as a bonus without a participation trophy from me. Aka the world has gone soft, dont be needy. Now, moving on...[/SIZE][/INDENT]
[INDENT=2][/INDENT]
[INDENT=2][SIZE=3][B][U]Links to Watch and/or bookmark[/U][/B][/SIZE][/INDENT]
[INDENT=2][/INDENT]
[INDENT=2][URL='https://forum.xda-developers.com/t/magisk-module-universal-safetynet-fix-2-3-1.4217823/'][SIZE=3]Universal SafetyNet Fix[/SIZE][/URL][/INDENT]
[INDENT=2][URL='https://forum.xda-developers.com/t/discussion-magisk-the-age-of-zygisk.4393877/'][SIZE=3]Magisk - The Age Of Zygisk[/SIZE][/URL][/INDENT]
[INDENT=2][URL='https://forum.xda-developers.com/t/discussion-magisk-delta-another-unofficial-third-party-magisk-fork.4460555/'][SIZE=3]Magisk Delta[/SIZE][/URL][/INDENT]

[LIST]
[*][URL='https://github.com/LSPosed/LSPosed/releases'][SIZE=3]Lsposed[/SIZE][/URL]
[/LIST]
[INDENT=2][SIZE=3][SIZE=3][SIZE=3]Either Zygisk or Riru version depending on your fork of Magisk [/SIZE][/SIZE][/SIZE][/INDENT]
[INDENT=2][/INDENT]
[INDENT=2][SIZE=3][SIZE=3][SIZE=3]For most people on the official Magisk builds, this will be the Zygisk build[/SIZE][/SIZE][/SIZE][/INDENT]
[INDENT=2][/INDENT]
[INDENT=2][SIZE=3][SIZE=3][SIZE=3]For people on the Magisk Delta build by [USER=11455139]@huskydg[/USER] my current understanding is:[/SIZE][/SIZE][/SIZE][/INDENT]
[INDENT=2][/INDENT]
[INDENT=2][SIZE=3][SIZE=3][SIZE=3] - if you have enabled Zygisk in your Magisk Manager, you should install the Zygisk build[/SIZE][/SIZE][/SIZE][/INDENT]
[INDENT=2][SIZE=3][SIZE=3][SIZE=3] - if you have disabled Zygisk in your Magisk Manager, you should install the Riru build[/SIZE][/SIZE][/SIZE][/INDENT]
[INDENT=2][/INDENT]
[INDENT=2][/INDENT]
[LIST]
[*][URL='https://github.com/Dr-TSNG/Hide-My-Applist/releases']Hide My Applist[/URL] (a v3 branch apk)
[/LIST]

[INDENT=2][B]Note #1 (Versions):[/B] Now [B]SAFE[/B] to use the downloader in Lsposed Manager to download it (at original time of putting up this guide it was only serving the older v2 builds)[/INDENT]
[INDENT=2][/INDENT]
[INDENT=2][B]Note #2 (Bootloops): [/B]HMA v2 also used a companion magisk module, that if you forgot uninstall when uninstalling HMA itself, would cause a bootloop.  HMA v3 [B]DOES NOT[/B] require a magisk module to achieve its purpose, so please [B]DO NOT[/B] attempt to install HMA v3 over the top of HMA v2, or install the magisk module from HMA v2 separately, in conjunction with v3. If you have HMA v2 installed, please uninstall the HMA v2 magisk module via Magisk Manager, then remove HMA, and reboot, before installing HMA v3.[/INDENT]



**Method:**


- **Install Lsposed**

From your launcher, open your Magisk Manager app (yours is hopefully renamed as mentioned earlier) and switch to the Modules tab (at bottom), then tap Install From Storage at the top of screen.

![](https://github.com/adrianmmiller/Hide-My-Applist-Guide/blob/main/HMA1.jpg?raw=true)

On the next screen, select the directory where you stored the Lsposed zip, and then tap it

![](https://github.com/adrianmmiller/Hide-My-Applist-Guide/blob/main/HMA2.jpg?raw=true)

The Lsposed module will now install, and when complete you should tap **Reboot** to reboot your device

![](https://github.com/adrianmmiller/Hide-My-Applist-Guide/blob/main/HMA3.jpg?raw=true)

After your device reboots, you will see a prompt to add a shortcut to your launcher, you can manually place it, but i usually just tap Add Automatically, and let it sort it out, for me, as my main launcher screen is full, this overflows onto a second launcher screen...

![](https://github.com/adrianmmiller/Hide-My-Applist-Guide/blob/main/HMA4.jpg?raw=true)



-**Install HMA**

Select the directory where you stored the HMA apk, and install it

![](https://github.com/adrianmmiller/Hide-My-Applist-Guide/blob/main/HMA5.jpg?raw=true)

After install is complete, you should see a notification in the notification bar, pull down your notification bar and tap the [B]Xposed Module Is Not Activated Yet[/B] notification

![](https://github.com/adrianmmiller/Hide-My-Applist-Guide/blob/main/HMA6.jpg?raw=true)

When the HMA app opens, tap to toggle the [B]Enable Module[/B] toggle to [B]On[/B], make sure the [B]ONLY[/B] scope that HMA is applied to is [B]System Framework[/B], then tap the gear icon towards bottom right to go to HMA's Settings

![](https://github.com/adrianmmiller/Hide-My-Applist-Guide/blob/main/HMA7.jpg?raw=true)



[LIST]
[*][B]Configure HMA[/B]
[/LIST]
When the Settings screen opens, tap on [B]Template Manage[/B]

![](https://github.com/adrianmmiller/Hide-My-Applist-Guide/blob/main/HMA8.jpg?raw=true)

On the next screen tap [B]Create A Blacklist Template[/B]

![](https://github.com/adrianmmiller/Hide-My-Applist-Guide/blob/main/HMA9.jpg?raw=true)

On the following screen, type [B]root[/B] into the [B]Template Name[/B] box, then tap [B]Edit List[/B], just below and to the right

![](https://github.com/adrianmmiller/Hide-My-Applist-Guide/blob/main/HMA10.jpg?raw=true)


Selecting root, HMA and lsposed apps...

On the following screen, you'll see a list of all your apps, select the following, by tapping to tick them:
[LIST]
[*]Magisks renamed (hidden) app - mines always App (because as i said, im lazy and its easy to add)
[*]HMA - obviously
[*]Any Xsposed/LSposed apps
[/LIST]

When youre done, press the back navigation key, swipe back or tap the back arrow in top left to return to main HMA screen

![](https://github.com/adrianmmiller/Hide-My-Applist-Guide/blob/main/HMA11.jpg?raw=true)



[LIST]
[*][B]Configure Apps[/B]
[/LIST]

From the main HMA Settings menu, tap [B]App Manage[/B]

![](https://github.com/adrianmmiller/Hide-My-Applist-Guide/blob/main/HMA12.jpg?raw=true)

On the following screen, you'll see a list of all your apps, select any which you want to hide root, HMA and any xposed/lsposed modules from, by tapping to tick them

This will normally be:
[LIST]
[*]Google Pay/Wallet
[*]Banking apps
[*]Any "detection" apps (see list in [B]Testing HMA[/B] section below for common detection apps)
[/LIST]
i.e. Any apps which complain about root or other sensitive app detection are a candidate for adding here.

For each app you add, do the following:
[LIST]
[*]Tap the toggle to the right of [B]Enable Hide[/B] to enable hiding
[*]Under [B]Template Config[/B] (toward bottom) tap [B]Using 0 Template[/B]
[/LIST]

![](https://github.com/adrianmmiller/Hide-My-Applist-Guide/blob/main/HMA13.jpg?raw=true)

On the popup window that appears:
[LIST]
[*]Tap the checkbox next to [B]root[/B] to select the root blacklist template
[*]Tap [B]OK[/B] to close the popup window
[/LIST]

![](https://github.com/adrianmmiller/Hide-My-Applist-Guide/blob/main/HMA14.jpg?raw=true)

You should now see a screen similar to this for the app you just configured

![](https://github.com/adrianmmiller/Hide-My-Applist-Guide/blob/main/HMA15.jpg?raw=true)

When youre done, press back navigation key, swipe back or tap the back arrow in top left to return to app list, and repeat the above few steps for each app you wish to hide root, HMA and any xposed/lsposed modules from

When youre done selecting all apps you wish to hide root, HMA and any xposed/lsposed modules from, press the back navigation key, swipe back or tap the back arrow in top left to return to main HMA screen

Close out from HMA

Reboot your device to activate HMA and the configuration you just setup

After reboot has completed, launching HMA from your launcher

![](https://github.com/adrianmmiller/Hide-My-Applist-Guide/blob/main/HMA16.jpg?raw=true)

You should show the following screen, showing the status as Activated

![](https://github.com/adrianmmiller/Hide-My-Applist-Guide/blob/main/HMA17.jpg?raw=true)


[B]Note:[/B] Any time you make a configuration change in HMA, you need to reboot for it to take effect

Please note that it can take several minutes on first boot after being configured, for HMA to take effect. Ive noticed this on several ROM flashes. I would wait a good 5 minutes before testing, or opening any apps you have hidden via HMA after this first initial boot.


[U][B]Testing HMA[/B][/U][B][U][B][U]:[/U][/B][/U][/B]

Of course you're probably going want to test the apps you primarily installed HMA to assist with, but you can of course test with the following test apps (some of which you may have had installed already and added during the [B]Configure Apps[/B] step.

One, [B]Applist Detector[/B], is linked in the main screen of HMA itself, but not installed by default, so on tapping it for the first time, it will prompt you to download it, or you can grab it before hand from [URL='https://github.com/Dr-TSNG/ApplistDetector/releases/']here[/URL]

The other well known detection tools are:

[B]Momo[/B] from [URL='https://t.me/magiskalpha']here[/URL] (TG only...may need to scroll to find)

[B]Ruru[/B] from [URL='https://github.com/byxiaorun/Ruru/releases']here[/URL] (Github)

[B]Oprek Root Detector[/B] from [URL='https://play.google.com/store/apps/details?id=com.godevelopers.OprekCek']here[/URL] (Google Play Store)

[B]TB Checker - SafetyNet & Root[/B] from [U][URL='https://play.google.com/store/apps/details?id=krypton.tbsafetychecker']here[/URL][/U] (Google Play Store)

[B]Security Check - Device Compliance[/B] from [URL='https://play.google.com/store/apps/details?id=com.hce.compliance.checker']here[/URL] (Google Play)

Note: After adding apps to the root blacklist or other configuration changes, you need to not only reboot to allow the changes to take effect, but also to force close and clear data for any of the above testing apps before testing again.

Note #2: The results of the tests are beyond the scope of this guide, and best discussed in the main Magisk threads, not here, as this is merely a guide for HMA, and as such would be the worst place to have your posts seen due to the low volume of traffic. Also please do not PM me about test results, all such PM's will go directly to /dev/null/




[B][U]HMA Backup & Restore:[/U][/B]

To save recreating the root blacklist template and apps list, you can backup HMA's config and restore it after a clean ROM flash or post factory reset

Backup:
[LIST]
[*]From the main HMA screen scroll down if need be (due to ad placement) and tap [B]Backup[/B]
[*]Locate where you want to save the [B]HMA_Config.json[/B] (prenamed) file and then tap [B]Save[/B]
[*]Copy[B] HMA_Config.json [/B]off device for safe keeping
[/LIST]

Restore:
[LIST]
[*]Copy[B] HMA_Config.json [/B]onto device if needed
[*]Run through the setup as above until you reach the main HMA window at the [B]Configure HMA[/B] stage
[*]From the main HMA screen scroll down if need be (due to ad placement) and tap [B]Restore[/B]
[*]Locate where you stored the [B]HMA_Config.json[/B] (prenamed) file and then tap [B]Restore[/B]
[*]If you rename (hide) the Magisk Manager app, and you should, you will need to add the (new) renamed Magisk Manager's app to the root blacklist template after restoring the HMA config:
[LIST]
[*]From the main HMA screen, tap [B]Manage Template[/B]
[*]Tap [B]root[/B] template
[*]Tap [B]Edit List[/B] (the first one) to the right of [B]X Apps Invisible[/B]
[*]Scroll to find your renamed Magisk Managers app and select it
[*]Press the back navigation key, swipe back or tap the back arrow in top left to return to main HMA screen
[/LIST]
[*]Close out from HMA
[*]Reboot your device to activate HMA and the configuration you just restored
[/LIST]

Please report any issues you may find with the guide above

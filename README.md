# Modernize-8110

Want the new cool UI thingies the newer KaiOS versions have but HMD won't update their devices? well then you're in luck I have time to waste on CSS!

## Features

here's a full list

- aligns the clock of the launcher to the right.
- shows a border instead of a background color on the grid view on the launcher.
- fixes that weird thing where the lower resolution of the icon shows up in single view.
- gets rid of the debugger icon in the statusbar
- replaces the gaia-icons to use the ones found in 2.5.3+
- the weird LTE logo next to the signal bar when mobile data is turned on is replaced with 4GLTE
- newer volume bar thingy
- Segoe Emoji (2019 or Windows 10 version, Unicode 12)

## Screenshots

![](/screenshots/index.png)
![](/screenshots/index1.png)
![](/screenshots/index2.png)
![](/screenshots/index3.png)
![](/screenshots/index4.png)
![](/screenshots/index5.png)
![](/screenshots/index6.png)
![](/screenshots/index7.png)
![](/screenshots/index8.png)

## FAQ

#### Will this work on other KaiOS devices?

Probably not, you can try but a lot of things will probably break... this uses the default `CSS` that is present on the 8110.

#### How to enable the theme after installing?

Use [Intent]("https://github.com/openGiraffes/Intent") to enable the theme... If you're racist and for some reason you hate anything that's Chinese go to `Device Preferences` in `WebIDE` and change the value of `dom.mozApps.selected_theme` to `nokia_sans.bananahackers.net`

#### I hate it! How do I uninstall this piece of garbage?

You can use [AllA](https://github.com/Lcsunm/ALLA-KaiOS/), or delete `/data/local/webapps/nokia_sans.bananahackers.net` and reboot.

#### How do I get emojis in the Symbols of my keyboard?

I'm using a modified version of the 8110's keyboard app... You can install the one used in GerdaOS... Or wait for me to release the one I made. For now you can use Google Assistant to type emojis you want.

#### Why does the emojis not show up on some apps?

This is because the emojis only show up on apps that utilize the `themeable{}` permission, if the app does not use it, the emojis will not work. If you want the emojis to always show up you'll need to modify the system partition therefore not making it systemless.

#### How do I change the emoji or font to the one I want?

Learn basic `CSS` and make a theme yourself lmao... Tip: Firefox only supports `COLR` and `OpenType-SVG` color formats for fonts so pick the emoji to use wisely.

#### Why is the date in the launcher not a 1:1 copy of the newer devices?

Because I have only modified the `CSS` and not `JavaScript`.

#### I found a bug, what to do?

Go to the Issues tab, don't bother pinging me on Discord.

## Credit

[ThemeWhite](https://github.com/Lcsunm/ThemeWhite-KaiOS) - only used as a reference no code was used at all.

iGameEveryday06 - useful screenshots, sent me a copy of the system image of the 800T.

Yes I made this without help at all hahaha.

## License

AGPLv3

unity-launcher-circle
=====================

This is the modified theme for Ubuntu Unity launcher.

![ScreenShot](https://raw.github.com/bitrevo/unity-launcher-circle/master/screenshot.png)

Please make a backup of the origial icons of Unity and overwrite the icons from this theme.

```
$ sudo mv /usr/share/unity/icons /usr/share/unity/icons.orig
$ sudo cp -r icons /usr/share/unity/icons
```


If you are using Numix Light theme with this modified theme, it's recommend to apply this patch to make the color of Unity top panel to dark.

```
$ sudo mv ~/.themes/Numix\ Light/gtk-3.0/gtk.css ~/.themes/Numix\ Light/gtk-3.0/gtk.css.orig
$ sudo cp gtk-3.0/gtk.css ~/.themes/Numix\ Light/gtk-3.0/
```

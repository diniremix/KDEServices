#KDE services app

- **Extract And Compress** version 1.4.4 based on [Extract And Compress KDE4](http://kde-look.org/content/show.php?content=84206) works fine on [Doplhin](https://www.kde.org/applications/system/dolphin/) Versión **15.08.2** and [KDE Frameworks](https://www.kde.org/announcements/kde-frameworks-5.0.php) **5.15.0**

##troubleshootings:

after installing check if the file exists "**konqpopupmenuplugin.desktop**" in 
```sh
/usr/share/kservicetypes5/
```

if not there run:
```sh
sudo ln -s /usr/share/kde4/servicetypes/konqpopupmenuplugin.desktop /usr/share/kservicetypes5/
```

##Thanks to
[Kde looks](http://kde-look.org/content/show.php?content=84206)

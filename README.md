Notification Popup Window Nuget [![Build status](https://ci.appveyor.com/api/projects/status/9fumwsbldabj54x3/branch/master?svg=true)](https://ci.appveyor.com/project/tulpep/notification-popup-window/branch/master)
========================
###A notification window that appears on the lower right part of the screen for .NET

![Screenshot](Screenshots/example1.png)


This project is based on a [Notification Window](http://www.codeproject.com/Articles/277584/Notification-Window) created in 2011 by Simon Baer. It is also base in [Office 2003-like popup notifier](http://www.codeproject.com/Articles/13547/An-Office-like-popup-notifier) created in 2006 by Nicolas Wälti.

###How to use it
You can install the lastest version using [NuGet](https://www.nuget.org/packages/Tulpep.NotificationWindow/)
```powershell
Install-Package Tulpep.NotificationWindow
```

And use it this way:
```cs
var popupNotifier = new PopupNotifier();
popupNotifier.TitleText = "Title of popup";
popupNotifier.ContentText  = "Content text";
popupNotifier.Popup();

```
This repository contains a Visual Studio Test Project if you want a working example.

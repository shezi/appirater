Introduction
------------
Appirater is a highly configurable, localized framework that you can drop into any iOS app which will help remind your users to review your app on the App Store. The framework is currently localized in English, French and Japanese. 

![Appirater screenshot][screenshot]


The code is released under the MIT/X11, so feel free to
modify and share your changes with the world. To find out more, check out the [project
homepage] [homepage].

Note: This fork of the appirater code has been enhanced quite a bit with improved code and 
new funcitonality such as memory usage improvements, localization in several languages,
and additional options for when to display the rating request dialog.

Getting Started
---------------
1. Add the Appirater code into your project
2. Add the `CFNetwork` and `SystemConfiguration` frameworks to your project
3. Call `[Appirater appLaunchedWithID:<Your apple provided software id>]` at the end of your app delegate's `application:didFinishLaunchingWithOptions:` method.
4. Call `[Appirater applicationWillEnterForeground]` from your app delegate's `applicationWillEnterForeground` method. 

License
-------
Copyright 2008. [Arash Payan] [arash].
This library is distributed under the terms of the MIT/X11.

While not required, I greatly encourage and appreciate any improvements that you make
to this library be contributed back for the benefit of all who use Appirater.

[homepage]: http://arashpayan.com/blog/index.php/2009/09/07/presenting-appirater/
[arash]: http://arashpayan.com
[screenshot] http://app-apps.com/images/appirater_screenshot.png 
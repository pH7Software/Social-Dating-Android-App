# Social Dating Android App

The pH7 Social Dating Android App allows you to use [pH7CMS](http://ph7builder.com) through an easy-going and intuitive Android app. Keep pH7CMS everywhere in your pocket and make as much modification as you can thanks the 100% open source code

## Overview

The app is basically a webview for pH7CMS Pro software allowing you to create your own social dating app with this android dating app builder.


## How It works

When your [pH7CMS Pro's website](http://ph7builder.com/pro) is live, you will be able to edit the app's URL in `MainActivity.java` by changing `public final static String URL_SITE = "http://demo.hizup.com/pH7CMS";` to the URL of your site like `public final static String URL_SITE = "http://my-ph7cms-dating-app.com/?mobapp=1";`

Note that the `?mobapp=1` is important for pH7CMS [MobileApp class](https://github.com/pH7Software/pH7-Social-Dating-CMS/blob/master/_protected/framework/Mobile/MobApp.class.php#L20). This will help your site to be even better than normally on native app!

Finally, to change the name of your app, just edit `/app/src/main/res/values/strings.xml` and change the second line like the following: `<string name="app_name">My Awesome Social Dating App</string>`

Then don't forget to change the package name by refactoring the app and compile the project and build the APK file.


## Author

Pierre-Henry Soria


## Contact

hello {AT} ph7builder {D0T} com


## Need a Professional Dating Site/App...?

Feel free to say hello and asking a free quote at [Web Agency](http://hizup.uk).


## License

This App and Code is under [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.txt) or later; Check the LICENSE.txt file for more details.

# android_nav_drawer

A simple Android navigation drawer template using the NavigationView class for the menu. 

This version on branch 'develop' can only run on Lollipop 5.0 due to the use of the new VectorDrawable class. The minSdkVersion is set for 21, targetSdkVersion is 22. This dramatically reduces the project size and your overhead asset prep work, because you only have to save a graphic once as xml, and it scales for different sizes of phones and tablets. You do not have to save an icon file in each of the mipmap folders or the hdpi, ldpi, xhdpi, xxdpi etc folders as we did for Kitkat and SDKs prior to Android 5.0.

Use the Material Design Icons 2.0.0 library (in the drawable-anydpi-v21 folders are xml files, ready to be dropped right in), or create your own. There are good tutorials, but I found that I had to simplify the path in Illustrator, and use the alignment tools before converting the shape to a compound path.

Very cool, convert an svg file to xml for android by dropping the SVG file in this browser: 
http://inloop.github.io/svg2android/
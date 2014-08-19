How to use
========

Simply add the repository to your build.gradle file:

```groovy
repositories {
    maven {
        url 'https://raw.githubusercontent.com/Goddchen/mvn-repo/master/'
    }
    mavenCentral()
}
```

And you can use the artifacts like this:

```groovy
dependencies {
    compile 'com.dropbox.chooser:android:1.0.0'
    compile 'com.facebook.android:facebook:3.17.1'

    // compile 'com.actionbarsherlock:actionbarsherlock:4.3.1'
    // use this for ActionBarSherlock (org. MavenCentral):
    compile 'com.actionbarsherlock:actionbarsherlock:4.4.0@aar'

    compile 'com.android:volley:1.0'
    compile 'com.actionbarsherlock:viewpagerindicator:2.4.1'
    compile 'com.jeremyfeinstein.slidingmenu:slidingmenu:1.3-SNAPSHOT'
    compile 'org.holoeverywhere:holoeverywhere:1.6.8'
    compile 'org.holoeverywhere:addon-preferences:1.6.8'
    compile 'org.holoeverywhere:addon-slider:1.6.8'
    compile 'org.holoeverywhere:addon-roboguice:1.6.8'
    compile 'org.roboguice:roboguice:2.1-SNAPSHOT'
    compile 'com.sherlock:navigationdrawer:1.0-SNAPSHOT'
    compile 'com.facebook.android:facebook:3.5.2'
    compile 'com.dropbox.chooser:android:1.0.0'
    compile 'com.mobeta.android.dslv:drag-sort-listview:0.6.1'
    compile 'com.doomonafireball.betterpickers:android-betterpickers:1.3.1'
    compile 'net.simonvt.menudrawer:menudrawer:3.0.3'
    compile 'com.emilsjolander:stickylistheaders:1.0.0-SNAPSHOT'
    compile 'org.jraf:android-switch-backport:1.0'
    compile 'com.github.manuelpeinado.multichoiceadapter:multichoiceadapter:2.2.5'
    compile 'com.github.manuelpeinado.glassactionbar:glassactionbar:0.2.1'
    compile 'com.github.chrisbanes.actionbarpulltorefresh:library:0.5'
    compile 'com.github.chrisbanes.actionbarpulltorefresh:extra-abs:0.5'
    compile 'com.github.manuelpeinado.refreshactionitem-native:RefreshActionItem:1.0.3'
    compile 'com.larswerkman:holo-color-picker:1.0-SNAPSHOT'
    compile 'com.fortysevendeg.swipelistview:swipelistview:1.0-SNAPSHOT'
}
```

Notes:

- Roboguice doesn't include MapActivity class, so if you're using with pre v2 Maps API it won't work!

License:
--------
The licenses are provided by the individual libary owner. This "mvn-repo" utilizes these libaries and
won´t provide any support, responsibility or licenses itself.

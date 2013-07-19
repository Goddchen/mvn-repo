How to use
========

Simply add the repository to your build.gradle file:

    repositories {
        maven {
            url 'https://github.com/Goddchen/mvn-repo/raw/master/'
        }
        mavenCentral()
    }

And you can use the artifacts like this:

    dependencies {
        compile "com.actionbarsherlock:actionbarsherlock:4.3.1"
        compile "com.android:volley:1.0"
        compile "com.actionbarsherlock:viewpagerindicator:2.4.1"
        compile "com.jeremyfeinstein.slidingmenu:slidingmenu:1.3-SNAPSHOT"
        compile "org.holoeverywhere:holoeverywhere:1.6.8"
        compile "org.holoeverywhere:addon-preferences:1.6.8"
        compile "org.holoeverywhere:addon-slider:1.6.8"
        compile "org.roboguice:roboguice:2.1-SNAPSHOT"
        compile "com.sherlock:navigationdrawer:1.0-SNAPSHOT"
        compile "com.facebook.android:facebook:3.0.2"
        compile "com.mobeta.android.dslv:drag-sort-listview:0.6.1"
        compile "com.doomonafireball.betterpickers:android-betterpickers:1.3.1"
        compile "net.simonvt.menudrawer:menudrawer:3.0.3"
        compile "com.emilsjolander:stickylistheaders:1.0.0-SNAPSHOT"
        compile "org.jraf:android-switch-backport:1.0"
        compile "com.github.manuelpeinado.multichoiceadapter:multichoiceadapter:2.2.5"
        compile "com.github.manuelpeinado.glassactionbar:glassactionbar:0.2.1"
        compile "com.github.chrisbanes.actionbarpulltorefresh:library:0.5"
        compile "com.github.chrisbanes.actionbarpulltorefresh:extra-abs:0.5"
    }

Notes:

- Roboguice doesn't include MapActivity class, so if you're using with pre v2 Maps API it won't work!

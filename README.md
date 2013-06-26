mvn-repo
========

How to use
--------

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
    }

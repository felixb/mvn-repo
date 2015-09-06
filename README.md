Artifacts
=========

There are the following artifacts available in this repo:

 * [de.ub0r.android.ub0rlogg0r:logg0r](https://github.com/felixb/ub0rlogg0r)
 * [de.ub0r.android.lib:lib](https://github.com/felixb/ub0rlib)
 * [de.ub0r.android.websms.connector.common:WebSMSAPI](https://github.com/felixb/websms-api)
 * [de.ub0r.android.eucookieconsent:library](https://github.com/felixb/eucookieconsent)

How to use
==========

Simply add the repository to your build.gradle file:

    repositories {
        maven {
            url 'https://raw.githubusercontent.com/felixb/mvn-repo/master/'
        }
        mavenCentral()
    }

And add the dependency to your project like this:

    dependencies {
        compile 'de.ub0r.android.ub0rlogg0r:logg0r:+'
    }

fx2048
======

The game 2048 built using JavaFX and Java 8. This is a fork based on the
Javascript version: https://github.com/gabrielecirulli/2048

Building fx2048
====================

You will need [Java 8](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
, [Maven](http://maven.apache.org/) and [Excelsior JET](http://www.excelsiorjet.com) installed to build the project. 
Just execute ant in the project root.

```bash
mvn package jet:build
```

Running fx2048
===================

After you've built the project you can run the resulting executable

```bash
./target/jet/app/Game2048
```

Running 2048FX on Mobile/Tablet
=====================

Thanks to the JavaFXPorts [project](https://bitbucket.org/javafxports), you can play 2048FX on mobile too.

For Android, go to Google Play: 

https://play.google.com/store/apps/details?id=org.jpereda.game2048

For iOS, go to the Apple Store:

https://itunes.apple.com/us/app/2048fx/id989966696?mt=8


License
===================

The project is licensed under GPL 3. See [LICENSE](https://raw.githubusercontent.com/brunoborges/fx2048/master/LICENSE)
file for the full license.

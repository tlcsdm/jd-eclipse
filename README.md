# JD-Eclipse

JD-Eclipse, a Java decompiler plug-in for the Eclipse platform.

![](https://raw.githubusercontent.com/tlcsdm/jd-eclipse/master/src/website/img/jd-eclipse.png)

- Java Decompiler projects home page: [http://java-decompiler.github.io](http://java-decompiler.github.io)
- JD-Eclipse source code: [https://github.com/tlcsdm/jd-eclipse](https://github.com/tlcsdm/jd-eclipse)

## Description
JD-Eclipse is a plug-in for the Eclipse platform. It allows you to 
display all the Java sources during your debugging process, even if 
you do not have them all.

## How to build JD-Eclipse ?
```
> git clone https://github.com/tlcsdm/jd-eclipse.git
> cd jd-eclipse
> ./gradlew build
```
generate _"build/distributions/jd-eclipse-x.y.z.zip"_

## How to install JD-Eclipse ?
Update Site:

Create a new update site in Eclipse with the following:

* Site name: Java Decompiler Eclipse Plug-in
* Site URL: https://raw.githubusercontent.com/tlcsdm/jd-eclipse/master/org.jd.ide.eclipse.site/site.xml

## How to check the file associations ?
Click on _"Window > Preferences > General > Editors > File Associations"_
- _"*.class"_ : _Eclipse_ _"Class File Viewer"_ is selected by default.
- _"*.class without source"_ : _"JD Class File Viewer"_ is selected by default.

## How to uninstall JD-Eclipse ?
1. Click on _"Help > About Eclipse > Installation Details"_,
2. Select _"JD-Eclipse Plug-in"_,
3. Click on _"Uninstall..."_.

## License
Released under the [GNU GPL v3](LICENSE).

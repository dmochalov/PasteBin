nbbuild_cndplugins_2018.zip

Here in the gzip archive, there are all plugins for Netbeans required for c++17 support.
They were downloaded from the daily builds. Currently, the site is unavailable.
How to use it?
1) Download the zip archive
2) Unpack it.
3) Start NetBeans, go-to Tools -> Plugins -> Downloaded.
4) Click Add Plugins and select all plugins in the achive.
5) Click install. 

You need to run your NetBeans on JDK 8 to install it successfully. Because nbm plugins require unpack200, and it only available on JDK8.

netbeans-trunk-nightly-201804200002-windows.exe
NetBeans 8.2 last dev nigthly build. It has support for c++17 but only runs on 1.8 JDK.

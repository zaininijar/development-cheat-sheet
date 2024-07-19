## Flutter Cheatsheet

##### <a href="#1" style="font-size: 18px;">#1 <a> No enable impeller on ios platform

```bash
flutter run --no-enable-impeller
```

##### <a href="#1" style="font-size: 18px;">#2 <a> Connect Wireless Debugging Android

###### Pair the Android device with the host machine using pairing code

```bash
adb pair <host>:<port> <code>
```

###### Check which mDNS daemon is used

```bash
adb mdns check
```

**_Or you can use NPM command line interface (CLI) tool_**

##### GitHub - saleehk/adb-wifi

###### Installation :

```bash
npm i adb-wifi -g
```

###### run

```bash
adb-wifi
```

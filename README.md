###

<div align="center">
  
![logo](https://raw.githubusercontent.com/OmBharsakle/Flutter-Cheat-Sheet/main/assets/Flutter%20Cheat%20Sheet.jpg)

</div>
 

###

<p align="center">Overall, The Flutter Cheat Sheet Contributes To Enhancing Productivity, Efficiency, And The Overall Quality Of Flutter Applications, Making It An Indispensable Resource In The Toolkit Of Flutter Developers.</p>

###

<h2 align="left">1. Code Start Line Code</h2>

###
 

```bash
import 'package:flutter/material.dart';

void main() {
  runApp(const MyApp());
}

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  // This widget is the root of your application.
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(),
		body:,
      ),
    );
  }
}
```
 
###

<h2 align="left">2. Status Bar Color Change Code</h2>

###


```bash
import 'package:flutter/services.dart';

void main() {
  SystemChrome.setSystemUIOverlayStyle(
      SystemUiOverlayStyle(
        statusBarColor: Colors.black,
        statusBarIconBrightness: Brightness.light
      )
  );
  runApp(const MyApp());
}
```
###

<h2 align="left">3. Splash Screen Timer Code</h2>

###


```bash
Timer(
      Duration(seconds: 3),
      () {
        Navigator.of(context).pushNamed('/home');
      },
    );
```
###

<h2 align="left">3. Splash Screen Timer Code</h2>

###


```bash
Timer(
      Duration(seconds: 3),
      () {
        Navigator.of(context).pushNamed('/home');
      },
    );
```

 

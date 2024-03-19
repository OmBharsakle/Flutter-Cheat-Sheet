###

<div align="center">
  
![logo](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiq6NY3W4RM-MDy2kfQVejr0drz3Q745wrMNM3URgzQRb2w3u6OXSJpQe616dLfY6IOG_Bkf1bi0YhcM2VFe6d1iO4nizje88gTci0ZWk-kJsInDJqzfP4I9xzRGuJ6yaAE2RL8SzqwseDQAZZ2oYpikR3mDshnr4ymYidugxz0TymbsjaZJDZVwh8hlUg/s16000/Purple%20Modern%20Professional%20Web%20Designer%20LinkedIn%20Banner%20(3).jpg)

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

 

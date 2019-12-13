# Day Night mode Switcher

Day Night Mode Switcher in Flutter

 <img alt="Awesome Flutter" src="https://img.shields.io/badge/Awesome-Flutter-blue.svg?longCache=true&style=flat-square" />

<img src="https://raw.githubusercontent.com/divyanshub024/day_night_switch/master/day_night_switch.gif" />

# Installation

Add to pubspec.yaml.

```
dependencies:
  day_night_switch:
```

## Usage

To use plugin, just import package 

`import 'package:day_night_switch/day_night_switch.dart';`


## Example
```
DayNightSwitch(
  value: val,
  moonImage: AssetImage('assets/moon.png'),
  sunImage: AssetImage('assets/sun.png'),
  sunColor: sunColor,
  moonColor: moonColor,
  dayColor: dayColor,
  nightColor: nightColor,
  onChanged: (value) {
    setState(() {
    val = value;
    });
  },
)

```


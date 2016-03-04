# dye
A simple dart library for easy color printing to terminal.

```dart
import 'package:dye/dye.dart';

main() {
  print(blue('Hello World'));
  print('${blue('Hello')} ${red('World')}');
}
```
Or, for a mode node feel -

```dart
import 'pacakge:dye/dye.dart' as dye;

main() {
  print(dye.blue('Hello World'));
  print('${dye.blue('Hello')} ${dye.red('World')}');
}

```

### Supports

* red()
* blue()
* green()
* yellow()
* magenta()
* cyan()
* black()
* white()
* gray()

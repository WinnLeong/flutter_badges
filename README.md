# Badges for Flutter

A flutter package for creating badges.

<img src="https://raw.githubusercontent.com/yadaniil/flutter_badges/master/example.gif" height="320px" >


## Installing:
In your pubspec.yaml
```yaml
dependencies:
  badges: ^0.0.4
```

## Example Usage:
```dart
import 'package:badges/badges.dart';

BadgeIconButton(
                itemCount: _counter, // required
                iconData: Icons.shopping_cart, // required
                badgeColor: Colors.green, // default: Colors.red
                badgeTextColor: Colors.white, // default: Colors.white
                hideZeroCount: true, // default: true
                onPressed: _increment),
                
```

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details

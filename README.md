Validating:

- phone
- name
- postalCode
- email
- url
- currency
- ip
- date
- time
- htmlTags
- password
- creditCard

For Dart/Flutter developers.
[Regexed Validator at pub.dartlang.org](https://pub.dartlang.org/packages/regexed_validator "Regexed Validator")

## Usage

Usage is pretty simple just pass a phone, date, email... to its validation method, see the example below

```dart
import 'package:regexed_validator/regexed_validator.dart';

main() {
  print( validator.email('example@example.co.uk') ); // true
  print( validator.htmlTags('<strong>Bold</strong>\n'
          '<em>Emphazied</em>\n'
          '<b>Bold</b>\n'
          '<i>Italics</i>\n'
          '<span id="foo" class="bar">Some text</span>\n'
          '<hr />')
  ); // true
}
```

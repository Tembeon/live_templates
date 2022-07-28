## Templates for [freezed](https://pub.dev/packages/freezed) package


### freezed class
```dart
import 'package:freezed_annotation/freezed_annotation.dart';

part '$fileNameWithoutExtension$.freezed.dart';

@freezed
class $NAME$ with _$$$NAME$ {
  const factory $NAME$({
      required int id,
      $END$
  }) = _$NAME$;
}
```

### freezedJson addition
```dart
factory $NAME$.fromJson(Map<String, dynamic> json) => _$$$NAME$FromJson(json);
```

### freezedJson part addition
```dart
part '$FILENAME$.g.dart';
```
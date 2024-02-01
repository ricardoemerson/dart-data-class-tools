# Change Log

## 0.8.1

- Revert the previous behavior.

## 0.8.0

- Simplify use of ValueGetter using `x?.call() ?? this.x` instead `x != null ? x() : this.x`. Thanks to [Petr Nymsa](https://github.com/petrnymsa).

## 0.7.0

- Update `List<Object> props = []` to `List<Object?> props = []` when any type of attribute has a nullable value when generates Equatable.

## 0.6.0

- Added support for uses ValueGetter for nullable types when generates copyWith.
- Added the setting `copyWith.usesValueGetter` to enable/disable uses of ValueGetter for nullable types when generates copyWith.


## 0.5.7

- Updated the badges in README.md.

## 0.5.2

Added support for snake_case json keys
Generate toString() when converting with Equatable
Other improvements

## 0.5.0

Added support for enums
Use factory constructors instead of static methods for json serialization

### 0.3.17

Added support for value equality on `Lists`, `Maps` and `Sets`.

### 0.3.16

Class fields can now also be declared after the constructor.
Minor improvements.

### 0.3.6 - 0.3.15

Fixed some bugs.

### 0.3.5

Added support for equatable by setting dart-data-class-generator.useEquatable to true.

Changed setting `dart-data-class-generator.constructor` to `dart-data-class-generator.constructor.enabled`
Changed setting `dart-data-class-generator.copyWith` to `dart-data-class-generator.copyWith.enabled`
Changed setting `dart-data-class-generator.toMap` to `dart-data-class-generator.toMap.enabled`
Changed setting `dart-data-class-generator.fromMap` to `dart-data-class-generator.fromMap.enabled`
Changed setting `dart-data-class-generator.toJson` to `dart-data-class-generator.toJson.enabled`
Changed setting `dart-data-class-generator.fromJson` to `dart-data-class-generator.fromJson.enabled`
Changed setting `dart-data-class-generator.toString` to `dart-data-class-generator.toString.enabled`
Changed setting `dart-data-class-generator.equality` to `dart-data-class-generator.equality.enabled`
Changed setting `dart-data-class-generator.hashCode` to `dart-data-class-generator.hashCode.enabled`

## 0.3.0

Added quick fixes.

## 0.2.0

Added support for @required annotation.
Changed the default hashCode implementation to bitwise operator.

## 0.1.0

Initial release (Beta).

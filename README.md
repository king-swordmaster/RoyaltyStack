# RoyaltyStack

Monorepo for the RoyaltyStack Dart and Flutter libraries.

## Packages

- `packages/royalty_type`: Result type and helpers for error handling.
- `packages/royalty_stack`: Umbrella package that re-exports bundled libraries.

## Usage

```dart
import 'package:royalty_type/royalty_type.dart';

final Result<int, String> value = Result.ok(42);
```

```dart
import 'package:royalty_stack/royalty_stack.dart';

final Result<int, String> value = Result.ok(42);
```

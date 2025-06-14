# Flutter tests

## Summary
- 🚀 Platforms
- 📃 Description
- ⚙️ Setup
- 💻 Use case

## Platforms
| Android | iOS | Web |
|:-------:|:---:|:---:|
|    ✅    |  ✅  |  ✅   |

## Description

This Flutter project demonstrates how to test a Flutter application, with examples of unit tests, integration tests, widget tests and golden tests.

### Unit Tests

Unit Tests focus on the application's smallest parts, such as individual functions, methods, or variables.  These tests operate in complete isolation and are generally implemented as pure Dart tests that don't require Flutter dependencies. They excel at validating contracts and business logic, providing developers with rapid and meaningful feedback while boosting their confidence in the codebase.

### Widget Tests

Widget Tests concentrate on individual UI components. The emphasis lies in testing the widget's hierarchical structure rather than its visual rendering. This testing approach is essential for assessing UI elements independently. Although widget tests can cover more extensive functionality, they should stay focused on single components to maintain their effectiveness.

### Integration Tests

Integration Tests serve as a middle ground between unit testing and comprehensive end-to-end testing. They replicate complete user workflows using mocked dependencies, enabling developers to validate how different application modules communicate and interact. These tests are especially beneficial for detecting disruptions in business logic and confirming that the application's various components function cohesively as a unified system.

### Golden Tests

Golden tests in Flutter offer an effective approach to validate how your widgets appear visually, guaranteeing consistent and accurate rendering throughout various updates and different scenarios. They work by evaluating the visual output of your widgets against previously stored 'golden' reference image files. When the current display aligns with the stored golden file, the test succeeds; however, any mismatch results in test failure, signaling a visual inconsistency that requires attention.

For further information, please refer to [Flutter documentation](https://docs.flutter.dev/testing/overview).

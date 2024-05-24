# flutter_skeleton_app_sample

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application that follows the
[simple app state management
tutorial](https://flutter.dev/docs/development/data-and-backend/state-mgmt/simple).

For help getting started with Flutter development, view the
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## Assets

The `assets` directory houses images, fonts, and any other files you want to
include with your application.

The `assets/images` directory contains [resolution-aware
images](https://flutter.dev/docs/development/ui/assets-and-images#resolution-aware).

## Localization

This project generates localized messages based on arb files found in
the `lib/src/localization` directory.

To support additional languages, please visit the tutorial on
[Internationalizing Flutter
apps](https://flutter.dev/docs/development/accessibility-and-localization/internationalization)

## Project file structure

```txt
/my_flutter_app
    /android
    /ios
    /lib
        /src
            /models
                - user.dart
                - order.dart
            /services
                - user_service.dart
                - order_service.dart
            /controllers
                - user_controller.dart
                - order_controller.dart
            /views
                /user
                    - user_list_view.dart
                    - user_detail_view.dart
                /order
                    - order_list_view.dart
                    - order_detail_view.dart
            /widgets
                - custom_button.dart
                - custom_list_item.dart
            /utils
                - constants.dart
                - helpers.dart
            /config
                - routes.dart
                - theme.dart
            main.dart
    /test
        /unit_tests
            - user_test.dart
            - order_test.dart
    /web
    pubspec.yaml
    README.md
```

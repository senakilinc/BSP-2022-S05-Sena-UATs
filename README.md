# BSP-2022-S05-Sena-UATs

This package provides the necessary details that would allow anyone to reproduce the testing framework for a Flutter demo counter app that was created as part of a semester project for the degree of Bachelor in Computer Science at the
University of Luxembourg by Sena Kılınç under the supervision of [Dr. Alfredo Capozucca](https://acapozucca.github.io/).

# Tools & Dependencies
This project uses [flutter_gherkin](https://pub.dev/packages/flutter_gherkin) version 2.0.0.

This project has been performed and executed using macOS. Anyone who wishes to change the target device should change the "targetDeviceID" configuration in [app_test.dart](https://github.com/senakilinc/BSP-2022-S05-Sena-UATs/blob/main/test_driver/app_test.dart) file.
# How to use?
-Clone or download the repository to your local machine.
-The project is built using the Flutter framework, so make sure you have the latest version of Flutter installed on your machine.
-Inside the root directory of the project, you will find the pubspec.yaml file. flutter\_gherkin and flutter\_driver dependencies are already added.
-After all the dependencies are installed, you can run the project by executing the following command:
```dart test_driver/app_test.dart --feature="counter_button.feature"```
# Expected Result

The output should look like this:

![alt text](/ExpectedOutput/result.png "Testing Result")
# License
[MIT](/LICENSE)

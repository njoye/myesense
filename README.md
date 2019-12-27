# myesense
This project contains the demo code (not tested by me) of [Rainer Schlund](https://github.com/rschlund) that was published [this repository](https://github.com/rschlund/esense). It can be used as a boilerplate for starting your own Swift based Flutter application. As mentioned before, the given source code is not tested - i can only assure you, that the configuration of the project is working.

### How to configure your own project with ESense (esense_flutter)
1. Create a new Swift based Flutter project using `flutter create -i swift myprojectname`
2. Add esense_flutter to the dependencies (in `pubspec.yaml`) by adding the following under the line `dependencies: `:
    `esense_flutter: 0.2.0+2`
3. Run `flutter pub get` in order to install the newly added dependency
4. Done, you can add your own code and compile your project now.

### More Information / Useful websites if you're new to this
- [Using Packages - Flutter](https://flutter.dev/docs/development/packages-and-plugins/using-packages)
- [esense_flutter - Package Website](https://pub.dev/packages/esense_flutter)

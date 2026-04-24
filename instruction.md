# Procedure in Android Studio

## 1) Create a new Flutter project

Open Android Studio and do the following:

Click New Flutter Project
Select Flutter Application
Enter project name, for example: image_widget_demo
Choose Flutter SDK path
Click Finish

## 2) Add an image to the project

Inside your Flutter project:

Create a folder named assets in the root directory
Put one image inside it, for example: flutter_logo.png

Your structure will look like this:

image_widget_demo/
├── assets/
│   └── flutter_logo.png
├── lib/
│   └── main.dart
└── pubspec.yaml

## 3) Register the image in pubspec.yaml

Open pubspec.yaml and add the asset path under flutter: section.

flutter:
  assets:
    - assets/flutter_logo.png

Make sure indentation is correct. In YAML, spacing matters.

## 4) Run flutter pub get

After saving pubspec.yaml, click:

Pub get in Android Studio
or
run this in terminal:
flutter pub get

## 5) Write the Flutter UI code

Open lib/main.dart and replace it with the following code

# flutter_personal_expenses_demo

A Flutter demo app to record personal expenses and see trends in spending over time via a chart.

Features:
1. Switch in real-time between light and dark mode - persists preference across app restarts.
2. Responsive to landscape and portrait modes.
3. When in landscape mode, can switch between showing chart or expenses list.
4. Adaptive interface that changes buttons and toolbar depending on whether the user is on Android or IOS.

## Demo

![Alt Text](https://firebasestorage.googleapis.com/v0/b/portfolio-ba483.appspot.com/o/expenses_portrait.gif?alt=media&token=2f2382d2-2123-4d80-aebf-5d7100657c97)
![Alt Text](https://firebasestorage.googleapis.com/v0/b/portfolio-ba483.appspot.com/o/expenses_landscape.gif?alt=media&token=25189a65-7de6-4e64-90dd-bb7ff35b57dc)

## Goolge Play Store

You can download the app from the playstore [here](https://play.google.com/store/apps/details?id=com.amnion.flutter_personal_expenses_demo).

## Code Dependencies

If you wish to run this code on your local machine, Flutter needs to be installed.

See instructions [here](https://flutter.dev/docs/get-started/install) for your operating system.

## Starting the app on your local machine

1. Clone this repository or download the zip file.
2. Connect your Android or Apple device to your local machine and make sure it is in developer mode (Android) or it is trusted (Apple). Alternatively, you can open a virtual device in Android Studio and/or Xcode.
3. In a command line, go to the project directory on your computer (wherever your cloned it to, or extracted the zip file) and type:
`flutter pub get`
4. In the same command line, in the same directory, type:
`flutter run`
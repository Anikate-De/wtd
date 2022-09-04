![Logo](readme_images/logo_banner.png)

A cross-platform tasklist application, made with Flutter, with persistent data storage.

Store all your tasks in the WTD app to always be on track. As soon as you're done with a task, just hit the checkbox beside to strikethrough it.

Works on all six platforms supported by Flutter!

## 🌟 Features
- Material UI
- SharedPreferences Data Storage
- Custom Input Dialog
- Provider State Management

## 📱 Screenshots
![Screenshots](readme_images/screenshots.png "Default UI, List of Tasks after addition, Task Addition Dialog")

## ❓How to Use

### Pre-requisites

- **Flutter** is installed and added to `PATH`

### Steps to Follow
- Get the packages, in your terminal, execute -
  ```
  flutter clean
  flutter pub get
  ```
- That's it, you can now run it!
  ```
  flutter run
  ```

## 🤝 Contributing

Contributions are always welcome!

See the [Contribution Guide](contributing.md) for ways to get started.

## 🤩 Inspired By

This project was inspired by Angela Yu's `Todoey` Flutter application, which was demonstrated in her course [The Complete 2021 Flutter Development Bootcamp with Dart](https://www.udemy.com/course/flutter-bootcamp-with-dart/) on Udemy.

This app deals with a crucial aspect that the `Todoey` app missed, which is, user data persistence. This app stores the data using the [Flutter SharedPreferences](https://pub.dev/packages/shared_preferences) package, thus making it available throughout every launch on the device.

## 📖Lessons Learned

WTD has been a great learning experience, especially in my early days of Flutter coding. While creating this project, my motto was to teach myself about Flutter and State Management techniques as much as I could.

I learnt many things along the way, the most notable ones are mentioned below -

- Provider State Management
- Shared Preferences
- Serialisation & De-serialisation
- ModalBottomSheet
- Improving Project Structure
- **and so much more...**

## 💡 Authors

- [@Anikate De](https://www.github.com/Anikate-De)

## 📝 License

Copyright © 2022-present, Anikate De

This project is licensed under [Apache License 2.0](LICENSE)
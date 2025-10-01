# 📸 Random Photo Generator

A simple iOS app built with UIKit that displays a randomly fetched photo from the internet and changes the background color each time a button is pressed.

> 🧪 Demo video link: https://reurl.cc/VWblMy

---

## ✨ Features

- Fetches a random image from [https://picsum.photos](https://picsum.photos/600/600)
- Displays the image in a centered `UIImageView`
- Changes the background color randomly upon button click
- Built using UIKit and written in Swift

---

## 🧱 Components Overview

### `ViewController.swift`

- Uses `UIImageView` to show the image and `UIButton` to trigger photo changes
- Calls `getRandomPhoto()` to fetch a new image from the internet
- Randomly changes the `view.backgroundColor` from a predefined list
- Uses Auto Layout manually via `frame` for layout

### `AppDelegate.swift`

- Handles app lifecycle events (standard boilerplate)
- Implements `didFinishLaunchingWithOptions` and scene configuration

---

## 📦 Dependencies

- No external libraries or frameworks used
- All functionality handled with native UIKit components

---

## 🚀 Getting Started

1. Open the project in Xcode.
2. Run the app on a simulator or physical device.
3. Tap the **"Next"** button to load a new photo and refresh the background color.

---

## 🖼 Preview

- Fetches a 600x600 pixel photo from `https://picsum.photos/600/600`
- Background color changes to one of the following:
  - `.systemPink`, `.systemPurple`, `.systemBlue`, `.systemRed`, `.systemBrown`, `.systemGreen`, `.systemYellow`

---

Created by Hope Chen

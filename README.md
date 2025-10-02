# 📸 Random Photo Generator

A simple iOS app built with UIKit that displays a randomly fetched photo from the internet and changes the background color each time a button is pressed.

> Demo video link: https://reurl.cc/VWblMy
---
> Notion Link: https://chipped-cost-454.notion.site/Random-Photo-Generator-27dffd23a9168004b4bfc8ac3e521640


## ✨ Features

- Fetches a random image from [https://picsum.photos](https://picsum.photos/600/600)
- Displays the image in a centered `UIImageView`
- Changes the background color randomly upon button click
- Built using UIKit and written in Swift

---
## Screenshot

<img width="608" height="514" alt="image" src="https://github.com/user-attachments/assets/3ffb2be4-f41e-4ad1-a23e-f53f5601866e" />

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

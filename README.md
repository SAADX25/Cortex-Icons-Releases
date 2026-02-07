# 🎨 Cortex Icons 🚀

> A collection of professional, high-resolution icons designed specifically for the project

---
## 📌 About the Project
The **Cortex Icons** project is the official library of icons used in our applications. We focus on modern design, clarity, and full compatibility with Windows user interfaces and Electron applications.

## 📁 Repository Contents
* **Icons/**: Includes all icons in PNG format with various sizes (256x256, 512x512).

* **Builds/**: Contains ready-to-use `.ico` files for desktop applications.

* **Assets/**: Original design resources.

* <img width="443" height="593" alt="Screenshot 2026-02-06 173421" src="https://github.com/user-attachments/assets/13528e7c-ec9f-4f3b-895d-e1ca618d04fb" />

## 🛠️ Technical Specifications
* **Supported Formats:** PNG, ICO.

* **Maximum Resolution:** 512x512 pixels.

* **Design Style:** Modern Gradient.

## 🚀 How to Use in Electron
To add the icon to your project, make sure to modify the icon path in your `electron-builder.json5` file:

```json5
win: {
icon: "path/to/icon.ico",

}

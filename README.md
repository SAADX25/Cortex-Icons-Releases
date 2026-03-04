# 🎨 Cortex Icons 🚀

> A collection of professional, high-resolution icons designed specifically for the project

---
## 📌 About the Project
The **Cortex Icons** project is the official library of icons used in our applications. We focus on modern design, clarity, and full compatibility with Windows user interfaces and Electron applications.

## 📁 Repository Contents
* **Icons/**: Includes all icons in PNG format with various sizes (256x256, 512x512).

* **Builds/**: Contains ready-to-use `.ico` files for desktop applications.

* **Assets/**: Original design resources.
<p align="center">
  <table>
    <tr>
      <td><img src="https://github.com/user-attachments/assets/41cba5a6-a0aa-41ff-bb39-83245bdface0" width="400"></td>
      <td><img src="https://github.com/user-attachments/assets/e1ecae70-ecea-4677-800e-ec190fcfef5b" width="400"></td>
    </tr>
  </table>
</p>


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

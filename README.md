# 🖼️ Image Tools GUI

A simple, modern desktop app for image resizing, icon (ICO) conversion, and Base64 generation, built with [Python](https://python.org/), [Pillow](https://pillow.readthedocs.io/), and [ttkbootstrap](https://ttkbootstrap.readthedocs.io/).  
No command line needed—just click, preview, and process images with ease!

![screenshot](.//Screenshot%202025-07-04%20191228.png)

## ✨ Features

- **Image Resize:** Resize images by width, height, or percentage, with optional aspect ratio lock.
- **ICO Converter:** Convert any image to Windows `.ico` format, with customizable size.
- **Base64 Generator:** Instantly create and copy Base64-encoded image data.
- **Batch Image Browser:** Browse an entire folder of images, preview them, and generate/copy Base64 on demand.
- **Drag & Drop (optional):** If you install [tkinterdnd2](https://pypi.org/project/tkinterdnd2/), drag-and-drop is supported (otherwise, click to browse).
- **Modern UI:** Made with ttkbootstrap for a clean, native look.

## 📥 Installation

1. **Clone or download this repository:**
    ```sh
    git clone https://github.com/yourusername/image-tools-gui.git
    cd image-tools-gui
    ```

2. **Install dependencies:**
    ```sh
    pip install pillow ttkbootstrap
    # Optional for drag-and-drop support:
    pip install tkinterdnd2
    ```

3. **Run the app:**
    ```sh
    python image_tools_gui.py
    ```

## 🖱️ Usage

- **Select an image** by clicking the drop area.
- **Resize:** Enter new size or percent, click "Resize Now" and save with a smart default filename.
- **Convert to ICO:** Choose the size and click "Convert to ICO...".
- **Base64:** Choose original or resized, click "Create Base64", then "Copy Base64".
- **Batch Browser:** Click "Browse Folder for Images" to open a popup tool for batch preview and Base64 generation.

## 📝 Requirements

- Python 3.8+
- [Pillow](https://pypi.org/project/Pillow/)
- [ttkbootstrap](https://pypi.org/project/ttkbootstrap/)
- (Optional) [tkinterdnd2](https://pypi.org/project/tkinterdnd2/)

## 💡 Tips

- **Smart Save:** When resizing or converting, the app suggests a filename like `myphoto_200x100.jpg` or `myicon_32.ico`.
- **Drag-and-drop** for images works if `tkinterdnd2` is installed.
- **Always on top?** No—popups are modal but don't block your file dialogs.

## 🏗️ Customization

- You can tweak the default window size, colors, or behaviors by editing `image_tools_gui.py`.
- For advanced automation or extensions, see the code comments.

## 📸 Screenshot

![Main Window](.//Screenshot%202025-07-04%20191228.png)

![Image Browser](.//Screenshot%202025-07-04%20191625.png)

## 🙏 Credits

- [Pillow](https://pillow.readthedocs.io/)
- [ttkbootstrap](https://ttkbootstrap.readthedocs.io/)
- [tkinterdnd2](https://pypi.org/project/tkinterdnd2/)
- Icon by Nikolay Verin at https://www.iconfinder.com/
  

---

MIT License  
Made with 💻 by [jiraiya78](https://github.com/jiraiya78)

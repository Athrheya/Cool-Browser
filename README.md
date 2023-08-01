
# Cool Browser

My Cool Browser is a simple web browser built using Python and PyQt5. It provides essential browsing features such as navigation and tab management. With a user-friendly interface, it offers a smooth and enjoyable web browsing experience.

## Requirements 
To run My Cool Browser, you need the following dependencies:

- Python 3
- PyQt5
- PyQtWebEngine
You can install the required packages using `pip`:
## Installation

Install all the required packages:
```bash
  pip install PyQt5 PyQtWebEngine
```
    
## Features

- **Navigation:** Easily navigate back, forward, and reload pages using the navigation toolbar.

- **Homepage:** Set a custom homepage or use the default one by clicking the "Home" button.

- **URL Entry:** Enter the URL of the website you want to visit in the URL bar and press Enter to load the page.

- **Tab Management:** Open multiple tabs and switch between them effortlessly.


## PyQt5:


PyQt5 is a Python binding for the Qt application framework, which allows developers to create cross-platform desktop applications with a native look and feel. Qt is a widely used C++ framework that provides a comprehensive set of tools for creating graphical user interfaces (GUIs) and handling various tasks like networking, file I/O, and more. PyQt5 enables Python developers to harness the power and flexibility of Qt to build interactive and feature-rich desktop applications.

- Key features of PyQt5 include:

1. **Widgets and Layouts:** PyQt5 provides a wide range of pre-built widgets (buttons, labels, text boxes, etc.) and layout managers (grid layout, box layout) to design the GUI of an application.

2. **Signals and Slots:** PyQt5 uses signals and slots to handle events and communication between different parts of the application. When a particular event occurs (e.g., button clicked), a signal is emitted, and the corresponding slot (a Python method) is executed.

3. **Cross-platform Compatibility:** Applications built with PyQt5 can run on various platforms like Windows, macOS, and Linux, without the need for extensive platform-specific code.

4. **Qt Designer Integration:** PyQt5 includes Qt Designer, a visual design tool that allows developers to create GUI layouts using drag-and-drop features. The designed layouts can be integrated into the Python code easily.

## Usage

1. Launch the browser by running `python main.py`.

2. Browse the web using the navigation toolbar or the URL bar.

3. To navigate back, click the "Back" button on the navigation toolbar.

4. To navigate forward, click the "Forward" button on the navigation toolbar.

5. To reload the current page, click the "Reload" button on the navigation toolbar.

6. To set a custom homepage, modify the `navigate_home` function in the `MainWindow` class in `main.py`.

7. To save a website as a bookmark, click the star icon in the address bar.


8. To switch between tabs, click on the tab you want to view.


Enjoy a cool browsing experience with My Cool Browser! Happy surfing! 🌊🌐
# Color Picker

This is a simple color picker application built using Python and Tkinter. It allows users to adjust RGB values using sliders, and the corresponding color is displayed in real-time. The app also provides the HEX and RGB color codes and allows users to copy the HEX code to the clipboard with a double-click on the color preview box.

## Features

- **RGB Sliders**: Adjust Red, Green, and Blue values to create a custom color.
- **Real-time Preview**: The selected color is displayed instantly in a preview box.
- **HEX Code Display**: The HEX code for the selected color is shown and can be copied to the clipboard.
- **RGB Code Display**: The RGB values (in the format `R, G, B`) for the selected color are shown.

## Installation

1. **Install Python 3.x**: Ensure that Python 3.x is installed on your machine.
2. **Install Tkinter**: Tkinter is included by default with Python. If you don't have it, you can install it by following the instructions [here](https://tkdocs.com/tutorial/install.html).

### Clone the Repository

```bash
git clone https://github.com/your-repo/color-picker.git
cd color-picker
```

### Run the Application

You can run the application directly by executing the Python script:

```bash
python color_picker.py
```

## Usage

1. Open the application, and you will see three sliders to adjust the Red (R), Green (G), and Blue (B) components of the color.
2. As you move the sliders, the color preview box and the HEX and RGB codes will update in real-time.
3. Double-click on the color preview box to copy the HEX code to your clipboard.
4. You can manually edit the HEX code in the provided entry field, and the sliders will update accordingly.

## Code Breakdown

- **`Colorpicker` Class**: This is the main class containing the application's logic. It defines the UI layout and handles the RGB slider changes and the color preview updates.
- **`Tkinter` Widgets**: The app uses various Tkinter widgets such as `Label`, `Scale`, and `Entry` to build the interface.
- **Clipboard Functionality**: Double-clicking the color preview box will copy the HEX code to the clipboard for easy use.

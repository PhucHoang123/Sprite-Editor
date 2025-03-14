# Sprite Editor - README

## Overview
The Sprite Editor is a lightweight pixel-based drawing tool designed for creating and editing sprites. It provides fundamental functionalities such as drawing, erasing, and filling pixels, making it a simple yet effective solution for sprite design.

## Features
- **Add Pixel**: Allows users to place individual pixels on the canvas.
- **Remove Pixel**: Enables the removal of pixels, effectively acting as an eraser.
- **Fill Pixel**: Implements a flood-fill algorithm to fill connected areas with a selected color.
- **Tool Selection**: Users can switch between different tools such as pencil, eraser, and fill tool.
- **Customizable Tool Size**: Adjust the size of the drawing tool for more precise or broader strokes.
- **Undo/Redo (Planned)**: Undo/redo functionality for better editing control.
- **Play-back Frame Animation**: Show and play the animation of all the drawn sprite.

## Installation
1. Ensure you have Qt installed (tested with Qt 6.8.0 MinGW 64-bit).
2. Clone or download the repository.
3. Open the `ToolBarTest.pro` project file in Qt Creator.
4. Build and run the project.

## Usage
1. **Select a Tool**: Use the provided buttons to choose a drawing tool (Pencil, Eraser, or Fill Tool).
2. **Draw on the Canvas**: Click on the canvas area to add or remove pixels.
3. **Fill a Region**: Select the fill tool and click on a region to apply a color fill.
4. **Adjust Tool Size**: Change the size of the pencil or eraser using the UI controls.

## Dependencies
- Qt Framework
- C++17

## Future Enhancements
- Implement color selection for pixels.
- Add support for multiple layers.
- Save and load sprite projects in JSON or image formats.
- Implement keyboard shortcuts for tool switching.

## Contributing
If you wish to contribute, feel free to fork the repository, make changes, and submit a pull request.

## License
This project is not use for academic misconduct.
## Author
Phuc Hoang - Chanphone Visathip - Thu Ha - Trenton Stratton


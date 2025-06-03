# Tkinter Image Processing App

A desktop GUI application built with Python and Tkinter that allows users to:
- Load and display images or folders of images.
- Extract text from images.
- Run simulations with accuracy graphs.
- Save processed images to a selected path.
- View results in separate windows with plotting.
- Refresh the application GUI.

## Features

✅ Load single image  
✅ Load folder of images  
✅ Extract text from image  
✅ Display accuracy graph (matplotlib-based)  
✅ Simulate thresholds and store images  
✅ Custom save directory  
✅ Clear display area  
✅ Refresh entire application  
✅ Consistent button layout and responsive UI

## Requirements

- Python 3.8 or later  
- `tkinter` (comes with standard Python)  
- `matplotlib`  
- `Pillow` (PIL)  
- `opencv-python` (if used for image processing)  

You can install the dependencies via:

```bash
pip install matplotlib Pillow opencv-python

Usage Flow
1.Load Image: Opens a file dialog to load a single image.

2.Load Folder: Loads all images in a selected folder.

3.Extract Text: Extracts and displays text from the image.

4.Storage Path: Select where to save threshold images.

5.10 Simulations: Runs and saves multiple threshold simulations.

6.Show Accuracy Graph: Displays accuracy plots based on results.

7.Clear Display: Clears current text/image results.

8.Refresh: Destroys and reinitializes the GUI window.

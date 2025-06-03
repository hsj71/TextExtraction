# Tkinter Image Processing App

A desktop GUI application built with Python and Tkinter that allows users to:
- Load and display images or folders of images.
- Extract text from images.
- Run simulations with accuracy graphs.
- Save processed images to a selected path.
- View results in separate windows with plotting.
- Refresh the application GUI.
<center>
<img src="https://github.com/hsj71/TextExtraction/blob/main/Images/Screenshot%20(698).png" width="70%">
</center>

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
```

## Usage Flow
1.Load Image: Opens a file dialog to load a single image.
<center>
<img src="https://github.com/hsj71/TextExtraction/blob/main/Images/Screenshot%20(701).png" width="70%">
</center>
2.Load Folder: Loads all images in a selected folder.
<center>
<img src="https://github.com/hsj71/TextExtraction/blob/main/Images/Screenshot%20(706).png" width="70%">
</center>
3.Extract Text: Extracts and displays text from the image.
<center>
<img src="https://github.com/hsj71/TextExtraction/blob/main/Images/Screenshot%20(703).png" width="70%">
</center>
4.Storage Path: Select where to save threshold images.
<center>
<img src="https://github.com/hsj71/TextExtraction/blob/main/Images/Screenshot%20(707).png" width="70%">
</center>
5.10 Simulations: Runs and saves multiple threshold simulations.
<center>
<img src="https://github.com/hsj71/TextExtraction/blob/main/Images/Screenshot%20(709).png" width="70%">
</center>
6.Show Accuracy Graph: Displays accuracy plots based on results.
<center>
<img src="https://github.com/hsj71/TextExtraction/blob/main/Images/Screenshot%20(694).png" width="70%">
</center>
7.Clear Display: Clears current text/image results.
<center>
<img src="https://github.com/hsj71/TextExtraction/blob/main/Images/Screenshot%20(711).png" width="70%">
</center>
8.Refresh: Destroys and reinitializes the GUI window.
<center>
<img src="https://github.com/hsj71/TextExtraction/blob/main/Images/Screenshot%20(698).png" width="70%">
</center>

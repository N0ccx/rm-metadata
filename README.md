# File Sorter and Image Metadata Remover

This Python script is designed to sort files by extension and remove metadata from .jpg and .png images.
    
Specifically target .jpg and .png files, and remove their metadata after sorting them into an "images" folder.

# Features

1. Automatically sorts files by extension.
2. Removes EXIF metadata from .jpg and .png images.
3. Can be customized for other file extensions and processing needs.

# Prerequisites

To run this script, you need to install the following Python libraries:

    bash

    pip install Pillow piexif

# How to Use

1. Clone the repository or download the script.
2. Place the script in the folder where your files are located.
3. Run the script:

        bash

        python image-rm.py

# Folder Structure

The script will create folders such as images, documents, music, etc., based on the file extensions.
You can modify the script to adjust folder names or add support for additional file types.

# Customization

To add more file types or change the folder organization:

1. Open file_arranger.py in any text editor.
2. Update the folders dictionary to map new extensions to the folder names of your choice.

# License

This project is open-source and available under the MIT License.

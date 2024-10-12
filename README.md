## File Sorter and Image Metadata Remover

This Python script is designed to sort files by extension and remove metadata from .jpg and .png images. The script will:

    Move files into designated folders based on their file extension.
    Specifically target .jpg and .png files, and remove their metadata after sorting them into an "images" folder.

# Features

    Automatically sorts files by extension.
    Removes EXIF metadata from .jpg and .png images.
    Can be customized for other file extensions and processing needs.

# Prerequisites

To run this script, you need to install the following Python libraries:

bash

pip install Pillow piexif

# How to Use

    Clone the repository or download the script.
    Place the script in the folder where your files are located.
    Run the script:

    bash

    python file_arranger.py

    The script will:
        Sort files based on their extension into pre-defined folders (like images, documents, etc.).
        For .jpg, .jpeg, and .png files, it will remove any metadata after moving them to the images folder.

# Folder Structure

    The script will create folders such as images, documents, music, etc., based on the file extensions.
    You can modify the script to adjust folder names or add support for additional file types.

# Customization

To add more file types or change the folder organization:

    Open file_arranger.py in any text editor.
    Update the folders dictionary to map new extensions to the folder names of your choice.

Example:

python

folders = {
    'txt': 'documents',
    'jpg': 'images',
    'png': 'images',
    'mp3': 'music',
    # Add more extensions as needed
}

# License

This project is open-source and available under the MIT License.

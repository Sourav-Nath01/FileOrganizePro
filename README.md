# FileOrganizePro

FileOrganizePro is a Python script designed to automatically organize files within a specified directory based on their file types. It monitors a source directory for incoming files and moves them to different destination directories according to their file extensions.

## Features

- Automatically sorts files into appropriate directories based on their file extensions.
- Supports sorting for various file types including audio, video, images, and documents.
- Utilizes the Watchdog library for monitoring file system events.
- Customizable destination directories for different file types.
- Handles file name conflicts by appending a unique identifier.
- Provides logging functionality for tracking file movements.

## Installation

1. Clone the repository:
  https://github.com/Sourav-Nath01/FileOrganizePro.git

2. Install dependencies:
  pip install watchdog


## Usage

1. Modify the configuration variables in the script according to your requirements:

- `source_dir`: Path to the directory to monitor for incoming files.
- `dest_dir_sfx`, `dest_dir_music`, `dest_dir_video`, `dest_dir_image`, `dest_dir_documents`: Destination directories for different file types.
- `audio_extensions`, `video_extensions`, `image_extensions`, `document_extensions`: Supported file extensions for each file type.

2. Run the script:
python fileAutomator.py


3. The script will start monitoring the source directory for file changes. As new files are detected, they will be sorted into the appropriate destination directories.

## Configuration

You can customize the script further by modifying the following variables:

- `image_extensions`: Supported image file extensions.
- `video_extensions`: Supported video file extensions.
- `audio_extensions`: Supported audio file extensions.
- `document_extensions`: Supported document file extensions.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.



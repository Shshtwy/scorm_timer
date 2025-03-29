# SCORM Timer

## Description
SCORM Timer is a Python-based utility designed to analyze SCORM package content and calculate the total media duration within a given SCORM folder. It scans the directory, identifies media files (such as MP3s and videos), and aggregates their playback durations to provide an estimated total time required to complete the SCORM module.

## Features
- Scans SCORM package directories for media files
- Extracts media durations using `ffmpeg` and `mutagen`
- Supports various audio and video formats
- Provides a summary of total media duration
- Displays progress using `tqdm`

## Prerequisites
Ensure you have the following installed on your system:
- Python 3.x
- `ffmpeg` (installed and accessible via command line)
- Required Python packages (install via `pip`):
  ```sh
  pip install mutagen ffmpeg-python tqdm
  ```

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/shshtwy/ScormTimer.git
   cd ScormTimer
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
Run the script by providing the path to the SCORM package directory:
```sh
python ScormTimerV1.py /path/to/scorm/folder
```

The script will process media files and output the total duration in hours, minutes, and seconds.

## License
This project is licensed under the MIT License.



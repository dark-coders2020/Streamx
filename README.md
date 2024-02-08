# Streamx

A simple torrent streamer written in Python 3.

## Tested Platforms

- Linux 64-bit
- Windows 10/11 64-bit with Python 3.8.2

## Prerequisites

Before running the application, ensure you have the following installed:

- [Python](https://www.python.org/downloads/)
- [Node.js](https://nodejs.org/en/download/)

## Supported Players

Streamx supports the following media players:

- [mpv](https://mpv.io/)
- [VLC](https://www.videolan.org/vlc/)

Note: You must have one of these players installed to run Streamx.

## Usage

1. Press `Windows+R` to open the "Run" box. Type `cmd` and then click "OK".

2. Navigate to the directory of your choice. For example, to navigate to the Documents folder, run:

   ```bash
   cd Documents
   ```

3. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/dark-coders2020/Streamx.git
   ```

4. Install webtorrent-cli:

   ```bash
   npm install webtorrent-cli -g
   ```

5. Navigate to the code folder. In this case, the code folder is `torrentStream`:

   ```bash
   cd torrentStream
   ```

6. Install all the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

7. Run the program:

   ```bash
   python index.py
   ```

## Options

You can specify the player name using the `--player` argument. For example:

```bash
  python index.py --player=mpv
```

## Author

- **Author:** Dark Coders
- **Contact:** For inquiries regarding software development projects, please reach out to me at [darkcoders2020@gmail.com](mailto:darkcoders2020@gmail.com). I offer competitive rates and professional services.

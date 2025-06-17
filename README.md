
# Penguingotchi Auto Register

Auto Register script for [Penguingotchi.fun](https://penguingotchi.fun/) using Python.

## Overview

This project automates the registration process on Penguingotchi.fun, a Solana-based NFT game platform. The script uses Python automation tools to interact with the website and perform the registration steps automatically.

## Features

- Automated browser control using Python
- Supports Brave browser (Chromium-based)
- Automates wallet connection and registration steps (customize as needed)
- Easy to configure and extend

## Requirements

- Python 3.7+
- Pyppeteer (Python port of Puppeteer)
- Brave browser installed on your system

## Installation

1. Clone this repository:

```
git clone https://github.com/silas0605/Penguingotchi.git
cd Penguingotchi
```

2. Install dependencies:

```
pip install -r requirements.txt
```

*Note: If `requirements.txt` is not available, install pyppeteer manually:*

```
pip install pyppeteer
```

## Configuration

- Update the path to Brave browser executable in the script (`p.py`) if needed.
- Customize selectors and steps in the script to match any website changes.
- If wallet connection requires manual steps, consider using a persistent browser profile.

## Usage

Run the script:

```
python p.py
```

The script will launch Brave browser, navigate to [penguingotchi.fun](https://penguingotchi.fun/), and perform the registration workflow automatically.

## License

This project is licensed under the [GPL-3.0 License](LICENSE).


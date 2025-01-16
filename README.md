# EduLingo

**EduLingo** is a Chrome extension designed to enhance your browsing experience by providing instant word or sentence meanings directly within the current tab. This extension leverages a Django server with REST framework on the backend and a client-side interface built using HTML, CSS, and JavaScript.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Features

- **Instant Translation**: Select any word or sentence in your browser to quickly get its meaning.
- **Seamless Integration**: Works within your current browser tab without needing to switch applications.
- **Customizable Interface**: User-friendly and responsive design for an intuitive user experience.

## Installation

### Backend Setup (Django Server)

1. Clone the repository:
   ```bash
   git clone https://github.com/subarnasaikia/EduLingo.git
   ```
2. Navigate to the `server` directory:
   ```bash
   cd EduLingo/server
   ```
3. Create and activate a virtual environment:
   ```bash
   python3 -m venv env
   source env/bin/activate  # For Linux/MacOS
   env\Scripts\activate  # For Windows
   ```
4. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Run the Django server:
   ```bash
   python manage.py runserver
   ```

### Chrome Extension Setup (Client Side)

1. Open Google Chrome and go to `chrome://extensions/`.
2. Enable **Developer mode**.
3. Click on **Load unpacked** and select the `client` directory from the cloned repository.

## Usage

- Select any text or word in your current browser tab.
- Right-click and choose the "EduLingo" option from the context menu to view the meaning.
- The extension communicates with the Django backend to fetch and display the meaning.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.



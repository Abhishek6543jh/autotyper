# Auto Typer

This is a simple auto-typer application built using `pynput` and `streamlit`. It allows users to automatically type a given text at a controlled speed. The application can be controlled through a web interface.

## Features

- **Auto Typing**: Automatically types the text provided in the input area.
- **Control via Web Interface**: Start and stop the auto-typer using buttons in the Streamlit web interface.

## Requirements

- Python 3.7+
- `streamlit` library
- `pynput` library

## Installation

1. **Clone the Repository**

    ```bash
    git clone https://github.com/yourusername/autotyper.git
    cd autotyper
    ```

2. **Install the Dependencies**

    ```bash
    pip install streamlit pynput
    ```

## Usage

1. **Run the Streamlit Application**

    ```bash
    streamlit run auto_typer.py
    ```

2. **Web Interface**

    - Open the web browser and go to the URL provided by Streamlit (usually `http://localhost:8501`).
    - Enter the text you want to auto-type in the text area.
    - Click on "Start Auto Typer" to start typing the text automatically after a 5-second delay. This gives you time to focus the cursor where you want the text to be typed.
    - Click on "Stop Auto Typer" to stop the typing process.

## Notes

- The application will wait for 5 seconds after clicking the start button before beginning to type. This gives you time to focus the cursor where you want the text to be typed.
- Adjust the typing speed by changing the `time.sleep(0.01)` value in the `type_text` function.

## Platform Compatibility

- **Windows**: The auto-typer is compatible with Windows. Ensure you run the application with appropriate permissions.
- **MacOS**: The auto-typer is compatible with MacOS.
- **Linux**: The auto-typer should work on Linux.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

[MIT LICENSE](LICENSE)

## Contribution

Feel free to fork this repository and contribute via pull requests. Any contributions, issues, and feature requests are welcome.

## Author

[Abhishek](https://github.com/Abhishek6543jh)

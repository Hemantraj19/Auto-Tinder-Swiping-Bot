# Tinder Auto-Liker Script

This script automates the process of liking profiles on Tinder using Selenium with Python. It logs into Tinder using Facebook credentials, handles pop-ups, and performs automatic likes.

## Prerequisites

- Python installed on your machine
- Chrome browser installed
- ChromeDriver executable for Selenium

## Setup

1. Clone the repository or download the script.

    ```bash
    git clone https://github.com/your_username/tinder-auto-liker.git
    ```

2. Install required packages.

    ```bash
    pip install selenium
    ```

3. Download ChromeDriver from [here](https://sites.google.com/chromium.org/driver/) and update the `chrome_driver_path` variable in the script with the path to your ChromeDriver executable.

4. Open the script (`tinder_auto_liker.py`) in a text editor.

5. Update the following variables with your Facebook login details:

    ```python
    FB_EMAIL = "YOUR_FACEBOOK_LOGIN_EMAIL"
    FB_PASSWORD = "YOUR_FACEBOOK_PASSWORD"
    ```

## Usage

1. Run the script.

    ```bash
    python tinder_auto_liker.py
    ```

2. The script will open a Chrome window, log in to Tinder, and start automatically liking profiles.

## Notes

- The script is designed for the free Tinder tier, which allows only 100 likes per day. Adjust the loop condition accordingly if you have a premium account.

- Make sure to handle potential changes in the Tinder website structure if the script stops working.

- Please be aware of Tinder's terms of service and use the script responsibly.

## Disclaimer

This script is for educational purposes only. The author is not responsible for any misuse or violation of Tinder's terms of service.

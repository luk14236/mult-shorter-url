# shorter-url.py

This Python script shortens URLs using various URL shortening services.

## Usage

1. **Prepare Script:**
   - Install the required library by running `pip install pyshorteners`.
   - Import the `pyshorteners` library.
   - Define the `get_short_url` function to shorten URLs.

2. **Run the Script:**
   - Call the `get_short_url` function with the URL you want to shorten as an argument.

## Requirements

- Python 3.x
- Libraries:
  - pyshorteners

## Overview

This script shortens URLs using various URL shortening services provided by the `pyshorteners` library.

## How it Works

- The script defines a `get_short_url` function that takes a URL as input.
- Inside the function, it tries to shorten the URL using different URL shortening services provided by `pyshorteners`.
- If a service fails to shorten the URL, it prints a message indicating the failure and moves on to the next service.
- Once the URL is successfully shortened, it returns the shortened URL.

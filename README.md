# Kanye Quotes App

## Introduction 🎤

Welcome to the Kanye Quotes App! This simple yet entertaining application fetches random quotes from Kanye West using the [Kanye Rest API](https://api.kanye.rest). With a sleek Tkinter GUI, you can get a new Kanye quote at the click of a button.

## Features 🌟

- Fetches random Kanye West quotes from the internet.
- Simple and intuitive GUI built with Tkinter.
- Updates the displayed quote dynamically at the click of a button.

<div style="display: flex;">
    <img src="images/Kanye Says.png" style="width: 50%;" alt="App Interface">
</div>

## How It Works ⚙️

### Fetching Quotes 📝

Using the powerful `requests` library, the application fetches quotes from the Kanye Rest API. The quote is then displayed on the Tkinter canvas.

### GUI Magic 🪄

The graphical interface is built with Tkinter, featuring:
- A canvas with a background image.
- A text widget to display the quote.
- A button to fetch a new quote, decorated with a Kanye-themed image.

## Requirements 📋

To run this application, you'll need:

- Python 3.x 🐍
- The `requests` library 🌐
- Tkinter (included with standard Python installations)

## Installation 🛠️

Follow these steps to set up and run the application:

1. Clone the repository to your local machine.
2. Make sure Python is installed on your system.
3. Install the `requests` library:
    ```sh
    pip install requests
    ```
4. Ensure you have the required images (`background.png` and `kanye.png`) in an `images` directory.
5. Run the script to start the application:
    ```sh
    python main.py
    ```

## Usage 💻

Here's how to enjoy Kanye's wisdom:

1. Run the `main.py` script.
2. A Tkinter window will pop up with a background image and an initial quote.
3. Click the Kanye button to fetch and display a new quote.

## Conclusion 🎉

The Kanye Quotes App is a fun project to practice working with APIs, Tkinter for GUI, and Python in general. Enjoy the profound (and sometimes hilarious) quotes from Kanye West!

Ready to get some Kanye wisdom? Run the app and let the quotes inspire you! 🧠

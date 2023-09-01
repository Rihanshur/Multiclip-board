# Multiclip-board

## Clipboard Manager

This is a simple Python clipboard manager script that allows you to save and load text data from the clipboard using command-line commands. You can save text data with a key and later retrieve it by specifying the key.

## Prerequisites

Before you begin, make sure you have Python installed on your system.

## Getting Started

1. Clone the repository:
2.Install the required Python packages

# Example

Here's an example of saving and loading data:
  python clipboard_manager.py save
  Enter a key: mydata
  Data saved!
  
  python clipboard_manager.py load
  Enter a key: mydata
  Data copied to clipboard.

# Configuration

You can configure the script by editing the following variables in the script file:

    SAVED_DATA: The name of the JSON file where the clipboard data is saved.

# License

This project is licensed under the MIT License - see the LICENSE file for details.

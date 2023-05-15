# Voice Assistant

A Voice Assistant for your PC using Python. Developed as part of the "Hands on Python" course at SRM University, AP.

This program takes continuous voice inputs from the user and performs a wide variety of tasks on the user's PC, completely hands-free, until the user asks the program to stop.

- [Features](#features)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

The Voice Assistant offers the following features:

- Get the current time
- Retrieve content from Wikipedia
- Open popular websites
- Search in popular search engines
- Get directions to a place
- Create or open local folders
- And perform many similar tasks

Show some ❤️ by starring the repository! ⭐

## Getting Started

### Installation

Install the dependencies by running the following commands:

```shell
pip install pyttsx3
pip install SpeechRecognition
```

### Usage

To run the program locally, follow these steps:

1. Clone the project:

   ```shell
   git clone https://github.com/adivishnu-a/Voice-Assistant
   ```

2. Navigate to the project directory:

   ```shell
   cd Voice-Assistant
   ```

3. Run the program:

   ```shell
   python voiceassistant.py
   ```

## FAQ

**Are changes required in any part of the code?**

No, the code is system and platform independent, so changes in the `.py` script are not required. Simply install the required dependencies and run the `.py` script.

**What are the dependencies for?**

The dependencies used in this program are the `pyttsx3` module for text-to-speech functionality, which works offline, and the `SpeechRecognition` module to take audio input from the user, recognize the user's commands, and convert them into text.

## Contributing

Contributions are welcome! If you find any issues or would like to contribute enhancements, please feel free to submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

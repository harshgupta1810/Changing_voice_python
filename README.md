# Text-to-Speech Converter

This is a Python script that uses the `pyttsx3` library to convert text into speech. It allows you to control the speaking rate, volume, and voice selection. Additionally, it can save the generated speech as an audio file.

## Table of Contents

1. [Badges](#badges)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Configuration](#configuration)
5. [Contributing](#contributing)
6. [License](#license)
7. [Acknowledgments](#acknowledgments)
8. [Documentation](#documentation)

## Badges

[![License](https://img.shields.io/badge/license-MIT-green)](https://opensource.org/licenses/MIT)

## Installation

1. Ensure you have Python installed on your system. You can download Python from the official website: [Python.org](https://www.python.org/downloads/)

2. Install the required `pyttsx3` library. Open the terminal/command prompt and run the following command:

   ```
   pip install pyttsx3
   ```

3. Download the `text_to_speech.py` script and place it in your desired directory.

## Usage

1. Run the Python script `text_to_speech.py` in a Python environment.

2. The script will use the `pyttsx3.init()` function to initialize the text-to-speech engine and configure the speaking rate, volume, and voice.

3. It will then use the `engine.say()` function to convert the text "Hello World!" into speech and play it.

4. The script will also print the current speaking rate and volume level.

5. You can customize the speaking rate and volume by changing the values of the `rate` and `volume` variables in the script.

6. To change the voice, uncomment one of the lines that set the voice using the `engine.setProperty('voice', voices[index].id)` function. The index represents the voice to be used (0 for male, 1 for female).

7. The script can also save the generated speech as an audio file. The line `engine.save_to_file('Hello World', 'test.mp3')` will save the speech as a file named `test.mp3`. You can change the text to be saved and the file name as per your requirements.

## Configuration

You can customize the text to be spoken by changing the text passed to the `engine.say()` function.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvement, feel free to open a pull request or create an issue on the GitHub repository.

## License

This project is open-source and licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code, but please provide proper attribution to the original creator, Harsh Gupta (Desparete Enuf).

## Acknowledgments

The Text-to-Speech Converter was created by Harsh Gupta (Desparete Enuf) to demonstrate the usage of the `pyttsx3` library for converting text to speech in Python. The code is provided here for reference and learning purposes.

## Documentation

The script uses the following concepts:

1. **Text-to-Speech Conversion**: The script uses the `pyttsx3` library to convert the specified text into speech.

2. **Rate and Volume Control**: The script demonstrates how to control the speaking rate and volume of the speech.

3. **Voice Selection**: The script allows you to choose between different voices for the speech.

4. **Saving Speech to File**: The script can save the generated speech as an audio file for future use.

# mdjvt.py

<p align="center" width="100%">
    <img width="60%" align="center" src="https://oceanofanythingofficial.github.io/Midjourney-Prompt-And-Video-Transcript-Generator/Midjourney-Prompt-And-Video-Transcript-Generator.jpeg"/>
</p>

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Overview

Welcome to the **mdjvt.py** repository, authored by **@OCEANOFANYTHINGOFFICIAL**. This script is designed to provide versatile output generation based on user input. It functions as a command-line utility, capable of generating script/text from video and audio files, crafting high-quality Midjourney prompts using prompt engineering, and facilitating the storage of outputs in both text and JSON formats.

## Features

The mdjvt.py Script offers the following key features:

1. **Transcription Generation:** Effortlessly generate script/text transcriptions from both video and audio files.
2. **High-Quality Midjourney Prompts:** Leverage the power of prompt engineering to create top-notch Midjourney prompts.
3. **Output Saving:** Conveniently store generated outputs in both plain text and JSON formats.

## Installation

Follow these steps to get the mdjvt.py Script up and running on your system:

1. **Python Installation:** Make sure you have Python 3.9.6 installed. If not, download it from the [Python official website](https://www.python.org/downloads/release/python-396/).

2. **Virtual Environment Setup:** For optimal package management, it's recommended to use a virtual environment. Install Virtualenv by running the command:

    ```
    pip install virtualenv
    ```

    Create a virtual environment named "venv" with:

    ```
    virtualenv venv
    ```

3. **Package Installation:** Install the required packages using the following command:

    ```
    pip install -r requirements.txt
    ```

4. **API Key Configuration:** By default, the script employs the Cohere module for prompt generation. So To run The Script you have to obtain an API key from [Cohere.ai](https://cohere.ai/) and paste it into the `config.py` file.

## Usage

Utilize the Custom Python Script as follows:

- To display the help message:

    ```
    python mdjvt.py
    ```

- To generate a script/text transcription from a video/audio file:

    ```
    python mdjvt.py -i "input_file_path" -o "output_file_path"
    ```

- To craft high-quality Midjourney prompts using prompt engineering:

    ```
    python mdjvt.py -i "input_string" -o "output_file_path"
    ```

## License

This Custom Python Script is distributed under the GNU AGPLv3 License. For further details, consult the [license document](https://www.gnu.org/licenses/agpl-3.0.en.html). Note that this script is intended for personal use; commercial use requires explicit authorization from the author.

---


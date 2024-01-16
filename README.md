# PDF to CSV Converter

## Overview

This Python script is designed to extract table data from a PDF file and save it in a CSV file. It utilizes a pre-trained model to analyze the PDF and convert the tables into a structured CSV format.

## Requirements

- Python 3.x
- Download the model and save it in the `models` folder (see "Installation" section for details).

## Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/yourusername/pdf-to-csv-converter.git
    cd pdf-to-csv-converter
    ```

2. Create a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use 'venv\Scripts\activate'
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Download the pre-trained model and save it in the `models` folder. You can find the model [here](https://example.com/path/to/model).

## Usage

Run the script with the following command:

```bash
python main.py --pdf_name 'Input.pdf'

# PDF to CSV (Table Data) 

## Overview

This Python script is designed to extract table data from a PDF file and save it in a CSV file. It utilizes a pre-trained model to analyze the PDF and convert the tables into a structured CSV format.

## Requirements

- Python 3.x
- Download the model and save it in the `models` folder (see "Installation" section for details).

## Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/abdullahx124/Internship-Task_1.git
    cd pdf-to-csv-converter
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Download the pre-trained model and save it in the `models` folder. You can find the model [[here](https://example.com/path/to/model](https://drive.google.com/drive/folders/16HF1wYXj3d3zzEcZUEk-svwaNi0nhJGc?usp=sharing).

## Usage

Run the script with the following command:

```bash
python main.py --pdf_name 'Input.pdf'

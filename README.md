# PDF Template Generator

This project generates a multi-page PDF document using Python, [FPDF](https://pyfpdf.github.io/), and [Pandas](https://pandas.pydata.org/). Each section of the PDF corresponds to a programming topic, with headers, footers, and lined pages, based on data from a CSV file.

## Features

- Reads topics and page counts from `topics.csv`
- Creates a PDF with a custom header and footer for each topic
- Draws horizontal lines to simulate lined paper
- Supports multi-page topics

## Files

- [`main.py`](main.py): Main script to generate the PDF.
- [`topics.csv`](topics.csv): CSV file listing topics and number of pages for each.
- [`output.pdf`](output.pdf): Generated PDF output.


## Usage

1. Install dependencies:
    ```sh
    pip install fpdf pandas
    ```
2. Run the script:
    ```sh
    python main.py
    ```
3. The output will be saved as `output.pdf`.

## Example

The script reads each topic from `topics.csv` and generates a section in the PDF with the topic as a header and footer, and the specified number of lined pages.

---
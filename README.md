![Python 3.11](https://img.shields.io/badge/python-3.11-blue.svg)
![Pandas](https://img.shields.io/badge/pandas-%5E1.3-blue)
![FPDF](https://img.shields.io/badge/fpdf-%5E1.7-blue)

# Topic-Based PDF Generator

## Description

This Python script generates a PDF document based on topics listed in a CSV file (`topics.csv`). 
Each topic from the CSV creates a new page in the PDF, with a header and footer displaying the topic name. 
The script uses the `pandas` library for data handling and `FPDF` for PDF generation. 
It's designed to create PDFs with a structured layout, including horizontal lines across each page and topic-specific headers and footers.

## Installation

1. **Clone the repository:**
   ```
   git clone <repository-url>
   ```

2. **Navigate to the project directory:**
   ```
   cd <project-directory>
   ```

3. **Install dependencies:**
   ```
   pip install pandas fpdf
   ```

## Usage

To run the script:

1. Ensure you have a `topics.csv` file in the same directory as the script. The CSV should have columns for "Topic" and "Pages".

2. Execute the script:
   ```
   python <script-name>.py
   ```

3. The output PDF, `output.pdf`, will be created in the same directory.

## CSV File Format

The `topics.csv` file should have the following format:

```
Topic,Pages
<topic1>,<number_of_pages_for_topic1>
<topic2>,<number_of_pages_for_topic2>
...
```

## Requirements

- Python 3.11
- Pandas
- FPDF

## Contributing

Feel free to fork the repository and submit pull requests.

## License

This project is under the MIT License.




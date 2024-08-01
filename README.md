# AmbitionBox Web Scraping Project

This project involves web scraping the AmbitionBox website to extract data about the most popular companies. The data includes the company's name, age, rating, job description, total employees, company type, and positive aspects. The goal of this project is to gather and analyze information about these companies to provide insights into their characteristics and employee experiences.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Extraction](#data-extraction)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Contact](#contact)

## Project Overview

This project uses Python and the BeautifulSoup library to scrape data from AmbitionBox. The focus is on collecting information about the most popular companies, which includes:

- **Company Name**: The name of the company.
- **Age**: How long the company has been in operation.
- **Rating**: The company's rating based on employee reviews.
- **Job Description**: A brief description of the company's job offerings or industry.
- **Total Employees**: The number of employees working in the company.
- **Company Type**: The type of company (e.g., IT Services, Consulting, Software Product).
- **Positive Aspects**: Positive reviews and aspects highlighted by employees.

## Data Extraction

The data was extracted using the following process:

1. **Sending HTTP Requests**: Sending requests to the AmbitionBox website to fetch the HTML content.
2. **Parsing HTML**: Using BeautifulSoup to parse the HTML and extract relevant information.
3. **Storing Data**: Storing the extracted data in a structured format (e.g., CSV or database) for further analysis.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/SubhamKumar-Gaurav/Web-Scraping-using-BeautifulSoup.git
    cd Web-Scraping-using-BeautifulSoup
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To scrape the data and store it in a CSV file, run the following command:

```python
python scrape_ambitionbox.py 

## Contributing 
Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request. Please make sure to follow the project's code style and include relevant tests. 

## Contact
For any questions or feedback, please reach out to:

Subham Kumar Gaurav: subhamgaurav2001@gmail.com
GitHub: SubhamKumar-Gaurav
# Web Scraping W3Schools Tutorials

This project demonstrates how to scrape tutorial links from the W3Schools homepage using Selenium and store the data in a Pandas DataFrame.



## Introduction

The purpose of this project is to scrape tutorial links from the W3Schools website and store the extracted data (titles and URLs) in a structured format using Pandas. This can be useful for creating a dataset of tutorial resources for further analysis or sharing.

## Setup

To set up this project, follow these steps:

1. **Clone the repository**:

    ```bash
    git clone https://github.com/yourusername/web-scraping-w3schools.git
    cd web-scraping-w3schools
    ```

2. **Create a virtual environment** (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. **Install the required libraries**:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the web scraping script and extract tutorial links, execute the following command:

```bash
python scrape_w3schools.py

# Coventry University Publications Web Crawler 📚🤖

## Overview

This project is a Python-based web crawler and search utility designed to collect and analyze research publication metadata from the Coventry University Pure Portal. It automates the extraction of publication titles, authors, links, and dates, storing them in a CSV file. The notebook then enables efficient searching and text-based analysis of the collected data, making it ideal for academic research, data science projects, or anyone interested in Coventry University's research output.

---

## Features

- **Automated Crawling:** Gathers publication data from the Coventry University research portal.
- **Respects Robots.txt:** Ensures ethical and legal crawling by obeying site rules and delays.
- **CSV Export:** Saves collected data in an easy-to-analyze CSV format.
- **Text Preprocessing:** Cleans and preprocesses publication titles for effective searching.
- **Inverted Index Search:** Quickly finds relevant publications using keyword queries.
- **Scheduling:** Option to run the crawler on demand or schedule weekly updates.
- **Easy to Use:** Runs as a Jupyter Notebook—ideal for experimentation and extension.

---

## Getting Started

1. **Clone this repository** or download the notebook file.
2. **Install dependencies** as prompted in the notebook (e.g., `schedule`, `beautifulsoup4`, `nltk`, `pandas`, etc.).
3. **Run the notebook** in Jupyter or Google Colab.
4. **Choose crawling mode:** Run immediately, or schedule for weekly updates.
5. **Search your collected data** using the built-in search cell.

---

## Example Usage

- Collect all publications from the Research Centre for Computational Science and Mathematical Modelling.
- Perform keyword searches to find relevant research or authors.
- Export results for further academic analysis.

---

## Requirements

- Python 3.x
- Jupyter Notebook or Google Colab
- Packages: `schedule`, `beautifulsoup4`, `nltk`, `pandas`, `requests`

---

## License

This project is for educational and research purposes. Please respect the target website's terms of service and robots.txt when crawling.

---

## Acknowledgements

- [Coventry University Pure Portal](https://pureportal.coventry.ac.uk)
  

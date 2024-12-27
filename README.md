# Script Transcription Scraper 📜

A Python-based web scraper that automates the extraction of movie and TV show transcripts from [Subslikescript](https://subslikescript.com). This project is designed to fetch transcripts dynamically, process the content, and save it as text files for offline usage.

## 🚀 Features
- Scrapes transcripts based on user-defined starting letters and page numbers.
- Handles errors and skips broken links gracefully.
- Dynamically generates text files with sanitized titles for easy organization.
- Uses `requests` and `BeautifulSoup` to efficiently fetch and parse HTML content.

## 🛠️ Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - `requests` for HTTP requests.
  - `BeautifulSoup` (with `lxml`) for HTML parsing and data extraction.

## 📋 How It Works
1. Input a starting character and page number.
2. The scraper navigates to the specified section of Subslikescript.
3. Extracts all available links to transcripts from the page.
4. Visits each link, extracts the transcript and title, and saves the transcript to a `.txt` file.


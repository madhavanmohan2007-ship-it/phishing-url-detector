# Phishing URL Detector

**Author:** YourName
**Program:** IBM SkillsBuild Cyber Security 2026, conducted by BharatCares

## Project Description
A beginner-friendly machine learning project that classifies a URL as **legitimate** or **phishing**. Instead of reading the web page, it extracts simple features from the URL text (length, number of hyphens and dots, presence of `@`, raw IP address, HTTPS usage, suspicious keywords and TLDs) and trains a Random Forest classifier on them.

## Dataset
- The notebook includes a small built-in labelled sample (20 legitimate and 20 phishing-style URLs) so it runs without any download.
- For larger experiments, use the UCI Machine Learning Repository dataset: [Phishing Websites](https://archive.ics.uci.edu/dataset/327/phishing+websites)

## Technologies Used
- Python 3
- pandas
- scikit-learn (Random Forest)
- Jupyter Notebook

## Setup and Run
1. Install Python 3.9 or later.
2. Install the dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Start Jupyter and open the notebook:
   ```
   jupyter notebook YourName_PhishingURLDetector.ipynb
   ```
4. Choose **Run > Run All Cells**.
5. Test your own link by calling `check_url("http://example-login-verify.tk")` in the last code cell.

## Key Information
- Label `1` = phishing, `0` = legitimate.
- The built-in sample is tiny, so the reported accuracy is only a demonstration, not a real-world benchmark.
- Possible improvements: a larger dataset, domain-age/WHOIS features, page-content analysis.

## Files
| File | Purpose |
|------|---------|
| `YourName_PhishingURLDetector.ipynb` | Complete project code |
| `requirements.txt` | Python dependencies |
| `YourName_ProjectReport.docx` | Project documentation |
| `README.md` | This overview |

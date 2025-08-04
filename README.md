# CRE Site Analyzer

An AI-powered tool for analyzing commercial real estate locations.

## Setup

1. Upload this project to Streamlit Cloud or run locally.
2. Add your API keys to `.streamlit/secrets.toml`:
```
GOOGLE_API_KEY = "your-google-api-key"
CENSUS_API_KEY = "your-census-api-key"
OPENAI_API_KEY = "your-openai-api-key"
```
3. Deploy or run:
```
pip install -r requirements.txt
streamlit run cre_site_analyzer_app_v2.py


# CRE Site Analyzer (AI-Powered)

Analyze commercial real estate using foot traffic, demographics, and GPT insights.

## 🛠 Setup

1. Upload to Streamlit Cloud or run locally
2. Add `.streamlit/secrets.toml` with:

```toml
GOOGLE_API_KEY = "your-google-api-key"
CENSUS_API_KEY = "your-census-api-key"
OPENAI_API_KEY = "your-openai-api-key"
```

3. Install and run:
```bash
pip install -r requirements.txt
streamlit run cre_site_analyzer_app_v2.py
```

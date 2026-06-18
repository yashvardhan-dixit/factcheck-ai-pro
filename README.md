# 🔍 FactCheck AI Pro - Automated PDF Fact-Checking

An advanced web application that automatically extracts and verifies factual claims from PDF documents using AI and live web search.

## 🔗 Live Demo
https://factcheck-ai-pro-gyyknd62muqqcavnhocaaf.streamlit.app/

## ✨ Key Features
- **AI-Powered Claim Extraction** - Automatically identifies statistics, financial data, dates, and factual assertions
- **Live Web Verification** - Cross-references claims against current web data using multiple sources
- **Comprehensive Analysis** - Classifies claims as Verified ✅, Inaccurate ⚠️, False ❌, or Unverifiable ❓
- **Professional Reporting** - Detailed analysis with evidence sources and corrected information
- **Export Capabilities** - Download results as JSON or CSV for further analysis
- **Zero Cost Operation** - Uses only free APIs and services

## 🛠️ Technology Stack
- **Frontend/Backend:** Streamlit
- **AI Engine:** Google Gemini 1.5 Flash (free tier)
- **Web Search:** DuckDuckGo Search (completely free)
- **PDF Processing:** PyMuPDF
- **Deployment:** Streamlit Community Cloud

## 🚀 Local Development

### Prerequisites
- Python 3.8+
- Google Gemini API key (free from Google AI Studio)

### Installation
```bash
git clone https://github.com/yourusername/factcheck-ai-pro.git
cd factcheck-ai-pro
pip install -r requirements.txt
streamlit run app.py

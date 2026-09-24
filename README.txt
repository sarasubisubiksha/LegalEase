# LegalEase AI - Gemini Version

This version adds Gemini AI document generation to the simple LegalEase application.

## Included
- Gemini AI drafting
- Agreement
- NDA
- Lease Agreement
- Employment Contract
- Employment Offer Letter
- Freelance Contract
- Editable document preview
- TXT/DOCX/PDF downloads
- `.env` API-key configuration

## 1. Install Python
Use Python 3.10+.

## 2. Open Command Prompt
Open CMD inside this project folder.

## 3. Create virtual environment

python -m venv venv

## 4. Activate it on Windows

venv\Scripts\activate

## 5. Install packages

pip install -r requirements.txt

## 6. Create your API key

Create a Gemini API key in Google AI Studio, then copy `.env.example` to `.env` and put your key after `GEMINI_API_KEY=`.

DO NOT upload the `.env` file or share your API key.

## 7. Run

streamlit run app.py

Then open http://localhost:8501 if Streamlit does not open the browser automatically.

## API model
The app uses Google's current GenAI Python SDK and the Gemini Interactions API with `gemini-3.8-flash`.

## Legal notice
The generated text is a draft. It may contain mistakes or omit requirements of the law applicable to a particular situation. A qualified legal professional should review any document before it is used for an actual legal matter.

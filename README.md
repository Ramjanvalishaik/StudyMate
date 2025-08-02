
# 📚 StudyMate: AI-Powered Academic Assistant

StudyMate is an interactive Streamlit-based application designed to help students and learners extract insights from study materials using Google's Gemini AI model. Users can upload documents and interactively:
- Ask questions
- Generate quizzes
- Summarize content
- Create structured study notes

---

## 🚀 Features

✅ Upload documents in **PDF, DOCX, TXT, CSV, JSON** formats  
✅ Extract content and break it into manageable chunks  
✅ Ask questions about the uploaded file using Gemini 1.5  
✅ Generate quizzes with answer explanations  
✅ Create detailed document summaries  
✅ Generate clean, organized study notes  

---

## 🛠️ Tech Stack

- **Frontend**: Streamlit  
- **AI Engine**: Google Gemini 1.5 Flash API  
- **PDF Processing**: PyMuPDF  
- **DOCX Parsing**: python-docx  
- **Data Handling**: pandas, JSON  
- **Custom Styling**: CSS injected via Streamlit  

---

## 📂 File Structure

```
app.py             # Main Streamlit application
```

---

## 🧪 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/studymate.git
cd studymate
```

### 2. Install Dependencies

Make sure you have Python 3.9+ and then:

```bash
pip install -r requirements.txt
```

If `requirements.txt` is not created yet, you can install manually:

```bash
pip install streamlit google-generativeai pymupdf python-docx pandas
```

### 3. Add Your Gemini API Key

In `app.py`, replace the placeholder with your API key:

```python
gemini_api_key = "YOUR_GEMINI_API_KEY"
```

Or enter it in the sidebar input field at runtime.

---

## ▶️ Run the App

```bash
streamlit run app.py
```

Then open `http://localhost:8501` in your browser.

---

## 📌 Notes

- Ensure your Gemini API key has access to the `gemini-1.5-flash` model.
- The app limits the input context length to avoid token overflow.

---

## 📄 License

This project is for educational and research use. No warranty or guarantees implied.

---

## 🙌 Acknowledgements

- [Streamlit](https://streamlit.io)
- [Google Generative AI (Gemini)](https://ai.google.dev/)
- [PyMuPDF](https://pymupdf.readthedocs.io)
- [OpenAI for the inspiration]

---

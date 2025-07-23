# Multilingual-OCR-Translation-Summarization-
@@ -35,25 +35,49 @@ Built with **Streamlit**, this app is an all-in-one NLP-powered tool for extract
| 📄 Language Data          | Language-specific stopwords      | Used for summarization and filtering |
| 🤖 Optional RAG Features  | Custom `rag_summarize()`         | Answering questions on uploaded content |

---

<h3>📺 Marathi Demo</h3>
<video width="600" controls>
  <source src="videos\Testing_on_Marathi_Text.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

<h3>📺 Hindi Demo</h3>
<video width="600" controls>
  <source src="videos\Multilingual OCR & Summarization - Google Chrome 2025-06-01 23-41-35.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

<h3>📺 English Demo</h3>
<video width="600" controls>
  <source src="videos\Multilingual OCR & Summarization - Google Chrome 2025-06-02 00-13-11.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>


## 🚀 How to Run the App

### 🔧 1. Clone the Repository

```bash
git clone https://github.com/your-username/ocr-translator-summarizer.git
cd ocr-translator-summarizer 
```
🧱 2. Set up Environment
Option A: Using Pipenv (Recommended)
```bash
pipenv install
pipenv shell
```
Option B: Using pip
```bash
pip install -r requirements.txt
```
▶️ 3. Run the App
```bash
streamlit run main2.py
```
Then open the provided localhost URL in your browser.

🧪 Example Use Cases
Extract Hindi or Marathi text from a scanned government form and summarize the content.

Upload a PDF with mixed-language content and translate it to English.

Ask the system to answer a question like "What is this document about?" based on the content.

📝 Notes
Tesseract must be installed locally and added to your system PATH.

For best OCR results, ensure clear, high-resolution scans.

Internet access is required to download translation and summarization models from Hugging Face.

To use the app offline, ensure all models (MarianMT, etc.) are pre-downloaded.

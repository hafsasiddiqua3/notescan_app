# 📝 NoteScan AI - OCR SaaS Application

Convert handwritten notes with diagrams into editable documents using Claude AI!

## 🌟 Features

- ✅ **Handwriting Recognition** - Accurately extracts handwritten text
- ✅ **Diagram Understanding** - Describes and interprets drawings, flowcharts, chemical structures
- ✅ **Multiple Export Formats** - Markdown, Word Document, Plain Text
- ✅ **Chemistry & Math Support** - Handles equations, formulas, subscripts
- ✅ **Easy to Use** - Simple drag-and-drop interface

## 🚀 Quick Deploy to Streamlit Cloud (FREE)

### Step 1: Prepare Your Files

Create a new folder with these files:
```
notescan-ai/
├── app.py              (the main Streamlit code)
├── requirements.txt    (dependencies)
└── README.md          (this file)
```

### Step 2: Push to GitHub

```bash
# Initialize git repository
git init
git add .
git commit -m "Initial commit - NoteScan AI"

# Create a new repository on GitHub, then:
git remote add origin https://github.com/YOUR_USERNAME/notescan-ai.git
git branch -M main
git push -u origin main
```

### Step 3: Deploy on Streamlit Cloud

1. Go to [share.streamlit.io](https://share.streamlit.io)
2. Sign in with GitHub
3. Click "New app"
4. Select your repository: `YOUR_USERNAME/notescan-ai`
5. Main file path: `app.py`
6. Click "Deploy"!

**Your app will be live at:** `https://YOUR_USERNAME-notescan-ai.streamlit.app`

---

## 🔧 Alternative Deployments

### Option 1: Hugging Face Spaces

1. Create account at [huggingface.co](https://huggingface.co)
2. Go to Spaces → Create new Space
3. Choose "Streamlit" as SDK
4. Upload your files
5. Your app will be at: `https://huggingface.co/spaces/YOUR_USERNAME/notescan-ai`

### Option 2: Gradio (Alternative UI)

Instead of Streamlit, you can use Gradio:

```python
# Install: pip install gradio anthropic pillow python-docx
import gradio as gr
# [Simplified Gradio version available on request]
```

---

## 💻 Local Testing

```bash
# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
```

Visit: `http://localhost:8501`

---

## 🔑 Getting Your Anthropic API Key

1. Go to [console.anthropic.com](https://console.anthropic.com)
2. Sign up or log in
3. Navigate to "API Keys"
4. Create a new key
5. Copy and paste into the app sidebar

**Note:** Keep your API key secure! Don't commit it to GitHub.

---

## 📊 How It Works

1. **Upload Image** - User uploads handwritten notes
2. **AI Analysis** - Claude Vision API analyzes the image
3. **Extract Content** - AI extracts text, describes diagrams
4. **Format Output** - Content is formatted in chosen format
5. **Download** - User downloads editable document

---

## 🎯 Use Cases

- 📚 **Students** - Digitize handwritten lecture notes
- 🔬 **Scientists** - Convert lab notebooks with chemical structures
- 👨‍🏫 **Teachers** - Archive handwritten materials
- 📝 **Professionals** - Digitize meeting notes and sketches

---

## 🛠️ Tech Stack

- **Frontend:** Streamlit
- **AI Model:** Claude Sonnet 4 (Anthropic)
- **Image Processing:** Pillow
- **Document Generation:** python-docx
- **Deployment:** Streamlit Cloud (Free tier)

---

## 📝 Example Usage

```python
# The app automatically:
# 1. Reads handwritten text
# 2. Describes diagrams: "A chemical structure showing..."
# 3. Extracts equations: "H₂SO₄ → 2H⁺ + SO₄²⁻"
# 4. Maintains structure: headings, lists, sections
```

---

## 🤝 Contributing

Feel free to fork and improve! Suggestions welcome.

---

## 📄 License

MIT License - Free to use and modify

---

## 🎓 Academic Project

Built as a SaaS demonstration for educational purposes.

**Teacher Requirements Met:**
- ✅ Deployed on SaaS platform (Streamlit)
- ✅ Functional with shareable link
- ✅ Real-world application
- ✅ Professional UI/UX

---

## 🆘 Troubleshooting

**Issue:** "Invalid API Key"
- **Solution:** Check your Anthropic API key is correct

**Issue:** "Image too large"
- **Solution:** Resize image to under 5MB

**Issue:** "Poor text extraction"
- **Solution:** Use clear, well-lit photos with good contrast

---

## 📞 Support

For issues or questions, open an issue on GitHub.

---

**🚀 Ready to deploy? Follow the steps above!**
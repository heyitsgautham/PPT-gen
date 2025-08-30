# 📊 PPT-gen

> Turn text into stunning presentations with AI, instantly.

**Author:** heyitsgautham (Gautham Krishna)  
**Contact:** 23f2000466@ds.study.iitm.ac.in

---

## ✨ What is PPT-gen?

Creating presentations shouldn’t feel like a chore. **PPT-gen** is a lightweight AI-powered tool that transforms plain text, markdown, or notes into a polished PowerPoint deck — in just a few clicks.

Whether you’re a student, researcher, or professional, PPT-gen takes care of the **design and formatting**, so you can focus on **content and ideas**.

---

## 🛠️ Quick Start

### 1. Clone the repo

```bash
git clone https://github.com/heyitsgautham/PPT-gen.git
cd PPT-gen
```

### 2. Install dependencies

```bash
# Backend (Python FastAPI + pptx libraries)
pip install -r requirements.txt

# Frontend (served as static HTML/JS/CSS)
# no build step needed
```

### 3. Run locally

```bash
uvicorn app:app --reload
```

Open: [http://localhost:8000](http://localhost:8000)

### 4. Deploy (Railway/Render/Vercel/Heroku)

Just connect your repo and deploy — no extra setup needed.

---

## 🚀 Why PPT-gen?

We’ve all been there — endless formatting, aligning text boxes, reusing templates, and copy-pasting content from notes into slides. **PPT-gen** fixes that.

- Paste your **raw text** → Get a **ready-to-use presentation**
- Apply your **own template** → Retain your branding, fonts, and colors
- Use your **LLM key** → Add creativity, polish, or adapt the tone
- Download instantly → No hassle, no waiting

It’s **fast, private, and customizable.**

---

## 🔑 Features

- 📝 **Flexible Input**: Paste large text, markdown, or structured notes.
- 🎯 **Smart Guidance**: Add a one-line instruction (e.g., _“make it a pitch deck”_).
- 🎨 **Template Reuse**: Apply your `.pptx` or `.potx` for consistent branding.
- 🖼️ **Image Reuse**: Automatically reuses images from uploaded templates.
- 📥 **Instant Download**: One-click `.pptx` output.
- ⚡ **Auto Splitting**: Breaks text into logical slides.
- 🔒 **Privacy First**: Your text, templates, and API keys never leave your system.

---

## 📌 Usage

1. Paste your text or markdown.
2. (Optional) Add guidance (_e.g., “make it a research summary”_).
3. Enter your LLM API key (OpenAI, Anthropic, Gemini).
4. Upload a `.pptx` or `.potx` template.
5. Click **Generate** → Download your styled presentation!

---

## 🏗️ Architecture

**Frontend**

- Responsive HTML + TailwindCSS
- Handles input, template upload, and download
- Clean UI with feedback + history tracking

**Backend (FastAPI)**

- Processes text, guidance, API key, and template
- Splits content intelligently into slides
- Maps to template fonts, layouts, and images
- Generates `.pptx` output using `python-pptx`

---

## 🌟 Future Scope

- Auto-generate **speaker notes**
- Prebuilt modes (_Sales deck, Pitch, Research summary_)
- Live **preview before download**
- Smarter retry + error handling

---

## 📄 License

MIT License – free for personal and commercial use.

---

⚡ _Built with love by Gautham Krishna (heyitsgautham) – IIT Madras DS (23f2000466@ds.study.iitm.ac.in)_

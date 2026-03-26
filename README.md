# 📄 PPTX Content Extractor & Preprocessor for AI

A Python-based toolkit designed to preprocess PowerPoint (`.pptx`) files into AI-friendly formats.  
This project helps simplify the process of extracting content from presentations so it can be easily summarized, analyzed, or processed using AI tools.

---

## 🚀 Project Overview

Working with `.pptx` files directly can be difficult for AI models due to:
- Complex layouts
- Embedded images containing text
- Non-linear formatting

This project solves that problem by converting presentations into cleaner, more structured formats:
- Extracts text directly from slides
- Outputs content into `.txt` and `.docx` formats
- Provides utilities to merge outputs for AI input

---

## ⚙️ Features

### ✅ Main Processor
- Iterates through a list of `.pptx` files
- Detects whether slides contain images
- If **images are present**:
  - Extracts images and adds them to word file
  - Saves output as `.docx`
- If **no images are present**:
  - Extracts slide text directly
  - Saves output as `.txt`

---

### 📄 TXT-Only Processor (Optional)
- A simplified version of the program
- Skips all image/OCR processing
- Extracts only textual content from `.pptx`
- Faster and useful when images are not important

---

### 🧩 TXT Merger Utility
- Combines multiple `.txt` files into a single file
- Makes it easier to:
  - Feed content into AI models
  - Perform bulk summarization
  - Maintain a continuous text flow

---

## 🧠 Use Case

This project is especially useful for:
- Students working with course slides
- AI-based summarization workflows
- Converting lecture materials into readable text
- Preprocessing data for NLP tasks

---

## 🛠️ Technologies Used

- Python
- `python-pptx` – for reading PowerPoint files
- `python-docx` – for generating Word documents

---

## ⚠️ Limitations & Notes

- Complex slide layouts may not always be perfectly parsed
- Extracted content may require manual verification
- This is an evolving project — features and structure may change

---

## 🔄 Future Improvements

- Better layout understanding
- Improved OCR handling
- Direct AI summarization integration
- GUI or web interface
- Support for more file formats (PDF, images, etc.)

---

## 📌 Disclaimer

> This project is still under development.  
> Users are advised to **review and verify extracted content** before using it for important tasks.

---

## 🤝 Contributions

This project is a work in progress. Suggestions, improvements, and contributions are welcome!

---

## 📬 Updates

The repository will be updated regularly as new features and improvements are added.

---

**Made to make AI summarization easier from messy slides 🚀**
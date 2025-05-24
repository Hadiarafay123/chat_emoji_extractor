# 📱 Chat Emoji Extractor

This beginner-friendly AI project extracts structured data (text, timestamps, emojis) from chat screenshots using OCR and Python.

---

## 🧠 What It Does

🖼️ **Input:** A chat screenshot (like WhatsApp)  
📤 **Output:** Structured JSON like this:

```json
{
  "messages": [
    {
      "timestamp": "2025-05-24T16:19:00Z",
      "text": "Heyyy bestieee!!",
      "emojis": ["😁", "💖"]
    }
  ]
}

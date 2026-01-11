Chatbot Widget Test

This is a minimal test site demonstrating embedding the Kaynai chatbot widget.

Files
- `index.html` — demo page with the widget snippet.
- `styles.css` — minimal styles for the demo.

How to view

Option 1 — Open directly
- Double-click `index.html` to open it in your browser.

Option 2 — Serve with Python (recommended if the widget requires an http(s) origin)

```bash
# from the project folder
python -m http.server 8000
# then open:
# http://localhost:8000/index.html
```

The widget configuration is in `index.html` near the bottom of the file. Adjust `window.chatbotConfig` as needed.

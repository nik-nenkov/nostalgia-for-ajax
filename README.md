# nostalgia-for-ajax

This project demonstrates a classic AJAX effect from the 2000s–2010s: dynamically updating part of a web page without reloading the whole page.

## How it works

- The main page (`index.html`) contains some static content and a dynamic section.
- Two buttons let you load content from `page_01.html` or `page_02.html` into the dynamic section.
- When you click a button, JavaScript fetches the content using AJAX and updates only that part of the page.
- Each subpage has different text and colors to show the effect.

## Try it out

1. **Serve the project locally** (required for AJAX to work):
   - Open a terminal in this folder.
   - Run:
     ```
     python3 -m http.server
     ```
   - Then open [http://localhost:8000](http://localhost:8000) in your browser.

2. Click the buttons to switch content in the dynamic section—no page reload needed!

---

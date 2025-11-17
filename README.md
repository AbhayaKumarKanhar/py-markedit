# py-markedit
---

````markdown
# py-markedit  
A simple, clean Python-based **Markdown editor with live preview**, designed for note-taking, documentation writing, and Markdown experimentation.

---

## 🚀 Features  
- Live Markdown preview  
- Minimal and distraction-free layout  
- Modular code structure (easy to extend)  
- File open/save handler  
- Clean separation of UI, editor logic, handlers, and theme files  
- Fully open-source (MIT License)

---

## 📦 Installation

### 1. Clone the repository  
```bash
git clone https://github.com/AbhayaKumarKanhar/py-markedit.git
cd py-markedit
````

### 2. (Optional but recommended) Create a virtual environment

```bash
python -m venv venv
venv\Scripts\activate   # Windows
# or
source venv/bin/activate  # Linux/macOS
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
python main.py
```

---

## 🖥️ Usage

* Type Markdown text in the left editor panel.
* The right panel shows the rendered preview in real time.
* Use file operations to create/open/save Markdown files.
* You may extend UI actions or themes inside the project folders.

---

## 🛠️ Project Structure

```
py-markedit/
├── converter/          # Markdown conversion logic
├── editor/             # Editor UI components
├── handlers/           # File handlers and event utilities
├── theme/              # UI themes (light/dark if implemented)
├── ui/                 # Main UI layout and windows
├── utils.py            # Helpers
├── main.py             # Application entry point
└── LICENSE             # MIT License
```

---

## 🎨 Customization

You may modify:

* **theme/** → change UI look or add themes
* **editor/** → enhance text-editing behavior
* **converter/** → add plugins or extend Markdown processing
* **handlers/** → add export/import features

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a new feature branch
3. Commit your changes
4. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👤 Author

Developed by **Abhaya Kumar Kanhar**
GitHub: [https://github.com/AbhayaKumarKanhar](https://github.com/AbhayaKumarKanhar)

---

Just tell me!

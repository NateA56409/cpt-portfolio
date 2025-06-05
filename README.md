# Nathaniel Aylsworth – Personal Portfolio Web App

This is a customizable personal portfolio website built with **Python (Flask)**, HTML/CSS, and JavaScript. It uses JSON files to dynamically load data for your reading list, timeline, and projects. Designed to be clean, organized, and easy to update.

## 🔧 Features

- Dynamic content loading with `.json` files (projects, reading list, timeline)
- Modern light purple theme
- Home page with navigation buttons
- Project drop-downs with description, date, and images
- Timeline with alphabetically ordered events and descriptions
- Reading list with book summaries, personal reflections, and connections to tech/business/CS

---

## 🗂️ Folder Structure

```
project-root/
│
├── static/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│   └── images/
│
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── projects.html
│   ├── timeline.html
│   └── reading.html
│
├── data/
│   ├── projects.json
│   ├── timeline.json
│   └── reading.json
│
├── app.py
└── README.md
```

---

## 🚀 Running the App

1. **Install Python 3** if you haven’t already.

2. **Install Flask**:
   ```bash
   pip install flask
   ```

3. **Run the app**:
   ```bash
   python app.py
   ```

4. Open your browser and go to:
   ```
   http://127.0.0.1:5000
   ```

---

## ✍️ Updating Your Content

### Projects – `data/projects.json`

```json
{
  "title": "Project Title",
  "date": "2024",
  "description": "Short description about what this project does.",
  "image": "images/your_image.png"
}
```

### Reading – `data/reading.json`

```json
{
  "title": "Book Title",
  "author": "Author Name",
  "summary": "Summary, your personal thoughts, and how the book influenced your view in CS, business, or technology."
}
```

### Timeline – `data/timeline.json`

```json
{
  "title": "Milestone Title",
  "date": "2024-01-01",
  "description": "A short description of the event or milestone."
}
```

### Images

Put your custom images in the `static/images/` folder and reference them like:
```json
"image": "images/your_image.png"
```

---

## 🌐 Page Navigation

- **Home** – `/`
- **Projects** – `/projects`
- **Timeline** – `/timeline`
- **Reading List** – `/reading`

You can return to the home page by clicking the **Home** button or your name in the navbar.

---

## 💡 Notes

- Make sure your `.json` paths and filenames match what’s in your folders.
- The project is easy to customize — just change the content in the `data/` folder.
- Ideal for portfolios, student profiles, or resume sites.

---

# Python Web Application

A simple and beautiful web application built with Python and Flask. This project demonstrates how to create a modern, responsive web application using Flask framework.

## ✨ Features

- 🚀 **Fast & Lightweight** - Built with Flask for optimal performance
- 🎨 **Modern Design** - Beautiful, clean UI with gradient backgrounds
- ⚡ **Easy to Deploy** - Simple setup and deployment process
- 📱 **Responsive Layout** - Works seamlessly on desktop, tablet, and mobile devices
- 🔄 **Multiple Pages** - Home and About pages with navigation

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- **Python 3.7 or higher** - [Download Python](https://www.python.org/downloads/)
- **pip** - Python package installer (usually comes with Python)

## 🚀 Installation

1. **Clone or download this repository**

2. **Navigate to the project directory:**
   ```bash
   cd web
   ```

3. **Create a virtual environment (recommended):**
   ```bash
   python -m venv venv
   ```

4. **Activate the virtual environment:**
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

5. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## 🏃 Running the Application

1. **Start the Flask development server:**
   ```bash
   python app.py
   ```

2. **Open your web browser and navigate to:**
   ```
   http://localhost:5000
   ```

3. **You should see the home page!** Navigate to `/about` to see the about page.

## 📁 Project Structure

```
web/
├── app.py              # Main Flask application with routes
├── requirements.txt    # Python dependencies
├── README.md          # Project documentation
├── templates/         # HTML templates directory
│   ├── index.html     # Home page template
│   └── about.html     # About page template
└── static/            # Static files directory
    └── style.css      # CSS stylesheet
```

## 🛠️ Technologies Used

- **Python 3** - Programming language
- **Flask 3.0.0** - Lightweight web framework
- **HTML5** - Markup language
- **CSS3** - Styling with modern features (Grid, Flexbox, CSS Variables)

## 📝 Customization

### Adding New Pages

1. Create a new HTML file in the `templates/` directory
2. Add a route in `app.py`:
   ```python
   @app.route('/your-page')
   def your_page():
       return render_template('your-page.html')
   ```
3. Update the navigation menu in your templates

### Styling

- Edit `static/style.css` to customize colors, fonts, and layout
- CSS variables are defined in `:root` for easy theme customization

## 🐛 Troubleshooting

### Port Already in Use
If port 5000 is already in use, you can change it in `app.py`:
```python
app.run(debug=True, host='0.0.0.0', port=8080)  # Change 5000 to any available port
```

### Module Not Found Error
Make sure you've installed all dependencies:
```bash
pip install -r requirements.txt
```

### Template Not Found Error
Ensure your HTML files are in the `templates/` directory and the directory name is spelled correctly.

## 📄 License

MIT License - Feel free to use this project for learning or as a starting point for your own applications.

## 🤝 Contributing

Contributions are welcome! Feel free to fork this project and submit pull requests.

## 📧 Support

If you encounter any issues or have questions, please open an issue on the repository.

---

**Happy Coding! 🎉**
.............................................................................................................................................................................................................................................................................

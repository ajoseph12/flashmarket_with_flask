# FlashMarket with Flask
Codebase for the Flask Course - Python Web Application Development

## About
This project is a web application built with Flask, following the tutorial by [Jim-VS-Code](https://www.youtube.com/watch?v=Qr4QMBUPxWo). It demonstrates how to create a marketplace application using Python and Flask framework.

## Prerequisites
- Python 3.7 or higher
- pip (Python package installer)

## Setup Instructions

1. Clone the repository
```bash
git clone https://github.com/yourusername/flashmarket_with_flask.git
cd flashmarket_with_flask
```

2. Create and activate a virtual environment
```bash
Windows
python -m venv venv
venv\Scripts\activate

macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

4. Run the application
```bash
python run.py
```

Visit `http://localhost:5000` in your browser.

## 📚 Tutorial Reference

This project follows the comprehensive Flask tutorial by [Jim-VS-Code](https://www.youtube.com/watch?v=Qr4QMBUPxWo).

### What You'll Learn
- 🔧 Flask application architecture
- 🗄️ SQLAlchemy database integration
- 🔐 User authentication & authorization
- 📝 Form handling with Flask-WTF
- 🎨 Dynamic templates with Jinja2
- 🛡️ Web security best practices
- 🔄 RESTful API development
- 🚀 Deployment strategies

## 🗂️ Project Structure
```bash
flashmarket_with_flask/
├── market/ # Main application package
│ ├── init.py # App initialization
│ ├── forms.py # Form definitions
│ ├── models.py # Database models
│ ├── routes.py # URL routes
│ └── templates/ # Jinja2 templates
│   ├── base.html # Base template with common layout
│   ├── home.html # Homepage template
│   ├── market.html # Market page template
│   ├── login.html # Login form template
│   └── register.html # Registration form template
├── run.py # Application entry point
├── requirements.txt # Project dependencies
└── README.md # Project documentation
```

## 🤝 Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🐛 Troubleshooting

### Common Issues
1. **Database errors**: Ensure SQLite is properly initialized
```bash
flask shell
>>> from market import db
>>> db.create_all()
```
2. **Module not found**: Verify virtual environment is activated
3. **Port already in use**: Change port in `run.py`

## 📝 License
This project is open-source and available under the MIT License.

## 📬 Contact
Your Name - [@yourusername](https://github.com/yourusername)

Project Link: [https://github.com/yourusername/flashmarket_with_flask](https://github.com/yourusername/flashmarket_with_flask)

## 🙏 Acknowledgments
- [Jim-VS-Code](https://www.youtube.com/watch?v=Qr4QMBUPxWo) for the excellent tutorial
- Flask documentation and community
- All contributors and users of this project


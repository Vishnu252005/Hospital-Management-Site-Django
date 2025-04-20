# LUNA - Django Web Application

A modern, responsive hospital management web application built with Django and Bootstrap. This application provides a seamless experience for patients to book appointments, view doctor profiles, and explore hospital departments.

## 🚀 Features

- **Patient Booking System**
  - Easy appointment scheduling
  - Real-time availability checking
  - Automated confirmation emails
  - Appointment history tracking

- **Doctor Profiles**
  - Detailed professional information
  - Specialization and expertise
  - Availability schedules
  - Contact information

- **Department Information**
  - Comprehensive department details
  - Available services
  - Specialized equipment
  - Department-specific doctors

- **User-Friendly Interface**
  - Responsive design for all devices
  - Dark mode support
  - Intuitive navigation
  - Modern UI/UX

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- **Python 3.8 or higher**
  ```bash
  python --version
  ```
- **Node.js 14.x or higher** (for development tools)
  ```bash
  node --version
  ```
- **Git** (for version control)
  ```bash
  git --version
  ```
- **Virtual Environment** (recommended)
  - Windows: `python -m venv`
  - macOS/Linux: `python3 -m venv`

## 🛠️ Installation Guide

### 1. Clone the Repository
```bash
git clone https://github.com/Vishnu252005/Hospital-Management-Site-Django.git
cd Hospital-Management-Site-Django
```

### 2. Set Up Virtual Environment

**Windows:**
```bash
python -m venv .venv
.venv\Scripts\activate
```

**macOS/Linux:**
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Database Setup
```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Create Superuser (Optional)
```bash
python manage.py createsuperuser
```

### 6. Run Development Server
```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` in your browser to see the application.

## 📁 Project Structure

```
Hospital-Management-Site-Django/
├── home/                  # Main application
│   ├── migrations/        # Database migrations
│   ├── templates/         # HTML templates
│   ├── static/           # Static files (CSS, JS, images)
│   └── views.py          # View logic
├── django_tutorial/       # Project configuration
├── templates/            # Base templates
├── static/              # Global static files
├── uploads/             # User uploaded files
├── manage.py           # Django management script
└── requirements.txt    # Project dependencies
```

## 🔧 Configuration

### Environment Variables
Create a `.env` file in the root directory with:
```
DEBUG=True
SECRET_KEY=your-secret-key
ALLOWED_HOSTS=localhost,127.0.0.1
```

### Database Configuration
The project uses SQLite by default. To use a different database:
1. Update settings.py
2. Install appropriate database adapter
3. Update requirements.txt

## 🎨 Customization

### Theme Customization
- Edit `static/css/style.css` for styling
- Modify `templates/base.html` for layout changes
- Update `static/js/main.js` for custom functionality

### Adding New Features
1. Create new models in `home/models.py`
2. Add views in `home/views.py`
3. Create templates in `templates/`
4. Update URLs in `home/urls.py`

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Support

For support, email support@luna.com or open an issue in the repository.

## 🙏 Acknowledgments

- Django Framework
- Bootstrap
- Font Awesome
- All contributors and supporters

---

Made with ❤️ by [Vishnu](https://github.com/Vishnu252005)

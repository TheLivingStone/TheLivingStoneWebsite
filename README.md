# The Living Stone Foundation Website

A modern, responsive website for The Living Stone Foundation - an innovative AI ecosystem builder delivering custom AI solutions and fostering the next generation of AI startups.

## 🚀 Overview

The Living Stone Foundation serves as a parent company and startup incubator, pioneering the future of artificial intelligence through our subsidiaries and strategic partnerships. Our primary subsidiary, Living Stone Solutions, delivers tailored AI solutions including custom LLMs, intelligent automation, and AI agent development for businesses.

## 🌟 Features

### **Core Pages**
- **Homepage** - Hero section with company overview and service highlights
- **About** - Company mission, vision, and leadership team
- **Services** - Detailed service offerings and technology stack
- **Solutions** - Industry-specific solutions with case studies
- **Contact** - Contact form with company information and FAQ

### **Design Highlights**
- **Responsive Design** - Mobile-first approach with seamless desktop experience
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Interactive Elements** - Tab-based solutions showcase, form validation
- **Performance Optimized** - Fast loading times and optimized assets
- **Accessibility** - ARIA labels, keyboard navigation, semantic HTML

### **Technical Features**
- **Flask Backend** - Python-based server with contact form processing
- **Database Integration** - SQLite database with user models
- **Email Handling** - Contact form submissions with email notifications
- **Cross-browser Compatibility** - Works across all modern browsers
- **SEO Optimized** - Meta tags, structured data, semantic markup

## 🛠️ Technology Stack

### **Frontend**
- **HTML5** - Semantic markup and accessibility
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript (ES6+)** - Interactive functionality and animations
- **Font Awesome** - Icon library for UI elements
- **Google Fonts** - Inter and Playfair Display typography

### **Backend**
- **Python 3.x** - Core programming language
- **Flask** - Web framework for routing and templating
- **SQLAlchemy** - Database ORM for user management
- **Flask-CORS** - Cross-origin resource sharing support

### **Database**
- **SQLite** - Lightweight database for development
- **User Models** - Contact form submissions and user data

## 📁 Project Structure

```
living-stone-foundation-website/
├── src/
│   ├── models/
│   │   └── user.py              # Database models
│   └── routes/
│       ├── user.py              # User-related routes
│       └── contact.py           # Contact form handling
├── static/
│   ├── assets/
│   │   └── images/              # Logo and visual assets
│   ├── index.html               # Homepage
│   ├── about.html               # About page
│   ├── services.html            # Services page
│   ├── solutions.html           # Solutions page
│   ├── contact.html             # Contact page
│   ├── styles.css               # Main stylesheet
│   └── script.js                # JavaScript functionality
├── database/
│   └── app.db                   # SQLite database
├── logs/
│   └── contact_submissions.log  # Contact form logs
├── main.py                      # Flask application entry point
└── README.md                    # Project documentation
```

## 🚀 Getting Started

### **Prerequisites**
- Python 3.7 or higher
- pip (Python package manager)
- Modern web browser

### **Installation**

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/living-stone-foundation-website.git
   cd living-stone-foundation-website
   ```

2. **Create virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install flask flask-cors flask-sqlalchemy
   ```

4. **Initialize database**
   ```bash
   python main.py
   ```

5. **Run the application**
   ```bash
   python main.py
   ```

6. **Access the website**
   - Open your browser and navigate to `http://localhost:5000`

## 📋 Usage

### **Development Mode**
The application runs in debug mode by default, enabling:
- Hot reload for code changes
- Detailed error messages
- Flask development server

### **Contact Form**
- Form submissions are logged to `logs/contact_submissions.log`
- Email notifications can be configured in `src/routes/contact.py`
- Form validation includes required field checking and email format validation

### **Database Management**
- User data is stored in SQLite database
- Database models are defined in `src/models/user.py`
- Database is automatically created on first run

## 🎨 Customization

### **Styling**
- Main styles are in `static/styles.css`
- Color scheme uses purple gradient (`#667eea` to `#764ba2`)
- Typography: Inter (body) and Playfair Display (headings)
- Responsive breakpoints: 768px (tablet) and 480px (mobile)

### **Content Updates**
- Update company information in HTML files
- Modify service offerings in `services.html`
- Update contact details in `contact.html`
- Add new case studies in `solutions.html`

### **Adding Pages**
1. Create new HTML file in `static/` directory
2. Add navigation links in header section
3. Update footer links if needed
4. Add corresponding routes in Flask if dynamic content needed

## 📱 Responsive Design

The website is fully responsive with breakpoints:
- **Desktop** (1200px+): Full grid layouts and side-by-side content
- **Tablet** (768px-1199px): Reduced columns and adjusted spacing
- **Mobile** (below 768px): Single column layout and mobile navigation

## 🔒 Security Features

- **CSRF Protection** - Secret key configuration
- **Input Validation** - Form data sanitization
- **SQL Injection Prevention** - SQLAlchemy ORM usage
- **Cross-Origin Requests** - CORS configuration

## 🚀 Deployment

### **Production Checklist**
- [ ] Update `SECRET_KEY` with secure random value
- [ ] Configure production database (PostgreSQL recommended)
- [ ] Set up email service for contact form notifications
- [ ] Enable HTTPS/SSL certificates
- [ ] Configure domain and DNS settings
- [ ] Set up monitoring and logging
- [ ] Optimize images and assets
- [ ] Enable gzip compression

### **Deployment Options**
- **Heroku** - Easy deployment with git integration
- **AWS EC2** - Full control over server environment
- **DigitalOcean** - Affordable VPS hosting
- **Netlify** (static hosting) - For frontend-only deployment

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a Pull Request

## 📞 Support

For technical support or questions:
- **Email**: info@thelivingstonefoundation.com
- **Phone**: +1 (540) 998-9766
- **Location**: Washington, DC

## 📄 License

This project is proprietary and confidential. All rights reserved by The Living Stone Foundation.

## 🔄 Version History

- **v1.0.0** - Initial website launch with core pages and functionality
- **v1.1.0** - Added contact form processing and database integration
- **v1.2.0** - Enhanced responsive design and accessibility features

## 📈 Future Enhancements

- [ ] Blog/News section for AI insights and company updates
- [ ] Customer portal for project tracking
- [ ] Interactive AI demos and calculators
- [ ] Multi-language support
- [ ] Advanced analytics and performance monitoring
- [ ] Content management system (CMS) integration
- [ ] API documentation portal
- [ ] Career portal with job applications

---

**The Living Stone Foundation** - Transforming businesses through innovative AI solutions and fostering the next generation of AI startups.

*Last updated: January 2025*

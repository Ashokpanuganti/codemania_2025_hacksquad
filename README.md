# 🎓 Student Assistant Chatbot - Codemania 2025 HackSquad

An intelligent AI-powered chatbot that assists students with academic information, course details, deadlines, and campus announcements.

## 🎯 Features

✅ **Course Information** - Get enrolled courses and subjects  
✅ **Deadline Tracking** - Get upcoming assignment and exam deadlines  
✅ **Academic Updates** - Receive department news and announcements  
✅ **Academic Calendar** - Check semester dates and holidays  
✅ **Library Support** - Get book availability and renewal information  
✅ **Fee Information** - Access fee structure and payment details  
✅ **Counseling Support** - Connect with academic advisors  
✅ **Natural Language** - Conversational AI-powered responses  
✅ **Real-time Updates** - Always updated with latest information  

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| **Python 3.8+** | Backend language |
| **Flask** | Web framework |
| **OpenAI API** | AI/ML responses |
| **Flask-CORS** | Cross-origin requests |
| **Python-dotenv** | Environment management |
| **HTML5/CSS3/JS** | Frontend UI |

## 📋 Requirements

```
flask
openai
flask-cors
python-dotenv
```

## 📁 Project Structure

```
codemania_2025_hacksquad/
├── app.py                          # Flask backend server
├── index.html                      # Frontend UI
├── script.js                       # Frontend logic
├── styles.css                      # Frontend styling
├── requirements.txt                # Python dependencies
├── .env                           # Environment variables
├── codemania_2025_hacksquad.pptx  # Project presentation
└── README.md                       # Project documentation
```

## 🚀 Quick Start

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)
- OpenAI API Key
- Git

### Installation & Setup

1. **Clone the repository:**
```bash
git clone https://github.com/Ashokpanuganti/codemania_2025_hacksquad.git
cd codemania_2025_hacksquad
```

2. **Create virtual environment:**
```bash
python -m venv venv

# On Windows:
venv\Scripts\activate

# On macOS/Linux:
source venv/bin/activate
```

3. **Install dependencies:**
```bash
pip install -r requirements.txt
```

4. **Setup environment variables:**
```bash
# Create .env file
cp create.env .env

# Edit .env and add your OpenAI API key
# OPENAI_API_KEY=your_api_key_here
```

5. **Run the application:**
```bash
python app.py
```

6. **Access the application:**
```
Open browser: http://localhost:5000
```

## 💬 Chatbot Capabilities

### 📚 Course Information
Ask about:
- "What courses am I taking?"
- "What are my enrolled subjects?"
- "Show me my course schedule"

### ⏰ Deadlines & Exams
Ask about:
- "What are my upcoming deadlines?"
- "When is the exam?"
- "What assignments are due?"

### 📢 News & Updates
Ask about:
- "Any recent news?"
- "What events are coming?"
- "Tell me about department updates"

### 📖 Academic Calendar
Ask about:
- "When does semester start?"
- "What are the holidays?"
- "When are exams scheduled?"

### 📚 Library Services
Ask about:
- "Is this book available?"
- "How do I renew a book?"
- "What's the library hours?"

### 💳 Fee Information
Ask about:
- "What's my fee structure?"
- "How do I pay fees?"
- "What are the payment deadlines?"

### 🎓 Counseling
Ask about:
- "How do I book a counselor?"
- "Academic advisor contact?"
- "Where's the counseling office?"

## 🔗 API Endpoints

### POST /chat
Send a message to the chatbot.

**Request:**
```json
{
  "message": "What are my courses?"
}
```

**Response:**
```json
{
  "response": "Your enrolled courses this semester are: 1. Data Structures 2. Operating Systems..."
}
```

## 🎨 Frontend UI

The application includes a clean, user-friendly web interface with:
- Message input field
- Chat history display
- Responsive design
- Professional styling
- Smooth animations

## 📊 Use Cases

1. **Student Information Access** - Quick access to academic details
2. **Deadline Management** - Never miss important dates
3. **Campus Announcements** - Stay updated with events and news
4. **Academic Support** - Get help with academic inquiries
5. **24/7 Availability** - Always available for student questions

## 🔒 Security

- Environment variables for sensitive data
- CORS enabled for security
- Input validation
- Error handling

## 📝 Environment Variables

Create a `.env` file in the root directory:

```
OPENAI_API_KEY=your_openai_api_key_here
FLASK_ENV=development
FLASK_DEBUG=True
```

## 🚀 Deployment

### Deploy to Heroku

1. Install Heroku CLI
2. Create `Procfile`:
```
web: python app.py
```

3. Deploy:
```bash
heroku create your-app-name
git push heroku main
```

### Deploy to PythonAnywhere

1. Upload project files
2. Configure WSGI file
3. Set environment variables
4. Reload web app

## 📸 Screenshots

*Add screenshots of the chatbot interface here*

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🐛 Known Issues

- OpenAI API responses may be rate-limited
- Real-time data requires database integration
- Mobile UI could be further optimized

## 🔄 Future Enhancements

- [ ] Database integration for real data
- [ ] User authentication system
- [ ] Multi-language support
- [ ] Mobile app version
- [ ] Voice input support
- [ ] Integration with university ERP systems
- [ ] Advanced analytics dashboard
- [ ] Scheduled notifications

## 📞 Support

For issues or questions:
- Email: ashokpannuganti786@gmail.com
- GitHub Issues: [Create an issue](https://github.com/Ashokpanuganti/codemania_2025_hacksquad/issues)

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🏆 Achievement

**HackSquad Challenge 2025** - Team submission for Codemania competition

## 🎓 Learning Outcomes

This project demonstrates:
- Flask web framework development
- RESTful API design
- Frontend-backend integration
- OpenAI API integration
- CORS and security best practices
- Python best practices

## 🔗 Links

- 📂 **Repository**: [GitHub](https://github.com/Ashokpanuganti/codemania_2025_hacksquad)
- 👤 **Author**: [Ashok Panuganti](https://github.com/Ashokpanuganti)
- 📊 **Presentation**: See `codemania_2025_hacksquad.pptx`

---

**Made with ❤️ for Codemania HackSquad 2025**

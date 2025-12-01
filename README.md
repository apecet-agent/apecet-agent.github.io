# 🎓 AP ECET College Information Bot

[![Status](https://img.shields.io/badge/status-active-success.svg)](https://apecet-agent.github.io)
[![Ethical Scraping](https://img.shields.io/badge/scraping-ethical-blue.svg)](https://apecet-agent.github.io/bot)
[![Python](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org)
[![License](https://img.shields.io/badge/license-Educational-green.svg)](LICENSE)

**Version:** 1.0  
**Purpose:** Help AP ECET students find colleges  
**Status:** ✅ Active

---

## 🎯 About This Bot

**APECETBot** is an educational tool that helps Andhra Pradesh ECET students discover colleges that match their entrance exam rank and preferences. We provide accurate, up-to-date information to help students make informed decisions about their engineering education.

### 🌟 Mission
Empower ECET students with transparent, accessible college information to make the best educational choices for their future.

---

## ✅ What We Collect (Public Data Only)

We collect **only publicly available information** from college websites:

- **🏫 College Information**: Name, location, contact details
- **📚 Branches**: CSE, ECE, Mechanical, Civil, Electrical, IT, AI&DS, etc.
- **💺 Seats**: Available seats per branch
- **💼 Placements**: Statistics, average package, top recruiters
- **📊 Cutoffs**: Admission rank cutoffs (General, OBC, SC, ST)
- **🏗️ Infrastructure**: Labs, libraries, facilities
- **👨‍🏫 Faculty**: Public faculty information

---

## ❌ What We DO NOT Collect (Private Data)

We **never** collect or access:

- ❌ Student records or personal data
- ❌ Passwords or login credentials
- ❌ Financial information
- ❌ Admin or internal pages
- ❌ Any private/restricted content
- ❌ Email addresses or contact details

**Your data security is our priority.**

---

## 🎯 Why Colleges Should Allow APECETBot

### Benefits for Colleges:

✅ **Increases Your Visibility**: Thousands of students discover your college  
✅ **Better Student Matching**: Right students apply to right colleges  
✅ **Reduces Inquiry Load**: Students get answers without calling you  
✅ **No Server Impact**: Only 1 visit every 2-3 days  
✅ **Free Promotion**: Your college data reaches qualified ECET candidates  
✅ **Updated Information**: We keep student-facing data current  

---

## 📧 For College Administrators

If you have questions about our bot:

**📧 Email:** apecet.bot@gmail.com  
**🌐 Website:** https://apecet-agent.github.io  
**💻 GitHub:** https://github.com/apecet-agent

### 🤖 Bot Details:

| Property | Value |
|----------|-------|
| Name | APECETBot |
| Version | 1.0 |
| User-Agent | `APECETBot/1.0 (+https://apecet-agent.github.io/bot)` |
| Purpose | Educational - Helping students find colleges |
| Visit Frequency | Once every 2-3 days |
| Server Impact | Minimal and respectful |

### 🛡️ How We Work:

1. ✅ We check your `robots.txt` file
2. ✅ We follow your rules strictly
3. ✅ We only access allowed public paths
4. ✅ We add delays between requests (5+ seconds)
5. ✅ We never overload your servers
6. ✅ We respect crawl-delay directives

### 🚫 To Block Us (if needed):

Add to your `robots.txt`:
```
User-agent: APECETBot
Disallow: /
```

**We will stop visiting immediately.** No questions asked.

---

## 📊 Data Accuracy Commitment

- 🔄 We update data every 2-3 days during admission season
- ✅ Students see the most recent public information
- 📧 Found incorrect data? Email us: apecet.bot@gmail.com
- ⚡ We'll correct it within 24 hours

---

## 🔐 Privacy & Ethics

We are committed to:

✅ **Respecting** all website privacy rules  
✅ **Following** robots.txt guidelines  
✅ **Collecting** only public information  
✅ **Being transparent** about our purpose  
✅ **Minimal** server impact  
✅ **Legal and ethical** data collection  
✅ **GDPR-style** principles (even though not required)

### 🌐 Ethical Scraping Principles:

1. **Honest Identification** - Clear User-Agent
2. **Respect Rules** - Check & follow robots.txt
3. **Slow & Respectful** - 1 request every 2-3 days per domain
4. **Public Data Only** - No login, no private pages
5. **Privacy First** - Never collect personal student data
6. **Transparent Purpose** - Educational mission

---

## 📱 For Students

Use this bot to:

- 🎯 Find colleges based on your ECET rank
- 📚 Discover available branches
- 💺 Get seat information
- 💼 View placement statistics
- 🏫 Compare colleges side-by-side
- 📊 Check previous year cutoffs

**🌐 Access:** Coming soon at https://apecet-agent.github.io

---

## 📚 Technical Information

### 🛠️ Built With:

- **Python** - Core language
- **BeautifulSoup** - HTML parsing
- **Requests** - HTTP library
- **Qdrant** - Vector database for smart search
- **Gemini AI** - Natural language understanding
- **Streamlit** - User interface

### 🔗 Links:

- **GitHub Repository:** https://github.com/apecet-agent/apecet-agent.github.io
- **Website:** https://apecet-agent.github.io
- **Email:** apecet.bot@gmail.com

---

## 📖 How It Works

```
1. 🔍 Discovery
   └─ We discover public pages ethically

2. ✅ Verification
   └─ We check robots.txt for allowed paths

3. 📥 Scraping
   └─ We collect only public data (2-3 day intervals)

4. 💾 Storage
   └─ We store data securely in vector database

5. 🤖 AI Processing
   └─ Gemini AI understands student queries

6. 💬 Query Response
   └─ Students ask questions, we provide personalized answers
```

---

## 🤝 Support & Contact

Have questions or concerns?

**📧 Email:** apecet.bot@gmail.com  
**🌐 Website:** https://apecet-agent.github.io  
**💻 GitHub Issues:** https://github.com/apecet-agent/apecet-agent.github.io/issues

**Average Response Time:** Within 24 hours

---

## 🙏 Acknowledgments

- **APECET Board** - For conducting the entrance exam
- **AP Engineering Colleges** - For publicly sharing information
- **Students** - For motivating us to build this tool
- **Open Source Community** - For amazing tools and libraries

---

## 📜 License

This project is licensed for **Educational Use Only**.

- ✅ Free for students
- ✅ Non-commercial
- ✅ Open source

---

## 📅 Project Status

**Last Updated:** December 2024  
**Status:** ✅ Active  
**Maintained by:** AP ECET Admission Agent Team

---

## 🚀 Roadmap

- [x] Basic scraping engine
- [x] Ethical scraping framework
- [x] Robots.txt compliance
- [ ] Gemini AI integration
- [ ] Qdrant vector database
- [ ] Streamlit web interface
- [ ] Public launch

---

## 💡 Contributing

We welcome contributions! If you're a developer interested in helping AP students:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

---

<div align="center">

**Built with ❤️ for AP ECET Students**

[Website](https://apecet-agent.github.io) • [Email](mailto:apecet.bot@gmail.com) • [GitHub](https://github.com/apecet-agent)

</div>

Maintained by: AP ECET Admission Agent Team

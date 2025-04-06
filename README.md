# 📚 StudyEasyArm Bot

A Telegram bot designed to support self-education, provide administrative assistance, and deliver useful opportunities (like job/volunteer/education programs) to Armenian users.

---

## 🚀 Features

- 🎓 Virtual Administrative Assistant
- 📦 Opportunity Repository (education, volunteering, jobs)
- 📖 Self-Education (books, podcasts, links, Telegram channels)
- 🧭 Simple menu-based navigation with inline buttons
- 🌐 Fully Armenian-language interface

---

## 🔑 Getting Started

### 1. Create a Bot with BotFather

1. Open [BotFather](https://t.me/BotFather) in Telegram.
2. Run the command: `/newbot`
3. Follow instructions and copy the **API Token** you receive.

### 2. Clone the Repository

```bash
git clone https://github.com/Razmik2001/StudyEasyArm.git
cd StudyEasyArm
```

### 3. Setup Environment Variables

Create a `.env` file in the root directory:

```
MYTOKEN=your_token_here
```

Replace `your_token_here` with the token you got from BotFather.

---

## 🐳 Run with Docker

### 1. Build the Docker image

```bash
docker build -t studyeasy-bot .
```

### 2. Run the Container

```bash
docker run -d --env-file .env --name studyeasybot studyeasy-bot
```

This will launch your bot in the background.

---

## 🧪 Development (Without Docker)

You can also run the bot locally:

```bash
pip install -r requirements.txt
python main.py
```

---

## 📂 Project Structure

```plaintext
.
├── AdminUni.json          # University info for Virtual Admin Assistant
├── Opportunities.json     # Opportunities data (education, volunteering, jobs)
├── selfStudy.json         # Books, podcasts, links, channels
├── main.py                # Main bot script
├── requirements.txt       # Python dependencies
└── .env                   # Your environment config (not tracked)
```

---

## 🤝 Contributing

1. Fork the repo
2. Create a new branch (`git checkout -b feature-xyz`)
3. Commit changes (`git commit -am 'Add feature'`)
4. Push to branch (`git push origin feature-xyz`)
5. Create a Pull Request

---

## 📬 Feedback

We’d love to hear your thoughts! Fill out the feedback form:
[Give Feedback](https://forms.gle/NApZjdb3Uhx2eypA9)

---

## 📜 License

MIT License. Feel free to use, modify, and share.

---

## 🇦🇲 Made with ❤️ for Armenian learners.


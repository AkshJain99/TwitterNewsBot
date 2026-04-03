# 🐦 TwitterNewsBot

An automated bot that fetches the latest news and posts it to Twitter (X) in real-time.
Built to keep your audience updated with trending and relevant news without manual effort.

---

## 🚀 Features

* 📰 Fetches latest news from APIs
* 🤖 Automatically posts tweets
* ⏱️ Scheduled posting (cron-based)
* 🔍 Customizable topics (tech, business, sports, etc.)
* 🧠 Smart filtering to avoid duplicates
* 🔐 Secure API key handling using environment variables

---

## 🛠️ Tech Stack

* **Backend:** Node.js
* **APIs:** News API (e.g., NewsData, NewsAPI)
* **Twitter Integration:** Twitter (X) API
* **Scheduler:** node-cron / cron jobs

---

## 📦 Installation

```bash
git clone https://github.com/your-username/twitterNewsBot.git
cd twitterNewsBot
npm install
```

---

## ⚙️ Environment Variables

Create a `.env` file in the root directory:

```env
NEWS_API_KEY=your_news_api_key
TWITTER_API_KEY=your_twitter_api_key
TWITTER_API_SECRET=your_twitter_api_secret
TWITTER_ACCESS_TOKEN=your_access_token
TWITTER_ACCESS_SECRET=your_access_secret
```

---

## ▶️ Run the Bot

```bash
npm start
```

---

## ⏰ Scheduling

You can configure how often tweets are posted inside your cron setup:

```js
cron.schedule('0 * * * *', () => {
  // Runs every hour
});
```

---

## 📁 Project Structure

```
twitterNewsBot/
│── src/
│   ├── services/       # API integrations
│   ├── utils/          # helper functions
│   ├── scheduler/      # cron jobs
│   └── index.js        # entry point
│── .env
│── package.json
│── README.md
```

---

## 🧠 How It Works

1. Fetch latest news articles
2. Filter and format content
3. Check for duplicates
4. Post tweet via Twitter API

---

## 📌 Future Improvements

* 📊 Analytics dashboard
* 🌍 Multi-language support
* 🧵 Thread-based tweeting
* 🧠 AI-based summarization

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork this repo and submit a PR.

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgements

* News APIs for providing data
* Twitter (X) API for posting capability

---

## ⭐ Support

If you like this project, give it a star ⭐ on GitHub!

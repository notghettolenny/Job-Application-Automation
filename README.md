# 🤖 Job Application Automation

![Python](https://img.shields.io/badge/built%20with-Python-3776AB?style=flat\&logo=python\&logoColor=white)
![Selenium](https://img.shields.io/badge/library-Selenium-43B02A?style=flat\&logo=selenium\&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

A Python automation script to apply for LinkedIn jobs that support **Easy Apply**.
The bot logs into your LinkedIn account, searches for jobs using specified keywords and location, filters results to *Easy Apply* jobs, and submits applications automatically if no additional questions are asked.

---

## ✨ Features

✅ Automates LinkedIn job search & application
✅ Filters jobs by “Easy Apply”
✅ Supports pagination — applies to jobs across all result pages
✅ Skips jobs already applied to or requiring additional input
✅ Configurable via `config.json` file
✅ Closes browser cleanly when finished

---

## 🏗️ Tech Stack

| Component          | Technology                            |
| ------------------ | ------------------------------------- |
| **Language**       | Python 3                              |
| **Web Automation** | [Selenium](https://www.selenium.dev/) |
| **Browser**        | Chrome WebDriver                      |

---

## 📁 Project Structure

```
Job-Application-Automation/
├── main.py             # Main bot logic (EasyApplyLinkedin class)
├── config.json         # Configuration file with credentials & search terms
├── README.md           # Project documentation
```

---

## 🚀 Getting Started

### 📋 Prerequisites

* Python 3.7+
* Google Chrome installed
* ChromeDriver (make sure it matches your Chrome version)
* LinkedIn account
* Selenium

---

### ⚙️ Installation

1️⃣ Clone the repository:

```bash
git clone https://github.com/notghettolenny/Job-Application-Automation.git
cd Job-Application-Automation
```

2️⃣ Install Python dependencies:

```bash
pip install selenium
```

3️⃣ Download [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/) and note its path.

4️⃣ Configure your `config.json`:

```json
{
  "email": "your_email@example.com",
  "password": "your_password",
  "keywords": "Software Engineer",
  "location": "San Francisco Bay Area",
  "driver_path": "/path/to/chromedriver"
}
```

---

## 🐍 Usage

Run the bot:

```bash
python main.py
```

The bot will:
✅ Log in to your LinkedIn account
✅ Search for jobs based on your keywords & location
✅ Filter for *Easy Apply* jobs
✅ Apply automatically to jobs that require no additional input

---

## 📝 Notes

⚠️ This bot only applies to jobs that:

* Support *Easy Apply*
* Don’t ask additional questions beyond uploading a resume

Jobs that require manual input are skipped automatically.
Be mindful of LinkedIn’s [Terms of Service](https://www.linkedin.com/legal/user-agreement) when using automation.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🤝 Contributing

Contributions and suggestions are welcome!

* Fork this repo
* Create your feature branch (`git checkout -b feature/my-feature`)
* Commit your changes
* Push to the branch (`git push origin feature/my-feature`)
* Open a Pull Request

---

## 📬 Contact

For questions or feedback, open an [issue](https://github.com/notghettolenny/Job-Application-Automation/issues).

---


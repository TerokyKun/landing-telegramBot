# Landing Page with Telegram Bot Application

This project is a **landing page** that allows users to submit applications, which are then sent directly to a **Telegram bot**. Built with **Node.js**, it uses environment variables for secure configuration.

---

## Features

- **User form** for submitting applications
- **Instant notification** to a Telegram bot
- **Environment-based configuration** using a `.env` file

---

## Prerequisites

- **Node.js** (recommended: latest LTS version)
- **NPM** (Node Package Manager)
- **Telegram bot token** (get one via [@BotFather](https://core.telegram.org/bots#botfather) in the Telegram app)

---

## Installation & Setup

1. **Clone the repository:**

```
git clone https://github.com/TerokyKun/landing-telegramBot.git
cd <project-directory>
```

---

2. **Install dependencies:**

```
npm install
```

3. **Create a `.env` file:**

- Copy the example file if provided, or create a new one in the project root.
- Add your **Telegram bot token** and any other required variables.
- Example:
  ```
  PORT=4312
  TELEGRAM_BOT_TOKEN=your-telegram-bot-token
  # Add other variables if needed
  ```
  > **Note:** Never commit your `.env` file to version control for security reasons.

---

4. **Start the application:**

- Build ts-app:

```
npx tsc
```

- or

```
npm run build
```

- Run app in prod:

```
npm run start
```

- or dev:

```
npm run dev
```

- or, if specified in `package.json`:

```
node build/main.js
```

- The application will automatically load environment variables from your `.env` file.

---

## Usage

- Open the landing page in your browser.
- Fill out the application form.
- Submitted data will be sent directly to your configured Telegram bot.

---

## Notes

- Make sure your bot is activated and has permission to receive messages.
- For production, secure your `.env` and never expose sensitive data.

---

---

<h1 align="center">Hipin Bot</h1>

<p align="center">Automate tasks in Hipin to enhance your efficiency and maximize your results!</p>

---

## 🚀 About Hipin Bot

Hipin Bot is a smart automation tool designed to simplify your gaming experience. With Hipin Bot, you can easily:

- **Auto Daily Check-in:** Automatically claim your daily rewards.
- **Auto Task Execution:** Run available tasks and collect rewards without manual effort.
- **Auto Farming:** Manage your farming sessions and claim rewards seamlessly.

Additional benefits include:

- **Multi-Account Support:** Handle multiple accounts at once.
- **Threading System:** Process accounts concurrently with configurable threading.
- **Proxy Support:** Optionally use proxies for added security.
- **Customizable Delays:** Fine-tune delays for switching accounts and loop iterations.

---

## 🌟 Version v1.0.0

### Initial Release

---

## ⚙️ Configuration in `config.json`

Below is an example configuration file. Adjust the settings as needed:

```json
{
  "farming": true,
  "task": true,
  "daily": true,
  "thread": 1,
  "proxy": false,
  "delay_account_switch": 10,
  "delay_loop": 3000
}
```

| **Function**           | **Description**                                        | **Default** |
| ---------------------- | ------------------------------------------------------ | ----------- |
| `farming`              | Automate farming sessions and reward claims            | `true`      |
| `task`                 | Automate task execution and reward claims              | `true`      |
| `daily`                | Automate daily check-in and claim rewards              | `true`      |
| `thread`               | Number of concurrent threads (accounts) to process     | `1`         |
| `proxy`                | Enable/Disable proxy usage                             | `false`     |
| `delay_account_switch` | Delay before switching accounts (in seconds)           | `10`        |
| `delay_loop`           | Delay before restarting the bot loop (in milliseconds) | `3000`      |

---

## 📥 How to Register

Get started with Hipin Bot by registering through the link below:

<div align="center">
  <a href="https://t.me/hi_PIN_bot/app?startapp=pAuthDl" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Register&logo=telegram&label=&color=2CA5E0&logoColor=white&style=for-the-badge" height="25" alt="telegram logo" />
  </a>
</div>

---

## 📖 Installation Steps

1. **Clone the Repository**  
   Clone the project to your local machine:

   ```bash
   git clone https://github.com/livexords-nw/hipin-bot.git
   ```

2. **Navigate to the Project Folder**  
   Change your directory to the project folder:

   ```bash
   cd hipin-bot
   ```

3. **Install Dependencies**  
   Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

4. **Configure Query**  
   Create a `query.txt` file and add your game query data.

5. **Set Up Proxy (Optional)**  
   If you want to use a proxy, create a `proxy.txt` file and list your proxies in the following format:

   ```
   http://username:password@ip:port
   ```

   (Only HTTP and HTTPS proxies are supported.)

6. **Run the Bot**  
   Execute the bot using the command:

   ```bash
   python main.py
   ```

---

## 🚀 Main Features

- **Auto Daily Check-in:** Claim your daily rewards automatically.
- **Auto Task Execution:** Run tasks and claim rewards without any manual effort.
- **Auto Farming:** Manage your farming sessions and collect rewards seamlessly.
- **Multi-Account Support:** Process multiple accounts concurrently.
- **Threading System:** Use configurable threading to run accounts in parallel.
- **Proxy Support:** Optionally enhance security with proxy usage.
- **Custom Delays:** Adjust delay intervals for account switching and bot looping.

---

## 🛠 Contributing

This project is developed by **livexords**.  
If you have any suggestions, questions, or would like to contribute, please get in touch:

<div align="center">
  <a href="https://t.me/livexordsscript" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Livexords&logo=telegram&label=&color=2CA5E0&logoColor=white&style=for-the-badge" height="25" alt="telegram logo" />
  </a>
</div>

---

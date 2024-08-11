📚 MechIfy - Your Ultimate Mechanical Engineering Study Bot 🤖

Welcome to **MechIfy**! This bot is designed to assist Mechanical Engineering students by providing resources, study assistance, and interactive learning support. Whether you need help with a specific topic or access to resources, MechIfy is here to guide you through your academic journey.

✨ Features

- **Resources 📚**: Get quick access to curated study materials based on your year of study or exam category.
- **AI Instructor 🤖**: Ask the bot any question related to Mechanical Engineering, and it will provide an informative and engaging response.
- **About ℹ️**: Learn more about the purpose and development of MechIfy.
- **Developers 👨‍💻**: Get to know the team behind MechIfy.

🚀 Getting Started

### Prerequisites

- Python 3.7+
- Telegram Bot API token

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/mechify-bot.git
   cd mechify-bot
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Set up your environment variables:**
   - Replace the placeholders in the bot script with your API keys and credentials:
     - `BOT_TOKEN`
     - `YOUTUBE_API_KEY`
     - `COHERE_API_KEY`
   - You can store these in a `.env` file for easier management.

### Running the Bot

1. **Start the bot:**

   ```bash
   python bot.py
   ```

2. **Interact with the bot on Telegram:**
   - Search for your bot by name on Telegram and start a conversation.

- **/start**: Start the bot and view the main menu.
- **Handle Messages**: Send a message to the bot to ask a question or request resources.

## 🛠️ Bot Functionalities

### Welcome Message & Menu

When users start the bot, they receive a welcome message along with a menu offering different options:

```plaintext
🎓Welcome to AAIT Mechanical Engineering Study Bot (Mechify)!🎓

Choose an option below to get started:
```

### Resource Access

Users can select their year or exam category to access relevant study materials:

```plaintext
🌟 Click below to access your study resources and level up your learning! 📚🚀
```

### AI Instructor

Users can ask the bot about any topic, and the bot will generate a detailed response using Cohere's AI:

```plaintext
Please mention the topic you want to learn about 📚, I'm here to help as your Ai Instructor! 🤖
```

### Developer Info

Information about the developers behind the bot:

```plaintext
👨‍💻 Developed with Passion by the AAIT Mechanical Engineering Team! 👩‍💻
```

## 🛡️ Error Handling

- The bot gracefully handles API errors and informs the user if it is unable to generate a response or fetch a YouTube video.

## 🙌 Acknowledgments

- **Cohere API** for natural language processing.
- **YouTube Data API** for fetching relevant video content.

---

Happy Studying! 🚀

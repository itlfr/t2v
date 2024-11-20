

# **Text-to-Speech Web Application**  
🚀 Transform any text into high-quality speech with ease!  

## **Overview**  
This is a **Next.js-powered web application** that converts user input text into an audio file. Designed for speed, simplicity, and accessibility, the app leverages the Google Text-to-Speech API to generate natural-sounding audio, making it perfect for personal, educational, or professional use.  

---

## **Key Features**  
- **Text-to-Speech Conversion**: Instantly converts text to audio using the powerful Google Cloud TTS API.  
- **Language Detection**: Automatically detects the language of the input text for seamless audio generation.  
- **Device Logging**: Tracks user devices and sends notifications for analytics purposes via Telegram Bot.  
- **Real-Time Notifications**: Alerts admin via Telegram whenever a new user visits the site.  
- **Responsive Design**: Fully optimized for all devices (mobile, tablet, and desktop).  
- **No Backend Hosting Needed**: Built entirely using Next.js, making it easy to deploy on platforms like **Vercel**.  

---

## **Project Structure**  
Here's an organized breakdown of the project's structure:  

```plaintext
📂 text-to-speech
├── 📂 public            # Static files like audio outputs
├── 📂 pages             # Application pages
│   ├── 📄 index.js      # Main page for text input
│   ├── 📄 result.js     # Result page displaying the audio
│   ├── 📄 _app.js       # Global configurations
│   └── 📄 api
│       └── 📄 tts.js    # API route for TTS conversion
├── 📂 styles            # CSS/SCSS files for styling
│   └── 📄 globals.css   # Global styles
├── 📄 package.json      # Project metadata and dependencies
├── 📄 next.config.js    # Next.js configuration
└── 📄 README.md         # Project documentation

```

---

**Getting Started**

Prerequisites

Ensure you have the following installed on your machine:

Node.js (v16 or higher)

NPM or Yarn


Installation

1. Clone the repository:

git clone https://github.com/your-username/text-to-speech.git
cd text-to-speech


2. Install dependencies:

npm install


3. Add your Google Cloud Text-to-Speech API key:

Create a .env.local file in the root directory:

GOOGLE_CLOUD_API_KEY=your_api_key_here
TELEGRAM_BOT_TOKEN=your_telegram_bot_token
ADMIN_CHAT_ID=your_telegram_chat_id





---

Running the Project

Development Mode:

npm run dev

Open http://localhost:3000 to view in the browser.

Build for Production:

npm run build
npm start

Deploy on Vercel:
Follow Vercel's deployment guide for seamless hosting.



---

How It Works

1. User Input: Enter text on the home page.


2. Language Detection: The app detects the language or uses the one you select manually.


3. Audio Conversion: The text is converted to speech and displayed on the result page.


4. Admin Notification: Device details of the user are logged and sent to a Telegram bot.




---

Technologies Used

Next.js: React framework for server-side rendering and static generation.

Google Cloud Text-to-Speech API: High-quality audio generation.

Telegram Bot API: Admin notifications via Telegram.

Bootstrap: Responsive, modern UI design.



---

Screenshots

Home Page

Enter your text and select a language:


Result Page

Listen to or download your audio file:



---

Future Enhancements

Add custom voice settings (pitch, speed, etc.).

Integrate multi-voice support for dialogue generation.

Enable audio storage limits with user-specific folders.



---

Contributing

Contributions are welcome! Follow these steps:

1. Fork the repository.


2. Create a new branch:

git checkout -b feature/your-feature


3. Commit your changes:

git commit -m "Add some feature"


4. Push the branch:

git push origin feature/your-feature


5. Open a pull request.




---

License

This project is licensed under the MIT License. See the LICENSE file for details.


---

Contact

Have questions or feedback? Feel free to reach out!

Telegram: https://t.me/devboda

GitHub: @itlfr



---

✨ Built with ❤️ by AbdulRahman AbdulJalil 

> هذا الملف **احترافي جدًا** ويحتوي على جميع المعلومات المطلوبة لعرض مشروعك بشكل مميز. يمكنك تعديل الروابط والمعلومات حسب الحاجة.


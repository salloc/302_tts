# 🗣️🤖 Welcome to 302.AI's AI Voice Generator 🚀✨

[中文](README_zh.md) | [English](README.md) | [日本語](README_ja.md)

Open-source version of the [AI Voice Generator](https://302.ai/tools/tts/) from [302.AI](https://302.ai).
You can directly log in to 302.AI for a zero-code, zero-configuration online experience.
Alternatively, customize this project to suit your needs, integrate 302.AI's API KEY, and deploy it yourself.

## ✨ About 302.AI ✨
[302.AI](https://302.ai) is a pay-as-you-go AI application platform, bridging the gap between AI capabilities and practical implementation.
1. 🧠 Comprehensive AI capabilities: Incorporates the latest in language, image, audio, and video models from leading AI brands.
2. 🚀 Advanced application development: We build genuine AI products, not just simple chatbots.
3. 💰 No monthly fees: All features are pay-per-use, fully accessible, ensuring low entry barriers with high potential.
4. 🛠 Powerful admin dashboard: Designed for teams and SMEs - managed by one, used by many.
5. 🔗 API access for all AI features: All tools are open-source and customizable (in progress).
6. 💡 Powerful development team: Launching 2-3 new applications weekly with daily product updates. Interested developers are welcome to contact us.

## Project Features
1. ⚙️ Cross-platform integration: OpenAI, Azure, Doubao, FishAudio, Minimax
2. 🌍 Multi-language support
3. 🎧 Online playback and speed adjustment
4. ⬇️ MP3 file download
5. 📂 Generation history management and recovery
6. 🗣️ Language-to-text and voice-to-voice functions
7. 🧬 Voice cloning
8. ⏺️ Audio file upload
9. 🌐 Internationalized interface: Chinese, English, Japanese, Korean, German, French

With the AI Voice Generator, anyone can become a voice creator! 🎉💻 Let's explore the new AI-driven world of voice together! 🌟🚀

## Tech Stack
- Next.js 14
- Tailwind CSS
- Shadcn UI

## Development & Deployment
1. Clone the project `git clone https://github.com/302ai/302_tts`
2. Install dependencies `pnpm install`
3. Configure the 302 API KEY as per .env.example
4. Run the project `pnpm dev`
5. Package and deploy `docker build -t tts . && docker run -p 3000:3000 tts`

## Interface Preview
![Interface Preview](docs/preview.png)

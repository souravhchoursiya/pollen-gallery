# 🌼 PollenStudio: AI Variation Gallery

A high-end, React-based web application that generates triple-styled AI variations of any prompt using the **Pollinations.ai** engine. 

Built with a "Bring Your Own Pollen" (BYOP) architecture, this app scales infinitely with **$0 server costs** to the developer.

## 🚀 Live Demo
[View the App Live on GitHub Pages](https://souravhchoursiya.github.io/pollen-gallery/)

---

## ✨ Key Features

- **3x Variation Logic:** Every prompt automatically generates three distinct artistic styles:
  - 🎨 **3D Pixar:** Vibrant, cinematic, and whimsical.
  - 📸 **Hyper-Realistic:** Intricate details via Unreal Engine 5 aesthetic.
  - 🖌️ **Watercolor:** Soft, storybook-style digital paintings.
- **BYOP Architecture:** Users connect their own Pollinations account. They pay for what they use; you pay $0 for hosting and API fees.
- **Local Persistence:** Your generation history is saved locally in your browser (`localStorage`), so your gallery is ready whenever you return.
- **One-Click Downloads:** High-resolution saves directly to your device with prompt-based filenames.
- **Glassmorphism UI:** A sleek, dark-mode interface designed for a premium creative experience.

## 🗝️ How to Use

1. **Connect:** Click the "Connect Pollinations Account" button.
2. **Authorize:** Log in via GitHub on the Pollinations secure screen.
3. **Generate:** Enter any description (e.g., *"A futuristic library in Delhi"*) and hit Create.
4. **Save:** Hover over any image to download it or view the original high-res link.

## 🛠️ Technical Stack

- **Frontend:** Vanilla React (React 18 via CDN)
- **Styling:** Tailwind CSS (Modern Utility-First CSS)
- **API:** Pollinations.ai (OpenAI-compatible `v1/images/generations` endpoint)
- **Deployment:** GitHub Pages

## 🔒 Privacy & Security

This app uses a **client-side redirect flow**. Your API key is captured in the URL fragment (`#api_key=...`), meaning it is handled entirely in your browser memory. **The key is never sent to any server** or stored in GitHub logs.

---

*Developed by [Souravh Choursiya](https://github.com/souravhchoursiya) — Powered by Pollinations.ai*

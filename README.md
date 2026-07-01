# Ctrl+V: EasyRead - AI Accessibility Reader

**Ctrl+V: EasyRead** is an elegant, client-side web application designed to break down digital barriers and expand reading access. Built for the **CTRL-V Hackathon**, the project aligns with the core philosophy of "instant access"—allowing users to simply paste complex, jargon-heavy text and instantly transform it into a simplified, readable, and highly accessible format.

---

## 🔗 Live Links
* **Live Web App:** [Click here to view the live site](https://Dufoo.github.io/ctrl-v-easyread/)
* **GitHub Repository:** [https://github.com/Dufoo/ctrl-v-easyread](https://github.com/Dufoo/ctrl-v-easyread)

---

## 💡 The Problem Statement
Accessing knowledge is one of the most critical challenges in the digital age. Millions of individuals face unnecessary daily obstacles when interacting with information due to:
* **Cognitive and Learning Differences:** Such as Dyslexia, ADHD, or cognitive fatigue.
* **Language Barriers:** Complex academic, medical, or legal vocabulary that restricts non-native speakers.
* **Visual Impairments:** Low vision or sensitivity to high light levels/poor contrast.

Standard reading tools are often hidden behind paywalls, require complex software installations, or lack custom layout configurations. 

---

## 🛠️ The Solution & Core Features
**Ctrl+V: EasyRead** removes these barriers instantly. By copy-pasting text, the user gains access to a robust toolbar of custom configurations:

1. **AI-Assisted Vocabulary Simplification:** Uses a specialized processing engine to detect complex, jargon-heavy terms (like *utilize*, *subsequent*, *cognitive*, *facilitate*) and translates them into plain-language alternatives, complete with visual highlights.
2. **Dynamic Reading Summaries:** Generates a structured quick-summary alert box to give the reader instant context.
3. **Dyslexia-Friendly Layout:** Features a toggle to apply customized letter-spacing, line-height, and a highly readable typeface to assist users with reading flow.
4. **Interactive Text-to-Speech (TTS):** Integrated audio reading allows users who struggle with visual tracking or focus to listen to the simplified text.
5. **Robust Contrast Adjustments:** Includes support for full **Dark Mode** and a custom **High Contrast Mode** (optimized yellow-on-black) to reduce eye strain and support users with severe light sensitivity.
6. **Font Resizing:** Real-time font scaling dynamically shifts the viewport text size to accommodate users with low vision.

---

## 💻 Tech Stack
The app is built to be lightweight, efficient, and fully responsive:
* **Frontend Structure:** HTML5
* **Styling Framework:** Tailwind CSS (loaded via CDN) for responsive layouts and modern theme configuration.
* **Core Logic:** Vanilla JavaScript (ES6+) for instant state management, responsive DOM rendering, and custom algorithm logic.
* **Audio Accessibility:** Web Speech API (`SpeechSynthesis`) for high-quality, native device-based screen reading without requiring external API keys.

---

## 🚀 How to Run Locally

Because the application is completely client-side, it requires zero complex setup:

1. Clone or download this repository:
   git clone https://github.com/Dufoo/ctrl-v-easyread.git

2. Navigate to the project folder and double-click index.html to open it instantly in any modern web browser.

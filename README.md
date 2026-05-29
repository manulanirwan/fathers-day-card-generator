# 👨‍👦 Father's Day Card Generator

A responsive, lightweight single-page web application that allows users to create and download personalized Father's Day cards. Built entirely with vanilla frontend technologies, this tool features dynamic client-side image processing, real-time custom text rendering, and instant photo layout adjustments.

---

## 🚀 Features

* **Dynamic Photo Upload:** Upload any image from your device. The application reads and processes the file locally and instantly using the browser.
* **Smart Aspect-Ratio Cropping:** Automatically centers and crops uploaded photos into a clean, rounded square to fit the card layout perfectly without stretching or distortion.
* **Premium Masculine Themes:** Easily switch between 4 distinct pre-configured canvas and border templates:
  * **Classic Navy:** Deep royal blues with clean slate accents.
  * **Executive Gold:** Elegant corporate amber and gold borders.
  * **Forest Minimal:** Earthy, modern greens and mint tones.
  * **Vintage Charcoal:** Structured slate and dark neutral frames.
* **Real-Time Custom Greetings:** Type a personalized message and watch it render onto the canvas on-the-fly, utilizing automated canvas word-wrapping logic.
* **Instant PNG Download:** Export the final card creation as a high-quality `Fathers_Day_Card.png` directly to your device.
* **Blogger-Ready & Mobile Responsive:** Scoped CSS layout rules ensure it embeds cleanly into third-party blogging platforms (like Blogger light themes) and fluidly scales down to mobile viewports.

---

## 🛠️ Tech Stack

* **HTML5:** Semantic markup structure and native `<canvas>` rendering context.
* **CSS3:** Custom grid configurations, smooth interactive transitions, and responsive media query breakpoints.
* **JavaScript (ES6+):** * `FileReader API` for secure, serverless client-side image loading.
  * `HTML5 Canvas API` for sequential pixel rendering, vector border paths, and text wrapping.

---

## 📦 Getting Started

Because this project has **zero external dependencies** and requires no build tools, setting it up is incredibly straightforward:

1. Clone this repository or download the source code:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/fathers-day-card-generator.git](https://github.com/YOUR_USERNAME/fathers-day-card-generator.git)

# Mobile LaTeX (移动端 LaTeX 公式助手)

> Compose and copy LaTeX formulas naturally on mobile devices, chat Math with AI on-the-go.  
> 专为手机端优化、配合 AI（ChatGPT / Claude / Gemini / DeepSeek）进行数学探讨与公式推导的纯静态 Web 实用工具。

---

## ✨ Features / 特性亮点

- 📱 **Mobile-First Ergonomics / 移动端专属键盘体验**
  - **Categorized Symbol Keypad / 分类符号键盘**：常用运算、微积分/代数、希腊字母、集合/逻辑、括号与矩阵等，告别在手机软键盘上层层翻找 `\`、`{}`、`^`、`_` 的痛苦。
  - **Smart Cursor Insertion / 智能占位与光标定位**：点击 `\frac{a}{b}` 或 `\sqrt{}` 自动在第一处参数 `{}` 内定位光标。
  - **Cursor Micro-Adjustment / 精确光标微调与撤销**：提供移动端专用的 `◀` `▶` 光标微调、`↶ Undo` 撤销与 `⌫` 退格键。
- 🤖 **AI Math Chat Companion / 专为 AI 数学问答打造**
  - 1-Click prompt packaging: "Explain Step-by-Step", "Solve / Simplify", "Mathematical Proof", "Check Derivation".
  - 一键复制并包装 AI 提示词（逐步推导、化简求解、严谨证明、检查漏洞），无缝粘贴到 ChatGPT / Claude / DeepSeek 手机端。
- 🌐 **Automatic i18n / 双语自适应 (中文 / English)**
  - Automatically detects browser/system language (`zh` → 中文, otherwise English).
  - One-tap manual toggle button in the header with preference saved in `localStorage`.
- ⚡ **Zero-Dependency Static App / 纯静态零依赖部署**
  - 100% Client-side KaTeX rendering with CDN.
  - Zero build step required. Perfect for **GitHub Pages**.
  - Standalone Web App ready (`apple-mobile-web-app-capable`, responsive `100dvh`, iOS safe area insets).
- 💾 **Persistence & History / 自动保存与历史记录**
  - Automatic `localStorage` draft backup to prevent loss when switching apps.
  - Quick access drawer for recently composed formulas and classic math templates.

---

## 📲 Add to Home Screen / 添加至手机主屏幕（全屏 App 体验）

To get a full-screen, native app-like experience without browser address bars:

### 🍏 iOS (Safari)
1. Open the website in **Safari** (`https://<username>.github.io/mobile-latex/`).
2. Tap the **Share** button (the square icon with an upward arrow `⬆` at the bottom).
3. Scroll down and select **"Add to Home Screen"** (添加到主屏幕).
4. Tap **"Add"** in the top right corner.
5. Launch **Mobile LaTeX** directly from your iPhone/iPad Home Screen as a standalone app!

### 🤖 Android (Chrome / Edge / Samsung Internet)
1. Open the website in **Chrome** or your preferred mobile browser.
2. Tap the **Three Dots Menu** (`⋮`) in the top right or bottom bar.
3. Select **"Add to Home screen"** (添加到主屏幕) or **"Install app"** (安装应用).
4. Confirm by tapping **"Add"**.
5. The app icon will appear on your Home Screen and app drawer.

---

## 🚀 How to Host on GitHub Pages / 部署到 GitHub Pages

1. Push this repository to your GitHub:
   ```bash
   git add .
   git commit -m "feat: mobile latex editor with i18n and AI prompts"
   git push origin main
   ```
2. In your repository on GitHub:
   - Go to **Settings** > **Pages**.
   - Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
   - Select **Branch**: `main`, Folder: `/(root)`, then click **Save**.
3. Your app will be live at `https://<username>.github.io/mobile-latex/`.

---

## 📄 License

MIT License

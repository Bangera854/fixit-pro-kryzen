# 🛠️ Fixit Pro

> **See errors, warnings, and hints inline at the end of each line — plus AI-powered batch fixing.**

[![VS Code Marketplace](https://img.shields.io/visual-studio-marketplace/v/KRYZEN.inline-diagnostics-kryzen?label=VS%20Code%20Marketplace&color=blue)](https://marketplace.visualstudio.com/items?itemName=KRYZEN.inline-diagnostics-kryzen)
[![Open VSX](https://img.shields.io/open-vsx/v/KRYZEN/inline-diagnostics-kryzen?label=Open%20VSX&color=purple)](https://open-vsx.org/extension/KRYZEN/inline-diagnostics-kryzen)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Fixit Pro turns VS Code into a faster debugging environment by displaying diagnostics inline and using AI to fix them automatically.

---

## ✨ Features

### 🆓 Free Tier
- **Inline Diagnostics** — See errors, warnings, and hints at the end of each line without hovering.
- **✨ AI Quick Fix** — Fix single errors using GitHub Copilot's Language Model API. **3 free fixes included** to try it out.
- **Full Customization** — Colors, font size, message length, and severity filters are all configurable.

### 💎 Pro Tier (Lifetime License)
- **♾️ Unlimited AI Quick Fixes** — No more free-tier limits.
- **🚀 Batch Fix All** — Fix **every** error in your current file with a single command. Save hours per week.

---

## 📦 Installation

### From VS Code Marketplace (Recommended)
1. Open VS Code.
2. Press `Ctrl+Shift+X` (or `Cmd+Shift+X` on Mac) to open the Extensions view.
3. Search for **"Fixit Pro"**.
4. Click **Install**.

### From Open VSX
For VS Codium, VSCode OSS, and other compatible editors:
- [Install from Open VSX](https://open-vsx.org/extension/KRYZEN/inline-diagnostics-kryzen)

---

## ⚙️ Requirements

- **VS Code** v1.90.0 or higher.
- **GitHub Copilot** extension must be installed and active. Fixit Pro uses your existing Copilot subscription to power the AI fixes — you do **not** need a separate API key.

---

## 🚀 Usage

1. Install Fixit Pro and reload VS Code.
2. Open any file (`.ts`, `.js`, `.py`, `.tsx`, etc.).
3. Diagnostics appear **automatically** at the end of each line — no hover required.

### Trigger AI Fixes

**Single Quick Fix:**
- Hover over an error → click the lightbulb (💡) → select **`✨ Fix with Fixit Pro AI`**
- Or press `Ctrl+.` (or `Cmd+.` on Mac) on the error line.

**Batch Fix All (Pro):**
- Open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`)
- Run: **`Fixit Pro: Fix All Errors in File (Pro)`**

**Toggle Inline Diagnostics:**
- Command Palette → **`Inline Diagnostics: Toggle On/Off`**

---

## 💎 Pricing & Licensing

| Tier | Price | Features |
|---|---|---|
| **Free** | ₹0 / $0 | Inline diagnostics + 3 AI quick fixes |
| **Pro (Lifetime)** | **₹499** (India) / **$15** (International) | Unlimited fixes + Batch Fix All |

### 🌍 Buy a License

- **🇮🇳 India (UPI / Card):** [Buy for ₹499 on Razorpay](https://rzp.io/rzp/nEbFc22y) 
- **🌍 International (Card / PayPal):** [Buy for $15 on Dodo Payments](https://checkout.dodopayments.com/buy/pdt_0NoHGurewXj7eD4Vci7gS?quantity=1) 

### 🔑 How to Activate Your License

After purchasing, you will receive an email receipt. **Reply to that email with your GitHub username** to receive your unique license key within 24 hours.

Once you have your key:

1. Open VS Code Settings (`Ctrl+,` / `Cmd+,`).
2. Search for **`licenseKey`**.
3. Paste your key into the **`Inline Diagnostics: License Key`** field.
4. Reload VS Code.
5. Enjoy unlimited AI fixes and Batch Fix All! 🎉

---

## 🛠️ Configuration

| Setting | Default | Description |
|---|---|---|
| `inlineDiagnostics.enabled` | `true` | Enable/disable inline diagnostics |
| `inlineDiagnostics.maxMessageLength` | `80` | Maximum characters per diagnostic message |
| `inlineDiagnostics.fontSize` | `0.85em` | Font size of inline messages (e.g., `12px`) |
| `inlineDiagnostics.errorColor` | `#ff6b6b` | Color for error messages |
| `inlineDiagnostics.warningColor` | `#ffa94d` | Color for warning messages |
| `inlineDiagnostics.infoColor` | `#74c0fc` | Color for info messages |
| `inlineDiagnostics.hintColor` | `#a9e34b` | Color for hint messages |
| `inlineDiagnostics.enabledSeverities` | `[0,1,2,3]` | Which severities to show (0=Error, 1=Warning, 2=Info, 3=Hint) |
| `inlineDiagnostics.licenseKey` | `""` | Your Pro license key (leave empty for free tier) |

---

## 🔒 Security & Privacy

- Fixit Pro **does not** collect any telemetry or personal data.
- AI requests are handled entirely through your existing GitHub Copilot subscription.
- License keys are validated locally using **RSA-2048 cryptographic signatures** — no server calls, no data leaves your machine.
- Your license key is stored only in your local VS Code settings.

---

## 🤝 Contributing

Contributions are welcome! If you find a bug or have a feature request:

1. Check the [existing issues](https://github.com/Bangera854/fixit-pro-kryzen/tree/main/ISSUE_TEMPLATE) to avoid duplicates.
2. Open a new issue with a clear title and description.
3. For pull requests, please:
   - Fork the repository.
   - Create a feature branch (`git checkout -b feature/my-feature`).
   - Commit your changes (`git commit -m 'Add my feature'`).
   - Push to the branch (`git push origin feature/my-feature`).
   - Open a Pull Request.

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 💬 Support

- 🐛 **Bug Reports:** [Open an issue](https://github.com/Bangera854/fixit-pro-kryzen/tree/main/ISSUE_TEMPLATE)
- 💡 **Feature Requests:** [Start a discussion](https://github.com/Bangera854/fixit-pro-kryzen/blob/main/ISSUE_TEMPLATE/feature_request.md)
- 📧 **License Issues:** Reply to your purchase receipt email.

---

## ⭐ Show Your Support

If Fixit Pro saves you time, please:
- ⭐ **Star this repository** on GitHub
- ⭐ **Leave a review** on the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=KRYZEN.inline-diagnostics-kryzen)

---

**Made with ❤️ by [KRYZEN](https://github.com/Bangera854)**

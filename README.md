# 🔮 Magic 8 Ball — Support

> Support page and documentation for the **Magic 8 Ball** iOS app.  
> The oracle is always listening. Shake your iPhone and find out.

---

## 🌐 Support Website

The support page is hosted via GitHub Pages at:

```
https://tgpm5yshnm-ui.github.io/-Magic-8-Ball-Support/
```

It includes:
- App feature overview
- Frequently asked questions
- Live contact form (powered by EmailJS)

---

## 📱 About the App

**Magic 8 Ball** brings the classic fortune-telling experience to life with features only your iPhone can deliver.

| Feature | Description |
|---|---|
| 📳 Shake to Reveal | Uses CoreMotion to detect a real physical shake — no buttons needed |
| 🎙️ Voice Input | Hold the mic button and speak your question live using Apple's Speech framework |
| 🔮 Color-Coded Answers | Inner eye glows green (positive), amber (neutral), or red (negative) |
| 📳 Haptic Feedback | Layered haptics make every shake feel satisfying |
| ☕️ Tip Jar | In-app purchases via StoreKit 2 — Kind Soul ($0.99), True Believer ($1.99), Cosmic Patron ($4.99) |

---

## 🛠 Tech Stack

- **SwiftUI** — UI framework
- **CoreMotion** — Physical shake detection via accelerometer
- **Speech + AVFoundation** — Live voice transcription (on-device)
- **StoreKit 2** — Consumable in-app purchases with Face ID / Touch ID
- **UIKit Haptics** — `UIImpactFeedbackGenerator` and `UINotificationFeedbackGenerator`

---

## ❓ FAQ

**The shake isn't being detected.**  
Hold the phone naturally and give it a firm, short jolt (like shaking a cocktail). The threshold requires ~2.5g of acceleration.

**The microphone button isn't working.**  
Go to **Settings → Privacy & Security → Microphone** and enable Magic 8 Ball. Also enable **Speech Recognition** in the same menu.

**My purchase didn't go through.**  
If the Apple payment sheet closed without a confirmation, you were not charged.

**Which iOS version is required?**  
iOS 16 or later. Compatible with iPhone 8 and newer.

---

## 📬 Contact

Use the contact form on the support page, or reach out directly via the GitHub Issues tab.

For refunds and billing, all purchases are handled by Apple:  
👉 https://reportaproblem.apple.com


## 📄 License

© 2026 All rights reserved.

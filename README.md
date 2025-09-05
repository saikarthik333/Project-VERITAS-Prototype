# Project VERITAS: A Digital Trust Layer for the Securities Market

**Submission for the Securities Market Hackathon 2025**

---

## 🎯 The Problem

Retail investors are increasingly targeted by sophisticated fraud, including:
* Deepfake videos of corporate leaders announcing fake news.
* Impersonation of registered advisors on social media.
* Pump-and-dump schemes orchestrated via WhatsApp and Telegram.
* Forged documents promising guaranteed IPO allotments.

These scams erode investor trust and cause significant financial harm.

---

## ✨ The Solution: Project VERITAS

Project VERITAS is a prototype for a new, proactive security layer for the Indian securities market. Instead of trying to detect fakes, we focus on **verifying authenticity**.

The concept is simple: Every official communication from a SEBI-registered entity (companies, advisors, etc.) is digitally signed. Our "Investor Shield" tool allows anyone to instantly verify the authenticity of these communications, rendering forgeries and impersonations ineffective.

---

## 🚀 Live Demo Prototype

This prototype demonstrates the core "Sign & Verify" loop of the VERITAS ecosystem.

* **Live Signer Page:** **[https://saikarthik333.github.io/Project-VERITAS-Prototype/signer.html](https://saikarthik333.github.io/Project-VERITAS-Prototype/signer.html)**
* **Live Verifier Page:** **[https://saikarthik333.github.io/Project-VERITAS-Prototype/verifier.html](https://saikarthik333.github.io/Project-VERITAS-Prototype/verifier.html)**

#### **How to Use the Demo:**

1.  **Open the Signer Page:** Act as a CEO or advisor. Type an official message and click "Sign & Generate Token".
2.  **Copy the Token:** Copy the entire block of text (the "Verifiable Token") that is generated.
3.  **Open the Verifier Page:** Now, act as a retail investor. Paste the token into the text box and click "Verify Authenticity".
4.  **See the Result:** The tool will instantly confirm if the message is authentic ✅ or if it has been tampered with ❌.

---

##  envisioning The Future

This simple prototype represents a scalable vision:

* **Browser Extension:** A real-world tool would automatically place a green checkmark next to verified information online.
* **Regulatory Mandate:** SEBI could mandate this for all registered entities, creating a nationwide "safe space."
* **API Integration:** Brokerage apps like Zerodha and Groww could integrate this to flag unverified news and tips directly on their platforms.

---

## 🛠️ Technology Stack (Prototype)

* **Frontend:** HTML5, CSS3, JavaScript
* **Cryptography:** `jsrsasign` library for in-browser Elliptic Curve Digital Signatures (ECDSA).
* **Hosting:** GitHub Pages

# 🕵️ Scam & Phishing Investigation Unit

An AI-powered phishing detection web application designed as an interactive digital investigation case file.

Instead of displaying a plain AI response, the application presents every analysis as an official investigation report complete with case numbers, evidence markers, risk scores, and archived case history.

## Preview

The application allows users to investigate:

- 📩 Emails
- 💬 SMS/Text Messages
- 🌐 Websites

Each submission receives:

- Risk score (0–100)
- Verdict (Safe / Caution / Scam Likely)
- Investigation summary
- Detailed evidence markers
- Recommended action
- Archived case history

---

## Features

### 📁 Case File Interface

A detective-inspired UI styled like an official investigation folder.

- Auto-generated case numbers
- Investigation status
- Rubber-stamp verdict animation
- Evidence report layout

---

### 🤖 AI Scam Analysis

Uses Anthropic Claude to inspect submitted content for phishing indicators including:

- Urgency tactics
- Fake sender identities
- Lookalike domains
- Credential theft attempts
- Suspicious links
- Requests for payments
- OTP/password harvesting
- Grammar inconsistencies
- Brand impersonation
- Too-good-to-be-true offers

---

### 📊 Risk Assessment

Each investigation produces:

- Scam probability score
- Verdict classification
- Investigation headline
- Plain-English explanation
- Evidence markers
- Recommended next steps

---

### 📂 Persistent Case History

Every completed investigation is stored locally.

Features include:

- Archived cases
- Reopen previous reports
- Investigation timestamps
- Clear history option

---

### 🎨 Immersive Experience

The interface includes:

- Manila-folder aesthetic
- Typewriter typography
- Rubber stamp verdict animation
- Investigation progress animation
- Evidence cards
- Risk meter

---

## Built With

- HTML5
- CSS3
- Vanilla JavaScript
- Anthropic Claude API

---

## How It Works

1. Choose the evidence type.
2. Paste a message, email, or website content.
3. Open a new case.
4. AI analyzes the evidence.
5. Receive a full investigation report.

---

## Live Preview

https://scam-detector.netlify.app/

---

## Project Structure

```
index.html
│
├── HTML
├── CSS
├── JavaScript
└── Claude API Integration
```

---

## Future Improvements

- Screenshot analysis
- URL reputation lookup
- Email header analysis
- Attachment scanning
- Dark mode
- Export investigation reports as PDF
- Multi-language support

---

## Disclaimer

This application provides AI-assisted guidance and should not be considered definitive proof that a message is legitimate or fraudulent.

Always verify sensitive requests independently before sharing personal information, passwords, or making financial transactions.

---

## Author

**Atharva Abhijit Deshmukh**

Designed and developed as an AI-powered cybersecurity project focused on phishing awareness and scam detection.

---

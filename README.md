# AIris – Smarter Vision for Safer Clicks
AIris is a lightweight, AI-powered mobile security application that detects malicious and suspicious URLs in real-time. It provides privacy-first, on-device protection to help users avoid phishing and harmful links across apps.

---
## Problem Statement

Mobile users are increasingly exposed to malicious links through messaging apps, emails, and social media platforms.

## Existing solutions:

- Depend heavily on cloud-based checks
- Offer limited offline protection
- Lack real-time cross-app monitoring
- Consume high device resources
- Provide poor explanation for non-technical users

There is a need for a **lightweight, real-time, privacy-friendly, mobile-first security solution that works even offline**.

---
## Solution

 - On-device AI-based URL detection
 - Offline heuristic threat analysis
 - Cross-app link monitoring
 - Real-time alerts before link access
 - Google Safe Browsing API integration (optional online verification)
 - Secure encrypted local scan logs
 - Interactive dashboard for history tracking

---

# How It Works

1. A link is clicked or entered.
2. AIris captures the URL.
3. The on-device ML model analyzes URL patterns.
4. Heuristic rules check for suspicious indicators.
5. (Optional) Safe Browsing API verifies the link online.
6. User receives an instant safety alert.
7. Result is stored securely in encrypted local storage.
8. Dashboard displays scan history and insights.

---

## Input

URL entered manually
URL detected via Accessibility Service

### Example:

http://secure-login-update.xyz

---

## Output
### Safe Link
- Status: Safe
- Confidence Score: 91%
- Reason: No suspicious patterns detected.

### Suspicious / Malicious Link
- Status: Suspicious
- Confidence Score: 85%
### Reasons:
- Suspicious domain structure
- Presence of phishing keywords
- Flagged by threat intelligence API
---
## System Architecture

User Click → URL Captured → On-Device ML Model → Heuristic Engine → (Optional API Check) → Alert → Encrypted Storage → Dashboard

---
# Key Features

- Real-time background scanning
- Offline AI detection
- Cross-app monitoring
- Lightweight and mobile-optimized
- Secure encrypted local database
- Community threat reporting (optional)
- Simple, clean dashboard

---
# Tech Stack
### Frontend

- Flutter
- Jetpack Compose

### AI / Machine Learning

- NLP-based URL pattern analysis
- Logistic Regression / Random Forest
- TensorFlow Lite (on-device inference)

### Backend

- Firebase Realtime Database
- Firebase Authentication (optional)

### Security

- Room Database
- Encrypted local storage

### APIs

- Google Safe Browsing API

---

## 👥 Team:

```
Hannah Daniel

Doshi Sayali

Hrishita Dey P

Shabista Sehar
```

---
 > Every Click. Verified.

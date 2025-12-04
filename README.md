ThreatLens :

Real-Time Voice Phishing Detection & Prevention System > Built for the 8th Mile X Overnight Hackathon by Team Tech Titans



The Problem: The Security Gap in UPI

Despite advanced banking security, India lost over ₹1,000 Crores to UPI fraud recently.

The Blind Spot: Banking apps see the transaction amount, but they are deaf to the coercion happening over the phone call before the PIN is entered.

The Threat: "Digital Arrests," fake rewards, and fear tactics exploit the irrevocable nature of UPI.

The Gap: Traditional Fraud Risk Management (FRM) is reactive. It flags transactions too late.

The Solution: Threat Level Detection (TLD) Engine

ThreatLens is a privacy-preserving mobile application that shifts defense from reactive monitoring to proactive communication intelligence. We stop the fraud during the call, not after the money is gone.

Key Features :

1. Automated Intervention: Instant, "Zero-Click" system-level call termination when a Maximum Threat is detected.

2. AI Voice Scanner: Real-time spectral analysis to flag synthetic and deepfake voices invisible to the human ear.

3. Dynamic Risk Scoring (DRSM): Aggregates linguistic urgency, impersonation markers ("CBI", "Police"), and context to calculate a threat score with 96% accuracy.

4. Community Threat Registry: Decentralized intelligence that instantly shares confirmed scammer patterns across the network.

5. System Architecture: Privacy by Design

We prioritize user privacy. Sensitive conversation data never leaves the device.

On-Device AI Processing: Raw audio is processed locally using mobile-optimized models (TensorFlow Lite) to extract features.

Gemini 1.5 Flash: Used for low-latency, multimodal reasoning on anonymized text data to detect complex intent.

Federated Learning: Model refinement happens across devices without centralizing raw user data.

Tech Stack :

Native Android (Kotlin) / React Native

AI/LLM

Google Gemini 1.5 Flash, TensorFlow Lite

Backend

Firebase (Real-time DB), Node.js Cloud Functions

Integrations

Android Telecom API, Bank Sandbox APIs

Alerts

Twilio / Exotel

Screenshots :









Dashboard

Active Threat Intervention

(Upload your app screenshots to an assets folder and link them here)

Installation & Setup

Clone the repo

git clone (https://github.com/splb1822/Overnight-Hackathon-Tech-Titans-)

Add API Keys

Create a local.properties file in the android root.

Add your Gemini API Key: GEMINI_API_KEY=your_key_here

Add Firebase configuration files (google-services.json).

Build

Open in Android Studio.

Sync Gradle and Run on an emulator/device (API Level 28+ required for Telecom API features).

Team Tech Titans

Vidit Singhal - Team lead

Sumukh Shetty - Development Head

Shlok Patel - Assistant developer 

Rudra Singh : Assistant developer 

Made with ❤️ and ☕ at 8th Mile X Overnight Hackathon.

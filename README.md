# 🛡️ CyberShield – Surprise-Based Social Engineering Awareness Platform

> **Testing Human Security in Real Conditions — Built for Ethiopia**

**CyberShield** is a realistic, AI-powered simulation platform that conducts **unannounced phishing, ransomware, voice scams, and red-team attacks** to test how employees and IT teams truly react when they believe an attack is real.

Designed by Ethiopian students for Ethiopian institutions, CyberShield addresses the critical gap between **theoretical training** and **real-world cyber readiness** — especially in government, banking, education, and healthcare.

🎯 *Mission:* Turn human vulnerability into human defense through **ethical surprise testing**, **localized awareness**, and **data-driven improvement**.

---

## 🔍 Why CyberShield?

In Ethiopia, digital transformation is accelerating — but **security culture is lagging**.  
Despite growing cyber threats, most organizations:
- Rely on outdated, one-time security training.
- Never test their teams with realistic attacks.
- Have no way to measure who clicks, who panics, and who reports.

Worse: **real hackers don’t warn their victims.**  
So why should security tests?

> 🔎 **CyberShield simulates real attacks — without prior notice — to reveal true organizational readiness.**

---

## 🎯 Objectives

1. **Test Real Behavior**  
   - Launch unannounced phishing, fake ransomware, and voice scams.
   - Measure click rates, reporting speed, and panic responses.

2. **Challenge IT Teams**  
   - Simulate covert C2 callbacks, log tampering, and malware beacons.
   - Evaluate SOC detection capabilities under surprise conditions.

3. **Improve Cyber Resilience**  
   - Deliver personalized feedback and gamified training.
   - Reduce human risk through repeated drills.

4. **Support Compliance**  
   - Generate audit-ready reports aligned with **INSA**, **NIST**, and **ISO 27001**.

---

## 🚀 Key Features

| Feature | Description |
|-------|-------------|
| **Unannounced Phishing** | AI-generated emails (Amharic & English) sent without warning. Tracks opens, clicks, and reports. |
| **Fake Ransomware Popup** | Harmless Electron.js popup mimicking WannaCry. Logs user reaction: pay, panic, or report? |
| **Bait Document Traps** | Decoy files (e.g., “Confidential_Budget.xlsx”) with hidden trackers. Alerts if opened/copied. |
| **Voice Clone Scams (Vishing)** | AI-generated audio: “This is IT — your system is infected.” Tests emotional manipulation. |
| **Stealth Red-Team Beacons** | Simulated malware "phoning home" to test SOC detection of outbound traffic. |
| **Live Admin Dashboard** | Real-time view of attack progress. No visibility for employees until debrief. |
| **Gamified Debrief Portal** | Post-test training with badges, leaderboards, and personalized feedback. |

---

## 🧪 Methodology: Realism Through Surprise

### Phase 1: Research & Authorization (2 Weeks)
- Partner with a willing organization (e.g., university, bank).
- Obtain **written approval from management**.
- Define scope: departments, roles, attack types.

### Phase 2: Covert System Setup (4 Weeks)
- Deploy backend (Flask + SQLite).
- Plant bait documents in shared drives.
- Configure tracking and phishing engine.

### Phase 3: AI Attack Generation (3 Weeks)
- Fine-tune **Mistral-7B** for realistic Amharic/English emails.
- Use **ElevenLabs API** for AI voice scams.
- Schedule attacks at realistic times (e.g., Monday morning).

### Phase 4: Surprise Testing (2 Weeks)
- Launch **3 unannounced attack waves**:
  1. Phishing + bait document
  2. Fake ransomware popup
  3. Voice scam + C2 beacon
- Collect behavioral data in real time.

### Phase 5: Debrief & Reporting (1 Week)
- Conduct **group debrief session**.
- Deliver **personalized feedback** and training.
- Generate **executive report** with risk scores and recommendations.

---

## ⚖️ Ethical & Legal Safeguards

We follow a strict ethical framework to ensure **responsibility, transparency, and dignity**:

| Principle | Implementation |
|---------|----------------|
| **Management Consent** | Full approval required before any test. |
| **No Real Harm** | All simulations are harmless. No real malware or data theft. |
| **Post-Test Transparency** | All participants are debriefed — never shamed. |
| **Anonymized Reporting** | Individuals hidden; only role/department shown. |
| **Right to Opt-Out** | High-risk roles (e.g., mental health) may be excluded. |

> ✅ This is **not a prank** — it’s a **professional security assessment**.

---

## 📊 Expected Outcomes

| Metric | Baseline | Target After 3 Drills |
|-------|---------|------------------------|
| Phishing Click Rate | 60–80% | ≤ 30% |
| Ransomware Panic | 70% | ≤ 20% |
| Reporting Time | 2+ hours | < 10 minutes |
| IT Detection Rate | < 40% | > 80% |

> 🌍 Goal: Scale to **Ethio Telecom, Commercial Bank of Ethiopia, Ministry of Health**, and beyond.

---

## ⚙️ Tech Stack

| Layer | Technology |
|------|-----------|
| **Frontend** | React.js (Dashboard), Electron.js (Ransomware Popup) |
| **Backend** | Python (Flask), SQLite |
| **AI** | Mistral-7B (Text), ElevenLabs (Voice) |
| **Tracking** | UUID logging, IP/device fingerprinting |
| **Deployment** | Docker (On-premise) — ideal for air-gapped or low-connectivity environments |

---

## 🗓️ Timeline 

| Phase | Duration |
|------|---------|
| Covert System Setup | 4 Weeks |
| AI Attack Design | 3 Weeks |
| Surprise Testing | 2 Weeks |
| Debrief & Final Report | 1 Week |

---

 Ethiopia’s digital future — one simulation at a time.**  
> _"Train like you fight. Fight like you train."_

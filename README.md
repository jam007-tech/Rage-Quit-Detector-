# Rage Quit Detector

> *"The seatbelt for digital communication."*
> *"The goal isn't to block communication — it's to create space for better decisions."*

**Rage Quit Detector** is an on-device AI browser extension and mobile app that detects emotional spikes from typing behavior and intercepts high-risk digital actions before they happen — protecting careers, relationships, and portfolios from impulsive communication.

---

## The Problem

We've all been there. A stressful moment, a furious reply, a panic trade — and the regret that follows. This is the **Amygdala Hijack Problem**: the brain's emotional system overrides rational judgment, and digital actions become irreversible in milliseconds.

| Stat | Source |
|------|--------|
| **88%** of professionals regret sending an email in the past year | Babbel, 2024 |
| **1.5%** annual underperformance for retail investors who trade emotionally | Industry data |
| **0** proactive enterprise HR tools exist to prevent problematic communication before it happens | Market gap |

**Why Now:** On-device ML (Apple Neural Engine, Google Tensor) now enables privacy-preserving keystroke analysis with zero data leaving the device. Twitter's 2021 "review before you send" experiment proved that adding friction reduces regrettable replies by **34%**.

---

## How It Works

```
Emotional Spike Detected
        ↓
On-device ML classifies emotional state (<50ms)
        ↓
Cooldown Lock activates (send button disabled)
        ↓
AI Rewrite Suggestion offered
        ↓
Regret Score updated
```

The entire pipeline runs **locally on-device** — no message content ever leaves the user's device.

---

## Core Features

### 1. Emotion Engine
Real-time behavioral signal detection using:
- **Typing Speed Spike** — WPM surge above 200% of user baseline
- **Caps Ratio** — more than 30% all-caps text
- **Punctuation Density** — more than 3 consecutive exclamation marks
- **Aggressive Vocabulary ML** — classifier flags hostile or impulsive language
- **Device Pressure** — haptic pressure as a secondary signal on mobile

### 2. Cooldown Lock
When the Emotion Engine triggers above threshold, the send button is disabled for a configurable period (default: **10 minutes**). The user can manually override, but the friction is intentional.

### 3. AI Rewrite Suggester
After a cooldown trigger, an AI assistant proposes a calmer, more professional alternative to the original message. Tracks acceptance rate to personalize over time.

### 4. Regret Score & Analytics
- Weekly cooldown summary (triggered vs. sent vs. held)
- Monthly Regret Score ("You avoided 4 career-damaging moments this month")
- Calm Streak Counter for habit formation
- Shareable milestone cards for organic virality

### 5. Team HR Dashboard *(Enterprise/Team tiers)*
- Aggregate stress trends across teams
- Manager dashboards with burnout-risk indicators
- Shared communication safety settings

---

## Architecture & Tech Stack

### On-Device ML
| Platform | Framework |
|----------|-----------|
| iOS (15+) | Core ML |
| Android (10+) | TensorFlow Lite |
| Chrome Extension | TensorFlow Lite |

Model size: **under 15MB** | Inference latency: **under 50ms** | Data transmitted: **zero**

### Platform Integrations
| Platform | Integration Method |
|----------|--------------------|
| Gmail | Chrome Extension + Gmail API (compose-window metadata) |
| Outlook | Office Add-In + Microsoft 365 API |
| iOS Messages & Mail | iOS Share Extension |
| Slack | Slackbot + on-device companion app |

---

## Target Users

**Priya, 34 — Senior Product Manager, Noida**
Communicates daily with leadership, clients, and engineers under high pressure. Has sent emails she deeply regrets, including one to her CEO during a performance cycle. Needs an automatic, frictionless safety net. → *Willing to pay: $5–8/month*

**Nirbhay, 29 — Retail Investor, Delhi**
Rs. 40,000 invested across 12 stocks, checks portfolio 8x daily. Lost 18% of his portfolio panic-selling during a dip. Knows emotional trading hurts him but can't stop in the moment. → *Willing to pay: $8–13/month*

**Dr. Sarah, 42 — Hospital Physician, Lucknow**
Manages 6 direct reports under extreme cognitive load. A single heated reply to an administrator resulted in a formal HR inquiry. Needs a system that catches worst moments before they define a career. → *Willing to pay: $10/month personal, or $6/seat via hospital HR budget*

---

## Pricing

| Tier | Price | Best For |
|------|-------|----------|
| **Free** | $0 | Casual professionals & first-time users (5 cooldowns/month) |
| **Pro** | $7/month | High-frequency communicators, managers, founders, PMs |
| **Team** | $12/seat/month | Startups, SMBs, customer-facing organizations |
| **Enterprise** | Custom | Healthcare, legal, finance, enterprise support orgs |

---

## Roadmap

### Phase 1: Private Beta (Months 1–2)
Validate trust, false-positive rate, and behavioral intervention acceptance with early users.

### Phase 2: Public Launch — Chrome + iOS (Month 3)
Launch core Emotion Engine, Cooldown Lock, and Basic Analytics. Validate product-market fit with knowledge workers.

### Phase 3: B2B Expansion (Months 5–6)
Launch Team Dashboard, test organizational communication safety use cases, begin Enterprise sales.

---

## Feature Prioritization (MoSCoW)

| Priority | Feature | Reason |
|----------|---------|--------|
| **MUST** | Zero keystroke data leaves device | Core trust differentiator |
| **MUST** | False positive rate under 5% | Drives immediate churn if failed |
| **MUST** | Emotion Engine accuracy | Core value proposition |
| **MUST** | Multi-platform API coverage | Required from day one |
| **SHOULD** | AI Rewrite Suggester | High perceived value, non-blocking |
| **SHOULD** | Regret Score shareable cards | Organic acquisition driver |
| **COULD** | Team HR Dashboard | Enterprise upsell, post-PMF |
| **WON'T** | Calendar-based send blocking | Nice to have, not now |

---

## North Star Metrics

| Feature | KPI | Stage |
|---------|-----|-------|
| Emotion Engine | False positive rate <5%, cooldowns/user/week >2 | Retention |
| AI Rewrite | Acceptance rate >70%, Free→Pro conversion >8% | Revenue |
| Regret Score | DAU/MAU stickiness, share rate, streak length | Acquisition |

---

## Privacy & Compliance

- **On-device inference only** — no message content transmitted to external servers
- **Open-source model** — auditable by design from Day 1
- **DPDPA 2023 compliant** — behavioral signal detection architected to comply with India's Digital Personal Data Protection Act
- Conservative thresholds and instant manual override to balance safety with urgency

---

## Key Risks & Mitigations

| Risk | Mitigation |
|------|------------|
| Privacy vs. Trust | Open-source model released on Day 1 |
| False Positives blocking urgent sends | Conservative thresholds + instant manual override |
| Platform API dependency | 3 platforms launching simultaneously |
| Regulatory compliance | DPDPA-compliant by design |
| Churn risk | Regret Score streak sustains long-term engagement |

---

## Market Opportunity

| Segment | Size |
|---------|------|
| Total Addressable Market | $70B+ |
| Serviceable Market | $10B+ |
| Knowledge Workers | 420M |
| Retail Investors | 50M |

---

## Author

Aman Mishra
NSUT

---

🚀 GigShield

AI-Powered Parametric Income Protection for India's Food Delivery Workers

Guidewire DEVTrails 2026 — Phase 1 Submission

📌 The Problem

India has 15+ lakh active food delivery workers (Zomato, Swiggy), earning around ₹27,700/month.

But when disruption happens (rain, flood, app outage):

Income becomes zero instantly

No sick leave

No emergency backup

Insurance today covers:

Health (ACKO, PM-JAY)

Accidents (Zomato/Swiggy)

❌ But no one covers income loss due to disruptions

👉 That is where GigShield comes in.

❓ Why Food Delivery (Not E-commerce or Grocery)?

We compared:

| Category      | Exposure | Income Measurement | Fraud Clarity |
| ------------- | -------- | ------------------ | ------------- |
| Food Delivery | Highest  | Direct             | Strong        |
| Grocery       | Medium   | Moderate           | Medium        |
| E-commerce    | Lowest   | Hard               | Weak          |

✅ Food delivery workers are:

Most exposed

Easy to measure

Highly underserved

👤 User Persona

Ramesh, 26, Mumbai

Earns ₹500–₹900/day

Works 10–14 hours

Uses ₹6k–₹10k Android phone

Lost ₹8k–₹12k last monsoon

Finds insurance claim process too complex

👉 Needs fast, simple payout — not forms.

🏆 Competitor Gap
| Product                 | Covers         | Missing             |
| ----------------------- | -------------- | ------------------- |
| Zomato/Swiggy Insurance | Accident       | ❌ Income loss       |
| ACKO/Digit              | Health         | ❌ Income loss       |
| PM-JAY                  | Health         | ❌ Income loss       |
| Farmer Insurance        | Weather income | ❌ Urban gig workers |

✅ GigShield = Income protection for disruptions

💰 Weekly Premium Model
| Plan    | Deliveries/Week | Premium | Max Payout |
| ------- | --------------- | ------- | ---------- |
| Starter | <50             | ₹29     | ₹800       |
| Regular | 50–100          | ₹49     | ₹1400      |
| Pro     | 100+            | ₹69     | ₹2000      |

Key points:

~1.2% of weekly income

Covers ~33% income loss

Week 1 = ₹29 (Trust Week)

⚡ Parametric Triggers (Auto Payout)

Triggers need 2 data sources:

| Event      | Example           | Payout  |
| ---------- | ----------------- | ------- |
| Heavy Rain | IMD + Weather API | ₹200/hr |
| Red Alert  | Govt + News       | ₹300    |
| Heatwave   | IMD + Weather     | ₹150    |
| Flood      | IMD + Traffic API | ₹350    |
| Curfew     | Govt + News       | ₹250    |
| App Outage | Downdetector      | ₹100    |

👉 Fully automatic, instant UPI payout.

🤖 AI/ML System
1. Risk Scoring

Based on location + 5-year weather data

2. Behaviour Tracking

Work hours

GPS movement

Battery usage

WiFi patterns

3. Claim System

🟢 Green → instant payout

🟡 Yellow → quick verification

🔴 Red → fraud check + partial payout

🛡️ Anti-Fraud System

We detect:

Fake GPS

Fake activity

Suspicious patterns

Real Rider vs Fraud

Real rider:

Movement, weak signal, battery drain

Fraud:

No movement

Stable WiFi

Clean signals

Extra Checks

Time clustering

Network similarity

Account connections

🎯 UX Design Principles

Never block full payout

70% instant, 30% later

Simple, fast process

No complex forms

Human review if needed

🏢 Business Model

GigShield = Technology Platform (B2B2C)

Partner with insurers (ACKO, Digit, SBI General)

We handle:

Risk engine

Fraud detection

User experience

🧑‍💻 Tech Stack
| Layer    | Tech                            |
| -------- | ------------------------------- |
| Frontend | React / Next.js (PWA)           |
| Backend  | Java / Spring Boot              |
| ML       | Python / FastAPI                |
| Database | PostgreSQL + Redis              |
| APIs     | IMD + OpenWeather + AccuWeather |
| Outage   | Downdetector                    |
| Payments | Razorpay UPI                    |
⚙️ Architecture Decision

Java → stable backend

Python → ML models

✅ Microservices = scalable + flexible

📱 Why PWA?

No Play Store needed

Works via link (WhatsApp)

Loads fast

Good for low-end phones

⚠️ Risks & Solutions
| Risk                   | Solution                   |
| ---------------------- | -------------------------- |
| Weather data delay     | Multi-source validation    |
| High claims in monsoon | Reinsurance support        |
| Low-end phones         | Digital fallback signals   |
| Licensing              | Partner with insurer       |
| User trust             | ₹29 trial + instant payout |

🛣️ Roadmap
Phase 1

Research

Architecture

README + Demo

Phase 2

MVP build

Policy system

Fraud detection

Phase 3

Full system

Dashboard

Payment simulation

Final pitch

🎯 Vision

15 lakh riders deserve a safety net when work stops.

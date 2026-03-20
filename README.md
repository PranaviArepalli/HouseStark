# 🏠 HouseStark
### *"Protecting the People Who Keep Your City Moving."*

> **An AI-enabled parametric income protection platform for gig economy delivery workers — built for the disruptions no one plans for.**

<br>

![Status](https://img.shields.io/badge/Status-In%20Development-orange?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)
![Stack](https://img.shields.io/badge/Stack-React%20%7C%20Node.js%20%7C%20Python%20ML-green?style=flat-square)
![Domain](https://img.shields.io/badge/Domain-InsurTech%20%7C%20GigEconomy-purple?style=flat-square)

---

## 📌 Table of Contents

- [Problem Statement](#-problem-statement)
- [Why This Matters](#-why-this-matters)
- [Solution Overview](#-solution-overview)
- [Target Users](#-target-users--persona)
- [Key Features](#-key-features)
- [How It Works](#-how-it-works)
- [AI/ML Integration](#-aiml-integration)
- [Parametric Triggers](#-parametric-triggers)
- [Tech Stack](#-tech-stack)
- [System Architecture](#-system-architecture)
- [Installation & Setup](#-installation--setup)
- [Usage Flow](#-usage-flow)
- [Future Enhancements](#-future-enhancements)
- [Contributors](#-contributors)
- [License](#-license)

---

## 🔴 Problem Statement

India has over **12 million gig delivery workers** operating on platforms like Zomato, Swiggy, Amazon, Zepto, and Dunzo. These workers are the backbone of urban commerce — yet they are among the most financially vulnerable individuals in the economy.

**The hard truth:**

- 🌧️ A heavy rain day means ₹0 income — no rides, no deliveries, no pay
- 🌫️ High pollution days lead to order drops of up to **40%** in affected zones
- 🚫 A local curfew or strike can wipe out an entire week's earnings
- 📉 Workers lose **20–30% of monthly income** due to external disruptions they cannot control
- 🚫 There is currently **no formal income protection system** designed for them

Traditional insurance does not address income loss from environmental or civic disruptions. These workers have no safety net.

---

## 💡 Why This Matters

> *"When a delivery partner can't work because of a storm, their children go hungry. That's not a risk problem — it's a justice problem."*

HouseStark exists to close the protection gap in the gig economy. We are not building another health or vehicle insurance product. We are building a **direct income shield** — triggered automatically, paid instantly, with no paperwork.

This is insurance reimagined for the people most likely to never receive it.

---

## ✅ Solution Overview

HouseStark is an **AI-powered parametric insurance platform** that:

- 🔒 Covers **loss of income only** (not health, vehicle, or accident)
- 📅 Prices risk dynamically with a **weekly premium model**
- ⚡ **Automatically triggers** payouts when verified real-world events occur
- 🤖 Uses **machine learning** to assess individual risk and detect fraud
- 📍 Monitors **hyperlocal conditions** (weather, AQI, civic events) in real time
- 💸 Delivers **instant simulated payouts** directly to the worker's wallet

No claims forms. No phone calls. No waiting.

---

## 👤 Target Users / Persona

### 🛵 Primary Persona: Food Delivery Partner

| Attribute | Detail |
|-----------|--------|
| **Name** | Ravi K. |
| **Platform** | Swiggy / Zomato |
| **Age** | 24–38 |
| **City** | Tier 1 / Tier 2 Indian metros |
| **Income** | ₹15,000 – ₹30,000/month |
| **Work Hours** | 8–12 hours/day, 6–7 days/week |
| **Biggest Risk** | Extreme weather, pollution spikes, curfews, bandhs |
| **Tech Comfort** | Moderate — uses a smartphone daily |

> **Secondary personas** (future scope): E-commerce delivery agents (Amazon, Flipkart, Zepto), hyperlocal grocery partners (Blinkit, BigBasket Now).

---

## 🌟 Key Features

### 🧠 1. AI-Powered Risk Assessment
Personalized weekly premiums are calculated using an ML model trained on historical delivery data, worker behavior patterns, weather trends, and local event databases. Each worker gets a unique risk score — not a generic quote.

### 📅 2. Weekly Dynamic Premium Model
Unlike monthly or annual insurance, HouseStark operates on a **7-day rolling cycle**. Premiums adapt weekly based on forecast risk in the worker's delivery zone. Low-risk week? Lower premium. Cyclone forecast? Higher protection automatically kicks in.

### ⚡ 3. Parametric Claim Automation
No claims officer. No paperwork. When a **verified trigger event** occurs (e.g., rainfall > 40mm in 3 hours in Zone 5), the system automatically validates conditions and initiates payouts for all enrolled workers in that zone — within minutes.

### 🔍 4. Fraud Detection System
An anomaly detection layer monitors claim patterns, GPS delivery data, weather API cross-validation, and behavioral signals. Suspicious claims are flagged and reviewed before payout — protecting the integrity of the fund pool.

### 🗺️ 5. Hyperlocal Risk Heatmaps
An interactive city-level heatmap visualizes **real-time disruption risk by pin code or delivery zone** — powered by live weather APIs, AQI feeds, and civic event data. Workers can see which zones are currently dangerous or high-risk.

### 📲 6. Smart Alerts & Predictive Forecasting
Push notifications warn workers **24–48 hours in advance** about expected weather events, pollution spikes, or civic disruptions. Predictive ML models forecast income impact so workers can plan, save, or opt into additional coverage.

### 📊 7. Earnings Tracker
A built-in weekly earnings dashboard lets workers track income trends, compare disruption-impacted weeks vs. normal weeks, and understand how HouseStark payouts have protected their monthly income.

### 🏅 8. Gamified Reliability Score
Workers build a **Reliability Score** over time based on consistent premium payments, accurate zone reporting, and platform activity. Higher scores unlock lower premiums, bonus payout multipliers, and priority claim processing.

### 💸 9. Instant Payout Simulation
When a claim triggers, the platform simulates an instant payout via integrated payment APIs (UPI / wallet mock). Workers see the credited amount in real time — no delays, no disputes.

---

## 🔄 How It Works

```
STEP 1 — ONBOARDING
Worker registers → links delivery platform ID → completes risk profile

STEP 2 — RISK SCORING
AI model evaluates zone, history, weather outlook, and platform data
→ Generates weekly premium quote (e.g., ₹25–₹80/week)

STEP 3 — ENROLLMENT
Worker reviews and accepts weekly coverage plan
→ Premium auto-deducted via UPI

STEP 4 — REAL-TIME MONITORING
Platform continuously monitors:
  → Weather APIs (IMD, OpenWeatherMap)
  → AQI/Pollution APIs (CPCB, IQAir)
  → Civic event feeds (news APIs, admin alerts)

STEP 5 — TRIGGER DETECTION
When a verified parametric threshold is crossed in a delivery zone:
  → System logs event with timestamp + geolocation
  → Fraud detection layer validates the claim
  → Eligible workers are identified

STEP 6 — AUTOMATIC PAYOUT
Claim approved instantly
  → Worker notified via SMS/app push
  → Payout credited to linked wallet (simulated)

STEP 7 — REVIEW & ADAPT
Worker earnings dashboard updates
  → AI model re-calibrates next week's premium
  → Reliability score adjusts accordingly
```

---

## 🤖 AI/ML Integration

HouseStark embeds intelligence at every layer of the platform:

| Module | AI Application | Method |
|--------|---------------|--------|
| **Premium Engine** | Personalized risk scoring | Gradient Boosted Trees (XGBoost) |
| **Trigger Validation** | Event classification & verification | Rule engine + NLP on news feeds |
| **Fraud Detection** | Anomaly detection on claim patterns | Isolation Forest / Autoencoder |
| **Earnings Forecast** | Weekly income prediction | LSTM Time-Series Model |
| **Risk Heatmaps** | Zone-level disruption likelihood | Spatial clustering + weather fusion |
| **Smart Alerts** | Disruption probability scoring | Logistic Regression + weather API |

**Training Data Sources:**
- Historical weather records (IMD, NASA POWER)
- Delivery platform order volume trends (synthetic / anonymized)
- AQI & pollution data (CPCB)
- Public civic event datasets

---

## ⚡ Parametric Triggers

Claims are triggered **automatically** — no human adjudication required — when verified real-world thresholds are crossed:

| Trigger Type | Example Condition | Payout |
|-------------|-------------------|--------|
| 🌧️ Heavy Rainfall | > 40mm in 3 hrs in delivery zone | 60% of weekly coverage |
| 🌊 Flooding | Zone flood alert issued by municipal body | 80% of weekly coverage |
| 🌫️ Severe Pollution | AQI > 300 for 4+ hours in zone | 40% of weekly coverage |
| 🌡️ Extreme Heat | Feels-like temp > 47°C sustained 6 hrs | 50% of weekly coverage |
| 🚫 Civic Curfew | Official curfew declared (verified) | 100% of weekly coverage |
| ✊ Bandh / Strike | Platform order drop > 70% + event verified | 70% of weekly coverage |
| 🌪️ Cyclone / Storm Alert | IMD red alert in worker's state | 100% of weekly coverage |

> All triggers are **multi-source validated** — at least 2 independent data sources must confirm before a claim fires.

---

## 🛠️ Tech Stack

### Frontend
- **React.js** — Component-based UI
- **Tailwind CSS** — Responsive design system
- **Leaflet.js / Mapbox** — Hyperlocal heatmaps & zone visualization
- **Chart.js / Recharts** — Earnings dashboard & analytics

### Backend
- **Node.js + Express** — REST API layer
- **Python (FastAPI)** — ML model serving
- **PostgreSQL** — Worker data, claims, premiums
- **Redis** — Real-time event caching & alert pub/sub

### AI/ML
- **Python** (scikit-learn, XGBoost, TensorFlow/Keras)
- **Pandas / NumPy** — Data processing pipelines
- **Jupyter Notebooks** — Model development & evaluation

### Integrations & APIs
- **OpenWeatherMap / IMD API** — Real-time weather data
- **IQAir / CPCB API** — Air quality index
- **News API / Google Alerts** — Civic disruption detection
- **Razorpay / UPI Mock API** — Simulated instant payouts
- **Firebase / Twilio** — Push notifications & SMS alerts

### DevOps
- **Docker** — Containerization
- **GitHub Actions** — CI/CD pipeline
- **AWS / Vercel** — Deployment

---

## 🏗️ System Architecture

```
┌──────────────────────────────────────────────────────────────────┐
│                        HOUSESTARK PLATFORM                       │
├─────────────────────────┬────────────────────────────────────────┤
│      FRONTEND (React)   │         BACKEND SERVICES               │
│  ┌─────────────────┐    │  ┌──────────────┐  ┌────────────────┐ │
│  │ Worker Dashboard │    │  │ Auth & Worker│  │  Premium       │ │
│  │ Heatmap Viewer   │◄──►│  │ Profile API  │  │  Engine (ML)   │ │
│  │ Earnings Tracker │    │  └──────────────┘  └────────────────┘ │
│  │ Alert Center     │    │  ┌──────────────┐  ┌────────────────┐ │
│  └─────────────────┘    │  │  Trigger      │  │  Fraud         │ │
│                          │  │  Monitor      │  │  Detection     │ │
├──────────────────────────┤  └──────────────┘  └────────────────┘ │
│   EXTERNAL DATA FEEDS    │  ┌──────────────────────────────────┐  │
│  • Weather APIs          │  │        Claims Automation          │  │
│  • AQI / Pollution       │◄─┤  Validate → Approve → Payout     │  │
│  • Civic Event Feeds     │  └──────────────────────────────────┘  │
│  • Platform Order Data   │  ┌──────────────────────────────────┐  │
└──────────────────────────┘  │     Payment Gateway (Mock)        │  │
                              │   UPI / Wallet Simulation         │  │
                              └──────────────────────────────────┘  │
```

---

## 🚀 Installation & Setup

> ⚠️ **Note:** This project is under active development. The setup below reflects the planned local development environment.

### Prerequisites
- Node.js v18+
- Python 3.10+
- PostgreSQL 14+
- Docker (optional but recommended)

### 1. Clone the Repository
```bash
git clone https://github.com/your-org/housestark.git
cd housestark
```

### 2. Install Frontend Dependencies
```bash
cd client
npm install
npm run dev
```

### 3. Install Backend Dependencies
```bash
cd server
npm install
npm run start
```

### 4. Set Up ML Services
```bash
cd ml
pip install -r requirements.txt
uvicorn app:app --reload --port 8000
```

### 5. Configure Environment Variables
```bash
cp .env.example .env
# Add your API keys:
# WEATHER_API_KEY, IQAIR_API_KEY, RAZORPAY_KEY, DB_URL, etc.
```

### 6. Run with Docker (Recommended)
```bash
docker-compose up --build
```

---

## 🧭 Usage Flow

```
1. 📱 Worker downloads app / visits web portal
        ↓
2. 🔐 Registers with phone number + delivery platform ID
        ↓
3. 🤖 AI generates personalized weekly risk score & premium quote
        ↓
4. ✅ Worker opts into weekly coverage plan (₹25 – ₹80/week)
        ↓
5. 📡 Platform begins real-time monitoring of worker's zone
        ↓
6. 🔔 Worker receives smart alert: "Heavy rain forecast tomorrow"
        ↓
7. ⚡ Trigger threshold crossed → auto-claim validated
        ↓
8. 💸 Payout credited to worker's UPI wallet instantly
        ↓
9. 📊 Dashboard updates: earnings protected, reliability score +
        ↓
10. 🔄 Cycle resets — new premium calculated for next week
```

---

## 🔮 Future Enhancements

- [ ] 🌐 **Multi-persona support** — Expand to e-commerce, grocery, and ride-hailing workers
- [ ] 🏦 **BNPL Premium Model** — Buy Now Pay Later for premium payments via NBFC partnerships
- [ ] 🤝 **Platform API Integration** — Direct data feeds from Swiggy/Zomato for income verification
- [ ] 🔗 **Blockchain Claim Ledger** — Immutable, transparent payout records via smart contracts
- [ ] 🌍 **Rural Expansion** — Adapt parametric model for agricultural income protection
- [ ] 📣 **Community Fund Pool** — Peer-to-peer micro-insurance pools for worker collectives
- [ ] 🏥 **Add-on Modules** — Optional bundled health micro-insurance at discounted rates
- [ ] 📈 **Regulator Dashboard** — Compliance and reporting tools for IRDAI sandbox readiness
- [ ] 🗣️ **Vernacular Support** — Full app experience in Hindi, Tamil, Telugu, Kannada

---

## 👥 Contributors

| Role | Name | GitHub |
|------|------|--------|
| Founder / Product Lead | _Your Name_ | [@yourgithub](#) |
| Backend Engineer | _Contributor_ | [@placeholder](#) |
| ML Engineer | _Contributor_ | [@placeholder](#) |
| Frontend Engineer | _Contributor_ | [@placeholder](#) |
| Design Lead | _Contributor_ | [@placeholder](#) |

> 🤝 Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a pull request.

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<br>

<div align="center">

**Built with ❤️ for the 12 million delivery workers who keep India running.**

*HouseStark — Because income protection shouldn't be a luxury.*

</div>

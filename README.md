<div align="center">

  <h1>BlinkZo 🚀</h1>
  <p><strong>Plan the moment. Shop smarter. Split fairly. Remember the experience.</strong></p>
  <p><em>The First Intent-Driven Occasion Operating System — Built at Eternal's SwiftDidLoad 2026</em></p>

  <!-- BADGES -->
  <p>
    <img src="https://img.shields.io/badge/Platform-iOS_18%2B-000000?style=for-the-badge&logo=apple&logoColor=white" alt="Platform iOS" />
    <img src="https://img.shields.io/badge/Swift-6.0-F05138?style=for-the-badge&logo=swift&logoColor=white" alt="Swift" />
    <img src="https://img.shields.io/badge/UI-SwiftUI-007AFF?style=for-the-badge&logo=swift&logoColor=white" alt="SwiftUI" />
    <img src="https://img.shields.io/badge/AI-Foundation_Models-00C853?style=for-the-badge&logo=apple&logoColor=white" alt="Foundation Models" />
    <img src="https://img.shields.io/badge/Architecture-MVVM_%2B_Observation-FF4081?style=for-the-badge" alt="Architecture" />
  </p>

  <p>
    <a href="#-the-problem--philosophy">Philosophy</a> •
    <a href="#-app-screenshots">Screenshots</a> •
    <a href="#-core-features">Core Features</a> •
    <a href="#-technical-architecture">Architecture</a> •
    <a href="#-getting-started">Getting Started</a> •
    <a href="#-team-peak-performers">Team</a>
  </p>
</div>

---

## 💡 The Problem & Philosophy

Today, grocery and food delivery apps ask a single question: **"What do you want to buy?"**

Because of this product-first approach, planning any occasion—or even restocking monthly household essentials—becomes deeply fragmented. Users are forced to manually browse category by category, cross-check their home pantry, calculate guest quantities, coordinate orders across apps, and manually split expenses.

**BlinkZo flips the paradigm:**

> *"People don't think in products. They think in moments."*

Instead of asking what items you want to add to a cart, BlinkZo asks: **"What are you trying to accomplish?"**

| ❌ Before BlinkZo (Fragmented Utility) | ✅ With BlinkZo (Connected Occasion OS) |
| :--- | :--- |
| Search category-by-category for hours | Express a single intent (*"Hosting dinner tomorrow"*) |
| Overbuy items already sitting in your kitchen | **Smart Fridge** cross-checks inventory automatically |
| Forget essential ingredients & monthly staples | **1-Tap Monthly Ration** learns & restocks household needs |
| Guess food quantities for large groups | **Compass AI** calculates exact portions with transparent math |
| Blindly divide bills using $\frac{\text{Total}}{N}$ | **Split Together** separates personal vs. shared items fairly |

---

## 📱 App Screenshots

<div align="center">
  <img src="binkzoapp.png" alt="BlinkZo App Screens — Contextual Home, Occasion Planner & Event Timeline, Split Together" width="100%" style="border-radius: 14px; box-shadow: 0 8px 30px rgba(0,0,0,0.12);" />
</div>

<br />

| Screen | Core Purpose | Key Highlights |
| :--- | :--- | :--- |
| **01 — Contextual Home** | Proactive Dashboard | Dynamic prompt cards (*"You're hosting dinner tomorrow. Your pantry already contains pasta and olive oil. Only 6 ingredients are needed"*), 12-minute ultra-fast delivery awareness, voice search, and 1-tap quick actions. |
| **02 — Occasion Planner** | Event & Timeline Companion | Bundled occasion curation (*Drinks, Desserts, Appetizers, Decor*), dynamic **Event Timeline** (`10:00 AM Morning Prep`, `02:00 PM Setup Venue`, `04:47 PM Guests Arrive`), and transparent AI reasoning (`12 Adults + 4 Kids`). |
| **03 — Split Together** | Collaborative Cart & Settlement | Real-time shared shopping rooms via QR/links, automated categorization of **Shared Essentials** vs. **Personal Requests**, and fair bill settlement. |

---

## 🌟 Core Features

### 1. 🏠 HOME — The Contextual Dashboard
The Home screen isn't a static directory of aisles; it is an active intelligence dashboard that understands your upcoming moments and pantry state.
* **Proactive Insights:** Displays actionable cards like: *"You're hosting dinner tomorrow. Your pantry already contains pasta and olive oil. Only 5 ingredients are needed."*
* **12-Min Instant Context:** Combines ultra-fast local delivery awareness with voice-enabled search, smart suggestions, and 1-tap access to **Planner**, **Smart Fridge**, and **Split Together**.

### 2. ✨ OCCASION PLANNER — The Compass Engine
Instead of starting with a blank search bar, start with an intention (*Birthday, Dinner Party, Movie Night, House Party*).
* **Categorized Bundles:** Automatically curates holistic event needs across **Appetizers, Drinks, Desserts, and Decor** (e.g., *"Hydration station setup with sparkling water and fresh juices for the kids"*).
* **Chronological Event Timeline:** Turns a delivery app into an event companion by structuring your day:
  * `10:00 AM` — **Morning Prep:** Receive groceries and marinate appetizers.
  * `02:00 PM` — **Setup Venue:** Arrange indoor seating and dining area.
  * `04:47 PM` — **Guests Arrive:** Serve welcome drinks and light snacks.
* **Transparent AI Reasoning:** Never wonder *why* an item is in your cart. BlinkZo explicitly displays the reasoning behind its math (e.g., scaling quantities specifically for `12 Adults + 4 Kids`).

### 3. 🧊 SMART FRIDGE — 1-Tap Monthly Ration & Pantry Intelligence
Manually going through every grocery category each month is exhausting, time-consuming, and leads to forgotten essentials.
* **1-Tap Monthly Ration (Foundation Models):** Powered by Apple's Foundation Models, Smart Fridge continuously learns your household's consumption rate and monthly needs over time. Restock your entire month's ration in **one single tap**.
* **Inventory States:** Tracks *Fresh Items*, *Expiring Soon* (waste risk alerts), and *Running Low* staples.
* **Pantry-to-Recipe Sync:** Suggests meals based on what you already own and lets you add *only* the missing ingredient with a single tap.

### 4. 💸 SPLIT TOGETHER — Collaborative & Fair Expense Splitting
Group grocery runs shouldn't end in awkward math or unfair $\frac{\text{Total}}{N}$ splits.
* **Live Shopping Room:** Create or join a group via Share Link, QR Code, or Nearby Share. Watch teammates add or cross off items in real time.
* **Fair Split Intelligence:** Automatically classifies cart items into **Shared Essentials** (divided among the group) and **Personal Requests** (assigned strictly to the individual who added them), accounting for dietary rules and discounts.

### 5. 👤 PROFILE — The Personalization Loop
Your profile isn't a dead-end settings page; it actively governs the entire app's intelligence.
* **Dietary Constraints & Macros:** Track **Protein Goals**, **Fruit & Veg servings**, and tags like `Vegetarian` or `Gluten-Free`.
* **System-Wide Filtering:** Setting `Vegetarian` in Profile automatically configures the Occasion Planner menu, filters Smart Fridge recipes, and adjusts Split Together calculations.

---

## 🏗 Technical Architecture

BlinkZo is engineered as a modern, modular, Apple-native application built from the ground up using **SwiftUI**.

```text
                         ┌─────────────────┐
                         │     BLINKZO     │
                         │   User Context  │
                         └────────┬────────┘
                                  │
                                  ▼
                         ┌─────────────────┐
                         │      HOME       │
                         │ Smart Dashboard │
                         └────────┬────────┘
                                  │
                    ┌─────────────┼─────────────┐
                    │             │             │
                    ▼             ▼             ▼
             ┌────────────┐ ┌───────────┐ ┌─────────────┐
             │  OCCASION  │ │  FRIDGE   │ │   SPLITTER  │
             │   PLANNER  │ │   INTEL.  │ │ COLLABORATE │
             └─────┬──────┘ └─────┬─────┘ └──────┬──────┘
                   │              │              │
                   ▼              ▼              ▼
                PLAN          UNDERSTAND       SHARE
                   │              │              │
                   └──────────────┼──────────────┘
                                  ▼
                              SHOPPING
                                  │
                                  ▼
                              CHECKOUT
                                  │
                                  ▼
                           FAIR SETTLEMENT
                                  │
                                  ▼
                            COMPLETE EVENT
                                  │
                                  ▼
                           LEARN & PERSONALIZE
```

### 🛠 Tech Stack & Frameworks
* **UI Framework:** `SwiftUI` (Dark-mode-first aesthetic, custom glassmorphic cards, fluid `NavigationStack` transitions, dynamic haptics).
* **State Management:** Apple's modern `Observation` framework (`@Observable`) for zero-lag reactive UI updates.
* **Concurrency:** `Swift Concurrency` (`async/await`) for non-blocking AI reasoning, cart calculations, and split analysis.
* **On-Device Intelligence:** `Foundation Models` framework architecture for contextual occasion reasoning, 1-tap ration learning, and fair split evaluation.
* **Persistence & Ecosystem Readiness:** Designed with `SwiftData`-ready models and `App Intents`-ready services for Siri and system-level shortcuts.

### 📂 Project Structure
```text
BlinkZo/
├── App/
│   └── BlinkZoApp.swift
├── Core/
│   ├── Models/
│   │   ├── User.swift
│   │   ├── Occasion.swift
│   │   ├── PantryItem.swift
│   │   ├── ShoppingGroup.swift
│   │   └── Settlement.swift
│   └── Services/
│       ├── FoundationModelService.swift
│       ├── OccasionPlanningService.swift
│       ├── PantryAnalysisService.swift
│       └── SplitCalculationService.swift
├── Features/
│   ├── Home/
│   │   ├── Views/HomeView.swift
│   │   └── ViewModels/HomeViewModel.swift
│   ├── OccasionPlanner/
│   │   ├── Views/ (OccasionHome, AIPlanView, TimelineCard...)
│   │   └── ViewModels/ (OccasionViewModel, PlanningViewModel)
│   ├── SmartFridge/
│   │   ├── Views/ (FridgeHome, PantryOverview, RestockView...)
│   │   └── ViewModels/ (FridgeViewModel, RestockViewModel)
│   ├── ExpenseSplitter/
│   │   ├── Views/ (ExpenseHome, ShoppingRoom, AISplit, SplitSummary...)
│   │   └── ViewModels/ (ExpenseViewModel, AISplitViewModel)
│   └── Profile/
│       └── Views/ProfileView.swift
└── SharedUI/
    └── Components/ (PrimaryButton, TimelineCard, InsightCard, MemberAvatar...)
```

---

## 🚀 Getting Started

### Prerequisites
* **macOS:** Sequoia or later
* **Xcode:** Xcode 16.0+ / Xcode 26+ (with iOS SDK support)
* **Target:** iOS 18.0+ Simulator or Physical iPhone

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Praneelpandey/BlinkZo.git
   cd BlinkZo
   ```
2. **Open in Xcode:**
   ```bash
   open BlinkZo.xcodeproj
   ```
3. **Build and Run:**
   * Select your target simulator (e.g., **iPhone 16 Pro**) or physical device.
   * Press `Cmd + R` to compile and launch **BlinkZo**.

---

## ⚡ Team Peak Performers

Built during a 24-hour sprint at **SwiftDidLoad 2026** (Eternal's invite-only iOS Hackathon in Delhi), representing **Parul University, Vadodara**.

* **Praneel Pandey** — *iOS Architecture, SwiftUI Engineering & Product Strategy*
* **Arpita Mishra** — *UI/UX Design, Human-Centered Research & Product Narrative*
* **Sharma Hemant Kumar** — *Data Modelling, State Management & Core Services*

### 🙏 Acknowledgements
A special thank you to the **Eternal** team (Zomato, Blinkit, District, Hyperpure, Bistro) for hosting an unforgettable developer experience, and to **Parul University**, **Prof. Umang Panchal** (Apple Certified Trainer), and **Dr. Vaibhav Gandhi** for their mentorship and support.

---

<div align="center">
  <p><strong>BlinkZo</strong> — <em>One occasion. One journey. One intelligent companion.</em></p>
</div>

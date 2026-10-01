# 📖 WSO2 APIM 4.7 & MI 4.5 Mobile Cookbook & Field Manual

> **Live Website:** 👉 **[https://fard1n.github.io/wso2-cookbook/](https://fard1n.github.io/wso2-cookbook/)**  
> Optimized for reading on mobile phones, tablets, and desktop browsers with zero external script or font dependencies.

---

## 📱 Mobile-Friendly Documentation Suite

This repository hosts the official developer field manual, security cookbook, and architectural references for **WSO2 API Manager 4.7** and **Micro Integrator (MI) 4.5**.

| Guide | Description | Live Link |
|---|---|---|
| 📖 **APIM 4.7 Cookbook** | Developer manual, OAuth2, live JWT anatomy, API Keys, SSL trust lesson (`900900`), and portal UI walkthroughs. | [Read Cookbook](https://fard1n.github.io/wso2-cookbook/) |
| 📘 **Portals Architecture Guide** | Comprehensive guide to the 4 portals (`/publisher`, `/devportal`, `/admin`, `/carbon`), wizards, policies, and Gateway internals. | [Read Portals Guide](https://fard1n.github.io/wso2-cookbook/wso2-portals-guide-book.html) |
| 📗 **Practitioner Field Manual** | 12-chapter textbook covering Kind A vs Kind B, Data Services XML (`.dbs`), URL math, and HA failover. | [Read Field Manual](https://fard1n.github.io/wso2-cookbook/working-with-wso2-book.html) |
| ⚡ **Interactive Architecture Flow** | Interactive simulation of packet flows, sticky sessions, round robin, Event Hub (`9711`), and node failover. | [Open Simulator](https://fard1n.github.io/wso2-cookbook/architecture-flow-interactive.html) |

---

## ✨ Features Built for Phone Reading

- 📱 **Responsive App Bar & Slide-in Drawer**: Hamburger menu (`☰`) with touch-friendly navigation drawer. Tapping any section scrolls smoothly and closes the drawer automatically.
- 📋 **1-Click Code Copy**: Touch-friendly copy buttons on all curl snippets, JWT payloads, and configuration XML.
- 🌓 **Dark & Light Mode**: Instant toggle saved to local storage, respecting system appearance.
- 🔠 **Font Size Adjuster**: `A-` / `A+` controls to adjust text sizing for comfortable reading anywhere.
- 📊 **Touch-Scroll Tables**: Tables wrapped in responsive overflow containers so column layouts never break or blow out mobile screen widths.
- ⚡ **Zero External CDN Dependencies**: 100% self-contained vanilla HTML/CSS/JS. Loads instantly on mobile networks.
- 📚 **Integrated Book Switcher**: Top navigation bar allows jumping between all 4 documentation volumes with one tap.

---

## 📑 Cookbook Table of Contents

1. **Foundations**: Portals Architecture & Developer Portal Navigation
2. **Security & Core Concepts**:
   - What is OAuth 2.0? (The Core Principle & 4 Actors)
   - Consumer Key vs Consumer Secret Demystified
   - Access Tokens & Inside a Live JWT (Header, Payload, Signature)
   - OAuth 2.0 vs API Keys: The Definitive Comparison
   - The `900900` Error & The SSL Trust Chain Mystery (`client-truststore.jks`)
   - Type 1 (Kind B / MI) vs Type 2 (Kind A / Go Microservice)
3. **Developer Portal (`/devportal`) Walkthrough**:
   - APIs Catalog & Details View
   - Applications & Team Sharing
   - Subscriptions & Throttling Tiers
   - Production vs Sandbox Keys
   - The "Generate Access Token" Modal Walkthrough
   - API Console (Try Out Swagger UI) & The 3 Common Traps
4. **Publisher Portal (`/publisher`) Walkthrough**:
   - Micro Integrator (MI) Service Catalog
   - Operations Configuration & The `/*` Wildcard Trap
   - Working Copy vs Revisions (Why Publish was Greyed Out)
   - Endpoints Configuration & Base URL Suffix Rule
   - Lifecycle States & Deployment Promotion
5. **Reference**: Complete UI & Security Dictionary

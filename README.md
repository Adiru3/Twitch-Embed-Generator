# Twitch Embed Generator 🌟

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Deployed-brightgreen)](https://pages.github.com/)
[![Twitch API](https://img.shields.io/badge/Twitch-API-9146FF)](https://dev.twitch.tv/docs/embed)
[![Pure JavaScript](https://img.shields.io/badge/Pure-JavaScript-F7DF1E)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

> A sleek, ready-to-deploy web application for creating embeddable Twitch.tv player links with zero backend requirements.

## ✨ Live Demo & Quick Start

**Live Demo**: https://adiru3.github.io/Twitch-Embed-Generator/

**One-Click Test** (replace `CHANNEL_NAME`):


### 🚀 5-Second Deployment
1. **Create** a new GitHub repository
2. **Copy** the [`index.html`](https://github.com/your-username/twitch-embed-generator/blob/main/index.html) code into your repository
3. **Enable** GitHub Pages in repository Settings → Pages
4. **Done!** Your generator is live at `https://your-username.github.io/repo-name`

## 🎯 What This Tool Does

This web application solves a common problem: **creating standalone, embeddable Twitch player pages** without needing backend infrastructure. Simply enter any Twitch channel name, and instantly get a shareable URL with a fully functional Twitch player embedded.

## ✨ Key Features

| Feature | Description | Benefit |
|---------|-------------|---------|
| **🎮 Instant Channel Embedding** | Enter any Twitch channel, get live player immediately | No technical knowledge needed |
| **🔗 Smart URL Parameters** | Direct links via `?channel=CHANNEL_NAME` parameter | Shareable, bookmarkable links |
| **📱 Fully Responsive Design** | Adapts perfectly to desktop, tablet, and mobile | Use anywhere, on any device |
| **📋 One-Click Link Copying** | Copy generated embed URL with a single click | Easy integration into other tools |
| **⚡ Zero Backend Required** | 100% HTML/CSS/JavaScript - deploys anywhere | Free hosting on GitHub Pages |
| **🔄 Real-time URL Updates** | Browser history updates without page reloads | Smooth user experience |

## 🛠️ Technical Implementation

### Architecture Overview
```mermaid
graph TD
    A[User Input/URL Parameter] --> B{Channel Name}
    B --> C[Twitch Player API v1.js]
    C --> D[Embed Player Creation]
    D --> E[Shareable URL Generation]
    E --> F[Copy to Clipboard]
    
    style A fill:#9146FF,color:#fff
    style F fill:#28a745,color:#fff

# OneDay Memory - Website Project Guide

**Note:** The source code for the official website is maintained in a separate repository: `OneDayMemory-Web`. This document serves as a strategic guide and reference for the website's purpose and content direction.

## 1. Project Overview
The `OneDayMemory-Web` project is the official public face of the OneDay Memory iOS application. It serves as the central hub for marketing, compliance, and user support.

- **Repository:** (Link to your OneDayMemory-Web repo, e.g., `https://github.com/username/OneDayMemory-Web`)
- **Live URL:** (Link to your live site, e.g., `https://onedaymemory.app` or `username.github.io/OneDayMemory-Web`)

## 2. Core Objectives
The website fulfills three critical roles required for App Store distribution and user acquisition:

1.  **Compliance Hub:** Hosts the mandatory Privacy Policy and Support URL required by Apple App Store Connect.
2.  **Marketing Landing Page:** Acts as a showcase for the app's features ("Echoes of Time", "Curate Stories") to drive downloads via organic search (SEO) and direct sharing.
3.  **Support Center:** Provides users with FAQ and contact channels for troubleshooting.

## 3. Design Philosophy & Aesthetic
The website follows a **Minimalist / Apple-esque** design language to mirror the iOS app's native look and feel.

- **Visual Style:** Clean typography (San Francisco font stack), ample whitespace, high-quality imagery, and subtle animations.
- **Tone of Voice:** Nostalgic yet modern, professional, and privacy-focused.
- **Primary Colors:**
  - Blue: `#007AFF` (Action buttons, links)
  - Text: `#1d1d1f` (Headers)
  - Background: `#ffffff` / `#f5f5f7` (Sections)

## 4. Content Structure
The website is a static site (HTML/CSS) consisting of three primary pages:

### 4.1 Home (`index.html`)
- **Hero Section:** App Icon, strong value proposition slogan ("Rediscover your memories..."), and "Download on the App Store" badge.
- **Features:** 3-4 key selling points (Time Travel, Privacy, curation) with icons.
- **Footer:** Copyright and navigation links.

### 4.2 Privacy Policy (`privacy.html`)
- **Purpose:** Legal disclaimer detailing data handling (Local storage, iCloud sync, no third-party tracking).
- **Maintenance:** Must be updated whenever the app's data collection practices change.

### 4.3 Support (`support.html`)
- **Purpose:** Troubleshooting and contact information.
- **Key Content:** FAQ section (common issues like sync, permissions) and a support email address.

## 5. Maintenance Guidelines for Team/AI
When modifying or discussing the website context:

- **Do not mix code:** Website HTML/CSS should strictly remain in the `OneDayMemory-Web` repo.
- **Sync Content:** Ensure that feature descriptions on the website match the latest App Store release notes.
- **Privacy Updates:** If the iOS app adds new permissions (e.g., HealthKit, Notifications), the `privacy.html` on the website MUST be updated immediately.

---
*This document is for internal reference to align development and marketing efforts.*

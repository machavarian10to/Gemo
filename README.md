<div align="center">

<img src="./gemo-logo.png" alt="Gemo Logo" width="80" />

# Gemo

**The food community where great recipes find great people.**

Share recipes, discover new dishes, earn rewards, and grow alongside a community of passionate food lovers.

[![Live App](https://img.shields.io/badge/Live-App-orange?style=for-the-badge)](https://gemo.app)
![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript)
![Supabase](https://img.shields.io/badge/Supabase-Backend-3ECF8E?style=for-the-badge&logo=supabase)

</div>

---

## What is Gemo?

Gemo is a social platform built around food. Users post recipes (called **Gems**), react to others' content, join communities around food interests, earn XP and coins through engagement, and unlock premium features as they grow. It combines the social dynamics of a content platform with a gamified progression system and AI-powered recipe tools.

> _"Earn your rank. Unlock real features."_

---

<!-- ## Screenshots

> _Add screenshots to a `docs/screenshots/` folder and update the paths below._

| Feed | Gem Creation | Profile |
|------|-------------|---------|
| ![Feed](docs/screenshots/feed.png) | ![Create](docs/screenshots/create.png) | ![Profile](docs/screenshots/profile.png) |

| Communities | Wallet | Discover |
|------------|--------|---------|
| ![Communities](docs/screenshots/communities.png) | ![Wallet](docs/screenshots/wallet.png) | ![Discover](docs/screenshots/discover.png) |

--- -->

## Features

### 🍽️ Gems (Posts)

The core content unit on Gemo is a **Gem** — a recipe post that comes in three forms:

- **Plates** — Photo-based recipe posts with rich text, multiple images, and hashtags
- **Bites** — Short video recipes (MP4/MOV) with thumbnails and descriptions
- **Polls** — Interactive polls with up to 10 options, optional images per option, and configurable durations (1 hour to 1 week)

All gem types support:
- Posting to your personal feed or a **community**
- Tagging official **pages** (restaurants, chefs, brands)
- `@mention` autocomplete in content
- **Scheduling** to publish at a future time _(Chef level and above)_
- **Boosting** to push a gem to the top of followers' feeds for 24 hours or 7 days

---

### 🌍 Feed & Discovery

- **Home Feed** — Infinite-scroll feed of gems from followed users and communities, with a stories bar at the top
- **Discover** — Algorithm-curated feed of trending gems and featured creators
- **Trending** — Top gems and trending hashtags updated in real time
- **Hashtag Pages** — Browse all gems tagged with `#anything`
- **Video Hub** — Dedicated page for video gems with an immersive player
- **Search** — Find users, hashtags, and pages instantly

---

### 👥 Communities & Pages

**Communities** are topic-focused groups (e.g. "Healthy Meal Prep", "Italian Cuisine Lovers"):
- Public or private visibility
- Any member can invite others
- Dedicated gem feed per community
- Up to 3 communities free, unlimited with Pro

**Pages** are official profiles for restaurants, chefs, food blogs, and brands:
- 8 page categories (Restaurant, Chef, Food Blog, Brand, and more)
- Multiple admins and authors
- Followers receive feed updates

---

### 📖 Stories

Ephemeral 24-hour content, similar to Instagram Stories:
- Image, video, text, and poll story types
- Accessible from the stories bar on the home feed
- Reactions and replies

---

### 💬 Social Interactions

- **Reactions** — Emoji reactions on gems (Pro users can set a custom emoji)
- **Double-tap to react** — Double-click/tap any gem card to instantly react with ❤️
- **Comments & replies** — Threaded comments with `@mention` support
- **Saves** — Bookmark gems to your personal saved collection
- **Following** — Follow creators to populate your feed

---

### 🤖 AI Features

- **Pantry** — Enter ingredients you have on hand; AI suggests recipes you can make right now
- **Daily Meal Plan** — AI generates a full-day plan (breakfast, lunch, dinner) tailored to your diet profile
- **AI Recipe Saves** — Save AI-generated recipes to your personal collection

> Free users get 1 AI pick per day. Pro users get 3 picks per day and full-day meal plans.

---

### 🏆 Levels & XP

Engagement earns XP. XP unlocks levels with real feature gates — not cosmetic-only.

| Level | XP Required | Key Perks |
|-------|------------|-----------|
| 🥣 Newbie | 0 | Posting, reacting, commenting, 1 saved recipe/day |
| 🍴 Foodie | 1,500 | Pin 1 gem, +50 coin reward |
| 👨‍🍳 Chef | 6,000 | Pin 3 gems, schedule posts, longer bio, +200 coins |
| 🍳 Master Chef | 20,000 | Gem analytics, profile visitor tracking, co-author gems, +500 coins |
| 🌟 Legendary | 50,000 | Verified badge eligible, +100 coins/month, host challenges, VIP support, +2,000 coins |

---

### 🪙 Coins & Shop

Coins are the in-app currency — **scarce by design** to keep them meaningful.

**Ways to earn coins:**
- Daily check-in (3 coins, with streak bonuses up to 200 coins for long streaks)
- Milestones: reactions received, followers gained, comments received
- Level-up rewards (50–2,000 coins per level)
- Pro subscription (2× coin multiplier on all activity)

**Spend coins in the Shop:**

| Category | Examples |
|----------|---------|
| 🎨 Customization | Profile hover card styles, app themes |
| 🚀 Boosters | Gem boost (24h / 7d), profile spotlight, XP & coin multipliers |
| 🔔 Sounds | Notification sounds — Kitchen Bell, Sizzle Pop, Chef's Whistle, Golden Chime |
| 🖼️ Backgrounds | 8 full app themes with light & dark variants |
| ⭐ Exclusive | Featured creator slots, community spotlight, priority support, early access |

---

### 💎 Gemo Pro

A subscription for users who want more depth.

| Feature | Free | Pro |
|---------|------|-----|
| AI picks per day | 1 | 3 |
| AI meal plan | Single meal | Full day |
| Saved recipes | 20 | Unlimited |
| Communities | 3 | Unlimited |
| Coin earning rate | 1× | 2× |
| Custom emoji reaction | ✗ | ✓ |
| Pro badge on profile & posts | ✗ | ✓ |
| Ad-free browsing | ✗ | ✓ |
| Early access to new features | ✗ | ✓ |
| 7-day free trial | ✓ | — |

---

### 🔔 Notifications

- **Live alerts** — Real-time toasts for reactions, comments, follows, mentions, coin earnings, and community invites
- **Notification history** — Full history panel accessible from the navbar
- **Per-gem muting** — Silence notifications for individual gems you don't want to track

---

### 🌐 Languages

Gemo is available in four languages, auto-detected from browser settings:

| Language | Code |
|----------|------|
| English | `en` |
| Georgian | `ka` |
| Russian | `ru` |
| Spanish | `es` |

---

### 🎨 Themes & Personalisation

- **8 purchasable app themes** — Amethyst, Ocean, Jade, Ruby, Aurora, Sunset, Galaxy, Meadow
- **Light & dark mode** for every theme
- **Profile hover card styles** — Glass, Aurora, Neon, Flip
- **Custom notification sounds** — Choose your alert tone
- **Achievement badges** — 6 automatic badges awarded for milestones (Early Supporter, Recipe Master, Food Scientist, Pro Creator, Verified Chef, Diamond Creator)

---

## Tech Stack

### Languages

| | |
|---|---|
| **TypeScript 5** | Primary language — strict typing throughout |
| **TSX / JSX** | React component markup |
| **SQL** | Supabase (PostgreSQL) schema and row-level security policies |

### Frontend

| Library | Purpose |
|---------|---------|
| [React 18](https://react.dev) | UI framework |
| [Vite 5](https://vitejs.dev) | Build tool & dev server |
| [Tailwind CSS 3](https://tailwindcss.com) | Utility-first styling |
| [shadcn/ui](https://ui.shadcn.com) | Accessible component system (Radix UI based) |
| [Framer Motion](https://www.framer.com/motion/) | Animations & transitions |
| [Lucide React](https://lucide.dev) | Icon library |
| [react-router-dom 6](https://reactrouter.com) | Client-side routing |
| [Embla Carousel](https://www.embla-carousel.com) | Touch-friendly carousels |
| [Recharts](https://recharts.org) | Analytics charts |
| [react-day-picker](https://react-day-picker.js.org) | Calendar date picker |
| [react-image-crop](https://github.com/DominicTobias/react-image-crop) | In-browser image editing |
| [html2canvas](https://html2canvas.hertzen.com) | Canvas / screenshot capture |
| [vaul](https://vaul.emilkowal.ski) | Drawer & sheet animations |
| [cmdk](https://cmdk.paco.me) | Command palette |

### State & Forms

| Library | Purpose |
|---------|---------|
| [Zustand 5](https://zustand-demo.pmnd.rs) | Global state management |
| [React Hook Form](https://react-hook-form.com) | Form handling |
| [Zod](https://zod.dev) | Schema validation |

### Backend & Infrastructure

| Service | Purpose |
|---------|---------|
| [Supabase](https://supabase.com) | PostgreSQL database, Auth, Realtime subscriptions, File storage |

### Internationalisation

| Library | Purpose |
|---------|---------|
| [i18next](https://www.i18next.com) | i18n core framework |
| [react-i18next](https://react.i18next.com) | React bindings |
| [i18next-browser-languagedetector](https://github.com/i18next/i18next-browser-languageDetector) | Auto language detection |

### Notifications

| Library | Purpose |
|---------|---------|
| [Sonner](https://sonner.emilkowal.ski) | Toast notifications |

---

## How to Use Gemo

1. **Sign up** — Create a free account with email or Google at [gemo.app](https://gemo.app)
2. **Set up your profile** — Add a photo, bio, and dietary preferences
3. **Post your first Gem** — Share a recipe as a photo post, video, or poll using the ✨ button
4. **Explore & Follow** — Browse Discover, search hashtags, and follow creators you like
5. **Join Communities** — Find or create communities centred around your food interests
6. **Earn XP & Coins** — React, comment, post, and check in daily to build your rank
7. **Unlock more** — Reach Chef level to schedule posts, or upgrade to Pro for AI meal plans, unlimited saves, and more

---

## Availability

> **This repository is private.** The source code is not publicly available.
>
> To use Gemo, visit **[gemo.lovable.app](https://gemo.lovable.app)** and create a free account — no installation required.

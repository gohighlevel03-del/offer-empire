# Affiliate Empire AI

**The ultimate AI-powered command center for affiliate marketers.**

Affiliate Empire AI is a comprehensive dashboard designed to automate, scale, and optimize every aspect of an affiliate marketing business.

## ⭐ Key Features

### 🎯 Intelligence & Strategy
- **Offer Finder AI**: Uses **Gemini 2.5 Flash** with **Google Search Grounding** to find real-time, high-ticket trending offers across the best platforms to find offers.
- **Hustler Mentor**: A persona-driven AI chatbot (powered by **Gemini 3 Pro**) that offers ruthlessly effective advice for scaling affiliate ventures.
- **Launch Planner**: Generates detailed, step-by-step 30-day launch roadmaps for any niche or product.
- **Compliance Guard**: Analyzes copy and funnels against FTC guidelines and ad network policies to prevent bans.

### 📄 Funnel & Website Builder
- **AI Page Generator**: Instantly generates headlines, sales copy, and HTML structures for Landing Pages, Sales Pages, etc.
- **Drag-and-Drop Interface**: Easily inject elements like Opt-in Forms, Call-to-Action buttons, and placeholder images.
- **SEO Optimization**: Auto-generated meta descriptions for every page.

### 📺 YouTube Automation Agent
- **Trend Research**: Scans the web for viral video topics and niches.
- **Content Studio**:
  - Generates full video scripts (Hook, Value, CTA).
  - **Veo Video Generation**: Creates professional video intros and clips using **Veo 3.1**, with options for **Cinematic Lighting** and **4K Resolution**.
- **Community Manager**: Auto-drafts engaging replies to YouTube comments.

### 🎨 Creative Marketing Lab
- **Veo Studio**: Create video ads from text prompts or animate static images (Image-to-Video).
- **Creative Editor**: Edit ad images using natural language prompts (e.g., "Add a neon glow", "Remove background") powered by **Gemini 2.5 Flash-Image**.
- **Copywriter Pro**: Direct response copywriting for emails, VSLs, and ads using the reasoning power of **Gemini 3 Pro**.

### 💼 Lead Generation
- **Lead Scraper**: Identifies potential B2B leads and business websites using Search Grounding.
- **Empire Wallet**: Tracks revenue, ad spend, and payouts in a unified financial dashboard.

---

## 🛠️ Tech Stack

- **Framework**: React 19
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **AI SDK**: Google Gemini SDK (`@google/genai`)
- **Visualization**: Recharts
- **Icons**: Lucide React

## 🤖 AI Models Utilized

This application uses a multi-model approach to optimize for speed, quality, and cost:

| Feature | Model Used | Reason |
|---------|-----------|--------|
| **Complex Reasoning / Copy** | `gemini-3-pro-preview` | Superior logic for strategy & persuasive writing. |
| **Real-time Data / Search** | `gemini-2.5-flash` | Low latency, grounding capabilities for accurate info. |
| **Video Generation** | `veo-3.1-fast-generate-preview` | State of the art generative video. |
| **Image Editing** | `gemini-2.5-flash-image` | Fast, instruction-based image manipulation. |

---

## 🚀 Getting Started

1. **API Key**: Ensure you have a valid Google Gemini API key.
   - *Note: Veo video generation requires a paid billing project.*
2. **Install**: `npm install`
3. **Run**: `npm start`

## ⚠️ Disclaimer

This tool is for educational and productivity purposes. Always verify AI-generated compliance advice with a legal professional and review generated content before publishing.

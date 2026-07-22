# 🧠 Content Intelligence Studio

> **An AI-powered editorial review platform that analyzes content like a professional editorial board.**
>
> Content Intelligence Studio simulates a panel of specialized AI reviewers that evaluate written and visual content for quality, engagement, clarity, authority, and platform optimization. Designed as a premium single-page web application, it provides creators, marketers, founders, and professionals with actionable insights to improve their content before publishing.

---

# 🚀 Overview

Creating high-quality content consistently is difficult.

Different platforms reward different writing styles, formats, and engagement strategies. Content Intelligence Studio acts as an intelligent AI editorial desk that reviews your content from multiple expert perspectives before it goes live.

Instead of relying on one generic review, the application orchestrates several specialized AI reviewers that independently evaluate your content and then produce a comprehensive editorial report.

The application supports both **text** and **image-based** content including analytics screenshots, thumbnails, transcripts, and social media posts.

---

# ✨ Features

## 📝 Intelligent Content Review

- Analyze LinkedIn posts
- Blog articles
- Twitter/X posts
- Instagram captions
- YouTube scripts
- Marketing copy
- Product launches
- Startup announcements

---

## 🖼 Image Analysis

Supports uploads such as

- Analytics screenshots
- LinkedIn analytics
- Instagram insights
- YouTube thumbnails
- Presentation slides
- Social media graphics

---

## 🤖 Multi-Agent AI Review Workflow

The application creates multiple specialist reviewers including:

- Hook & Opening Analyst
- Authority & Thought Leadership Reviewer
- Storytelling Reviewer
- Platform Optimization Specialist
- Readability Reviewer
- Engagement Reviewer
- CTA Reviewer
- Grammar & Style Reviewer
- Rewrite Generator
- Senior Editorial Reviewer

Each reviewer independently evaluates the content before a final synthesis.

---

## 📊 Detailed Content Scorecard

Provides scores for

- Hook Quality
- Readability
- Authority
- Engagement
- Structure
- Platform Optimization
- CTA Strength
- Overall Content Score

---

## 💡 AI Recommendations

Receive

- Strengths
- Weaknesses
- Missed Opportunities
- Platform-specific improvements
- Better titles
- Better hooks
- Improved formatting
- Content rewrites
- Publishing checklist

---

## 📈 Executive Report

Includes

- Executive Summary
- Content Health Report
- Highest Impact Improvements
- Before vs After Comparison
- AI Performance Estimate
- Future Optimization Prompts

---

# 🎯 Supported Platforms

- LinkedIn
- Twitter / X
- Instagram
- Facebook
- Medium
- YouTube
- Personal Blogs
- Product Hunt
- Startup Landing Pages

---

# 💻 Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Responsive Design
- Dark Mode
- Glassmorphism UI
- CSS Animations
- Fetch API

---

# 🎨 UI Highlights

- Premium SaaS Interface
- Responsive Layout
- Smooth Animations
- Interactive Cards
- Upload Preview
- Live Activity Log
- Reviewer Status Indicators
- Modern Dashboard
- Elegant Dark Theme

---

# 🔄 Workflow

### Step 1

Interview the user

- Content Type
- Platform
- Goal
- Upload Type
- Review Strictness

↓

### Step 2

Upload

- Text
- Images
- Screenshots
- Thumbnails
- Analytics

↓

### Step 3

Assign AI reviewers

↓

### Step 4

Each reviewer analyzes independently

↓

### Step 5

Generate

- Scores
- Insights
- Recommendations

↓

### Step 6

Senior Editor combines all reviews

↓

### Step 7

Final Editorial Report

---

# 📂 Project Structure

```
Content-Intelligence-Studio/
│
├── index.html
└── README.md
```

---

# 📱 Responsive Design

Optimized for

- Desktop
- Laptop
- Tablet
- Mobile

---

# 🎯 Ideal Users

- Content Creators
- LinkedIn Creators
- Founders
- Startup Teams
- Marketers
- Copywriters
- Students
- Freelancers
- Agencies
- Personal Branding Experts

---

# 📸 Example Use Cases

- Review a LinkedIn thought leadership post
- Improve startup launch announcements
- Optimize marketing copy
- Analyze YouTube thumbnails
- Review Instagram captions
- Evaluate analytics screenshots
- Generate stronger hooks
- Rewrite weak CTAs

---

# 📌 Build Constraints

- Single HTML file
- Vanilla HTML
- Vanilla CSS
- Vanilla JavaScript
- No external libraries
- Responsive
- Zero syntax errors
- Commercial-grade UI
- Smooth animations
- Robust error handling
- Loading states
- Retry logic

---

# 🧩 Original Prompt

```text
Content Intelligence Studio

You are an expert content strategist, platform growth specialist, creator coach, behavioral psychologist, prompt engineer, AI systems architect, UX designer, and senior frontend developer.

Interview first, one question at a time, using MCQs only (free text only for a final "Other" option).

What type of content would you like to analyze?
Which platform is it for?
What was your primary goal?
What would you like to upload? (text, image, screenshot, thumbnail, analytics, transcript, etc.)
How critical should the review be?

After the interview, build a polished single-page HTML application called Content Intelligence Studio that acts as an AI content consultant. The app should accept both text and image inputs and analyze them using the Claude Messages API (fetch to https://api.anthropic.com/v1/messages, no key required).

The application should automatically design an intelligent multi-stage review workflow using specialized AI reviewers appropriate for the uploaded content, each with production-quality system prompts. Every insight, score, explanation, and recommendation must come directly from Claude through live API calls. Do not use hardcoded logic, placeholder analysis, canned feedback, or rule-based scoring.

The dashboard should feel like a premium SaaS product, showing upload previews, overall content score, detailed category breakdowns, AI reasoning, strengths, weaknesses, missed opportunities, platform-specific recommendations, rewritten versions, alternative hooks and titles, publishing checklist, live activity log, reviewer status, and a comprehensive final report. If images or screenshots are uploaded, Claude must analyze the visual content directly.

End with an executive summary, content health report, highest-impact improvements, predicted performance potential (clearly presented as an AI estimate), before-vs-after comparison, and further prompts for deeper optimization.

Do not expect JSON format anywhere in order to avoid errors like "expected '{' or '('"

Build constraints:
Single self-contained HTML file using only vanilla HTML, CSS, and JavaScript. No external libraries. Commercial-grade UI/UX, responsive design, dark mode, smooth animations, interactive visualizations, robust error handling, loading states, graceful retry logic, and zero syntax errors.
```

---

# ⚠️ Important Note

The original prompt specifies using the Claude Messages API **without requiring an API key**. However, Anthropic's official Messages API requires authentication using a valid API key and appropriate request headers. As a result, live API calls will fail unless valid credentials are supplied or the application is modified to simulate AI responses locally.

---

# 📄 License

This project is intended for educational, portfolio, and learning purposes.
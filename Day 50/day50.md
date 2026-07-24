# 🛡️ Defend Your Experience

An AI-powered interview preparation platform that helps users confidently defend every claim they make about themselves. Instead of asking generic interview questions, the application extracts meaningful claims from resumes, LinkedIn profiles, portfolios, project documents, and other career materials, then challenges users with adaptive follow-up questions that simulate real interviewer conversations.

The goal is **not to improve a resume**—it's to ensure users can confidently explain and justify every achievement, project, skill, and experience during actual interviews.

---

# 🚀 Features

* 📄 Upload resumes, portfolios, LinkedIn profiles, bios, and project documents
* 🔍 Automatically extract meaningful claims from uploaded content
* 🎯 AI-powered adaptive interview simulation
* 💬 Personalized follow-up questions based on previous answers
* ⚠️ Detect weak claims, vague statements, and unsupported achievements
* 📊 Confidence tracking and answer quality indicators
* 📈 Interactive progress visualization
* 🏆 Final Defence Report with actionable recommendations
* 📂 Session history
* 💾 Local storage support
* 📥 Export interview reports
* 📱 Responsive design
* ✨ Premium glassmorphism dark UI
* 🔄 Graceful fallback handling for temporary API errors

---

# 🎯 How It Works

### 1. Case Intake

Upload your resume, portfolio, or any document describing your experience.

### 2. Claim Extraction

The application identifies every meaningful claim that could be questioned in an interview.

Examples include:

* Projects
* Leadership experiences
* Technical skills
* Certifications
* Academic achievements
* Professional accomplishments

### 3. Cross-Examination

Instead of using a fixed questionnaire, the AI becomes an intelligent interviewer that continuously asks personalized follow-up questions based on the user's responses.

### 4. Defence Report

Receive a comprehensive report highlighting:

* Well-defended experiences
* Weak claims
* Missing evidence
* Confidence scores
* Suggestions for stronger interview responses

---

# 💡 Why This Project?

Many candidates have strong resumes but struggle when interviewers ask:

* "How exactly did you build this?"
* "Can you prove the impact?"
* "What was your contribution?"
* "What was the biggest technical challenge?"
* "Why did you choose this approach?"

Existing interview preparation tools usually ask generic questions.

**Defend Your Experience** focuses entirely on **your own experience**, helping you confidently defend every claim before facing a real interviewer.

---

# 🛠️ Tech Stack

* HTML5
* CSS3
* JavaScript (ES6+)
* Anthropic Messages API
* Local Storage

---

# ✨ Highlights

* Adaptive AI interview flow
* Personalized questioning
* Dynamic claim extraction
* Confidence analytics
* Defence scoring
* Interactive dashboard
* Responsive user interface
* Premium glassmorphism design

---

# 📸 Application Workflow

```
Upload Experience
        │
        ▼
Extract Claims
        │
        ▼
AI Cross-Examination
        │
        ▼
Confidence Analysis
        │
        ▼
Defence Report
```

---

# 🎯 Use Cases

* Software Engineering Interviews
* Campus Placements
* HR Interviews
* Technical Interviews
* Behavioral Interviews
* Internship Preparation
* Portfolio Defense
* Startup Pitch Practice

---

# 📌 Prompt Used

```text
# Defend Your Experience

You are an expert interviewer, recruiter, hiring manager, behavioral psychologist, communication coach, UX designer, and senior frontend developer.

Interview the user first, asking one question at a time and using MCQs whenever possible. Understand what they want to defend, why they are preparing, and the type of audience they expect to face. They may upload a resume, LinkedIn profile, portfolio, bio, project, research, performance review, startup story, freelance work, or any document describing their experience.

Before building the application, determine the user's preferred visual style. If previous conversation memory already indicates their design preferences, use those automatically. Otherwise, ask using an MCQ. Adapt the entire interface, typography, layout, animations, and interactions to that style instead of using a default design.

Generate a premium, fully interactive Defend Your Experience application as a single self-contained HTML file using only HTML, CSS, and JavaScript.

The application should use the Anthropic Messages API directly from the HTML application. Assume it runs inside Anthropic's HTML artifact environment where authentication is handled automatically. Never ask for an API key or build a backend.

Instead of reviewing the uploaded document, extract every meaningful claim and treat it as something that must be defended. Become an intelligent skeptic that continuously challenges the user with personalized follow-up questions generated specifically from their own experience. Every answer should influence the next question, allowing the conversation to naturally become deeper, more specific, and more realistic over time.

The application should feel like an adaptive interview rather than a fixed questionnaire. It should identify weak claims, missing evidence, vague statements, and opportunities to tell stronger stories while helping the user build confidence in defending their own experience. Every challenge and every recommendation should be unique to the uploaded content rather than based on generic interview templates.

Provide meaningful visualizations, progress tracking, confidence indicators, and a final Defense Report that clearly shows which experiences are well defended, which need improvement, and how the user can strengthen them before facing a real interviewer.

Make the purpose immediately obvious to first-time users with clear explanations, intuitive navigation, and helpful empty states. Support drag-and-drop uploads, local storage, session history, exports, responsive design, and graceful fallback handling for temporary API errors such as rate limits.

The objective is not to improve a resume. The objective is to help users confidently defend every claim they make about themselves.

Return only the complete HTML file.
```

---

# 🎓 Learning Outcomes

Through this project, I explored:

* AI-assisted interview preparation
* Adaptive conversational workflows
* Prompt engineering
* Dynamic question generation
* User-centered experience design
* Interactive frontend development
* Progress visualization
* Local data persistence
* AI-driven assessment systems

---

## ⭐ If you found this project interesting, consider giving it a star!

# Compare & Decide Builder

An interactive **Compare & Decide Builder** that researches real-world data, compares multiple options across customizable criteria, and generates a live weighted ranking.

Built as a **single-file HTML application** with no external libraries, designed for decision-making using transparent research, citations, and interactive scoring.

---

## Features

- Interactive comparison dashboard
- Live ranking based on adjustable criteria weights
- Research-backed data with visible citations
- Source transparency panel
- Collapsible "How this was researched" section
- Flags estimated/synthetic values separately from verified data
- Responsive modern UI
- Loading, empty, and error states
- Pure HTML, CSS & JavaScript
- No frameworks or dependencies

---

## Demo Scenario

**Category**
- Cloud Hosting Providers

**Compared Options**
- AWS
- Google Cloud Platform
- Microsoft Azure
- DigitalOcean

**Target Audience**
- Solo developers
- Startups
- Small engineering teams

**Primary Decision**
> Which cloud provider is the best choice for reliable production workloads?

---

## Comparison Criteria

- Pricing
- Compliance & Security Certifications
- Support Quality & Response Time
- Ease of Use & Developer Experience

---

## Research Methodology

The application researches and cites information from trusted sources such as:

- Official documentation
- Pricing pages
- SLA documentation
- Compliance pages
- Independent review websites
- Industry reports

Every displayed value includes:

- Source citation
- Verification status
- Estimate warning (if applicable)

---

## Prompt Used

```text
Compare & Decide Builder

You are an expert research analyst, data journalist, UX designer, and frontend developer.

Before generating anything, interview the user ONE QUESTION AT A TIME in quiz form (MCQs only).

1. What are you trying to decide between? (Ask for the general category, then present four realistic examples of comparable options in that category.)
2. Who is this tool for, and what's the one decision they need to walk away confident about?
3. What criteria matter in this comparison? (Ask for at least four measurable criteria, e.g. cost, time, risk, quality, availability.)
4. Where should the underlying data come from? (Ask the user to name at least two real, citable sources per criterion, or confirm you should research and cite real sources yourself.)
5. Should the user be able to weight criteria by personal priority, or see one fixed ranking?

After collecting the answers:

1. Research and verify real data points for each option against each criterion, using only sources you can name and cite. Do not invent numbers, benchmarks, or scores.

2. Build a premium single-file HTML application (HTML/CSS/JavaScript only, no external libraries) that lets the user adjust criteria weights and see a ranked result update live.

The application should:
- Display a visible sources panel listing every citation used.
- Flag clearly if any data point is an estimate or a synthetic placeholder rather than sourced fact.
- Handle loading states, empty states, and edge cases gracefully.
- Be fully responsive with clean, professional visual design.

3. Add a collapsible "How this was researched" panel explaining where each data point came from and any conflicts between sources you had to resolve.

Generate the complete application only after all interview questions have been answered.

Return ONLY the complete HTML inside one code block.
```

---

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript

---

## Highlights

- Interactive MCQ interview flow
- Dynamic weighted scoring engine
- Research-backed comparisons
- Transparent source attribution
- Responsive premium dashboard
- Single-file architecture
- Offline-capable interface

---

## Use Cases

- Cloud Platform Comparison
- AI Model Comparison
- Laptop Buying Guide
- Programming Language Comparison
- Database Selection
- Hosting Providers
- SaaS Evaluation
- Framework Selection
- Career Decision Support
- Product Comparison Dashboards

---
---

## License

This project is open source and available under the MIT License.
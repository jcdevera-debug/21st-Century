# Jonash De Vera Portfolio Website

## About Me

Hi! I'm **Jonash De Vera**, an Accountancy student, dancer, choreographer, and creative designer passionate about combining storytelling, performance, and visual design. My work reflects a commitment to showcasing both artistic expression and professional growth through meaningful digital experiences.

> **"Driven by purpose, grounded in passion, and constantly evolving."**

---

# Portfolio Website Project

This project is a personal portfolio website designed to highlight my journey as a dancer, choreographer, performer, and student leader. The website presents my story, accomplishments, experiences, and contact information through a visually cohesive and personality-driven interface.

---

## Homepage

![Homepage](./images/homepage.png)

### Reflection
The homepage was designed to establish a strong first impression through bold typography, warm color palettes, and a featured portrait. I wanted visitors to immediately recognize both my creative identity and professional aspirations through a clean yet expressive layout.

---

## My Story

![My Story](./images/my-story.png)

### Reflection
This section focuses on personal storytelling and self-expression. The floral elements, warm colors, and textured background were intentionally selected to create a reflective atmosphere that communicates growth, passion, and authenticity.

---

## 🏆 Projects & Experiences (Major Achievements)

![Projects and Experiences](./images/project-experiences.png)

### Reflection
I organized my major experiences and accomplishments into a structured layout that allows visitors to quickly understand my most significant milestones. The design balances visual appeal and readability to effectively showcase achievements without overwhelming the audience.

---

## Projects & Experiences (Additional Achievements)

![Other Experiences](./images/other-experiences.png)

### Reflection
This section expands on my portfolio by presenting additional experiences that contributed to my development as a performer, leader, and creative individual. Maintaining the same visual language across sections ensures consistency and strengthens the overall branding of the website.

---

## Contact Page

![Contact Page](./images/contact-page.png)

### Reflection
The contact page was designed with simplicity and accessibility in mind. By providing clear communication channels and social media links, visitors can easily connect with me while experiencing a design that remains consistent with the rest of the portfolio.

---

# Design Philosophy

The website combines elegance, creativity, and personal storytelling. Burgundy tones, floral accents, and curated imagery were chosen to reflect passion, artistic expression, and individuality while maintaining a professional and organized presentation.

---

# Technologies Used

- Canva

---

# Author

**Jonash De Vera**

Dancer • Choreographer • Creative Designer

*"Driven by purpose, grounded in passion, and constantly evolving."*





# The Davao SME Tax Compliance Prompt System

> **Role:** Digital Solutions Architect  
> **Client:** Local Government Unit (LGU), Davao City  
> **Focus Area:** Tax Compliance Support for Micro, Small, and Medium Enterprises (MSMEs)

---

## Project Overview

This Prompt Playbook was developed to provide a reusable AI prompt framework that generates localized tax compliance advisories for MSMEs in Davao City. The system aims to eliminate generic or foreign-centered AI outputs by embedding Philippine tax context, regional business conditions, and practical communication standards into the prompt.

---

# 1. System Prompt Template (V3 – Final Optimized)

> **Act as a Senior MSME Tax Compliance Advisor specializing in the Davao Region.**
>
> **Objective:** Draft a 300-word advisory brief that helps Micro, Small, and Medium Enterprises (MSMEs) understand and improve their tax compliance practices.
>
> **Context:** MSMEs in Davao City commonly experience challenges involving bookkeeping, tax filing deadlines, record management, and the adoption of digital tax systems. The audience consists of local business owners with limited accounting backgrounds.
>
> **Constraints:**
> - Use a professional and community-centered tone.
> - Focus exclusively on Philippine tax compliance requirements and local business conditions.
> - Do NOT reference U.S., European, or international tax systems.
> - Explain technical concepts using simple, practical language.
> - Avoid excessive legal or accounting jargon.
> - Promote compliance, transparency, and long-term business sustainability.
>
> **Output Format:**
>
> ```text
> ### Situation Overview
> ### Key Compliance Challenges
> ### Compliance Action Steps
> ```
>
> Under **Compliance Action Steps**, provide **exactly three actionable recommendations**.

---

# 2. Prompt Battle Ledger

| Version | Prompt Modifier Added | Output Quality Reflection |
| :--- | :--- | :--- |
| **V1** | "Write tax advice for small businesses." | Too broad. Generated generic business recommendations and occasionally referenced foreign tax systems that were irrelevant to Philippine MSMEs. |
| **V2** | Added Philippine taxation context, MSME audience, and professional tone. | More relevant, but the recommendations remained generic and lacked localized business conditions. |
| **V3** | Added Davao-specific context, formatting requirements, word limit, and localization constraints. | Successfully produced practical, concise, and regionally relevant tax compliance guidance suitable for MSMEs in Davao City. |

---

# 3. Sample Prompt Execution

## User Input

> Create an advisory for MSMEs in Davao City regarding quarterly tax filing compliance.

---

## AI Output (Excerpt)

### Situation Overview

Many MSMEs in Davao City experience challenges in complying with quarterly tax filing requirements due to limited bookkeeping practices, unfamiliarity with electronic filing systems, and insufficient awareness of filing deadlines.

### Key Compliance Challenges

- Incomplete bookkeeping records
- Missed filing deadlines
- Limited understanding of digital filing platforms

### Compliance Action Steps

1. Maintain updated financial records throughout the quarter.
2. Utilize BIR-approved electronic filing systems to ensure timely tax submissions.
3. Develop a compliance calendar to monitor filing schedules and documentary requirements.

---

# 4. Visual Branding Asset

## Engine Used

- ChatGPT Image Generation (DALL·E)
- Canva Magic Media

---

## Visual Prompt

> Create a flat minimalist vector icon representing SME tax compliance in Davao City. The design should feature a small business storefront integrated with a tax document and a check mark. Use a monoline vector style with a maximum of three colors, no gradients, a white background, and a clean geometric composition. The icon should communicate professionalism, accountability, and local economic development while remaining suitable for LGU reports, presentations, and digital dashboards.

---

## Design Rationale

The storefront represents local MSMEs operating within Davao City. The tax document symbolizes proper record-keeping and regulatory compliance, while the check mark represents accountability and successful adherence to tax obligations. The minimalist vector style ensures the icon remains readable across reports, presentations, websites, and government communication materials.

---

# 5. Reflection

The prompt engineering process demonstrated that introducing localized constraints significantly improved AI-generated outputs. Initial versions produced broad business advice that occasionally referenced foreign taxation systems. By progressively incorporating Philippine tax regulations, defining the intended audience, and embedding Davao-specific business conditions, the final prompt generated practical recommendations that are both relevant and actionable for MSMEs.

This project illustrates how prompt engineering can transform AI into a more reliable communication tool for supporting local government initiatives and regional economic development.

---



# mindanao-crop-production-visual-report
## Project Overview

This project demonstrates an AI-assisted workflow for cleaning and visualizing regional agricultural data to support evidence-based policymaking.

---

## Dataset

**Topic:** Crop Production in Mindanao

**Format:** CSV

---

## Structural Adjustments Performed

The AI performed the following preprocessing steps:

- Removed duplicate observations
- Standardized municipality names
- Converted production values into numeric format
- Removed blank records
- Corrected inconsistent capitalization
- Filled missing values using appropriate interpolation
- Verified column headers

---

## Chart 1: Annual Crop Production Trend


### Analysis

Crop production steadily increased between 2020 and 2023 before declining in 2024. The decrease may reflect weather disturbances affecting agricultural productivity across several Mindanao provinces.

---

## Chart 2: Top Producing Municipalities


### Analysis

The visualization indicates that production remains concentrated in a small number of municipalities, suggesting opportunities for infrastructure investments in emerging agricultural areas.

---

## Human Reflection

The AI significantly reduced the time required for cleaning and organizing the dataset. However, human oversight remained necessary to validate missing values and ensure that data transformations did not distort the original records. The resulting visualizations provide policymakers with a concise representation of production trends while supporting data-driven planning.

---


# mindanao-development-literature-audit
# Literature Verification Log

## Research Topic
Tax Compliance Challenges among SMEs in Mindanao

## Research Objective

This project evaluates the reliability of AI-generated literature summaries by comparing them against verified academic and government sources. The goal is to identify hallucinations, unsupported claims, and potential biases before using the information for policy-related research.

---

## AI Prompt Used

"Generate a literature review on tax compliance challenges among SMEs in Mindanao. Include major themes, statistics, government reports, and academic studies published from 2020 to 2025."

---

## AI-Generated Summary Audit

| AI-Generated Statement / Citation | Source Vetted Against | Status | Human Correction / Empirical Note |
|----------------------------------|----------------------|---------|-----------------------------------|
| SMEs spend 250 hours annually on tax compliance. | World Bank Doing Business Report | ⚠️ Partially Verified | Figure applies to national compliance burden and is not specific to SMEs in Mindanao. |
| Tax complexity is the primary challenge for 78% of SMEs. | DTI MSME Report 2023 | ❌ Hallucination | Statistic not found in source document. |
| Tax literacy affects compliance behavior among SMEs. | Reyes et al. (2022) | ✅ Verified | Supported by findings on taxpayer awareness and compliance. |
| Digital tax filing reduces compliance costs. | BIR Annual Report 2024 | ✅ Verified | Report notes increased adoption of eBIR and online filing systems. |

---

## Literature Matrix

| Author/Source | Year | Key Findings | Relevance |
|--------------|------|-------------|-----------|
| BIR Annual Report | 2024 | Expansion of digital filing systems | Supports modernization efforts |
| DTI MSME Report | 2023 | SMEs experience administrative burdens | Provides policy context |
| World Bank | 2022 | Compliance costs affect small firms | International perspective |
| Reyes et al. | 2022 | Tax knowledge improves compliance | Theoretical support |

---

## Critical Reflection on Tool Limitations

The AI tool significantly reduced the time needed to synthesize multiple sources. However, the verification process revealed several limitations. Some numerical claims could not be traced to any primary source, suggesting possible hallucinations. In addition, the AI occasionally generalized national findings and presented them as specific to Mindanao. These observations highlight the importance of human oversight when using AI-assisted research tools. While AI can accelerate literature discovery and thematic analysis, all empirical claims should be independently verified before inclusion in academic or policy outputs.

---

## Sources Consulted

1. BIR Annual Report 2024
2. DTI MSME Development Report 2023
3. World Bank Doing Business Report
4. Relevant peer-reviewed journal articles

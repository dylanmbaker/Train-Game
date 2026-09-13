URL: https://github.com/codyfarlow1/Senior_Project_1/tree/main

# Senior Project 1 Assignments & FAQ

> **Disclaimers:** 
> - Gemini Generative AI was utilized as an instructional design tool to assist in structuring, formatting, and refining these assignment requirements, FAQs, and sample materials.
> - As an instructor, I can occasionally make mistakes, introduce typos, or overlook specific edge-case details in these documents. If any requirement appears unclear, ambiguous, or contradictory, please do not hesitate to reach out to me directly for clarification—I am always happy to help!

---

## Semester Schedule, Due Dates & Grade Weights Overview

| Deliverable | Week | Target Due Date | Grade Weight |
| :--- | :--- | :--- | :--- |
| **Assignment 1: Project Initiation Foundations** | Week 4 | Sep 13 | 5% |
| **Assignment 2: User Requirements & Ethical Audit** | Week 6 | Sep 27 | 5% |
| **Assignment 3: Architectural Blueprint & Operational Plan** | Week 8 | Oct 11 | 5% |
| **Assignment 4a: Midterm Presentation Slide Deck** | Week 9 | Oct 25 |  |
| **Assignment 4b: In-Class Midterm Presentation Defense** | Week 10 | Oct 30 | 15% |
| **Assignment 4c: Midterm Checkpoint Written Report** | Week 11 | Nov 1 | 15% |
| **Assignment 5: Data Schema, API Contracts, & Final Design Draft** | Week 13 | Nov 15 | 5% |
| **Assignment 6: Production Backlog & Implementation Plan** | Week 15 | Nov 29 | 5% |
| **Assignment 7a: Public Presentation & EOH Defense** | Week 16 | Dec 4 | 30% |
| **Assignment 7b: Final Project Blueprint Report & Artifact** | Week 16 | Dec 6 | 15% |

> **Submission Policy & Work-Life Balance:** All deliverables are targeted for **11:59 PM CT** on the specified date via **Blackboard**. However, I understand that life happens and unexpected challenges can arise. If life gets in the way or you run into severe obstacles, please reach out to me as early as possible rather than overwhelming yourself. I strongly prefer that you communicate when you need help and prioritize submitting high-quality work over rushing a submission—just contact me so we can work out an extension.

---

## Assignment 1: Project Initiation Foundations
* **Grade Weight:** 5%
* **Deliverable Format:** Document Section / APA PDF Submission (part of Midterm compilation)
* **Example Relevant Courses:** COMM 111 (Public Speaking)

### Requirements:
1. **Team Roles & Responsibilities:** Formal organization of team members, assigned leadership/technical roles, and defined individual domain ownership.
2. **Project Brand Kit & Identity Guidelines:** Formal visual and brand specification sheet for the project entity, including official project logo assets, color palette (HEX/RGB codes), typography standards, and brand identity guidelines for marketing and UI/UX consistency.
3. **Repository Setup:** Provisioning and initialization of the official version control environment (e.g., GitHub/GitLab), including `.gitignore`, branch protection rules, and access permissions.
4. **Contribution Guide:** Documentation defining repository workflow standards, branch naming conventions, pull request procedures, code review requirements, and commit message formats.
5. **AI Log & Usage Policy:** Operational tracking system and guidelines documenting approved generative AI tools, transparency protocols, and logged prompts/outputs used during ideation and development.
6. **Market Feasibility Analysis:** Analysis evaluating existing commercial or open-source solutions, target audience identification, competitor analysis, and value proposition mapping.
7. **Project Business Case:**
   * **Introduction:** Problem space statement and project justification.
   * **Customers & Competitors:** Target demographic definition and competitive differentiation.
   * **Innovation & Impact:** Core novelty and expected return on investment (ROI)/impact.
   * **Role Statements:** Formal individual position descriptions.

### Sample AI Log Entries (`AI_LOG.md`):
Below are representative examples of how teams should log generative AI tool usage in their repository:

| Date | Team Member | Tool & Version | Prompt / Query Summary | Output Received & Intended Use | Human Verification & Modifications Made |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **2026-08-28** | Alex Chen | ChatGPT (GPT-4o) | *"Generate 5 competitive analysis dimensions for a real-time web application competing with Jira."* | Outlined feature parity, pricing, API extensibility, and cloud latency. | Selected 3 relevant dimensions; modified feature list to reflect our capstone MVP constraints. |
| **2026-09-02** | Jordan Taylor | Claude 3.5 Sonnet | *"Draft a starter GitHub Actions workflow file for running PyTest on PRs to the main branch."* | Generated a `.github/workflows/test.yml` file with matrix testing. | Fixed Python version targets to match our stack (`3.11`) and added environment variable secrets. |
| **2026-09-05** | Sam Rivera | Gemini 1.5 Pro | *"Help structure a market feasibility section focusing on university student adoption rates."* | Provided an outline covering survey strategies, pain points, and user acquisition. | Rewrote the introductory section using localized survey data collected from campus peers. |

### Frequently Asked Questions & Clarifications:
> **Q: What is expected in the Project Brand Kit for Assignment 1?**  
> **A:** Your Brand Kit establishes a professional identity for your project. Include a clean vector/high-res logo, primary and secondary brand colors with exact color codes (HEX/RGB), selected font pairings for headings and body text, and a brief description of tone/style. This ensures consistent branding across slides, wireframes, posters, and the final application interface.

> **Q: What happens if our team members haven't finalized the exact coding duties yet for Role Statements?**  
> **A:** Focus on domain ownership rather than specific lines of code. Roles should specify who owns areas such as Lead Architecture, Frontend/UX, Backend/Database, or Quality Assurance/CI/CD. Every member must have clear accountability.

> **Q: How detailed does the AI Log need to be? Do we log every query?**  
> **A:** You do not need to log basic syntax searches. You **must** log prompts used for system architecture, algorithm design, starter code generation, or structural content generation. Keep a running `AI_LOG.md` in your repository using the tabular format shown above.

> **Q: Can we change our project idea after submitting Assignment 1?**  
> **A:** Minor pivots are normal, but changing the core concept after Week 4 severely risks your schedule. Any concept shift requires explicit approval from the instructor.

---

## Assignment 2: User Requirements & Ethical Audit
* **Grade Weight:** 5%
* **Deliverable Format:** Document Section / APA PDF Submission (part of Midterm compilation)
* **Example Relevant Courses:** CS 580 (Software Engineering), Phil 354 (Ethics and Computing)

### Requirements:
1. **Target Customer Personas:** Detailed profile representations of intended end-users and primary stakeholders.
2. **Functional Requirements Backlog:** Comprehensive catalog of functional requirements written as standard user stories, complete with clear acceptance criteria and MVP tagging.
3. **Ethical & Legal Compliance Risk Assessment:**
   * Analysis of software engineering ethics related to the product.
   * Assessment of data privacy compliance (e.g., GDPR, HIPAA, COPPA as applicable).
   * Accessibility standards audit (e.g., WCAG compliance targets).
   * Intellectual property (IP) and licensing considerations for third-party tools/libraries.

### Frequently Asked Questions & Clarifications:
> **Q: How many user stories are expected in the backlog?**  
> **A:** Quality and completeness matter over sheer count. Most capstone projects yield 20–30 user stories. Ensure every story follows the format: *"As a [user], I want [feature] so that [benefit]"* and contains measurable Acceptance Criteria.

> **Q: Does every project need HIPAA or COPPA compliance analysis?**  
> **A:** No. Evaluate regulations relevant to your specific domain. If your app handles health data, address HIPAA. If it targets minors, address COPPA. If neither applies, explicitly state why and focus on general data privacy (GDPR/CCPA) and data storage ethics.

> **Q: How do we handle open-source license audits for packages we haven't installed yet?**  
> **A:** Audit the primary frameworks and dependencies you plan to use (e.g., React, PostgreSQL, PyTorch). Ensure you are not pairing copyleft licenses (like GPL) with proprietary code intent without understanding the legal obligations.

---

## Assignment 3: Architectural Blueprint & Operational Plan
* **Grade Weight:** 5%
* **Deliverable Format:** Document Section / APA PDF Submission (part of Midterm compilation)
* **Example Relevant Courses:** CS 580 (Software Engineering), CS 664 (Computer Networks)

### Requirements:
1. **High-Level System Diagram:** Architectural schematic detailing system components, subsystem boundaries, data flow pipelines, and cloud/infrastructure layers.
2. **Technology Stack Justification:** Technical evaluation and defense of selected frameworks, programming languages, databases, and third-party APIs against technical constraints.
3. **Low-Fidelity UI/UX Wireframes & User Flows:** Visual mockups or wireframes illustrating primary user interaction paths, screen transitions, and core user interfaces (incorporating the visual language from your Brand Kit).
4. **Requirements Test Matrix:** Mapping matrix linking each functional requirement/user story to specific verification and validation test methods.
5. **Initial Schedule & Operational Process Layout:** Initial project milestone timeline and defined team workflow methodologies (sprint cycles, meeting cadence, communication channels).

### Frequently Asked Questions & Clarifications:
> **Q: Do wireframes need to look like finished visual designs?**  
> **A:** No. Low-fidelity wireframes focus on structural layout, navigation hierarchy, and user interaction flow—not pixel-perfect styling or final color palettes. Tools like Figma, Balsamiq, or clean digital sketches are acceptable.

> **Q: What is the difference between Verification and Validation in the Test Matrix?**  
> **A:** **Verification** answers *"Did we build the system right?"* (e.g., unit tests, API integration tests checking against specs). **Validation** answers the question *"Did we build the right system?"* (e.g., user acceptance tests and stakeholder reviews that ensure user needs are met).

---

## Assignment 4: Midterm Checkpoint Report & Presentation Defense
* **Grade Weight:** 30% Total (Assignment 4b weight of 15%; Assignment 4c weight of 15%)
* **Deliverable Format:** Single cohesive APA PDF (`TeamNameCS598_MT.pdf`) + Slide Deck Submission
* **Example Relevant Courses:** CS 580 (Software Engineering), COMM 111 (Public Speaking)

### Report & Document Requirements (4c):
1. **Document Assembly:** Full integration of revised and expanded content from Assignments 1, 2, and 3 into a single unified report, addressing all prior instructor feedback.
2. **Front Matter:**
   * Title Page following standard APA format.
   * Formal Executive Abstract.
   * Dynamic Table of Contents with functional in-document clickable links.
3. **Appendices:** Attached supplemental diagrams, data tables, wireframe sheets, or research figures.
4. **Written Submission Schedule:** The full compiled written report is due by **Sunday of Week 11** (Nov 1).

### Midterm Checkpoint Presentation Requirements (4a & 4b):
* **Schedule:** Presentations take place in class on **Friday of Week 10** (Oct 30).
* **Slide Submission Due Date (4a):** The final slide deck must be submitted via Blackboard by **Sunday at 11:59 PM prior to presentation week** (Sunday of Week 9 / Oct 25).
* **In-Class Defense (4b):** Execution of the live team presentation.
* **Time Structure:** Strictly **7 to 9 minutes total** (aim for an 8-minute presentation). Presentations shorter than 7 minutes or longer than 9 minutes will lose points. Followed by 3 minutes of feedback and up to 3 minutes of Q&A.
* **Slide Branding:** Every slide must include the **Team Name** and the **Name of the Individual Slide Presenter**. Presenters will directly answer any Q&A related to their presented slides.
* **Slide Structure (Mapped to Assignments 1–3):**
  1. **Slide 1: Team & Project Identity** *(from Assignment 1)* – Team name, project logo/branding, team members/roles, and presentation date.
  2. **Slide 2: Problem Statement & Value Proposition** *(from Assignment 1)* – Core problem space, project justification, target audience, and intended impact.
  3. **Slide 3: Competitive Landscape & Tech Moat** *(from Assignment 1)* – Competitor analysis and technical novelty/differentiation.
  4. **Slides 4 & 5: Requirements & Technical Specifications** *(from Assignments 2 & 3)* – High-level summary of customer personas, user stories, non-functional requirements (latency, security, scalability), and the test verification matrix.
  5. **Slide 6: Legal, Ethical & Risk Audit** *(from Assignment 2)* – Ethical considerations, data privacy compliance (GDPR/HIPAA/COPPA), IP licensing, and potential misuse or breach risks.
  6. **Slide 7: Evolution of Engineering Roles** *(from Assignment 1)* – Updated individual position descriptions and refined technical domain ownership.
  7. **Slide 8: Schedule, Critical Path & Agile Response** *(from Assignment 3)* – Milestone schedule, team workflow methodologies, critical technical dependencies, and risk mitigation plans.
* **Grading Focus:** Teams will be primarily evaluated on demonstrated improvement and addressing past instructor/peer feedback.

### Frequently Asked Questions & Clarifications:
> **Q: Can we just copy and paste Assignments 1, 2, and 3 together for the written report?**  
> **A:** Copying raw sections is not enough. The Midterm report must read as a single, cohesive document. You must resolve all previous instructor comments, harmonize terminology across sections, smooth out transitions, and format the entire document under consistent APA guidelines.

> **Q: When are the presentation slides due?**  
> **A:** Slide decks must be uploaded to Blackboard by the **Sunday prior to the presentations** (Sunday of Week 9) to allow time for instructor review before Friday's in-class sessions.

> **Q: What happens if our presentation runs under 7 minutes or over 9 minutes?**  
> **A:** Time limits are strictly enforced. Presentations outside the 7–9 minute range will receive a point deduction. Practice with a timer to ensure your pacing lands right at the 8-minute mark.

> **Q: How should we structure the `TeamNameCS598_MT.pdf` file name?**  
> **A:** Use your official registered team name without spaces or special characters (e.g., `DataDynamosCS598_MT.pdf` or `TeamAlphaCS598_MT.pdf`). All team members' individual names must still be listed on the title page itself.

---

## Assignment 5: Data Schema, API Contracts, & Final Design Draft
* **Grade Weight:** 5%
* **Deliverable Format:** Document Section / APA PDF Submission (part of Final Blueprint compilation)
* **Example Relevant Courses:** CS 665 (Introduction to Database Systems), CS 580 (Software Engineering)

### Requirements:
1. **Entity-Relationship Diagrams (ERDs) & Database Schema:** Fully normalized database models, table structures, relationships, data types, and key constraints.
2. **API Endpoint Specifications:** Formal API contracts detailing routes, HTTP methods, request headers/bodies, response payloads, and status codes.
3. **Detailed System Design & UML Diagrams:** In-depth technical models (e.g., class diagrams, sequence diagrams, component diagrams) and documented design alternatives/trade-offs.
4. **Tooling & AI Usage Boundaries:** Explicit identification of implementation toolchains, frameworks, and formal operational boundaries/policies regarding AI-assisted code generation during development.

### Frequently Asked Questions & Clarifications:
> **Q: What if our project uses a NoSQL database (like MongoDB or Firebase) instead of a relational SQL database?**  
> **A:** You still need a schema diagram! Document your document collections, object structures, embedding vs. referencing strategies, indexes, and document validation rules.

> **Q: How detailed do the API specs need to be?**  
> **A:** Provide complete contracts. Specify exact JSON request/response bodies, expected data types, success status codes (e.g., `200 OK`, `201 Created`), and error handling responses (e.g., `400 Bad Request`, `401 Unauthorized`, `404 Not Found`).

---

## Assignment 6: Production Backlog & Implementation Plan
* **Grade Weight:** 5%
* **Deliverable Format:** Document Section / APA PDF Submission (part of Final Blueprint compilation)
* **Example Relevant Courses:** CS 580 (Software Engineering)

### Requirements:
1. **Team Weakness & Risk Mitigation Assessment:** Critical assessment of technical skill gaps, resource constraints, or single points of failure within the team, paired with actionable mitigation strategies.
2. **Production-Ready Project Task Board:** Fully initialized development board (e.g., Jira, GitHub Projects) containing broken-down implementation tasks derived from the SRS.
3. **Semester 2 Roadmap & Sprint Planning:** Structured schedule defining multi-week sprint cycles, feature rollouts, milestone targets, task assignments, and individual responsibilities for the upcoming coding semester.

### Frequently Asked Questions & Clarifications:
> **Q: Are we expected to write production code during Semester 1?**  
> **A:** Semester 1 focuses on design, requirements, architecture, and proof-of-concept experiments (Week 12). Full-scale feature development occurs in Semester 2. However, your production backlog for Semester 2 must be fully ticketed and ready before this semester ends.

> **Q: How granular should sprint tasks be in Jira/GitHub Projects?**  
> **A:** Tasks should represent 4 to 16 hours of work. Avoid vague epics like "Build Backend." Instead, break work down into actionable units, such as "Implement JWT authentication middleware" or "Create user profile database migration script."

---

## Assignment 7: Final Project Blueprint & EOH Defense
* **Grade Weight:** 45% Total (7a EOH Defense weight of 30%; 7b Final Report & Artifact weight of 15%)
* **Deliverable Format:** Single cohesive APA PDF (File Naming: `TeamNameCS598_FINAL.pdf`) + In-Person Public Presentation + Mobile App / Executable Artifact
* **Example Relevant Courses:** CS 580 (Software Engineering), COMM 111 (Public Speaking)

### Presentation Defense Requirements (7a - Friday, Dec 4 | 30% Weight):
* **Public Presentation & Elevator Pitch Defense:** Execution of a live team presentation and project proposal defense at the Engineering Open House (EOH) event on **Friday of Week 16 (Dec 4)**. Presentations must feature a concise **2–3 minute elevator pitch** that delivers a high-impact overview of the problem, the proposed system architecture, the core innovation, and the Semester 2 implementation plan to faculty, peers, and industry judges.

### Written Blueprint & Artifact Requirements (7b - Sunday, Dec 6 | 15% Weight):
1. **Final Blueprint Assembly:** Comprehensive merge of the updated Midterm content (Assignments 1–3) with the newly finalized design and implementation materials (Assignments 5–6), due on **Sunday of Week 16 (Dec 6)**.
2. **Front Matter & Formatting:**
   * Updated Executive Abstract reflecting the complete blueprint.
   * Updated Table of Contents with working internal links.
   * Complete APA-formatted references list citing all external literature, frameworks, and specifications.
3. **Mandatory Delivery Artifact:** All project teams are required to specify and include either a **mobile application build (APK/IPA/TestFlight link) or a standalone executable binary** in their final project deliverable package.

### Frequently Asked Questions & Clarifications:
> **Q: What constitutes an acceptable "mobile application or final executable" for Assignment 7?**  
> **A:** Teams must provide a compiled, runnable artifact—such as an Android APK, iOS TestFlight/build bundle, desktop executable installer (`.exe`, `.dmg`), or containerized standalone package (`Docker` / runnable binary)—demonstrating the system's deployment capability or proof-of-concept build environment.

> **Q: What if our project is strictly a web service or backend API?**  
> **A:** Web services should be bundled with a runnable container (`Docker Compose`), a hosted live demo link, or a packaged local script/CLI executable alongside API documentation.

> **Q: How strictly enforced is the 2–3 minute elevator pitch for the EOH presentation?**  
> **A:** Highly strictly! EOH judges and guests visit many stations. Your team must deliver a sharp, compelling 2–3 minute hook that explains the core value proposition, architecture, and Semester 2 roadmap before opening up to deeper technical Q&A or wireframe walkthroughs.

> **Q: What is expected for the Engineering Open House (EOH) defense if we haven't built the full app yet?**  
> **A:** You are presenting and defending your **Project Proposal and Technical Blueprint**. Your pitch must showcase the problem, market need, architectural design, wireframe walkthroughs, proof-of-concept validation results, and execution roadmap for the Semester 2 building.

> **Q: Do we need a poster for EOH?**  
> **A:** Presentation formatting guidelines (slides vs. poster display) will be finalized by Week 12 based on departmental arrangements for the event space. Prepare digital slides that translate easily into print format if required.
# Future Interns Internship — Task 1: AI Website Copy Generator

## 📌 Submission Details
- **Internship Domain:** Prompt Engineering
- **Track Code:** PE
- **Task Number:** 01
- **Project Title:** AI Website Copy Generator for Local Businesses

---

## 🏢 Business Choice
- **Name:** The Daily Grind Cafe
- **Industry:** Food & Beverage / Specialty Cafe
- **Target Audience:** Remote workers, local neighborhood residents, and coffee enthusiasts.
- **Tone & Style:** Friendly, warm, community-centric, and clear.

## 🧠 Engineered Prompt Logic & Techniques Used
To ensure the LLM generated website-ready, persuasive content rather than generic text, the following structural frameworks were used:

1. **Role Prompting (Persona Adoption):** Activating specific personas (e.g., `[Role]: You are an elite conversion-focused website copywriter...`) forced the LLM to write copy focused on customer benefits and conversion rather than just listing features.
2. **Context & Variable Isolation:** By segregating `[Business Info]` parameters (Name, Target Audience, Core Value Proposition, Tone), the prompts are entirely modular. An intern or agency can easily swap out the cafe data for another local business type without altering the core prompt structure.
3. **Negative Constraints:** The prompts included instructions such as *"Do not use cliché AI phrases like 'nestled in the heart of'"*. This restricted the AI from using overused corporate filler phrases, resulting in a natural, human tone.
4. **Structured Layout Demands:** The prompts mandated exact Markdown output structures (`[Instructions]: Generate... Headline, Sub-headline, Hero...`). This ensured the output layout matched standard, wireframe-ready web components.

## 📂 Repository Layout
- `/prompts`: Contains the raw text files for the engineered system-role prompts.
- `/outputs`: Contains the final, polished Markdown copies ready to be handed off to a web developer.
- 

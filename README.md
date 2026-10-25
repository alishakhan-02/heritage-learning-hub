# Heritage Learning Hub

A responsive React + Vite internship project prototype for exploring Indian heritage, learning through short modules, checking knowledge with quizzes, tracking progress, saving places, and managing a local content catalogue.

## Pages and end-to-end flow

1. **Home** – featured heritage, shortcuts, progress summary.
2. **Explore Heritage** – search and filter heritage cards by category.
3. **Heritage Details** – descriptions, facts, learning prompts and official source links.
4. **Learning Modules** – structured self-paced module list.
5. **Lesson View** – lesson content, reflection prompt, official source and completion tracking.
6. **Quiz Zone** – 5-question quiz, answer explanations and score history.
7. **My Progress** – completion overview and quiz history.
8. **Saved Places** – bookmark collection.
9. **Admin Panel** – add/remove local catalogue entries.
10. **Sign-in modal** – demo display name and role selection.

## Genuine reference links

- Taj Mahal – UNESCO World Heritage Centre: https://whc.unesco.org/en/list/252/
- Humayun's Tomb – UNESCO World Heritage Centre: https://whc.unesco.org/en/list/232/
- Yoga – UNESCO Intangible Cultural Heritage: https://ich.unesco.org/en/RL/yoga-01163
- India's UNESCO intangible heritage elements: https://ich.unesco.org/en/state/india-IN?info=elements-on-the-lists
- India's World Heritage properties: https://whc.unesco.org/en/statesparties/in/

The sample entries are grounded in the linked UNESCO records. Newly added admin entries are labelled drafts and require fact-checking before they should be treated as verified.

## Run locally

Requirements: Node.js 18+ and npm.

```bash
npm install
npm run dev
```

Open the local URL shown by Vite. For a production build:

```bash
npm run build
npm run preview
```

## Important prototype limitations

- Login is a **demo identity selector**, not real authentication.
- Progress, saved items and catalogue edits use browser `localStorage`; data is local to that browser/device.
- Role selection does **not** provide secure role-based access control. A real deployment needs a backend, hashed passwords or a managed identity provider, server-side authorisation, validation, database persistence and audit logging.
- The study-note download is plain text (`.txt`) in this prototype, not a designed PDF.
- Images are loaded from remote Unsplash URLs and require internet access. Confirm usage rights or replace with appropriately licensed / government-provided assets before public deployment.
- This package is not deployed; deploy the Vite build to Vercel/Netlify after testing. For the full internship scope, add a Node/Express API and PostgreSQL/MongoDB database before claiming production security or multi-user functionality.

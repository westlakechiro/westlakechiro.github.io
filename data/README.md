# data/

Public-facing data files served from `westlakechiro.github.io/data/`.

## Files

- **`spinney-knowledge-base.json`** — knowledge base for the Spinney chatbot. 200 Q&A entries covering practice basics, Dr. Brad, first-visit info, chiropractic basics, common conditions, treatments offered, insurance, lake-life scenarios, and how chiropractic compares to other care.

  Includes top-level scaffolding the chatbot vendor / runtime needs: required AI disclaimer, red-flag trigger list (immediate 911 routing), banned/approved phrasing lists, a paste-ready system-prompt template, and a fallback for unknowns.

  All answers were written to comply with the practice's compliance framework: no "cure," "heal," "treats [disease]," "guaranteed," "permanent results" language; no diagnosis; no medication recommendations; no imaging interpretation.

## Important

This data is public. It contains NO patient health information — only general FAQ content about Westlake Chiropractic and chiropractic care.

If the chatbot is later wired up to actually collect symptom information from visitors, that flow must run on HIPAA-eligible infrastructure with a signed Business Associate Agreement, and the disclaimer in the JSON should be updated accordingly. Until then, the disclaimer explicitly tells users not to share personal health information.

# AI Adaptive Learning Path 2030

An Education 2030 prototype exploring how AI-style adaptive systems can move learners away from a fixed one-size-fits-all curriculum toward mastery-driven learning routes.

## Core idea
Traditional path: **Chapter 1 → Chapter 2 → Chapter 3 → Exam**

Adaptive path: **Evidence → Mastery estimate → Prerequisite check → Advance or intervene → Re-check → Adapt again**

## Features
- Dynamic mastery model across connected Python concepts
- Prerequisite-aware next-topic recommendations
- Adaptive mastery checks
- Automatic intervention route after incorrect responses
- Live visual learning-path timeline
- “Why this route?” explainability
- Learner dashboard and mastery state
- Teacher insight / human-oversight view
- Learning history and local persistence
- Responsive mobile interface

## Important implementation note
This version is a transparent **AI-adaptive learning prototype**. Its recommendation engine is deterministic and runs locally in the browser; it does not pretend to call a generative AI model. This makes the adaptation logic easy to demonstrate and inspect. A future version can add an LLM for generated explanations/questions while retaining the explicit mastery and prerequisite rules.

## Education 2030 principle
**AI recommends. Educators decide.** Adaptive systems should make learning evidence and recommendations visible to teachers rather than silently making high-impact educational decisions.

## Live Demo
https://ai-adaptive-learning-path-2030.onrender.com

## Version history
- **V1 — Adaptive path:** prerequisite graph, mastery checks, next-topic recommendation and intervention routing.
- **V2 — Explainability & oversight:** live path visualization, “Why this route?” reasoning and teacher insight view.
- **V3 — Evidence-aware adaptation:** repeated evidence now changes mastery progressively; recommendation cards expose evidence confidence and avoid treating a single correct answer as permanent mastery.

**Current version: V3**

### V3 decision model
The local engine combines **mastery + prerequisite readiness + repeated evidence confidence**. Generative AI remains intentionally separate from this transparent decision layer so future LLM-generated content cannot silently control progression.

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
Deployment URL will be added after publishing.

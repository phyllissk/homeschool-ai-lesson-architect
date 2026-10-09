# AI Homeschool Curriculum & Multi-Sensory Lesson Architect

## Overview
This repository showcases an AI prompt engineering framework and structured system prompt that transforms broad educational topics into custom, multi-sensory homeschool lesson plans. Designed to adapt to specific learner needs—such as early reading development, tactile phonics, and differentiated pacing—the system generates structured, actionable instructional guides for parent educators.

## Core Capabilities & Technical Design
* **Adaptive Prompt Engineering:** Uses strict persona guidelines, age-appropriate cognitive benchmarks, and variable input parameters (grade level, learning style, available materials).
* **Multi-Sensory Activity Integration:** Automatically routes concepts into Visual, Auditory, Kinesthetic, and Tactile (VAKT) learning modes (e.g., sound hopscotch, tactile spelling trays, Elkonin boxes).
* **Structured Output Parsing:** Enforces strict JSON/Markdown schema outputs ensuring consistent delivery of materials lists, time breakdowns, and comprehension checks.
* **Edge-Case & Constraint Handling:** Prevents generic AI outputs by enforcing hands-on engagement constraints and eliminating reliance on screens or excessive worksheets.

---

## Repository Structure
* `/prompts/master_lesson_architect_prompt.txt`: System prompt containing role constraints, instructional frameworks, and output formatting rules.
* `/docs/lesson_generation_flow.md`: Operational logic showing how user parameters route into custom lesson outputs.
* `/examples/sample_output_early_reader.json`: Full benchmark example demonstrating an early reading and phonics lesson plan output.

---

## Technical Application & Use Cases
This architecture demonstrates foundational skills in:
1. **System Prompt Design:** Structuring system instructions for domain-specific LLM assistants.
2. **User Experience (UX) for EdTech:** Simplifying complex lesson planning into intuitive, step-by-step parent guides.
3. **Guardrails & Quality Control:** Implementing negative constraints ("No passive screen time") to guarantee high-value, active learning recommendations.

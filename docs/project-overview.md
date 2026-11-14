# Project overview – FP Agentic Mentor

## TL;DR

FP Agentic Mentor is a conceptual AI agent for Vocational Education and Training (VET). It explains competencies in accessible language, proposes practical activities, builds personalised learning paths and helps learners assemble a verifiable evidence portfolio. The aim: less confusion, more autonomy and a clearer path to employability.

## Description

FP Agentic Mentor is a conceptual proposal for an educational AI agent designed to transform learning and skill development in VET. It gives students and educators intelligent guidance that clarifies competencies, activates motivation, supports progress and produces real evidence of capability.

The agent acts as an **educational digital worker**: it complements the teacher's role, supports decision-making and strengthens learner autonomy. Rather than building the agent technically, this proposal focuses on defining the experience, the capabilities and the educational value of a human–AI collaboration model for VET.

## The problem

VET asks learners to demonstrate real competencies, but the learning experience has three recurring frictions:

- **Lack of clarity.** Competency statements such as "configure network services" or "manage virtualised environments" are hard to interpret, which leads to uncertainty, low motivation and superficial learning.
- **No clear learning path.** Learners often do not know which activities to do next or how to connect theory and practice, and teachers repeat the same instructions many times.
- **Weak or fragmented evidence.** Evidence of learning ends up spread across platforms and personal folders, with little structure or traceability, which makes it harder to show what a learner can do.

## What FP Agentic Mentor does

| Capability | What it does |
|---|---|
| **Competency Clarity** | Translates each competency into plain language, with examples, mastery levels and evidence criteria. |
| **Learning Path Builder** | Creates an adaptive route based on the module, the learner's pace and level. |
| **Evidence Portfolio** | Suggests practical activities and organises the resulting evidence into a portfolio aligned with competencies. |
| **Progress Coach** | Supports motivation with feedback, reminders and progress visualisation. |

## How it works (conceptual flow)

1. **Intake** – the learner enters their module, competency or pending activity.
2. **Reasoning & generation** – the agent interprets the competency and drafts explanations, activities and recommendations.
3. **Human validation** – the teacher or learner reviews, adjusts and approves the suggestions.
4. **Evidence generation** – the learner completes the activities with the agent's guidance.
5. **Portfolio assembly** – the agent organises the evidence into a coherent, competency-aligned portfolio.

**Guiding principle:** AI proposes, humans decide.

## Conceptual architecture (stack-agnostic)

| Layer | Role |
|---|---|
| Intake | Form, chat or learning-platform capture |
| Source of truth | Structured repository of competencies, activities and evidence |
| Agent / LLM | Competency explanation, activity generation, progress analysis |
| Orchestration | Workflow that connects the steps and enforces human validation |
| Evidence & portfolio | Organisation of evidence and portfolio creation |

Candidate technologies include Azure OpenAI, Copilot Studio, Power Automate, SharePoint and Microsoft Forms, or open agent frameworks. The design prioritises reliability, safety and no additional cost for schools.

## Expected impact

- Time returned to teachers, who spend less effort repeating explanations.
- More complete and better-aligned evidence of learning.
- Better understanding of competencies by learners.
- Greater learner autonomy.
- Structured, traceable portfolios that learners can use for internships and job interviews.

These are expected outcomes of the proposal, to be validated in a future pilot.

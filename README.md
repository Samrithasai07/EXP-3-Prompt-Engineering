# EXP-3-PROMPT-ENGINEERING-

## Aim: 
Evaluation of 2024 Prompting Tools Across Diverse AI Platforms: 
ChatGPT, Claude, Bard, Cohere Command, and Meta
Experiment:
Within a specific use case (e.g., summarizing text, answering technical questions), compare the performance, user experience, and response quality of prompting tools across these different AI platforms.

## Algorithm:
Stage 1: Experimental Design

1. Multi-Dimensional Use Case Selection
Instead of evaluating a single task, this experiment integrates two complementary domains:

Analytical Task: Technical Question Answering (tests reasoning + logic + coding)
Interpretive Task: Text Summarization (tests understanding + communication)

This hybrid approach ensures evaluation of both cognitive depth and linguistic efficiency.

2. Prompt Engineering Strategy
Prompts are designed using a layered instruction technique:

Step-wise instruction flow
Audience-specific variation
Constraint-based formatting

This ensures testing of:

Instruction comprehension
Context retention
Output structuring ability

# Prompt
## Prompt 1: Advanced Technical Reasoning

Explain quantum entanglement in three layers:
(1) Beginner-friendly explanation
(2) Technical explanation with key principles
(3) Real-world analogy

Then generate a Python simulation using Qiskit demonstrating a basic quantum communication process.
The code must be modular, commented, and executable.

## Prompt 2: Adaptive Summarization

Summarize a complex passage in two formats:

A simplified paragraph for general readers
Bullet-point insights for experts

Ensure clarity differentiation between both outputs.

## Prompt 3: Constraint-Based Precision

Summarize a paragraph strictly in three sentences only, without losing meaning or introducing redundancy.

Stage 3: Execution Environment
Platforms tested: ChatGPT, Claude, Gemini, Cohere Command, Meta AI
Same prompts used across all systems
No parameter tuning (default settings)
Single-turn interaction (no follow-up refinement)

## Output
| Metric                | ChatGPT   | Claude    | Gemini   | Cohere   | Meta   |
| --------------------- | --------- | --------- | -------- | -------- | ------ |
| Accuracy              | High      | High      | Medium   | Medium   | Low    |
| Clarity               | High      | Very High | Medium   | High     | Medium |
| Depth                 | High      | Very High | Medium   | Low      | Low    |
| Instruction Following | Excellent | Good      | Moderate | Moderate | Weak   |
| Code Quality          | Strong    | Moderate  | Moderate | Weak     | Weak   |

<img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/b29bb08f-a462-4622-84b7-fe423609d591" />

## Result
The experiment demonstrates that prompt engineering plays a critical role in shaping AI responses, and different platforms exhibit distinct behavioral strengths.

ChatGPT emerged as the most consistent and reliable performer, excelling in both structured reasoning and coding tasks.
Claude showed superior explanatory depth and natural language quality, making it ideal for long-form content.
Gemini performed well in speed and general knowledge integration, but lacked consistency in complex tasks.
Cohere Command proved effective for concise, business-oriented outputs.
Meta AI was suitable for basic interactions but lacked advanced reasoning capabilities.


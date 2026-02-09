# csc113_h_1-2-b_track.md
A breakdown of what we can respond to AI, with the assist of what it can do to help us do or study.

# H.1.2 — Continuing with SAGE (Track B: Prompt Masters)
**Course:** CSC-113 AI Fundamentals  
**Student:** Nicholas Candanoza  
**Due Date:** Feb 9, 11:59 PM  

---

## Overview

For this assignment, I built and tested a custom AI assistant called **SAGE (Study Assistant & Guide Engine)**. The goal was to design an assistant that helps me study more effectively by explaining concepts clearly, generating practice questions, and guiding me instead of giving direct homework answers. I also created a reusable prompt library and documented my testing and refinement process.

---

## Part 1: My SAGE Assistant

### What I Designed SAGE to Do

I designed SAGE to help me study for CSC-113 and other college courses by breaking down complex topics into simpler explanations, providing practice questions, and helping me reflect on my understanding. SAGE is meant to support learning, not replace it.

---

### My System Instructions

#### Version 1 (Initial)

You are SAGE (Study Assistant & Guide Engine), a personalized study companion for a college student.

Your job:
- Help me understand AI and computer-related concepts in plain language
- Generate practice questions and examples when asked
- Explain ideas using everyday analogies
- Ask clarifying questions when prompts are unclear
- Be honest when you are unsure about an answer

Your personality:
- Patient
- Encouraging
- Clear and direct

Rules:
- Do not give full answers to graded homework
- Guide me step by step instead of solving problems for me
- Use simple language unless I request more detail

---

#### Version 2 (After Testing)

You are SAGE (Study Assistant & Guide Engine), a personalized study companion for a college student studying AI fundamentals and general college coursework.

Your job:
- Explain concepts in plain, beginner-friendly language
- Use short examples or analogies when possible
- Generate practice questions, summaries, or checklists when asked
- Ask at least one clarifying question for complex topics
- Clearly state when information may be uncertain or limited

Your personality:
- Patient
- Encouraging
- Concise

Rules:
- Never provide direct answers to graded assignments
- Keep responses under 150 words unless I ask for more detail
- Break complex explanations into numbered steps
- Acknowledge frustration before helping if I seem confused

---

### What I Changed and Why

I added a word limit because SAGE was initially too wordy. I also strengthened the rules about not giving direct answers after noticing it sometimes solved problems instead of guiding me. Adding numbered steps helped make explanations easier to follow.

---

## Testing Results

### Test 1: Basic Explanation
- **What I asked:** Explain what prompt engineering is  
- **How SAGE responded:**  
Prompt engineering is how you phrase instructions so an AI understands what you want. It’s more about being clear and specific than using fancy words. For example, asking for an explanation with an example usually works better than a vague question.  
- **Quality:** Excellent  
- **Notes:** Easy to understand and not overwhelming  

---

### Test 2: Practice Questions
- **What I asked:** Generate practice questions about system instructions  
- **How SAGE responded:**  
SAGE generated questions asking about the purpose of system instructions, how they affect AI behavior, and why rules matter. It also offered to explain answers or turn them into multiple-choice questions.  
- **Quality:** Good  
- **Notes:** Questions were helpful and made me think  

---

### Test 3: Pushing the Boundaries
- **What I asked:** Predict future AI laws  
- **How SAGE responded:**  
SAGE explained that it can’t predict exact laws but described current trends like privacy, transparency, and accountability. It also asked what context I needed this for.  
- **Quality:** Good  
- **Notes:** Followed the honesty rule well  

---

### Test 4: Following My Rules
- **What I asked:** Tried to get a direct homework answer  
- **How SAGE responded:**  
SAGE refused to give a direct answer and instead suggested breaking the problem into smaller parts and asked which part I was struggling with.  
- **Quality:** Excellent  
- **Notes:** Rules worked exactly as intended  

---

### Test 5: A Real Task
- **What I asked:** Help summarize an AI ethics reading  
- **How SAGE responded:**  
SAGE gave a short summary focusing on fairness, responsibility, and human accountability in AI systems, and offered to turn it into study notes.  
- **Quality:** Excellent  
- **Notes:** Very useful for studying  

---

### What I’ll Use SAGE For Going Forward
- Studying for quizzes and exams  
- Reviewing AI concepts  
- Generating practice questions  
- Summarizing readings  
- Checking my understanding before submitting work  

---

## Part 2: My Prompt Library

### Learning & Studying

**Prompt 1:**  
Explain this topic as if I’m new to it, using simple language and one example.  
**Use this when:** Learning a new concept  
**Works best with:** ChatGPT  

**Prompt 2:**  
Create 5 practice questions on this topic with brief explanations.  
**Use this when:** Studying for quizzes  
**Works best with:** Gemini  

---

### Creating & Building

**Prompt 3:**  
Summarize this reading into key bullet points under 150 words.  
**Use this when:** Reviewing assignments  
**Works best with:** ChatGPT  

**Prompt 4:**  
Create a short study checklist for this topic.  
**Use this when:** Preparing to study  
**Works best with:** Any  

---

### Evaluating & Improving

**Prompt 5:**  
Review my response and suggest improvements without rewriting it.  
**Use this when:** Editing assignments  
**Works best with:** Claude  

**Prompt 6:**  
Tell me what parts of this topic I might misunderstand.  
**Use this when:** Checking comprehension  
**Works best with:** ChatGPT  

---

### My Choice

**Prompt 7:**  
Explain this concept using a real-life analogy.  
**Use this when:** I’m confused  
**Works best with:** Gemini  

**Prompt 8:**  
Ask me 3 questions to test whether I really understand this topic.  
**Use this when:** Self-testing  
**Works best with:** Any  

---

## Reflection

This assignment helped me understand how important system instructions and prompt wording really are. Small changes made SAGE much more useful. Testing and refining it showed me that AI works best as a guide, not a shortcut. Yes it could give all the answers but, we still would need to learn what we can do for coding and all sorts of things, because if we depend on AI how will we know how to code or do other things ourselves.

# Prompt Engineering Case Study: FinTech User Access Risk

## Scenario Overview
You are a GRC analyst at a growing FinTech company preparing for a SOC 2 Type I audit. Leadership asks:  
"What are our biggest risks around user access, and what should we be doing about them?"

---

## Step 1: Unstructured Prompt

**Prompt:**
"What are the access risks and controls for SOC 2?"

### Observations
- Output is broad and generic
- Assumes mature controls exist
- Uses compliance language unsuitable for leadership

---

## Step 2: Structured Prompt

**Prompt:**

**Role:** GRC analyst  
**Task:** Identify and explain key access risks  
**Context:**  
- Company type: FinTech  
- Data: Customer PII  
- Environment: Cloud-based SaaS  
- Goal: SOC 2 Type I  

**Output Format:**  
1. Risk statement  
2. Business impact  
3. Example controls  
4. Why these controls matter  

**Constraints:**  
- Assume leadership is non-technical  
- Avoid compliance jargon  
- Keep under 250 words  

---

## Step 3: Validation Questions (Governance Layer)

Follow-up questions asked to AI:
- "What assumptions are you making about our access controls?"
- "Which part of this response would require human validation?"

### Purpose
These questions introduce AI governance concepts such as human oversight and assumption testing without explicitly labeling them as governance.

---

## Step 4: Iteration Prompt

**Prompt:**
"Rewrite the response assuming the company has no formal access review process and is early-stage."

### Outcome
- Controls become more realistic
- Risk explanations are better aligned to organizational maturity

---

## Self-Scoring Rubric
- 20–25: Job-ready thinking  
- 15–19: Strong foundation  
- <15: Needs structured prompting  

**Final Score:** 23/25

---

## Key Takeaway
This case study demonstrates how structured prompting, validation questions, and iteration improve AI reliability and align outputs with real-world organizational maturity.


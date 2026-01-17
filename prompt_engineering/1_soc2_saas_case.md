# Prompt Engineering Case Study: SOC 2 SaaS Risk Communication

## Scenario Overview
You are a junior GRC analyst at a small SaaS company preparing for its first SOC 2 audit. Leadership asks you to explain a cybersecurity risk related to customer data access in clear, business-friendly language and recommend basic controls.

---

## Step 1: Poorly Structured Prompt (Baseline)

**Prompt:**
"Explain a cybersecurity risk and controls for SOC 2."

### Observations
- Output is generic and high-level
- Uses compliance jargon
- Not tailored to company context
- Not suitable for non-technical leadership

**Score:** 2/5

---

## Step 2: Structured Prompt Using Framework

**Prompt:**

**Role:** You are acting as a junior GRC analyst  
**Task:** Your task is to explain a cybersecurity risk related to customer data access and recommend basic controls  
**Context:** The company is a SaaS provider storing customer data in cloud-based systems  
**Format:** Provide the response as:
1. Risk description  
2. Business impact  
3. Example controls  
**Constraints:**
- Use simple, non-technical language  
- Avoid framework jargon  
- Keep under 200 words  

### Observations
- Output is clearer and more relevant
- Still assumes controls without validation
- Improved readability

**Score:** 4/5

---

## Step 3: Expert-Level Prompt

**Prompt:**
You are acting as a junior GRC analyst supporting a SaaS company preparing for its first SOC 2 audit.  
Your task is to explain a cybersecurity risk related to unauthorized access to customer data and recommend basic controls.  

**Context:**  
- Data stored in cloud-based systems  
- Audience is non-technical leadership  

**Output Format:**  
1. Risk description  
2. Business impact  
3. Example controls  

**Constraints:**  
- Use plain business language  
- Avoid compliance jargon  
- Keep the response under 200 words  

### Observations
- Clear, accurate, and leadership-ready
- Controls are practical and understandable
- Suitable for audit preparation discussions

**Score:** 5/5

---

## Key Takeaway
This exercise demonstrates that AI outputs improve significantly when prompts are structured with role clarity, context, format, and constraints. Strong prompt engineering reduces risk, improves accuracy, and supports governance objectives without explicitly referencing frameworks.


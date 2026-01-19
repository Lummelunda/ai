# **Operational Companion**

  

## **Purpose**

  

This document translates the Human–AI Responsibility Framework and Context Architecture into **practical operating patterns**.

  

It describes how to structure work so that:

- humans retain intent, judgement, and accountability
    
- AI performs bounded cognitive operations
    
- context is shaped to match the task
    
- outputs remain reviewable, correctable, and reusable
    

  

This is not about writing better prompts.

  

It is about **running cognitive work as a system**.

---

## **Core operating principle**

  

**AI should never be asked to think and decide at the same time.**

  

Every failure mode observed in practice traces back to violations of this rule.

  

Instead:

- humans decide _what matters_
    
- AI explores _what’s possible_
    
- structure determines _what’s reliable_
    

---

## **The three execution modes**

  

Every AI interaction should be explicitly in one of these modes.

|**Mode**|**Purpose**|**AI function**|**Human role**|
|---|---|---|---|
|Mode A|Discriminate|classify, compare, evaluate|define criteria|
|Mode B|Generate|explain, write, reframe|choose direction|
|Mode C|Calibrate|check, ground, verify|decide authority|

Mixing modes in a single step causes output degradation.

---

## **Standard operating loop**

  

### **Step 1: Human sets intent**

  

Before invoking AI, clarify internally:

- What decision or outcome am I working toward?
    
- Is this exploratory or evaluative?
    
- What happens if this is wrong?
    

  

If the outcome is irreversible or external, AI output must remain intermediate.

---

### **Step 2: Choose the cognitive operation**

  

Pick one primary operation:

- expansion
    
- compression
    
- evaluation
    
- synthesis
    
- validation
    
- explanation
    

  

Do not combine incompatible operations.

  

Bad example:

  

> “Analyse this, decide what’s best, and write a recommendation.”

  

Good example:

  

> “Extract constraints.”

> “Compare options against them.”

> “Then write a summary.”

---

### **Step 3: Choose context structure**

  

Select the context format that matches the task:

|**Task**|**Context**|
|---|---|
|Decide, evaluate, compare|structured|
|Explain, teach, narrate|prose|
|Fact-check, align, verify|reference|

If structure mismatches the task, no prompt refinement will fix it.

---

### **Step 4: Delegate bounded work**

  

AI output must be:

- reviewable
    
- interruptible
    
- non-final
    

  

If you cannot comfortably say “this is a draft,” delegation has gone too far.

---

### **Step 5: Human judgement re-enters**

  

Humans must explicitly do one of the following:

- discard
    
- select
    
- combine
    
- correct
    
- escalate
    

  

If output is accepted implicitly, judgement laundering has occurred.

---

## **Common operational patterns**

  

### **Pattern 1: Night-shift handoff**

  

Use AI to:

- expand options
    
- surface blind spots
    
- draft alternatives
    

  

Never to:

- choose direction
    
- commit to conclusions
    

  

Morning work begins with judgement, not continuation.

---

### **Pattern 2: Semantic scaffolding**

  

When reliability matters:

1. Convert prose into structured blocks
    
2. Run evaluation or comparison
    
3. Convert back into prose
    

  

This isolates reasoning from narrative.

---

### **Pattern 3: Freeze context before writing**

  

For high-stakes writing:

- first produce a “truth layer” (facts, constraints, claims)
    
- then lock it
    
- only then generate narrative
    

  

This prevents silent drift.

---

### **Pattern 4: Reference grounding**

  

When accuracy matters:

- one document is declared authoritative
    
- AI is instructed to deviate only explicitly
    
- mismatches are flagged, not corrected automatically
    

  

AI should _signal uncertainty_, not resolve it.

---

## **When outputs degrade**

  

Do not immediately rewrite prompts.

  

Instead diagnose:

|**Symptom**|**Likely cause**|
|---|---|
|Overconfident wrong answers|missing reference authority|
|Shallow reasoning|prose used where structure required|
|Incoherent output|multiple modes mixed|
|“Sounds right” but wrong|judgement delegated|

Fix structure before language.

---

## **What this enables**

  

Used correctly, this operational model allows:

- reuse of context across tasks
    
- stable collaboration with AI over time
    
- separation of thinking from writing
    
- safe scaling of AI involvement
    
- reduction of cognitive fatigue without loss of control
    

---

## **What this does not enable**

  

This framework does not support:

- autonomous decision-making
    
- unsupervised deployment
    
- outcome ownership by AI
    
- elimination of human judgement
    

  

Those remain structural impossibilities, not tooling gaps.

---

## **Final rule**

  

**If you cannot explain why the AI produced something, you cannot trust it.**

  

Understanding comes from:

- knowing the mode
    
- knowing the structure
    
- knowing where judgement re-enters
    

  

That is the operational boundary.

---

## **How the three documents now work together**

| **Document**          | **Answers**                        |
| --------------------- | ---------------------------------- |
| Agency Principles     | Who owns what                      |
| Context Architecture  | What structure enables reliability |
| Operational Companion | How work actually runs             |

Together, they form:


**A complete thinking infrastructure, not a prompt technique.**

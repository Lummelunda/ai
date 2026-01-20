# **Operational Companion**

  

## **Purpose**

  

This document translates the Agency Principles and Context Principles into **practical operating patterns**.

  

It describes how to structure work so that:

- humans retain intent, judgement, and accountability
    
- AI performs bounded cognitive operations
    
- context is shaped to match the task
    
- outputs remain reviewable, correctable, and reusable
    

  

This is not about writing better prompts.

  

It is about **running cognitive work deliberately**, rather than implicitly.

---

## **Core operating principle**

  

**AI should not be treated as both a reasoning engine and a decision authority in the same step.**

  

Many observed failure modes trace back to this boundary becoming blurred.

  

As a working discipline:

- humans decide _what matters_
    
- AI explores _what’s possible_
    
- structure influences _what’s reliable_
    

  

Some tasks require exploratory judgement and reasoning to coexist.

In those cases, outputs must be treated as provisional and reviewed with higher vigilance.

---

## **The three execution modes**

  

Every AI interaction should have one dominant execution mode.

|**Mode**|**Purpose**|**AI function**|**Human role**|
|---|---|---|---|
|Mode A|Discriminate|classify, compare, evaluate|define criteria|
|Mode B|Generate|explain, write, reframe|choose direction|
|Mode C|Calibrate|check, ground, verify|decide authority|

Mixing modes is sometimes useful, but increases ambiguity and error risk.

When modes are combined, human review must become correspondingly stronger.

---

## **Standard operating loop**

  

### **Step 1: Human sets intent**

  

Before invoking AI, clarify internally:

- What decision or outcome am I working toward?
    
- Is this exploratory or evaluative?
    
- What happens if this is wrong?
    

  

If the outcome is irreversible or externally consequential, AI output should remain explicitly intermediate.

---

### **Step 2: Choose the cognitive operation**

  

Select one primary operation:

- expansion
    
- compression
    
- evaluation
    
- synthesis
    
- validation
    
- explanation
    

  

Avoid combining incompatible operations in a single step when reliability matters.

  

Bad example:

  

> “Analyse this, decide what’s best, and write a recommendation.”

  

More reliable approach:

  

> “Extract constraints.”

> “Compare options against them.”

> “Then write a summary.”

---

### **Step 3: Choose context structure**

  

Select the context format that matches the operation:

|**Task**|**Context**|
|---|---|
|Decide, evaluate, compare|structured|
|Explain, teach, narrate|prose|
|Fact-check, align, verify|reference|

When structure mismatches the task, improvements in prompting rarely compensate.

---

### **Step 4: Delegate bounded work**

  

AI output should be:

- reviewable
    
- interruptible
    
- non-final
    

  

If you cannot comfortably describe the result as a draft or working artefact, delegation has likely gone too far.

---

### **Step 5: Human judgement re-enters**

  

Humans explicitly decide to:

- discard
    
- select
    
- combine
    
- correct
    
- escalate
    

  

If output is accepted implicitly, judgement has drifted rather than been exercised.

---

## **Common operational patterns**

  

### **Pattern 1: Night-shift handoff**

  

Use AI to:

- expand options
    
- surface blind spots
    
- draft alternatives
    

  

Not to:

- choose direction
    
- commit to conclusions
    

  

Work resumes with judgement, not continuation.

---

### **Pattern 2: Semantic scaffolding**

  

When reliability matters:

1. Convert prose into structured blocks
    
2. Perform evaluation or comparison
    
3. Convert results back into prose
    

  

This reduces interference between reasoning and narrative.

---

### **Pattern 3: Freeze context before writing**

  

For higher-stakes writing:

- first establish a “truth layer” (facts, constraints, claims)
    
- explicitly lock it
    
- generate narrative only afterward
    

  

This does not prevent error, but makes drift easier to detect.

---

### **Pattern 4: Reference grounding**

  

When accuracy matters:

- declare one document authoritative
    
- instruct AI to flag deviations rather than silently correct them
    
- treat mismatches as review signals
    

  

AI should surface uncertainty, not resolve it autonomously.

---

## **When outputs degrade**

  

Do not immediately rewrite prompts.

  

First diagnose structural causes:

|**Symptom**|**Likely cause**|
|---|---|
|Overconfident wrong answers|missing or weak reference authority|
|Shallow reasoning|prose used where structure was needed|
|Incoherent output|multiple modes mixed|
|“Sounds right” but wrong|judgement implicitly delegated|

Adjust structure before language.

---

## **What this enables**

  

Used consistently, this operational model can support:

- reuse of context across tasks
    
- more predictable collaboration with AI
    
- separation of thinking from writing
    
- scalable use of AI without surrendering ownership
    
- reduced cognitive fatigue through clearer handoffs
    

  

These are tendencies, not guarantees.

---

## **What this does not enable**

  

This companion does not support:

- autonomous decision-making
    
- unsupervised deployment
    
- outcome ownership by AI
    
- elimination of human judgement
    

  

Those limits are structural, not technical.

---

## **Final rule**

  

**If you cannot explain why the AI produced something, you should not rely on it.**

  

Understanding comes from:

- knowing the dominant mode
    
- knowing the context structure
    
- knowing where judgement re-enters
    

  

That is the operational boundary.

---

## **How the three documents work together**

|**Document**|**Answers**|
|---|---|
|Agency Principles|Who owns what|
|Context Principles|How structure influences reliability|
|Operational Companion|How work is run in practice|

Together, they form:

  

**a disciplined approach to collaborating with AI — not a guarantee of correctness, and not a prompt technique.**

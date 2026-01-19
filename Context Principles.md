# **Context Architecture Principles**

  
**How to structure information so AI reasoning stays reliable**

---

## **Core principle**

  

**AI reliability depends more on information structure than on model capability.**

  

Large language models do not distinguish between facts, narrative, constraints, or examples unless those distinctions are made explicit.

  

When information types are mixed, outputs drift.

  

Context architecture exists to prevent that collapse.

---

## **What context architecture governs**

  

Context architecture defines:

- what information is provided
    
- what role that information plays
    
- what type of reasoning the model is allowed to perform
    

  

It does **not** define intent, goals, or decisions.

Those remain human responsibilities.

---

## **The three AI cognitive modes**

  

AI operates in different functional modes depending on task and input structure.

  

Selecting the wrong mode is the most common cause of failure.

---

### **Mode A: Discriminative**

  

**Collapse the possibility space**

  

Used for:

- evaluation
    
- comparison
    
- classification
    
- selection
    
- fit or disqualification
    
- constraint checking
    

  

Requires:

- explicit categories
    
- stable terminology
    
- structured input
    

  

Fails when given narrative or persuasive prose.

---

### **Mode B: Generative**

  

**Expand the possibility space**

  

Used for:

- explanation
    
- framing
    
- teaching
    
- writing
    
- narrative construction
    

  

Requires:

- continuous prose
    
- semantic flow
    
- linguistic context
    

  

Fails when input is overly rigid or symbolic.

---

### **Mode C: Calibration**

  

**Measure against fixed truth**

  

Used for:

- fact checking
    
- consistency validation
    
- drift detection
    
- hallucination prevention
    

  

Requires:

- authoritative reference
    
- immutability
    
- narrow scope
    

  

Fails when reference is mixed with interpretation or persuasion.

---

## **Information types and allowed roles**

  

Each type of context supports exactly one primary function.

  

### **Canonical reference**

  

Purpose:

- define what is true
    
- define hard constraints
    
- prevent drift
    

  

Used for: calibration

Must not persuade or speculate.

---

### **Structured semantic reference**

  

Purpose:

- enable judgement
    
- constrain reasoning space
    

  

Used for: evaluation, selection, comparison

Optimised for discriminative reasoning.

---

### **Prose context**

  

Purpose:

- enable understanding and articulation
    

  

Used for: explanation, writing, framing

Optimised for generative reasoning.

---

### **Compressed derivatives**

  

Purpose:

- speed and recall
    

  

Used for: convenience only

Never a source of truth.

---

## **Hard rules**

1. No document may serve more than one primary role.
    
2. Canonical reference is never derived from narrative.
    
3. Structured context constrains; it does not explain.
    
4. Prose explains; it does not decide.
    
5. Summaries are never authoritative.
    

  

Breaking these rules produces semantic drift.

---

## **Context selection cheat sheet**

|**Task**|**Preferred input**|**AI mode**|**Why it works**|
|---|---|---|---|
|Decide, evaluate, compare|Structured reference|Discriminative (A)|Collapses the possibility space|
|Explain, write, teach, frame|Prose context|Generative (B)|Enables linguistic flow|
|Check, validate, ground|Canonical reference|Calibration (C)|Measures against fixed truth|

---

## **Quick context selection guide**

  

Before providing context, ask:

  

**1. Am I asking the model to judge or choose?**

→ Use structured semantic reference (Mode A)

  

**2. Am I asking the model to explain or express?**

→ Use prose context (Mode B)

  

**3. Am I asking the model to verify correctness?**

→ Use canonical reference (Mode C)

  

If the answer is “all of the above”, split the task.

  

Do not combine modes in a single prompt.

---

## **Relationship to human responsibility**

  

Context architecture supports judgement.

It does not replace it.

  

Humans remain responsible for:

- intent
    
- framing
    
- interpretation
    
- acceptance of consequences
    

  

AI performs operations within the boundaries context defines.

---

## **Operating rule**

  

> **Humans decide what matters.**

> **Context determines how the model reasons.**

> **AI generates intermediate output only.**

---

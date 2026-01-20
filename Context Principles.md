# **Context Principles**

  

**How to structure information so AI reasoning stays reliable**

---

## **Core principle**

  

**AI reliability is strongly influenced by information structure, often as much as by model capability.**

  

Large language models do not inherently distinguish between facts, narrative, constraints, or examples unless those distinctions are made explicit.

  

When information roles blur, reasoning becomes ambiguous and outputs are more likely to drift.

  

Context principles exist to reduce that ambiguity and make failure more visible, not to guarantee correctness.

---

## **What context principles govern**

  

Context principles define:

- what information is provided
    
- what role that information plays
    
- what type of reasoning the model is encouraged to perform
    

  

They do **not** define intent, goals, values, or decisions.

  

Those remain human responsibilities.

---

## **The three AI cognitive modes**

  

AI behaviour shifts depending on task framing and input structure.

  

Selecting a mismatched mode is one of the most common causes of degraded output.

  

These modes are functional descriptions, not strict partitions.

They describe tendencies, not guarantees.

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
    

  

Works best with:

- explicit categories
    
- stable terminology
    
- structured input
    

  

Performance degrades when inputs rely primarily on narrative or persuasive prose.

---

### **Mode B: Generative**

  

**Expand the possibility space**

  

Used for:

- explanation
    
- framing
    
- teaching
    
- writing
    
- narrative construction
    

  

Works best with:

- continuous prose
    
- semantic flow
    
- linguistic context
    

  

Performance degrades when inputs are overly rigid, symbolic, or prematurely constrained.

---

### **Mode C: Calibration**

  

**Measure against fixed reference**

  

Used for:

- fact checking
    
- consistency validation
    
- drift detection
    
- hallucination reduction
    

  

Works best with:

- authoritative reference
    
- immutability
    
- narrow scope
    

  

Performance degrades when reference material is mixed with interpretation, persuasion, or speculative language.

---

## **Information types and typical roles**

  

Different context types tend to support different reasoning functions.

  

Blending roles is sometimes workable, but increases cognitive load and error probability.

---

### **Canonical reference**

  

Purpose:

- define what is treated as true
    
- define hard constraints
    
- limit drift
    

  

Primarily used for: calibration

  

Should avoid persuasion, interpretation, or speculation.

---

### **Structured semantic reference**

  

Purpose:

- constrain reasoning space
    
- enable comparison and evaluation
    

  

Primarily used for: discriminative reasoning

  

Optimised for judgement, not explanation.

---

### **Prose context**

  

Purpose:

- support understanding and articulation
    

  

Primarily used for: generative reasoning

  

Optimised for expression, not decision-making.

---

### **Compressed derivatives**

  

Purpose:

- speed, recall, convenience
    

  

Used as working material only.

  

Should not be treated as authoritative sources of truth.

---

## **Operational guidelines**

  

The following are not hard prohibitions, but reliability guidelines.

  

Violating them does not cause automatic failure, but increases ambiguity and the burden on human judgement.

1. Documents serving multiple roles increase risk of semantic drift.
    
2. Deriving canonical reference from narrative increases hidden assumptions.
    
3. Structured context constrains reasoning but does not explain meaning.
    
4. Prose explains meaning but should not be treated as decisive.
    
5. Summaries trade fidelity for speed and should not be authoritative.
    

  

These guidelines exist to make reasoning boundaries legible, not rigid.

---

## **Context selection cheat sheet**

|**Task**|**Preferred input**|**AI mode**|**Why it helps**|
|---|---|---|---|
|Decide, evaluate, compare|Structured reference|Discriminative (A)|Narrows the possibility space|
|Explain, write, teach, frame|Prose context|Generative (B)|Enables linguistic flow|
|Check, validate, ground|Canonical reference|Calibration (C)|Measures against stable reference|

---

## **Quick context selection guide**

  

Before providing context, ask:

  

**1. Am I asking the model to judge or choose?**

→ Structured semantic reference (Mode A)

  

**2. Am I asking the model to explain or express?**

→ Prose context (Mode B)

  

**3. Am I asking the model to verify correctness?**

→ Canonical reference (Mode C)

  

If the honest answer is “more than one,” separate the task.

  

Combining modes is sometimes useful, but should be done consciously and with increased human review.

---

## **Relationship to human responsibility**

  

Context principles support judgement.

  

They do not replace it.

  

Humans remain responsible for:

- intent
    
- framing
    
- interpretation
    
- acceptance of consequences
    

  

Context shapes how the model reasons.

It does not determine what should be decided.

---

## **Operating rule**

  

> **Humans decide what matters.**

> **Context influences how the model reasons.**

> **AI produces intermediate output only.**

---

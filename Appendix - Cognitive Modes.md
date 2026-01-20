# **Appendix: Cognitive Modes**

  

**A practical reference for how large language models behave under different reasoning conditions**

  

This appendix provides a concrete, operational description of the three cognitive modes referenced throughout the framework.

  

The modes described here are not model features or configuration options. They are **functional states induced by task framing and context structure**.

  

The model does not “switch modes” internally.

Humans place it in a mode by what they ask and how information is structured.

  

This reference is intended for lookup and diagnosis, not for first-time explanation.

For guidance on when and how to use each mode, see **Context Principles** and **Operational Companion**.

---

## **Mode A: Discriminative reasoning**

  

**Structure-first**

|**Category**|**Description**|
|---|---|
|**Primary function**|Collapse the possibility space|
|**Typical tasks**|Classification, categorisation, comparison, ranking, evaluation, qualification or disqualification, consistency checking, constraint enforcement, eligibility determination, matching problems to known patterns|
|**Characteristics**|Prefers explicit labels and stable schemas. Sensitive to ambiguity. Degrades with metaphor or persuasive language. Performs best when terminology is reused consistently.|
|**Typical outputs**|Tables, matrices, checklists, structured summaries, yes/no decisions with reasoning, scored comparisons|
|**Common failure modes**|Vague categories, unstable terminology, narrative inputs disguised as criteria|

---

## **Mode B: Generative reasoning**

  

**Language-first**

|**Category**|**Description**|
|---|---|
|**Primary function**|Expand or reshape the possibility space|
|**Typical tasks**|Explanation, narrative construction, reframing, summarisation, teaching, ideation, writing assistance, tone adaptation, storytelling, synthesis|
|**Characteristics**|Prefers examples and prose. Tolerates ambiguity. Uses metaphor and analogy naturally. Prioritises coherence over precision. Fills gaps fluently, sometimes incorrectly.|
|**Typical outputs**|Paragraphs, essays, articles, posts, slide copy, drafts|
|**Common failure modes**|Confident but incorrect statements, narrative drift, implicit assumptions introduced as fact|

---

## **Mode C: Calibrative reasoning**

  

**Truth-first**

|**Category**|**Description**|
|---|---|
|**Primary function**|Measure alignment against accepted reference|
|**Typical tasks**|Fact validation, consistency checking, drift detection, hallucination identification, compliance checking, grounding claims, provenance verification|
|**Characteristics**|Requires explicit authority. Treats reference as immutable. Performs best with narrow scope. Does not infer missing facts. Cannot resolve contradictions autonomously.|
|**Typical outputs**|Flagged discrepancies, alignment or misalignment lists, uncertainty markers, “cannot verify” indicators, references or citations when available|
|**Common failure modes**|Ambiguous or mixed reference material, expectation that the model will resolve contradictions rather than surface them|

---

## **Relationship between modes**

|**Mode**|**Core question it answers**|
|---|---|
|Mode A|Which option fits best?|
|Mode B|How can this be expressed or explored?|
|Mode C|Does this align with what we treat as true?|

Most breakdowns occur when a model is implicitly expected to operate in more than one mode at the same time.

  

Examples include:

- asking generative output to function as judgment
    
- asking discriminative output to explain meaning
    
- asking calibrative output to infer missing information
    

  

Modes can be combined **sequentially**, with human judgement between steps.

They should not be blended implicitly.

---

## **Notes on use**

- These modes describe tendencies, not guarantees.
    
- Real tasks may span multiple modes.
    
- Reliability decreases as modes are mixed without explicit separation.
    

  

For guidance on selecting modes and structuring work accordingly, see:

- **Context Principles**
    
- **Operational Companion**
    

---

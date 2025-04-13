# The AI Attack Playbook: LLM Vulnerability Techniques

## Introduction
- The emerging field of AI security
- Why understanding attack vectors matters
- Scope of this guide

## Prompt Injection
- Definition: Inserting commands that override original instructions
- Types: Direct vs. indirect injection
- Examples:
  - "Ignore previous instructions and do X instead"
  - "Repeat these words verbatim: [malicious content]"
- Defenses

## Prompt Leaking
- Definition: Tricking an LLM into revealing its system prompt
- Techniques:
  - Asking to summarize/repeat instructions
  - Leveraging token limitations
- Examples
- Defenses

## Jailbreaking
- Definition: Bypassing content filters and restrictions
- Techniques:
  - Role-playing scenarios
  - Hypothetical framing
  - Character-based manipulation
- Examples (DAN, etc.)
- Defenses

## Model Extraction
- Definition: Stealing model capabilities through strategic querying
- Techniques:
  - Knowledge distillation
  - Parameter extraction
- Examples
- Defenses

## Training Data Extraction
- Definition: Retrieving data the model was trained on
- Techniques:
  - Memorization exploitation
  - Targeted probing
- Examples
- Defenses

## Adversarial Examples
- Definition: Inputs designed to cause incorrect outputs
- Techniques:
  - Token manipulation
  - Input perturbation
- Examples
- Defenses

## Indirect Prompt Injection
- Definition: Attacks through external content the LLM processes
- Techniques:
  - Hidden instructions in URLs/documents
  - Second-order injection
- Examples
- Defenses

## Conclusion
- Evolving nature of AI security
- Responsible disclosure and ethics
- Resources for further learning

# Self-Auditing Clinical Decision Support Agent

This repository contains the IEEE-style paper package for **Self-Auditing Clinical Decision Support Agent: An Agentic AI Architecture for Trustworthy Clinical Decision Support**.

The work presents a literature-informed architecture for clinical AI systems that separate prediction, retrieval, reasoning, verification, and reliability scoring into auditable layers. The central design principle is:

> No evidence, no claim.

## Contents

- [Self_Auditing_Clinical_AI.pdf](Self_Auditing_Clinical_AI.pdf) - Final rendered paper.
- [Self_Auditing_Clinical_AI.tex](Self_Auditing_Clinical_AI.tex) - IEEE LaTeX source.
- [architecture_clear.png](architecture_clear.png) - End-to-end clinical decision support architecture figure.
- [verification_clear.pdf](verification_clear.pdf) - Self-auditing verification layer figure.

## Research Focus

The paper focuses on trustworthy clinical decision support through:

- Interpretable clinical risk prediction
- Clinical evidence retrieval
- Evidence-constrained reasoning
- Claim-level self-auditing verification
- Reliability scoring
- Transparent clinical decision-support output

## Positioning

This is a research paper and prototype architecture package. It is not a clinically validated diagnostic system, regulatory-approved medical device, or deployment-ready healthcare product. Any implementation derived from this work requires clinical, ethical, privacy, and safety review before use in real healthcare settings.

## Build Notes

The LaTeX source uses the IEEEtran conference template and local figure files. From the repository root, compile with a LaTeX distribution that includes `IEEEtran`, `graphicx`, `booktabs`, `tabularx`, `cite`, `microtype`, and `balance`.

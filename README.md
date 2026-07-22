# 🛡️ Prahari AI

> **A case-file-style Digital Public Safety prototype that turns suspicious calls into evidence-backed scam verdicts.**

[![ET AI Hackathon 2.0](https://img.shields.io/badge/ET%20AI%20Hackathon-2.0-blueviolet)](https://github.com/ridhi-png/prahari)
[![Prototype](https://img.shields.io/badge/Status-Prototype-orange)](https://github.com/ridhi-png/prahari)
[![Offline Ready](https://img.shields.io/badge/Works-Offline-success)](https://github.com/ridhi-png/prahari)

## The Problem

Digital-arrest and coercive scam calls are escalating fast. In just the first 9 months of 2024, India reportedly lost **₹1,776 Cr** to digital-arrest scams.  
Prahari AI is designed to help responders and citizens quickly classify suspicious call narratives with structured, explainable analysis.

## What Prahari AI Does

Prahari AI is a single-page, case-file web experience that:

- Analyzes a suspicious call transcript
- Runs a **multi-agent tribunal** of 4 independent AI roles:
  1. **Legal-Claim Verifier**
  2. **Coercion Analyst**
  3. **Financial Intent Agent**
  4. **Network Correlation Agent**
- Converges on a stamped verdict:
  - **SCAM CONFIRMED**
  - **CASE CLOSED — SAFE**
- Visualizes linked incidents on a detective-style corkboard
- Includes a counterfeit-currency screening exhibit

## How It Works (5-Layer Architecture)

1. **Data Sources**  
   Call transcript input, case metadata, and currency exhibit inputs.

2. **Ingestion Layer**  
   Structured parsing and normalization of statements, entities, and claim patterns.

3. **Intelligence Agents Layer**  
   Four independent agents review the same transcript from distinct reasoning lenses.

4. **Response Layer**  
   Tribunal convergence, confidence scoring, evidence traces, and stamped verdict output.

5. **Compliance & Knowledge Loop**  
   Case logging, investigator feedback, and evolving knowledge references for future patterns.

## Key Features

- **Tribunal Reasoning Engine**: Independent agent opinions before final convergence
- **Case Corkboard Network View**: Linked-case visual graph for pattern spotting
- **Currency Verification Exhibit**: Counterfeit-note screening as supporting evidence
- **Case-File UX**: Detective board narrative with verdict stamps and evidence blocks

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Architecture**: Single-file web app (no backend required)
- **Runtime**: Browser-based, can run fully offline

## Run Locally

No setup required.

1. Clone or download this repository.
2. Open `index.html` directly in your browser.

Or use the live demo: **https://ridhi-png.github.io/prahari/**

## Judging-Criteria Mapping

| Hackathon Criterion | Prahari AI Mapping |
|---|---|
| Problem Relevance | Targets high-impact digital-arrest fraud with clear public-safety utility |
| Innovation | Multi-agent tribunal reasoning with converged explainable verdict |
| Technical Execution | Lightweight single-page app, deterministic UX, no backend dependency |
| Usability & UX | Case-file format, stamped outcomes, evidence-first flow |
| Impact Potential | Fast triage support for citizens, institutions, and responders |

---

**Built for ET AI Hackathon 2.0**
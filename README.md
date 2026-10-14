# Eliciting, Specifying, and Validating Ethical Requirements in AI-Based Software Systems: A Structured Literature Synthesis and Lifecycle Framework

[![LaTeX Compilation](https://img.shields.io/badge/LaTeX-pdflatex-blue.svg)](https://www.latex-project.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> **Research Manuscript --- Requirements Engineering for AI (RE4AI)**  
> **Topic / Project:** NCKH - Nghiên cứu Khoa học  
> **Date:** October 2026  

---

## 📖 Overview

AI-based software systems increasingly raise ethical concerns that are difficult to translate into implementable software requirements. Although global guidelines identify values such as fairness, transparency, privacy, human oversight, safety, and accountability, practitioners still face a **principles-to-practice gap**.

This research presents a structured, literature-informed synthesis around three core research questions:
- **RQ1**: Which ethical requirements should be considered in AI-based software systems, and how can they be specified with measurable criteria?
- **RQ2**: Which techniques can elicit ethical requirements from direct and indirect stakeholders?
- **RQ3**: How can these requirements be validated and verified across the design, development, and operational AI lifecycle?

---

## 🧩 Key Conceptual Dimensions

The paper organizes ethical requirements into six primary dimensions:

1. **Fairness & Non-discrimination**: Disparate impact ratio, demographic parity, equalized odds, and subgroup error rate parity.
2. **Transparency & Explainability**: Feature importance (SHAP, LIME), contrastive explanations, model cards, and datasheets.
3. **Privacy & Data Governance**: Differential privacy ($\epsilon, \delta$), data minimization, consent tracking, and retention policies.
4. **Human Oversight & Autonomy**: Human-in-the-loop (HITL), human-on-the-loop (HOTL), and meaningful override capabilities.
5. **Safety, Robustness & Reliability**: Adversarial perturbation tolerance, out-of-distribution (OOD) detection, and fail-safe fallback modes.
6. **Accountability & Auditability**: Traceability graphs, immutable audit logging, incident response runbooks, and algorithmic impact assessments.

---

## 📂 Repository Structure

```text
.
├── .gitignore                           # Git ignore rules for LaTeX auxiliary files
├── README.md                            # Project overview and documentation
├── main.tex                             # Primary entrypoint for LaTeX compilation
└── ethical_requirements_ai_revised.tex   # Original manuscript source file
```

---

## 🛠️ How to Compile the LaTeX Manuscript

### Using `pdflatex` (Command Line)
```bash
pdflatex main.tex
pdflatex main.tex  # Run twice to resolve references and citations
```

### Using `latexmk`
```bash
latexmk -pdf main.tex
```

### Overleaf / TeXStudio / VS Code
- Import this repository directly into Overleaf or open the folder in VS Code with the **LaTeX Workshop** extension.
- Select `main.tex` or `ethical_requirements_ai_revised.tex` as the root document and build.

---

## 📑 Citation & Attribution

If you refer to this framework or manuscript in your research:

```bibtex
@article{nckh_re4ai_2026,
  title={Eliciting, Specifying, and Validating Ethical Requirements in AI-Based Software Systems: A Structured Literature Synthesis and Lifecycle Framework},
  author={Tran, Dinh Son and Contributors},
  journal={Requirements Engineering for AI (RE4AI) Research Manuscript},
  year={2026},
  month={October}
}
```

---

## 📄 License
This repository is open for research and academic purposes under the [MIT License](LICENSE).

## **CLARA: CL Accuracy Reference Agent**

[![Release](https://img.shields.io/github/v/release/Cellular-Semantics/clara-agent)](https://img.shields.io/github/v/release/Cellular-Semantics/clara-agent)
[![Build status](https://img.shields.io/github/actions/workflow/status/Cellular-Semantics/clara-agent/main.yml?branch=main)](https://github.com/Cellular-Semantics/clara-agent/actions/workflows/main.yml?query=branch%3Amain)
[![codecov](https://codecov.io/gh/Cellular-Semantics/clara-agent/branch/main/graph/badge.svg)](https://codecov.io/gh/Cellular-Semantics/clara-agent)
[![Commit activity](https://img.shields.io/github/commit-activity/m/Cellular-Semantics/clara-agent)](https://img.shields.io/github/commit-activity/m/Cellular-Semantics/clara-agent)
[![License](https://img.shields.io/github/license/Cellular-Semantics/clara-agent)](https://img.shields.io/github/license/Cellular-Semantics/clara-agent)

**Repository:** <https://github.com/Cellular-Semantics/clara-agent/>

**Documentation** <https://Cellular-Semantics.github.io/clara-agent/>

**CLARA** (_CL Accuracy Reference Agent_) is an agentic validation pipeline designed to improve the quality and reliability of the [Cell Ontology (CL)](https://github.com/obophenotype/cell-ontology) by verifying that term-level assertions are supported by referenced literature.

The system retrieves relevant full-text references for CL terms and automatically checks whether both formal and textual definitions are substantiated. Built on top of [PaperQA2](https://arxiv.org/abs/2403.04304) (Skarlinski et al., 2024), the current prototype has demonstrated high accuracy in detecting hallucinations and identifying unsupported claims—making it a valuable tool for ontology curators.

### ✨ Features

- Automated evidence validation for Cell Ontology term assertions
- Uses LLM-based semantic search (PaperQA2) to retrieve and assess supporting literature
- Integrates with GitHub Actions to run on pull requests, validating proposed terms and edits
- Supports synonym-aware matching and confidence scoring
- Designed to improve efficiency without sacrificing accuracy

### 📄 License

This project is licensed under the **Apache License 2.0**.
See the [LICENSE](https://github.com/Cellular-Semantics/clara-agent/blob/main/LICENSE) file for details.

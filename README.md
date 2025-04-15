# Samsung Prism - Universal Prompt Store for SmartThings

## 🌐 Overview

As LLM technology matures, numerous use cases in **Smart Home** and **Smart Building** domains can be realized using AI-driven inferences. However, there is currently no centralized repository that offers a **unified prompt store** and **benchmarking** of prompt performance across use cases.

This project aims to build a **Universal Prompt Store** for Samsung SmartThings, enabling reliable and comparative prompt engineering across diverse scenarios.

---

## 📌 Problem Statement

- With the stabilization of LLMs, there is a growing opportunity to apply them in smart environments.
- There is a lack of a **single source** for collecting, organizing, and benchmarking prompts for smart home and building scenarios.
- Prompt engineering evolves rapidly, making **comparison and versioning** of prompts crucial.
- There is a need for structured **experimentation** using well-defined prompts to derive accurate and efficient inferences.

---

## 🎯 Project Goals

- Create and maintain a **centralized repository of prompts** tailored for Smart Home and Smart Building use cases.
- Support a variety of **LLM-based use cases**, including:
  - Security monitoring
  - Device usage tracking
  - Activity recognition
  - Elderly care assistance
  - Data summarization
  - Device maintenance
  - Recipe recommendations
  - Energy consumption patterns
- Provide tools for **evaluating** and **comparing inference results** across different prompt versions and models.

---

## 📁 Repository Structure

```bash
samsung-prism/
├── prompts/
│   ├── smart_home/
│   └── smart_building/
├── datasets/
│   ├── open_source/
│   └── simulated/
├── evaluations/
│   └── inference_comparisons/
├── notebooks/
│   └── prompt_experiments.ipynb
├── docs/
│   └── prompt_guidelines.md
└── README.md

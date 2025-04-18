# Improving Reproducibility: A Case Study

> **Note**: This repository is a **fork** of the excellent work by **Subham Subba** and **Suman Chatterjee** in their paper:
["Machine learning-driven determination of key absorber layer parameters in perovskite solar cells"](https://doi.org/10.1016/j.mtcomm.2024.111113).  
>
> We acknowledge and appreciate their contributions to perovskite solar cell research.  
>
> Our goal here is **not to critique their work**, but to use it as a foundation to demonstrate reproducibility best practices for educational purposes.

---

## 🎯 Purpose of This Repository  
The original research provides insights into a predictive and interpretible model for device bandgap. Allowing for predictions on how device composition effects the bandgap, conduction band minimum (CBM) and valence band mimimum (VBM).

However, reproducing computational results can be challenging, even for robust research. This repository:  
- **Demonstrates** how to improve code accessibility for reproducibility.  
- **Highlights** tools and workflows to help others build on existing work.  
- Acts as a **learning resource** for open science practices.

---

## 🛠️ Workshop: Learn Reproducibility Step-by-Step  
This repository pairs with a **guided workshop** to teach reproducibility best practices using the original project as a case study.  
- **What you’ll learn**: Dependency isolation, project organization, and documentation.  
- **Get started**: Follow the [workshop guide](./WORKSHOP.md) to explore iterative improvements branch-by-branch.  

---

## 🔍 What We’ve Changed (and Why)  
To make the project more approachable for newcomers, we’ve iterated on the original code with:  

| Improvement               | Branch           | Tools Used          |  
|---------------------------|------------------|---------------------|  
| Dependency Management     | `dependencies`   | `project.toml`, `uv` |  
| Organized Project Structure| `structure`      | Modular folders, path fixes |  
| Documentation             | `docs`           | `README.md`, docstrings |  

**This is not a judgment on the original work** — all research code evolves! We aim to show how small changes can amplify impact.  

---

## 🙏 Acknowledgments  
- **Original Authors**: [@subhamsubba](https://github.com/subhamsubba/analysis) for their foundational work.  
- **Paper**: Subba and Chatterjee, “Machine Learning-Driven Determination of Key Absorber Layer Parameters in Perovskite Solar Cells.” (https://doi.org/10.1016/j.mtcomm.2024.111113).  


<!-- ---

## 🚀 How to Use This Repository  
1. **Compare Branches**:  
   ```bash
   git checkout main          # Original code (unchanged)
   git checkout dependencies  # Dependency improvements
   git diff main..dependencies
   ``` -->
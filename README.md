# code-unza25-csc4792-project_team_20-repository
# CSC 4792 | Assignment #5: Business Understanding Checkpoint  
**Deadline:** August 16, 2025 | **Course Year:** 2024/25  

---

## 📌 Project Title  
**Reference Author Affiliation: Predict if Authored by the University of Zambia Staff**

---

## 👥 Team Members  
- Taonga  
- Chibwanta  
- Ebenezer  
- Nelson
- Stephan

(*Each member has contributed to this submission with a commit tagged `[BU]`.*)

---

## 1. Business Understanding  

### Problem Statement  
The University of Zambia wants to quickly identify research authored by its staff in the institutional repository.  
Manually verifying affiliations is **slow and error-prone**.  
We aim to build a **predictive model** that classifies whether an ETD document was authored by UNZA staff, based on metadata and content.  

---

### Business Objectives  

**What does "success" look like from a practical perspective?**

**Primary Success Indicators:**  
- **Automated Classification**: System can process references faster than manual review  
- **Research Visibility**: UNZA can quickly identify and showcase internal research citations  
- **Administrative Efficiency**: Reduce reference review time from days to hours  
- **Decision Support**: Enable evidence-based faculty evaluation and research planning  

**Practical Success Metrics:**  
- **Time Savings**: 80% reduction in manual reference verification time  
- **Processing Capability**: Handle 100–200 ETDs for comprehensive analysis  
- **Accuracy**: >80% classification accuracy for administrative decision-making  
- **User Adoption**: Research staff can operate system with minimal training  

---

### Data Mining Goals  
Primary goal: **Build a supervised classification model**  
- We will build and evaluate a **binary classifier** that inputs parsed reference metadata and outputs:  
  - **1** → Authored by UNZA Staff  
  - **0** → Non-UNZA Author  

---

### Initial Project Success Criteria  
- **Accuracy**: The model should achieve at least **80% accuracy** and **F1-score ≥ 0.80** on a held-out test dataset when classifying ETDs as authored by UNZA staff or not.  
- **Efficiency**: The model should reduce manual affiliation verification time by at least **80%** compared to the current process.  
- **Processing Capability**: The model should be able to process at least **50 ETDs per hour** on available university hardware or cloud resources.  

---

## 📂 Repository Structure  

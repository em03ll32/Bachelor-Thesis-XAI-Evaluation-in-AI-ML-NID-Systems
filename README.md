# XAI Evaluation in AI/ML NID Systems

## Abstract
The accelerating integration of machine learning (ML) and artificial intelligence (AI) into network intrusion detection systems (NIDS) enhances threat detection capabilities but introduces the challenge of algorithmic opacity, complicating the interpretation of security alerts for analysts. 

This thesis empirically evaluates the explanatory quality and domain suitability of two prominent explainable AI (XAI) methods: **Local Interpretable Model-agnostic Explanations (LIME)** and **SHapley Additive exPlanations (SHAP)**, within the context of digital forensics and network security. 

The applied quantitative experimental framework trains advanced tree-based ML classifiers (Random Forest, XGBoost, CatBoost) on widely used NIDS datasets (CIC-IDS2017 and CSE-CIC-IDS2018). Comparing the XAI methods, this study analyzes descriptive accuracy, sparsity, stability, and runtime using a rigorous statistical testing framework. 

**Key Findings:**
* **SHAP** is generally preferred in high-stakes environments if precise and stable feature attribution is needed, though its high computational complexity limits it to low-frequency scenarios.
* **LIME** may be preferable during time- and resource-sparse scenarios, such as incident response, or if a more thorough feature analysis is required.

By providing a statistically validated framework for XAI evaluation, this research addresses the selection challenges in cybersecurity stemming from the inherent trade-off between classification model accuracy and explainability. The comparative analysis equips practitioners with the evidence needed to align defense strategies with specific operational needs.

## Keywords
`Network Intrusion Detection Systems` `Explainable AI` `Machine Learning` `LIME` `SHAP` `Evaluation Metrics` `Cybersecurity`

---

## Bachelor Thesis Verification
*Original hash values for the submitted thesis document.*

| Algorithm | Hash Value |
| :--- | :--- |
| **SHA256** | `0fbb7c024d3574802ca5f4f50382656b45d9f98aadbdde0ce87264111b406d07` |
| **SHA512** | `a33f35c6d5e1896529439b96a0d17ca3e9fcfcdad31a1c3f0ec76a301b23974734f4e544cd00199d7f37252fd3cdb6846c71d033064ae00368b05f9af09afbb0` |

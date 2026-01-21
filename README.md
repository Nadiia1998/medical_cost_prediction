# Healthcare Cost Prediction with Explainable AI

[Try the model](https://nadiia199826-medical-cost-prediction.hf.space/?__theme=system&deep_link=CFMsjaEQdrE)

## Project Overview
This project aims to predict **annual healthcare treatment costs** for patients based on
demographic, lifestyle, medical, and insurance-related factors.

In addition to accurate predictions, the system provides **transparent explanations**
using SHAP, highlighting which factors contribute most to the final cost estimate.

The solution includes an interactive **Gradio web interface** for real-time predictions
and explanations.

---

## Project Goals
- Build reliable regression models for healthcare cost estimation
- Combine multiple models using an ensemble approach
- Provide **human-readable explanations** for each prediction
- Deliver an easy-to-use web interface for non-technical users

---

## Models Used
- Random Forest Regressor
- Gradient Boosting Regressor
- **Stacking Regressor** as the final ensemble

---

## Explainability
The project uses **SHAP (SHapley Additive exPlanations)** to:
- Identify the most influential features
- Show positive cost drivers
- Express feature impact as a percentage of total predicted cost

## Web Application
The Gradio interface allows users to:
- Enter patient data with sensible default values
- Select binary medical conditions using Yes/No inputs
- Receive:
  - Predicted annual cost
  - Top cost-driving factors in plain English


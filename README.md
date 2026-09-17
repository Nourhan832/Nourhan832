# Hi, I'm Nourhan Hamze

I am a **junior AI/ML engineer** with a background in mechatronics and an M.E. in Electrical and Computer Engineering focused on **Artificial Intelligence and Machine Learning** at the American University of Beirut.

My work centers on developing reliable, interpretable, and uncertainty-aware AI systems, particularly for healthcare applications. I am interested in clinical machine learning, explainable AI, LLM evaluation, hybrid ML–LLM systems, and applied AI engineering.

## Featured research

### [Machine Learning for Amblyopia Outcome Prediction](https://github.com/Nourhan832/amblyopia-outcome-prediction)

Clinical machine-learning research using routinely collected data to predict treatment response and final visual outcomes in pediatric amblyopia.

- Evaluated Logistic Regression, Random Forest, Extra Trees, and CatBoost.
- Used SHAP to interpret influential clinical predictors.
- Conducted baseline-only sensitivity analysis to distinguish presentation-time prognosis from treatment-informed prediction.
- Accepted for publication in the *Journal of the American Association for Pediatric Ophthalmology and Strabismus (Journal of AAPOS)*.

### Amblyopia Hybrid ML–LLM Decision-Support Agent

An uncertainty-aware extension of the amblyopia prediction research that combines Random Forest and LLM outputs through trust-based agreement gating.

- Achieved 72.8% gated accuracy at 69.5% coverage versus 66.8% ML-only and 64.9% LLM-only performance.
- Routes accepted cases to outcome-specific regression and defers uncertain or conflicting cases for clinician review.
- Built and deployed a FastAPI research prototype integrating ML and LLM inference on Render with API rate limiting.
- [Live demo](https://amblyopia-website-5wk5.onrender.com)

### [LLM Robustness Against Public Health Misinformation](https://github.com/Nourhan832/llm-public-health-robustness)

A multi-layer framework for evaluating how LLMs respond to neutral, misinformation-seeking, and provocative public-health prompts.

- Compared DeepSeek, GPT-4.1-nano, LLaMA, and Gemini across 6,273 prompts.
- Combined mechanistic behavioral metrics with a rubric-guided LLM-as-a-Judge evaluation.
- Contributed to generating and structuring prompts for all evaluated LLMs.
- Implemented the Layer 2 LLM-as-a-Judge evaluation.
- Presented at FedCSIS 2026.

## Additional engineering work

- **[ResQDrones](https://github.com/Nourhan832/resqdrones-firefighting-drone):** A semi-autonomous firefighting-drone prototype using YOLOv8 fire detection, Raspberry Pi, IoT alerts, structural simulation, and physical flight testing. Supported through TÜBİTAK 2209-A funding and recognized as a Best Graduation Project.
- **LightAid:** An offline Li-Fi emergency communication concept for environments where conventional connectivity is unavailable.
- **[Haris](https://github.com/Nourhan832/haris-team23):** Security middleware for protecting multi-agent and LangGraph-based AI workflows, developed as a team project in Amazon Industry Program 5.0. This repository is maintained as a portfolio copy of the original Team 23 project.

## Technical focus

- **Machine Learning:** Python, scikit-learn, XGBoost, TensorFlow/Keras, pandas, NumPy, model validation, SHAP, conformal prediction
- **LLMs & AI Systems:** LLM evaluation, adversarial testing, LLM-as-a-Judge, prompt engineering, OpenAI API, Claude API
- **Computer Vision & Engineering:** YOLOv8, C/C++, MATLAB/Simulink, Raspberry Pi, AWS IoT, Git, Linux
- **Familiar with:** LangGraph, FastAPI, REST APIs, Render, API rate limiting

## Highlights

- Journal of AAPOS paper accepted in 2026
- FedCSIS 2026 research paper
- 1st Place — WiDS @ AUB Hackathon 2025
- TÜBİTAK 2209-A Research Project Funding Recipient
- High Honors graduate in Mechatronics Engineering

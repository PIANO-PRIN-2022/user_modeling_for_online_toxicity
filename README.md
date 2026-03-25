# user_modeling_for_online_toxicity

This repository collects the models and tools developed by the UniPI team 
within the PIANO project (WP2 - User Modeling).

## Models and Tools

### UTOXIC
An Interpretable Data-Driven Approach for Modeling Toxic Users via Feature Extraction  
*Gneri, Pollacci, Guidotti*  
🔗 https://github.com/LauraPollacci/UTOXIC

UTOXIC is an interpretable machine learning framework for detecting and characterizing toxic users in Online Social Networks. 
It extracts linguistic, stylistic, affective, and clustering-based features from user comments, then performs both binary 
classification (toxic vs. non-toxic) and multi-class classification (harassment, violence, racism, vulgarity). 
The framework integrates SHAP-based explainability techniques to provide transparent, interpretable insights at both local and global levels. 
Evaluated on a Reddit dataset of over 8 million comments from 15,000 users, UTOXIC achieves up to 93.6% accuracy in binary classification.

If you use this package in your research, please cite:
```bibtex
@inproceedings{pollacci2025interpretable,
  title={An Interpretable Data-Driven Approach for Modeling Toxic Users via Feature Extraction},
  author={Pollacci, Laura and Gneri, Jacopo and Guidotti, Riccardo},
  booktitle={World Conference on Explainable Artificial Intelligence},
  pages={180--201},
  year={2025},
  organization={Springer}
}
```

---

### TRAITS
Unsupervised and Interpretable Detection of User Personalities in Online Social Networks  
*Cascione, Pollacci, Guidotti*  
🔗 https://github.com/acascione/traits

TRAITS (Tool for Revealing Attributes and Identifying Toxic and Safe profiles) is an unsupervised, interpretable framework for detecting personality profiles of users in Online Social Networks. 
It leverages latent embeddings derived from Transformer-based personality detectors trained on an external dataset (PANDORA/OCEAN), 
combined with linguistic and affective features, to cluster users into behavioral profiles without requiring ground-truth personality labels. 
Applied to a Reddit dataset of 15k users, TRAITS identifies six distinct profiles (Aggressive, Provocative, Mildly-Toxic, Constructive, Contentious, and Neutral), providing transparent, 
explainable insights to support personalized moderation strategies.

If you use this package in your research, please cite:
```bibtex
@inproceedings{cascione2025unsupervised,
  title={Unsupervised and Interpretable Detection of User Personalities in Online Social Networks},
  author={Cascione, Alessio and Pollacci, Laura and Guidotti, Riccardo},
  booktitle={World Conference on Explainable Artificial Intelligence},
  pages={162--179},
  year={2025},
  organization={Springer}
}
```

---

### SIMVALE
Multi-domain Validation of LLM-Based Simulators via Interpretable and Latent Representations  
*Coda Giorgio, Fidone, Pollacci*  
🔗 https://github.com/LauraPollacci/SIMVALE

SIMVALE (Simulator Validation with Latent Embeddings) is a generalizable, multi-domain framework for quantitatively assessing the fidelity of LLM-based social simulators. 
It combines interpretable feature extraction across multiple domains (linguistic style, readability, sentiment, toxicity, personality) with latent representations obtained from fine-tuned BERT models, 
enabling both global and local validation at the level of behavioral profiles. 
Applied to an Online Social Network simulator (COSMOS), SIMVALE evaluates how well simulated user behavior matches real-world patterns and how effectively different moderation strategies reduce harmful content.

If you use this package in your research, please cite:
```bibtex
@inproceedings{coda2025multi,
  title={Multi-domain Validation of LLM-Based Simulators via Interpretable and Latent Representations},
  author={Coda-Giorgio, Luca and Fidone, Giacomo and Pollacci, Laura},
  booktitle={International Conference on Discovery Science},
  pages={411--426},
  year={2025},
  organization={Springer}
}
```

---

### Eval_Moderation_OSN
Evaluating Moderation in Online Social Network  
*Pollacci, Milli, Guidotti*  
🔗 https://github.com/GiulioRossetti/Eval_Moderation_OSN
🔗 https://github.com/LauraPollacci/Eval_Moderation_OSN

Eval_Moderation_OSN is a simulation-based framework for studying the dynamics of toxic content propagation and the effectiveness of moderation strategies in Online Social Networks. 
It provides implementations of the SEIZ (Susceptible–Exposed–Infected–Skeptic) epidemic model in three variants: a baseline model without moderation, a version with a basic moderator applying uniform interventions, 
and a smart moderator version that leverages user psychological profiles based on Dark Triad traits to deliver personalized, threshold-driven moderation. 
Personalized moderation proves significantly more effective than generic approaches in limiting the spread and persistence of toxic behavior, offering a flexible tool for designing adaptive content governance strategies.

If you use this package in your research, please cite:
```bibtex
@article{milli2025evaluating,
  title={Evaluating Moderation in Online Social Network},
  author={Milli, Letizia and Pollacci, Laura and Guidotti, Riccardo},
  journal={arXiv preprint arXiv:2512.20225},
  year={2025}
}
```

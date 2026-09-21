---
title: "Predicting survival of patients with deep burns using supervised machine learning algorithms"
date: 2026-09-15
author: "Ethan4325"
issue: https://github.com/deepcharles/macs3050-journal/issues/81
---

### Students

Ethan

### Question 1: Reference

```bibtex
Hashemi, S., Keshavarzi, A., Erfannia, L., Zarei, A., & Yazdani, A. (2026a). Predicting survival of patients with deep burns using supervised machine learning algorithms. Scientific Reports. https://doi.org/10.1038/s41598-026-70066-8

Hashemi, S., Keshavarzi, A., Erfannia, L., Zarei, A., & Yazdani, A. (2026b). Predicting survival of patients with deep burns using supervised machine learning algorithms. Scientific Reports. https://doi.org/10.1038/s41598-026-70066-8

Hashemi, S., Keshavarzi, A., Erfannia, L., Zarei, A., & Yazdani, A. (2026c). Predicting survival of patients with deep burns using supervised machine learning algorithms. Scientific Reports. https://doi.org/10.1038/s41598-026-70066-8

Hashemi, S., Keshavarzi, A., Erfannia, L., Zarei, A., & Yazdani, A. (2026d). Predicting survival of patients with deep burns using supervised machine learning algorithms. Scientific Reports. https://doi.org/10.1038/s41598-026-70066-8
```

### Question 2: Research question

The research asks whether machine learning can accurately predict death in deep-burn patients using only data from the first 24 hours. It matters because early prediction can help doctors prioritize treatment and resources for high-risk patients.

### Question 3: Data

Who: 528 patients with deep (third-degree) burns; 240 died in the hospital and 288 survived.
What: 24 variables measured within the first 24 hours, including burn size (%TBSA), age, sex, inhalation injury, burn cause, laboratory results, and other clinical factors. The main outcome was in-hospital death.
When: The study was conducted in 2024, using information from the first 24 hours after admission.
Where: Amir al-Momenin Burn Trauma Training and Treatment Center in Shiraz, Iran.
How: Researchers performed a retrospective analysis of hospital patient records, using only data available during the first 24 hours to avoid data leakage.

### Question 4: Results

The logistic regression model performed very well, with an AUROC of 0.992 and only 5 errors out of 106 patients. Burn size (%TBSA) was the strongest predictor. The data supports the findings, but the model still needs testing in other hospitals.

### Question 5: Cited articles

@article{park2022prediction,
  title={Prediction of Mortality after Burn Surgery in Critically Ill Burn Patients Using Machine Learning Models},
  author={Park, Ji Hyun and Cho, Yongwon and Shin, Donghyeok and Choi, Seong-Soo},
  journal={Journal of Personalized Medicine},
  volume={12},
  number={8},
  pages={1293},
  year={2022},
  doi={10.3390/jpm12081293}
}

@article{schmidt2025bochum,
  title={Bochum Burn Survival (BoBS) score - A novel machine learning-based burn survival prediction score developed with data from the German Burn Registry},
  author={Schmidt, Sonja Verena and Drysch, Marius and Reinkemeier, Felix and Puscz, Flemming and Hinzmann, Jannik and Lehnhardt, Marcus and Wallner, Christoph},
  journal={Burns},
  volume={51},
  number={8},
  pages={107614},
  year={2025},
  doi={10.1016/j.burns.2025.107614}
}


@article{motamedi2025simultaneous,
  title={Simultaneous prediction of early and delayed mortality in burn patients: a comparative machine learning analysis of feature importance in a single-center retrospective study},
  author={Motamedi, Mehran and Moallemkolaei, Najibeh Mohseni and Hesamirostami, Mohammadhossein and Ghorbani, Mojtaba and Shokrizadeh Arani, Leila},
  journal={BMC Medical Informatics and Decision Making},
  volume={26},
  number={1},
  pages={7},
  year={2025},
  doi={10.1186/s12911-025-03311-1}
}

### Question 6: Questions for the authors

Why did you choose logistic regression as the final model instead of a more complex model with similar performance?
How well do you expect the model to work in other hospitals or countries?
How would doctors choose the best risk threshold for deciding which patients need more urgent care?

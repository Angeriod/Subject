# Binary Classification Prediction Project

## Project Overview

This project focuses on solving a binary classification problem using a detailed dataset and applying advanced data science techniques. The main goal was to accurately predict two distinct classes using a variety of models and methodologies.

### Dataset Summary

- **Features**: 1000 continuous variables (`X0` to `X999`).
- **Training Set**: 5000 instances (Positive class: 436, Negative class: 4564).
- **Test Set**: 3500 instances.
- **Evaluation Metric**: F1-score.

## Methodologies

The project employed several key techniques to address the challenges posed by the dataset, particularly its imbalanced nature and high dimensionality.

1. **Oversampling**: To counter the imbalance in the training set, oversampling methods were applied to increase the representation of the minority class.
2. **PCA (Principal Component Analysis)**: PCA was utilized to reduce the dimensionality of the dataset, focusing on retaining the most informative features.
3. **Ensemble Modeling on Ensemble Modeling**: An ensemble of approximately 15 different models was created to leverage the strengths of various predictive models and improve overall accuracy. plus, performed ensemble modeling on ensemble modeling

## Challenges and Solutions

- **Model Performance Variability**: The performance of the models varied significantly with different `random_state` values. A specific value was identified and fixed to ensure consistent model training and evaluation.
- **Softmax Ensemble Limitations**: Experimentation with softmax ensemble techniques revealed that merely stacking ensemble models does not guarantee performance improvements, highlighting the complexity of model integration. 예를 들어, "Ensemble modeling on top of another ensemble modeling also did not guarantee performance improvements 

## Achievements

The project achieved an impressive **2nd place** in the competition, demonstrating the effectiveness of the chosen methodologies and the strategic approach to overcoming the challenges encountered.

![머신러닝](https://github.com/Angeriod/Subject/assets/97516571/fbb4ba13-93e6-4f1c-8ff8-1e86672a52fa)

## Key Takeaways

This project underscores the importance of:
- Addressing dataset imbalances through oversampling.
- Reducing feature space dimensionality to enhance model performance.
- Carefully combining multiple models to improve prediction accuracy.
- Recognizing the limitations of certain techniques, such as softmax ensembles, in specific contexts.

By meticulously addressing each aspect of the project, from dataset preparation to model selection and integration, significant progress was made in binary classification prediction, as evidenced by the high placement in the competition.

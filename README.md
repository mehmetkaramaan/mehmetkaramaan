<div align="center">

# Mehmet Mikail Karaman

### Artificial Intelligence · Python · Engineering

**AI Master's Student | AI Model Development | Mechanical Engineering Background**

[Computer Vision](#selected-ai-projects) · [Machine Learning](#selected-ai-projects) · [Time Series](#areas-of-interest) · [Control Engineering](#engineering-background)

</div>

---

## About me

I'm pursuing a **master's degree in Artificial Intelligence** and developing AI models with **Python**. My interests span **machine learning, deep learning, image processing, computer vision, and time series analysis**.

During my **undergraduate studies in Mechanical Engineering**, I developed my knowledge and skills in **control engineering**. That background shapes how I approach AI: understanding system behavior, working with measurements, and connecting models to practical engineering problems.

My projects include medical image segmentation, plant disease classification for a camera-based application, and tabular machine learning. I enjoy taking a project from data preparation and model training to evaluation, visualization, and deployment-oriented model export.

## Selected AI projects

### 🌿 Plant Disease Camera AI

**EfficientNetB0 · Transfer Learning · TensorFlow Lite**

I trained a model for an application that identifies supported plants and predicts diseases or healthy conditions from a camera image of a leaf. The workflow combines **PlantVillage, FieldPlant, and PlantDoc**, harmonizes class names, converts annotated boxes into classification crops, and trains a **50-class EfficientNetB0** model.

- Two-stage training: pretrained feature extraction followed by fine-tuning.
- Recorded pooled internal-test accuracy: **92.59%**; Top-3 accuracy: **98.49%**.
- Includes class-level evaluation, training curves, and TensorFlow Lite export code.

[Explore the project →](https://github.com/mehmetkaramaan/plant-disease-camera-ai)

### 🩻 BreastDM Lesion Segmentation

**MLSRS-SegFormer · Transformers · Medical Image Processing**

I implemented a custom **TensorFlow/Keras MLSRS-SegFormer** model to predict pixel-level breast lesion masks using **BreastDM**. The project covers paired image/mask preprocessing, augmentation, multi-scale transformer features, Bayesian hyperparameter search, and visual comparison of predictions with reference masks.

- Best observed validation Dice: **0.6052**, with IoU **0.5000** at the same epoch.
- Includes recorded experiment evidence and documented evaluation limitations.

[Explore the project →](https://github.com/mehmetkaramaan/breastdm-mlsrs-segformer)

### 📊 Credit Approval Classification

**scikit-learn · Tabular Data · Model Comparison**

I explored the **UCI Credit Approval** dataset through missing-value handling, categorical encoding, scaling, and classification. I compared **Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, and SVM**, then explored Gradient Boosting tuning and cross-validation.

- Recorded baseline Gradient Boosting test accuracy: **91.30%**; ROC-AUC: **0.9591**.
- Includes confusion matrices, a separate train/test comparison, and reproducibility notes.

[Explore the project →](https://github.com/mehmetkaramaan/credit-approval-machine-learning)

*Metrics summarize saved experiments with different tasks and evaluation protocols. Each repository explains its dataset splits, preprocessing choices, and limitations.*

## Tools I work with

| Area | Tools and experience |
| --- | --- |
| Programming | **Python**, C++ |
| Deep learning | TensorFlow, Keras, transfer learning, custom model layers |
| Machine learning | scikit-learn, model comparison, GridSearchCV, cross-validation |
| Data preparation | NumPy, pandas, class mapping, augmentation, missing-value handling |
| Evaluation and visualization | Matplotlib, Seaborn, confusion matrices, classification and segmentation metrics |
| Model tuning and export | Keras Tuner, Bayesian search, TensorFlow Lite conversion |

## Engineering background

**Mechanical Engineering undergraduate studies → Control engineering development → Master's studies in Artificial Intelligence**

I am interested in bringing these areas together through data-driven modeling, analysis of dynamic systems, and AI applications that connect software with the physical world.

## Areas of interest

- **AI model development:** training, fine-tuning, evaluating, and improving models.
- **Computer vision and image processing:** classification, segmentation, and visual feature learning.
- **Time series analysis:** temporal patterns, forecasting, and sensor-data applications.
- **AI and control engineering:** exploring how learned models can support engineering systems.

---

<div align="center">

**Turning data into models, and models into practical applications.**

</div>

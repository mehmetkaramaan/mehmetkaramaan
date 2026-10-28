[Connect with me on LinkedIn](https://www.linkedin.com/in/mehmetmikailkaraman/)

<div align="center">

# Mehmet Mikail Karaman

### Artificial Intelligence · Python · Autonomous Systems

**AI Master's Student | AI Model Development | Mechanical Engineering Background**

[Computer Vision](#selected-projects) · [Machine Learning](#selected-projects) · [Time Series](#areas-of-interest) · [Control Engineering](#engineering-background)

</div>

---

## About me

I'm pursuing a **master's degree in Artificial Intelligence** and developing AI models with **Python**. My interests span **machine learning, deep learning, image processing, computer vision, control engineering and time series analysis**.

I also work with **C++ and object-oriented programming (OOP)**. My repositories include explanations and examples of **C++ lambda expressions**, alongside small applications that explore classes, object interactions, and reusable program structure. I use these projects to connect programming concepts with practical implementations.

During my **undergraduate studies in Mechanical Engineering**, I developed my knowledge and skills in **control engineering**. I have designed a **UAV control system**, worked with **control algorithms**, and used **Kalman filtering**. These experiences connect my interest in AI with dynamic systems, measurements, and engineering applications.

My image-processing work also includes **windowing-based image filtering**. In addition, I have taken courses and carried out studies in **antenna theory and signal processing**, broadening my background in signals, filtering, and engineering systems.

My AI projects include medical image segmentation, plant disease classification for a camera-based application, and tabular machine learning. I enjoy taking a project from data preparation and model training to evaluation, visualization, and deployment-oriented model export.

My recent engineering projects include **AERIS**, a camera-guided autonomous UAV firefighting simulation using **Gazebo, PX4 SITL, Python, OpenCV and MAVLink**, and **NASA C-MAPSS turbofan sensor forecasting**, comparing ten ML/DL models with a persistence baseline. I build interactive interfaces to make mission state, sensor measurements, predictions and model errors easier to inspect.

## Selected projects

### AERIS — Autonomous UAV Firefighting

**Gazebo · PX4 SITL · Python · OpenCV · MAVLink · A\* · Coverage Planning**

I developed a simulated UAV system that visually discovers a water station, refills, searches for unknown fire locations, performs simulated suppression, verifies the result from camera observations, and returns to its recorded launch position. It combines **LiDAR-based obstacle avoidance**, persistent camera-coverage mapping and a ground control station with live video, telemetry and event logs.

- One controlled benchmark completed **441/441 search cells**, suppressed **two fires** and performed **two refills**.
- Coverage-aware routing reduced flown distance from **692.8 m to 413.2 m (40.4%)** versus the earlier planner on the same fire/station layout. This is a single-run comparison, not a general performance guarantee.
- The showcase includes a **40-second Gazebo recording**, three GCS captures, architecture and validation results, plus independent Python examples with **six public sample tests**.
- **Selected source publication:** the integrated mission, perception, avoidance and flight-command implementation remains private. This project has been tested in simulation; no physical flight is claimed.

[Explore the project →](https://github.com/mehmetkaramaan/aeris-uav-showcase)

### NASA C-MAPSS — Turbofan Sensor Forecasting

**Python · Time Series · Machine Learning · Deep Learning · Interactive Visualization**

I compared **ten learned models and a persistence baseline** for **next-cycle T50 sensor prediction** using NASA C-MAPSS FD001 engine trajectories. Each forecast uses the preceding **30 operating cycles**; engine-level train/validation separation and training-only preprocessing limit information leakage.

- Models include KNN, Decision Tree, Random Forest, Extra Trees, Gradient Boosting, XGBoost, CatBoost, LightGBM, MLP and SimpleRNN.
- **CatBoost**, selected by validation RMSE, achieved recorded held-out test **RMSE 4.1227 °R** and **MAE 3.2940 °R**, versus persistence RMSE **5.6698 °R**: **27.29% lower RMSE** in that experiment.
- Built an English browser dashboard with an animated engine schematic, recorded sensor playback, and **one to four independent forecast/residual panels**, MAE/RMSE comparison and CSV export.
- The dashboard replays recorded measurements and stored forecasts; it is not a thermodynamic simulator or a remaining-useful-life predictor.

[Explore the code and results →](https://github.com/mehmetkaramaan/turbofan-sensor-forecasting-dashboard) · [Open the live demo →](https://mehmetkaramaan.github.io/turbofan-sensor-forecasting-dashboard/)


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
| Programming | **Python**, **C++**, object-oriented programming, lambda expressions |
| Control and estimation | UAV simulation, control algorithms, Kalman filtering, bounded motion commands |
| Robotics and ground control | Gazebo, PX4 SITL, MAVLink, OpenCV camera processing, LiDAR-based avoidance, telemetry dashboards |
| Navigation and coverage | A* route planning, camera-footprint coverage mapping, set-cover and 2-opt route refinement |
| Time-series forecasting | NASA C-MAPSS sensor windows, XGBoost/CatBoost/LightGBM, tree ensembles, MLP, SimpleRNN, persistence baselines |
| Signals and image filtering | Windowing-based image filtering; coursework and studies in signal processing and antenna theory |
| Deep learning | TensorFlow, Keras, transfer learning, custom model layers |
| Machine learning | scikit-learn, model comparison, GridSearchCV, cross-validation |
| Data preparation | NumPy, pandas, class mapping, augmentation, missing-value handling |
| Evaluation and visualization | Matplotlib, Seaborn, confusion matrices, classification and segmentation metrics |
| Model tuning and export | Keras Tuner, Bayesian search, TensorFlow Lite conversion |

## Programming examples

- [C++ Lambda Expressions](https://github.com/mehmetkaramaan/LAMBDA_EXPRESSIONS): explanations and examples exploring lambda expressions in C++.
- [Coffee Machine Project](https://github.com/mehmetkaramaan/CoffeMachine_Project): a Python application built with classes and object interactions.
- [The Quiz Project](https://github.com/mehmetkaramaan/The-Quiz-Project): an application exploring object-oriented programming concepts.
- [C++ Snake Game](https://github.com/mehmetkaramaan/Cpp): a game project applying C++ programming.

## Engineering background

**Mechanical Engineering undergraduate studies → Control engineering development → Master's studies in Artificial Intelligence**

My control engineering work includes UAV control system design, control algorithms, and Kalman filtering. Through AERIS, I apply this background to simulated autonomous missions, perception-guided search, obstacle avoidance and ground control. My turbofan forecasting project connects time-series modeling with engine sensor measurements and comparative evaluation. Alongside coursework in antenna theory and signal processing, I am interested in connecting engineering systems with data-driven models.

## Areas of interest

- **AI model development:** training, fine-tuning, evaluating, and improving models.
- **Computer vision and image processing:** classification, segmentation, and visual feature learning.
- **Time series analysis:** temporal patterns, forecasting, and sensor-data applications.
- **AI and control engineering:** exploring how learned models can support engineering systems.

---

<div align="center">

**Turning data into models, and models into practical applications.**

</div>

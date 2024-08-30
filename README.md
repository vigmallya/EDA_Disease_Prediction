
# Parkinson's disease Detection

[![Binder](https://img.shields.io/badge/launch-Jupyter_Notebook-orange?logo=jupyter&logoColor=white)](https://mybinder.org/v2/gh/vigmallya/EDA_Disease_Prediction/HEAD?labpath=Parkinsons_Disease_Detection.ipynb)

Parkinson's disease is a long-term, progressive neurological disorder that primarily affects movement, leading to symptoms like tremors, muscle stiffness, slowness of movement, and difficulties with balance and coordination. As the disease progresses, these symptoms can worsen, significantly impacting a person's daily life and independence. Detecting Parkinson's early is crucial, as it allows for timely intervention and management strategies that can help slow the progression of symptoms and improve the quality of life for those affected. To aid in early detection, researchers often analyze various data points, particularly those related to voice characteristics, which can be early indicators of the disease. 

The dataset used for detecting Parkinson's includes measurements of vocal features such as fundamental frequency (`MDVP:Fo(Hz)`, `MDVP:Fhi(Hz)`, `MDVP:Flo(Hz)`), variations in pitch (`Jitter` metrics), variations in amplitude (`Shimmer` metrics), and other attributes like the harmonic-to-noise ratio (`HNR`) and signal fractal scaling measures (`RPDE`, `DFA`). These features are derived from voice recordings of 195 individuals and are analyzed to identify patterns that distinguish between those with Parkinson's (`status` = 1) and those without it (`status` = 0). By studying these subtle changes in voice, researchers can develop more accurate and earlier diagnostic tools, which are crucial for managing the disease and helping patients maintain their independence and well-being for as long as possible.

To predict whether an individual has Parkinson's disease based on the vocal features in the dataset, I have implemented several machine learning models, including the Support Vector Machine (SVM) classifier, XGBoost, and logistic regression. These models are well-suited for classification tasks like this, where the goal is to accurately distinguish between individuals with and without the disease. Each model was trained on the dataset to learn patterns associated with Parkinson's, utilizing the vocal measurements as input features. After training, the models were evaluated using accuracy scores to determine how well they could predict the presence of Parkinson's disease. By comparing the performance of these models, I aimed to identify the most reliable method for early detection, potentially offering valuable tools for clinicians in diagnosing Parkinson's disease at an early stage, when interventions can be most effective.

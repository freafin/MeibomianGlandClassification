# MeibomianGlandClassification
This code is part of the paper "Predicting Meibomian Gland Dropout and Feature Importance Analysis with Explainable Artificial Intelligence" by Fredrik A. Fineide, Andrea M. Storås, Tor P. Utheim and Michael A. Riegler.
Dry eye disease is a common and potentially debilitating medical condition. Meibum secreted from the meibomian glands is the largest contributor to the outermost, protective lipid layer of the tear film. Dysfunction of the meibomian glands is the most common cause of dry eye disease. 
As meibomian gland dysfunction progresses, gradual atrophy of the glands is observed. The meibomian glands are commonly visualized
through meibography, a technique requiring specialist equipment and knowledge that might not be available to the physician.
In the present project we use machine learning on clinical tabular data to predict the degree of meibomian gland dropout.
Moreover, we employ explainable artificial intelligence on the best performing algorithms for feature importance evaluation. 
The best performing algorithms were AdaBoost, multilayer perceptron and LightGBM which outperformed the majority vote baseline
classifier in every included evaluation metric for both multioutput and binary classification. 
Through explainable artificial intelligence known associations are validated and novel connections identified and discussed.

Classification:

Implementation steps:

    1- Load the Data User Modeling Dataset (DUMP).
    
    2- Define the target label.
    
    3- perform label encodin.
    
    4- Extracting the most two important features.
    
    5- Apply SVM and perceptron classifiers.
    
    6- Apply OVR on SVM model.
    
    7- Apply argmax to aggregate confidence score and model performance.
    
    8- Apply OVO on SVM model.
    
    9- Apply argmax for OVO SVM model.
    
Conclusion:

    - During this assignment we made an exceptionally good practice about classification and applied 
      different binary classifiers with each other to achieve multiple classifications and compare the 
      results of them to make analysis and learn the causes of different performances Therefore, we 
      found out that the performance of support vector machine is better than the perceptron as -
      Perceptron model try to find the hyperplane that separates two sets but does not try to 
      optimize the separation "distance". 
    
    - On the other hand, SVM tries to maximize the "support vector", the distance between the two 
      closest opposite sample points. -The SVM typically tries to use a (kernel function) to project the 
      sample points into high dimension space to make them linearly separable, while the perceptron 
      assumes the sample points are already linearly separable

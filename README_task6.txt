
 Objective  
The goal of this task is to understand and implement the **K-Nearest Neighbors (KNN)** algorithm for classification problems using the **Iris dataset**.  

 Tools & Libraries  
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

 Dataset  
We used the **Iris Dataset**, a built-in dataset in Scikit-learn.  
It contains **150 samples** of iris flowers, with **4 features**:  
- Sepal length  
- Sepal width  
- Petal length  
- Petal width  

Target classes:  
- Setosa  
- Versicolor  
- Virginica  

 Steps Implemented  
1. **Load Dataset** (Iris from sklearn)  
2. **Normalize Features** using StandardScaler  
3. **Train-Test Split** (70% training, 30% testing)  
4. **Apply KNN Classifier** with different values of K (1, 3, 5, 7, 9)  
5. **Evaluate the Model**  
   - Accuracy Score  
   - Confusion Matrix  
   - Classification Report  
6. **Visualize Accuracy vs K**  
7. **Decision Boundary Plot** (using first 2 features for visualization)  

 Results  

- Accuracy varied with different values of **K**.  
- Best performance was observed around **K = 3 or 5**.  

Example output metrics:  
- Accuracy ≈ **0.97**  
- Confusion Matrix correctly classified most samples.  

Decision boundaries clearly separated the classes.  

 Screenshots  

### Accuracy vs K
(Insert plot image here after running code)

### Decision Boundary
(Insert decision boundary visualization here)


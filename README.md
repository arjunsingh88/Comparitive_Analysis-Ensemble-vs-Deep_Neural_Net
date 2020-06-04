# Comparitive Analysis (Ensemble V/S Deep Neural Net)

### Pipeline

* **`Step 1:`** Reading Data
    - Check for Missing values
* **`Step 2:`** Preprocessing Data
    - Handling outlier
    - Special Character Operation
		- Datatype conversion
		- Dropping Duplicates
    - Dropping irrelevant columns
    - Finding correlation
    - Checking Data distribution
* **`Step 3:`** Feature engineering
    - Derived Attributes
    - Scaling the dataset for optimized processing
* **`Step 4:`** Random Forest Classifier ----- Deep Neural Network
* **`Step 5:`** Random Forest Classifier ----- Deep Neural Network(hyperparameter tuned)
* **`Step 6:`** Visualizing the diffrence in accuracy using hiplot(*excellent for hyperparameter tuning visualization)

### Models 
|Model|Architecture|
|:---:|:---:|
|`Ensemble`<br>(Random forest)|![Random forest](https://user-images.githubusercontent.com/45566835/83410670-16af1f00-a417-11ea-934e-b8b8df3e4f8c.png)|
|`Deep Neural network`|![Deep Neural network](https://user-images.githubusercontent.com/45566835/83410674-1747b580-a417-11ea-934a-5e862bd69fc2.png)|

### Results

|Random Forest Hyperparameter Tuned Visualization|
|:---:|
|![Random forest Hyperparameter tuned](https://user-images.githubusercontent.com/45566835/83796982-2b531780-a6a2-11ea-824c-5fd72f999e87.JPG)|

|Neural Network Hyperparameter Tuned Visualization|
|:---:|
|![NN Hyper-tuned](https://user-images.githubusercontent.com/45566835/83797498-0a3ef680-a6a3-11ea-94a8-0ea5fe8b85dc.JPG)|

### Conclusion
* Computation cost V/S Accuracy 
* Random Forest computationally less expensive but accuracy wise almost similar

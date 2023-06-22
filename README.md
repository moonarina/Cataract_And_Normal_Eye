# About The Notebook

### Data Image Classification
![Screenshot from 2023-06-22 22-44-50](https://github.com/moonarina/Cataract_And_Normal_Eye_Image_Classification/assets/114307876/e1a9f0a0-fc10-4a7c-a7f4-7b4b65ef240c)

Source Image: https://thea.ua/en/your-eye-health/cataract/

In this notebook, I will focus on two classes from the dataset: cataract and normal eye. The objective is to compare the process of building and training a neural network from scratch with using Convolutional Neural Network (CNN) and Transfer Learning. The comparison will be based on several factors, including training time, ease of creation, accuracy, and consistency. By conducting this analysis, we aim to assess the advantages and disadvantages of each approach to determine the most suitable method for the given task.

This notebook started as a personal trial to test the results, but I realized that it could be beneficial for others as well. Therefore, I decided to enhance it by adding valuable insights and incorporating relevant references that can provide further assistance.

# Insights For CNN

1. The model acheived 77% accuracy and f1-score for the test set
2. The model has stopped earlier with only 30 epochs of training due to early stopping, and to notice if it would continue this would result a clear overfitting
3. Each Eboch took about 44 seconds to execute
4. Although it achieved almost a good accuracy but validation loss wasn't consistant at all and has a lot of fluctuations

# Insights For Transfer Learning

1. The model acheived 60% accuracy and f1-score for the test set
2. The model has stopped earlier with only 30 epochs of training due to early stopping, and to notice if it would continue this would result a clear overfitting
3. Each Eboch took about 22 seconds to execute
4. Although it achieved almost a good accuracy but validation loss wasn't consistant at all and has a lot of fluctuations

# Conclusion

Comparing Transfer Learning and CNN has been a fascinating exploration that has the potential to enhance our results with improved accuracy, consistency, and faster training. Here are the key findings:
1. The baseline model achieved a 77% accuracy, showing a 17% improvement over our own Transfer Learning neural network, which reached 60% accuracy.
2. The training phase of the baseline model proved to be more consistent and faster compared to our own neural network.
3. Although our custom-built neural network may have room for improvement, it's noteworthy how effortless and efficient it was to utilize the baseline model. Building a network from scratch, fine-tuning it, and achieving comparable or better results can be challenging.
4. Therefore, it is highly recommended to leverage the power of baseline models with CNN before attempting to create a custom network. This approach can potentially save a significant amount of time and effort while still yielding satisfactory outcomes.
   
By considering these insights, researchers and practitioners can make informed decisions when selecting the appropriate approach for their specific tasks.

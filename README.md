# Tea-Leaf-Disease-Classification-using-Transfer-Learning-

## Dataset 
This dataset contains 368 total images. 113 algal leaf,113 brown blight and 142 white spot images. 

## Models Used 
- Model 1: VGG16 
- Model 2: ResNet50

## Discussion
- VGG16 performed better than ResNet50.
- VGG16 achieved the highest validation accuracy of 87.27% and a test accuracy of 83.93%, while ResNet50 achieved a validation accuracy of 78.18% and a test accuracy of 66.07%.
- From the classification report, VGG16 gave better overall results across the classes. It performed well for the white spot class, achieving an F1-score of 0.91. The algal leaf and brown blight classes both achieved F1-scores of 0.79.
- In comparison, ResNet50 produced lower F1-scores, especially for the brown blight class, which had an F1-score of 0.56.

## Conclusion
- Based on experimental results, VGG16 was the best performing model for this dataset.  
- According to the bar chart for model comparison VGG16 achieves the highest test accuracy. 
- Therefore, VGG16 is more suitable for classifying the tea leaf disease images in this experiment. 

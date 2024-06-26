# BodyPix-Evaluation

BodyPix Evaluation is a repository designed to evaluate the performance of the BodyPix model on various datasets (Currently support OCHuman dataset). BodyPix is an open-source machine learning model developed by TensorFlow.js for real-time person segmentation in the browser and Node.js. This repository provides a set of scripts and tools to assess the accuracy, precision, recall, and other metrics of the BodyPix model against ground truth annotations.

### Key Features
- **Dataset Preparation**: Easily prepare your dataset for evaluation by following simple instructions and guidelines provided in the repository.  
- **Evaluation Scripts**: Access ready-to-use Python scripts for evaluating the BodyPix model's performance on your dataset, including metrics such as IoU (Intersection over Union), Dice Coefficient, Precision, Recall, and Accuracy.  
- **Batch Processing**: Utilize batch processing capabilities to efficiently evaluate large datasets, with progress tracking and results per batch.  

### Results 
#### BodyPix  
| Dataset  | Mean IoU | Mean Dice | Mean Precision | Mean Recall | Mean Accuracy | mAP  |
|----------|----------|-----------|----------------|-------------|---------------| ---------------|
| OCHuman  | 0.5438   | 0.6724    | 0.6639         | 0.7572      | 0.8540        | 0.7369         |


### Acknowledgements
[TensorFlow.js](https://github.com/de-code/python-tf-bodypix)
[OCHuman API](https://github.com/liruilong940607/OCHumanApi)

### Related Projects
BodyPix: Official TensorFlow.js implementation of BodyPix.

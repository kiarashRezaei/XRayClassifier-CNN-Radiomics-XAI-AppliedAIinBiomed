# Chest X-ray Classification for Pneumonia and Tuberculosis

## Introduction

This repository contains the implementation and evaluation of various machine learning and deep learning model for the automatic classification of chest X-ray images to diagnose Pneumonia and Tuberculosis as the final project for Applied AI in Biomedicine course (A.Y. 22/23) at Politecnico di Milano.
 The diagnosis of these respiratory diseases is crucial for timely intervention and preventing severe consequences, such as respiratory failure and death. Chest X-rays are particularly useful for diagnosing Pneumonia but less reliable for Tuberculosis, making it challenging for medical professionals to accurately interpret the images.

## Purpose

The purpose of this project is to develop a classification model that can assist medical practitioners in diagnosing Pneumonia and Tuberculosis from chest X-ray images. By leveraging machine learning techniques, this model aims to provide a scalable tool to ease the burden of manual analysis and offer more consistent results by reducing the variability introduced by human observers as well as providing explainability to ensure the use of reasonable features in the diagnosis process.

## Dataset

The dataset used for training and evaluating the classification model consists of chest X-ray images with annotations for Pneumonia, Tuberculosis and Normal cases. it can be accessed via [This Link](https://drive.google.com/file/d/15McF3hjhzEpDGyFV_GL0--SqXyINZe7T/view?usp=drive_link)

## Methodology

The project involves the following key steps:

1. **Preprocessing**: The dataset undergoes preprocessing to ensure that the images are properly formatted and normalized. This step is crucial for extracting meaningful features and enhancing the model's performance.

2. **Feature Extraction**: Various feature extraction methods are employed to capture relevant information from the chest X-ray images. Extracted features are essential for the subsequent classification process.

3. **Classification Techniques**: The extracted features are used to train and test several machine learning models. Different classification techniques are explored, such as Support Vector Machines, Convolutional Neural Networks, and Ensemble methods, to identify the most effective approach.

4. **Model Evaluation**: The performance of each classification model is rigorously evaluated using appropriate metrics, including accuracy, precision, recall, and F1-score, to determine the best-performing model.

5. **Explainable AI Techniques**: The interpretability of the best models is also assessed using explainable AI techniques. This ensures that the model's decisions can be understood and trusted by medical professionals.

## Results

The results of the classification models, along with their performance metrics, will be included in the final report. The report will also discuss the interpretability of the best models, providing insights into their decision-making processes.

## Contributing

If you are interested in contributing to this project, feel free to submit pull requests. Please adhere to the coding guidelines and ensure that your contributions align with the project's objectives.

## Note 
This project has been done on Kaggle (Model notebooks) and google Colab (XAI notebooks), therefore the directories should be changed for running on local.

## License

This project is under the [MIT License](LICENSE), allowing users to modify and distribute the code for their purposes while acknowledging the original authors.

## References

[1]    Moberg, A., Taléus, U., Garvin, P., Fransson, S., & Falk, M. (2016). Community-acquired pneumonia in primary care: clinical assessment and the usability of chest radiography. Scandinavian Journal of Primary Health Care.

[2]    Kumar, N., Bhargava, S., Agrawal, C., George, K., Karki, P., & Baral, D. (2005). Chest radiographs and their reliability in the diagnosis of tuberculosis.. JNMA; journal of the Nepal Medical Association.

[3]    Lin, T. Y., Goyal, P., Girshick, R., He, K., & Dollár, P. (2017). Focal loss for dense object detection. In Proceedings of the IEEE international conference on computer vision (pp. 2980-2988).

[4]    Zaheer, M., Reddi, S., Sachan, D., Kale, S., & Kumar, S. (2018). Adaptive methods for nonconvex optimization. Advances in neural information processing systems, 31.

[5]    Ayaz M, Shaukat F, Raja G. Ensemble learning based automatic detection of tuberculosis in chest X-ray images using hybrid feature descriptors. Phys Eng Sci Med. 2021 Mar;44(1):183-194. doi: 10.1007/s13246-020-00966-0. Epub 2021 Jan 18. PMID: 33459996; PMCID: PMC7812355.

[6]    Selvaraju, R. R., Cogswell, M., Das, A., Vedantam, R., Parikh, D., & Batra, D. (2017). Grad-cam: Visual explanations from deep networks via gradient-based localization. In Proceedings of the IEEE international conference on computer vision (pp. 618-626).

[7]    Ribeiro, M. T., Singh, S., & Guestrin, C. (2016, August). " Why should i trust you?" Explaining the predictions of any classifier. In Proceedings of the 22nd ACM SIGKDD international conference on knowledge discovery and data mining (pp. 1135-1144).

[8]    Nori, H., Jenkins, S., Koch, P., & Caruana, R. (2019). Interpretml: A unified framework for machine learning interpretability. arXiv preprint arXiv:1909.09223.


# pneumonia-detection
Designing a DL based algorithm for detecting pneumonia.


PROBLEM STATEMENT
• DOMAIN: Health Care
• CONTEXT:
Computer vision can be used in health care for identifying diseases. In Pneumonia detection we need to detect Inflammation
of the lungs. In this challenge, you’re required to build an algorithm to detect a visual signal for pneumonia in medical
images. Specifically, your algorithm needs to automatically locate lung opacities on chest radiographs.
• DATA DESCRIPTION:
- In the dataset, some of the features are labeled “Not Normal No Lung Opacity”. This extra third class indicates that while pneumonia was
determined not to be present, there was nonetheless some type of abnormality on the image and oftentimes this finding may mimic the
appearance of true pneumonia. Dicom original images: - Medical images are stored in a special format called DICOM files (*.dcm). They
contain a combination of header metadata as well as underlying raw image arrays for pixel data.
- Dataset has been attached along with this project. Please use the same for this capstone project.
- Original link to the dataset : https://www.kaggle.com/c/rsna-pneumonia-detection-challenge/data [ for your reference
only ]. You can refer to the details of the dataset in the above link
- Acknowledgements: https://www.kaggle.com/c/rsna-pneumonia-detection-challenge/overview/acknowledgements.
• PROJECT OBJECTIVE: Design a DL based algorithm for detecting pneumonia.
• PROJECT TASK: [ Score: 100 points]
1. Milestone 1: [ Score: 40 points]
‣ Input: Context and Dataset
‣ Process:
‣ Step 1: Import the data. [ 3 points ]
‣ Step 2: Map training and testing images to its classes. [ 4 points ]
‣ Step 3: Map training and testing images to its annotations. [ 4 points ]
‣ Step 4: Preprocessing and Visualisation of different classes [4 Points]
‣ Step 5: Display images with bounding box. [ 5 points ]
‣ Step 6: Design, train and test basic CNN models for classification. [ 10 points ]
‣ Step 7: Interim report [ 10 points ]
‣ Submission: Interim report, Jupyter Notebook with all the steps in Milestone-1
2. Milestone 2: [ Score: 60 points]
‣ Input: Preprocessed output from Milestone-1
‣ Process:
‣ Step 1: Fine tune the trained basic CNN models for classification. [ 5 points ]
‣ Step 2: Apply Transfer Learning model for classification [4 points]
‣ Step 3: Design, train and test RCNN & its hybrids based object detection models to impose the bounding box or
mask over the area of interest. [ 8 points ]
‣ Step 4: Pickle the model for future prediction [ 3 Points]
‣ Step 5: Final Report [40 Points]
‣ Submission: Final report, Jupyter Notebook with all the steps in Milestone-1 and Milestone-2

Issue_Detection_Paper
Overview
This repository contains the data and code necessary to replicate the experiments conducted in the study of Issue Detection in app reviews using Transfer Learning and the ChatGPT API. The goal is to automatically detect issues from user reviews, focusing particularly on low-rated app reviews.

Directory Structure
Data Files:
annotated_dataset_for_multi_classifications.csv: Dataset used for multi-class issue detection.
annotated_dataset_for_binary_classifications.csv: Dataset used for issue detection.
end-user reviews dataset from low rated apps.csv: Dataset used for detecting issues in low-rated app reviews.

Code Files:
ChatGPT_API.ipynb: Jupyter notebook for issue detection using the ChatGPT API.

Transfer Learning/: Folder containing files related to transfer learning-based issue detection models.

Requirements
Python 3.x

Jupyter Notebook or JupyterLab

Libraries: pandas, scikit-learn, matplotlib, openai, jupyter

Running the Experiments
Step 1: Install the Requirements
To install the required dependencies, use the following command:

bash
Copy
Edit
pip install pandas scikit-learn matplotlib jupyter openai
Step 2: Data Overview
annotated_dataset_for_multi_classifications.csv: Contains labeled data for multi-class classification of issues in app reviews.
annotated_dataset_for_binary_classifications.csv: Contains labeled data for issue detection in app reviews(binary classification).
end-user reviews dataset from low rated apps.csv: Contains raw user reviews from low-rated apps. These reviews are used for training and testing the issue detection model.

Step 3: Running the Notebooks
ChatGPT API Issue Detection:
Open ChatGPT_API.ipynb to use the ChatGPT API for detecting issues in reviews.

Run the notebook cells and interact with the API to detect issues based on user feedback.

Transfer Learning Model:
Navigate to the Transfer Learning/ folder for scripts and resources for training models using transfer learning.

Follow the instructions inside the folder to train and evaluate the issue detection models.

Data Description
annotated_dataset_for_multi_classifications.csv: A labeled dataset containing reviews and issue labels for multi-class classification.

end-user reviews dataset from low rated apps.csv: Raw reviews data used for issue detection in low-rated app reviews.

Contact Information
For questions or feedback regarding the replication package, please contact [nekdil2003@gmail.com].

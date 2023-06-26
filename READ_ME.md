Detecting Brain Tumors
==============================

**Problem Statement:** Can we leverage machine learning to provide timely diagnoses of brain cancer by detecting tumors prematurely?

**Magnetic Resonance Imaging (MRI)** is a medical imaging technique that uses magnetic fields to generate images of the internal structures of the body. It is useful in providing medical insights and **diagnostic information** to specialists so they can determine the appropriate course of action in treating their patients. 

The survival rate for cancer in the past ten years has been around 30%. Unfortunately, you cannot prevent brain tumors by simply changing your lifestyle (diet, exercise etc). According to the American Cancer Society, you can reduce the risk by limiting radiation exposure to the head.

Since there is no way to prevent it from happening, the best solution is to identify the anomalies early and begin treatment as soon as possible. This project will hopefully serve as a small step towards accurately detecting the presence of tumors and in the future, be able to classify them, thereby speeding up the diagnosis.

**Dataset:**
This notebook explores a dataset that contains almost 4500 Brain MRIs. It was obtained online from a diagnostic imaging clinic in Brazil. <br>

Dataset_Link:https://www.kaggle.com/datasets/fernando2rad/brain-tumor-mri-images-44c

Project Organization
==============================
In this folder, you will find the following:
	

	data:
		raw:
            _NORMAL T1
            _NORMAL T2
            Astrocitoma T1
            Astrocitoma T1C+
            Astrocitoma T2
            ...
            Tuberculoma T1C+
            Tuberculoma T2

            [44 different folders]




	notebooks:
	- 1. Notebook#1_Data Exploration & Processing
	- 2. Notebook#2_LogisticRegression
	- 3. Notebook#3_XGBoost&CNN
	- Capstone_Report
      - processed_imgs
      - requirements.txt		
	- READ_ME.md
==============================

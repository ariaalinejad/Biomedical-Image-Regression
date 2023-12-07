# Biomedical-Image-Regression
Project to develop ML algorithms for image regression on biomedical images, with a special focus on the effects of data aumentation on the limited dataset. 

Dataset:
33 images of mice with tumors. The images have been processed to display heatmaps representing the bioluminescence signal intensity resulting from an injection of mammary carcinoma cells fraction enriched with extracellular vesicles. 
The provided presentation showcases examples of the beforementioned images. 

Goal:
The predict signal intensity values and extract meaningful features from the images using supervised learning techniques.


Conclusion: 
Both a simple CNN architecture, and supervised learning using Mobilenet V2 can give good results. Where the simple CNN is superior. Additionally, it is clear that data augmentation is crutial and results in great improvement when working with such a small dataset.


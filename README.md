# Covid Detection via CT Scan Image Analysis

Big Data and Cloud Computing Course Submission

See full report [HERE]()

# Executive Summary

Two years after the first infection of the disease, COVID-19 remains one of the most pressing and concerning diseases that is affecting our daily lives. At present, a lot of data have already been generated and collected from the patients and medical institutions concerning the disease. This study aims to utilize both machine and big data to create possible insights and preliminary descriptive analysis that may help in the generating data driven medical assessments.

CT-Scan images were processed and filtered using open lung layers to represent a CT-scan image collection. Selected layers were then processed and masked to isolate the lung and vessels portion of the image. These masks were then used to check area ratios comparing how prominent the detected vessels were relative to the lung area. SIFT was also performed to extract features from the images and matching was done between members of the same classification. And finally, a simple CNN was trained using the layers as input in trying to classify as infected or healthy.

Image processing and masking showed that although it cannot be generalized, covid-positive cases tend to have higher vessel (or lesion) to lung area ratio compared to healthy lungs. Feature detection and matching algorithm such as SIFT helped determine the features of the images and found out that there more features matched in the healthy CT-scan images. And lastly, neural networks trained to classify the selected images got a validation accuracy of 80%.

For future studies, the machine learning models could still be improved by changing its architecture design and applying data augmentation techniques on the dataset to increase the generalizability of the model. The use of more images or more representative slices could also be used to gather more information. Other methods of image segmentation could also be explored.

![image](https://user-images.githubusercontent.com/71246479/188300683-eeb8816d-f8b4-404f-81b7-a71a5d206f2a.png)

## Disclaimer

Don’t use this study for self-diagnosis without performing a clinical study and consulting with a medical specialist.

# Contributors

dela Resma, Marvee

La Rosa, Patrick

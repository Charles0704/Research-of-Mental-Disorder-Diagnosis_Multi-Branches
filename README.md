# Research of Mental Disorder Diagnosis (Multi Branches)  

### Introduction:  
Nearly one billion people suffer from mental disorders globally, with 94% undiagnosed due to a shortage of clinicians. This study introduces MDscan, a tool for screening ten mental disorders using the SCL-90-R instrument, explainable AI, and the ShapRadiation algorithm. MDscan converts 90 indicators into interpretable diagnostic images, improving screening efficiency and transparency. Field tests show high accuracy, with F1 scores of 0.77 to 0.94, enhancing trust in AI for clinical use.

### Model Analysis (Sample dataset):  
Built and trained a CNN model in a PyTorch environment to perform multi-class classification(all labels) on the 2D images, achieving a final accuracy around 86%.  
![Figure_1](https://github.com/user-attachments/assets/889de272-e121-48d0-b2f9-72f4a5b60ff5)


### CNN structure：
![4ccd04b237ce753cb2a424c862f8787](https://github.com/user-attachments/assets/069f73df-0d8e-43c0-962b-d9429c3d0aba)


### Result:
Image created under the framework:  
Based on responsible AI using CNN model trained, interpretation of pixels towards each mental disorder is as follows:  
![R1](https://github.com/user-attachments/assets/ce5f78e5-5ef9-4cb9-8bde-be9e2129dd9b)  

![R2](https://github.com/user-attachments/assets/f9dadfaa-1363-47d6-a66d-2756d3b5baca)  

Each image represents a patient and is divided into distinct areas, with each area indicating a specific mental disorder. Darker pixels within an area suggest a higher likelihood that the patient may have the corresponding disorder.

### Future work:
We are investigating methods to transform categorical variables into numerical representations and subsequently map them to individual pixels in an image.  

Some ideas:  
* Label Encoding  
* One-Hot Encoding  
* Embedding:  Word2Vec, TF-IDF, BERT, AlBert

Here is the result:  

![Xscanner](https://github.com/user-attachments/assets/bf25768e-99ee-4ff5-9710-798e05487ed0)


### Reference:  
**https://github.com/LeeGorden/Mental-Disorder-Diagnosis_Multi-Branches?tab=readme-ov-file**

### Contact:

Head research assistant: Gorden Li email: likehao1006@gmail.com  
Research assistant: Charles He email:chuxuan@wustl.edu










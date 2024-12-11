# Research of Mental Disorder Diagnosis (Multi Branches)  

### Introduction:  
As the real-life applications of machine learning become increasingly prevalent, ethical concerns surrounding AI solutions, especially in sensitive areas like healthcare, have gained significant attention. The responsible AI framework we proposed generates highly accurate and interpretable images, achieving over 90% accuracy in field experiments based solely on human visual assessments. More importantly, these images empower mental health experts to diagnose disorders without requiring any prior knowledge of ML algorithms, thus bridging the gap between AI and clinical expertise.

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

Combining responsible AI, final images are as follows:  

![R3](https://github.com/user-attachments/assets/dc01a2b1-95af-48ac-997f-f101fe9003dd)  

Each image represents a patient and is divided into distinct areas, with each area indicating a specific mental disorder. Darker pixels within an area suggest a higher likelihood that the patient may have the corresponding disorder.

### Future work:
We are investigating methods to transform categorical variables into numerical representations and subsequently map them to individual pixels in an image.
Some ideas:  
Label Encoding  
One-Hot Encoding  
Embedding Encoding  


### Reference:  
**https://github.com/LeeGorden/Mental-Disorder-Diagnosis_Multi-Branches?tab=readme-ov-file**

### Contact:

Head research assistant: Gorden Li email: likehao1006@gmail.com  
Research assistant: Charles He email:chuxuan@wustl.edu










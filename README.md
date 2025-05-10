# Alzheimer-s-Disease-Detection-MRI-CNN-RNN-
Detecting Alzheimer’s Disease (AD) using MRI scans with CNN and/or RNN models is one of the most impactful deep learning applications in healthcare.
🧠 Alzheimer’s Disease Detection using MRI, CNN, RNN
✅ 1. Problem Statement
Detect if a person is:

Normal

Mild Cognitive Impairment (MCI)

Alzheimer’s Disease (AD)

Using brain MRI images, the goal is to classify the stage of Alzheimer's for early diagnosis.

3. Architecture
✅ CNN (Convolutional Neural Network)
Used for 2D or 3D feature extraction from MRI slices

Layers: Conv2D → ReLU → MaxPooling → Dropout → Dense

Output: Multi-class classification (CN, MCI, AD)

✅ RNN or LSTM (if using MRI slices as sequences)
Treat slices across brain regions as time steps

Used when 3D volume is converted into sequential 2D slices

Combines spatial + sequential features

<img width="701" alt="image" src="https://github.com/user-attachments/assets/542bf1d0-a55d-4a71-9018-59b11d9b8a46" />
<img width="749" alt="image" src="https://github.com/user-attachments/assets/54d23634-cda8-470d-ad31-36c747964b28" />
<img width="556" alt="image" src="https://github.com/user-attachments/assets/3623608e-6888-4cbd-8e58-0ddc6784c8b3" />
<img width="833" alt="image" src="https://github.com/user-attachments/assets/e9e4e5b5-230d-4b6b-b142-f36175b4dda8" />
<img width="1028" alt="image" src="https://github.com/user-attachments/assets/821e4f42-f48b-42dc-b070-de63d7e05716" />
<img width="671" alt="image" src="https://github.com/user-attachments/assets/5040eb59-9793-4fa4-b69c-0f695e87985e" />

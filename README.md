# Content-Noise Complementary Learning for Medical Image Denoising

This repository contains an implementation of the "Content-Noise Complementary Learning for Medical Image Denoising" paper by Mufeng Geng. 
The original code was implemented by the author of the paper, Dr. Mufeng Geng, and has been adapted to run on Jupyter Notebook.
The original repository link: https://github.com/gengmufeng/CNCL-denoising

# Dataset
The CT images challenge dataset used in this implementation can be found at: https://www.aapm.org/GrandChallenge/LowDoseCT/. ↗ The dataset is located in the Patient_Data/Training_Image_Data/3mm B30 directory, and quarter-dose images are used as noisy input, and full-dose images are used as ground truth for training the model.

# Trained Model
The trained CNCL-U-Net model for low-dose CT denoising is available at: https://drive.google.com/drive/folders/1_qamlI2KArQQNZZQa2gGfwYn7vJ5aeIG. ↗ The model has been provided by Mufeng Geng.

# Usage
To run the implementation, open the "CNCL_denoising.ipynb" notebook in Google Colaboratory and follow the instructions. The notebook contains all necessary code for loading the dataset, training the model, and evaluating the results.

# References

- Mufeng Geng, Xiangxi Meng, Jiangyuan Yu, Lei Zhu, Lujia Jin, Zhe Jiang, Bin Qiu, Hui Li, Hanjing Kong, Jianmin Yuan, Kun Yang, Hongming Shan, Hongbin Han, Zhi Yang, Qiushi Ren, and Yanye Lu. "Content-Noise Complementary Learning for Medical Image Denoising".

- Original implementation by Dr. Mufeng Geng: https://github.com/gengmufeng/CNCL-denoising ↗

# SAUD-Dataset and NUIQ-Method for underwater image enhancement
implementation of ''Underwater Image Enhancement Quality Evaluation: Benchmark Dataset and Objective Metric''.

## 📋 Table of content
1. 📎[Paper Link](#paper-link)
2. 💡[Abstract](#abstract)
3. 📃[Requirement](#requirement)
4. 📖[Usage](#usage)
5. 🍎[Noting](#noting)
6. ✨[Statement](#statement)
7. 🔍[Citation](#citation)

## 📎Paper Link
Underwater Image Enhancement Quality Evaluation: Benchmark Dataset and Objective Metric ([link](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9749233 "https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9749233"))
- Authors: Qiuping Jiang, Yuese Gu, Chongyi Li, Runmin Cong, Feng Shao
- Institution: The School of Information Science and Engineering, Ningbo University

## 💡Abstract
Due to the attenuation and scattering of light by water, there are many quality defects in raw underwater images such as color casts, decreased visibility, reduced contrast, etc. Many different underwater image enhancement (UIE) algorithms have been proposed to enhance underwater image quality. However, how to fairly compare the performance among UIE algorithms remains a challenging problem. So far, the lack of comprehensive human subjective user study with large-scale benchmark dataset and reliable objective image quality assessment (IQA) metric makes it difficult to fully understand the true performance of UIE algorithms. We in this paper make efforts in both subjective and objective aspects to fill these gaps. Firstly, we construct a new Subjectively-Annotated UIE benchmark Dataset (SAUD) which simultaneously provides real-world raw underwater images, readily available enhanced results by representative UIE algorithms, and subjective ranking scores of each enhanced result. Secondly, we propose an effective No-reference (NR) Underwater Image Quality metric (NUIQ) to automatically evaluate the visual quality of enhanced underwater images. Experiments on the constructed SAUD dataset demonstrate the superiority of our proposed NUIQ metric, achieving higher consistency with subjective rankings than 22 mainstream
NR-IQA metrics.

## 📃Requirement
matlab

## 📖Usage
You can download our SAUD-Dataset from（Modification date 2022.05.05）
>BaiduYun Disk: [SAUD-Dataset-released](https://pan.baidu.com/s/1za34vyTa1Ms-RfuOPAbl6w)  (key:yiaa)
>
>Google Drive: [SAUD-Dataset-released](https://drive.google.com/drive/folders/1XUKMKsPyu2LSGAMz_kMN9-hmgMnblcJd?usp=sharing)

You can download our NUIQ-Metric from
>BaiduYun Disk: [NUIQ-Metric-released](https://pan.baidu.com/s/1g47JmZCciLfOpfW4IdI44g)  (key:yiaa)
>
>Google Drive: [NUIQ-Metric-released](https://drive.google.com/drive/folders/13d19eHTT1xBK5ZX0S_R6qXKWg4Egsylz?usp=sharing)

## 🍎Noting
Our NUIQ Method was trained to predict the rank of different enhanced results associated with the same raw underwater image. Therefore, the NUIQ scores cannot be used to compare the quality of enhanced images with different contents.
Do not test on single image!

## ✨Statement
This project is for research purpose only, please contact us for the licence of commercial use. For any other questions please contact jiangqiuping@nbu.edu.cn. 805682724@qq.com.

## 🔍Citation
- If you find this work useful for you. Please cite:
>@ARTICLE{9749233,  
>author={Jiang, Qiuping and Gu, Yuese and Li, Chongyi and Cong, Runmin and Shao, Feng},  
>journal={IEEE Transactions on Circuits and Systems for Video Technology},   
>title={Underwater Image Enhancement Quality Evaluation: Benchmark Dataset and Objective Metric},   
>year={2022},  
>volume={},  
>number={},  
>pages={1-1},  
>doi={10.1109/TCSVT.2022.3164918}
}

[回到顶部](#readme)

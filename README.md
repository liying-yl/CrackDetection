# CrackDetection

* **FPHBN:** Fan Yang*, Lei Zhang*, Sijia Yu, Danil Prokhorov, Xue Mei, and Haibin Ling.<br />
  "Feature Pyramid and Hierarchical Boosting Network for Pavement Crack Detection." IEEE TRANSACTIONS ON INTELLIGENT TRANSPORTATION SYSTEMS, UNDER REVIEW. 
  [[paper](https://ieeexplore.ieee.org/abstract/document/8694955)]
  [[code](https://github.com/fyangneil/pavement-crack-detection)]
  
AIU: 

|  Dataset  |    Crack500  |    GAPs384    |   CrackTree200    |    CFD   |    Aigle-RN & ESAR & LCMS   |
|:---------:|:------------:|:-------------:|:-----------------:|:--------:|:---------------------------:|
|   FPHBN   |    0.489     |     0.081     |        0.041      |   0.173  |             0.079           | 
|    HED    |    0.481     |     0.069     |        0.040      |   0.154  |             0.075           |    
  
Time(s):

|  Dataset  |    Crack500  |    GAPs384    |   CrackTree200    |    CFD   |    Aigle-RN & ESAR & LCMS   |
|:---------:|:------------:|:-------------:|:-----------------:|:--------:|:---------------------------:|
|   FPHBN   |    0.197     |     0.024     |        0.377      |   0.133  |             0.259           | 
|    HED    |    0.067     |     0.086     |        0.130      |   0.047  |             0.098           | 

* **DeepCrack1:** Yahui Liu, Jian Yao ∗, Xiaohu Lu, Renping Xie, Li Li.<br />
  "DeepCrack: A deep hierarchical feature learning architecture for crack segmentation." 
  [[paper](https://www.sciencedirect.com/science/article/pii/S0925231219300566)]
  [[code](https://github.com/yhlleo/DeepCrack/blob/master/dataset/DeepCrack.zip)]
  
|    Method    |     G    |           C        |       I/U       |  Precision  |     Recall    |   F1 Score    |Time(s)|
|:------------:|:--------:|-------------------:|:---------------:|:-----------:|:-------------:|:-------------:|:-----:|
|  DeepCrack1  |   97.5   |        97.0        |       80.2      |    86.1     |       86.9    |      86.5     |   109 |   
| DeepCrack-GF |   98.6   |        95.0        |       85.9      |    85.2     |       86.6    |      85.9     |   118 |
|    SegNet    |   98.0   |        82.3        |       78.5      |    79.7     |       72.9    |      76.2     |   184 |   
|      HED     |   95.8   |        87.7        |       70.0      |    59.4     |       69.1    |      63.9     |   56  |

G:GlobalAccuracy   C:Class average accuracy   I/U: Mean intersection over union over all classes  GF:Guided filter

|   Detector   |    Loss    |    Accuracy    |    Precision    |    Recall   |    F1 Score   |   AIU   |   Deep Learning   |  Time(s)  |
|:------------:|:----------:|:--------------:|:---------------:|:-----------:|:-------------:|:-------:|:-----------------:|:---------:|
|     FPHBN    |      -     |       -        |        -        |    -        |       -       |  0.489  |       Y           |  0.197    |
|DenseNet-FCN  |   0.708    |                |                 |             |               |         |       Y           |           |
|     CNN&ipp  |      -     |      0.707     |      0.577      |    0.672    |      0.621    |    -    |       Y           |           |
|     U-net    |   0.025    |       -        |      0.9        |      0.91   |        0.9    |    -    |       Y           |           |
|  DeepCrack1  |      -     |       -        |      0.861      |    0.869    |     0.865     |    -    |       Y           |           |
|  DeepCrack2  |      -     |       -        |      0.9315(AP) |      -      |       -       |    -    |       Y           |           |
|      FCN     |      -     |       0.9796   |      0.8173     |      0.7897 |       0.7995  |    -    |       Y           |           | |  CrackNet    |      -     |       -        |      0.9013     |      0.8763 |       0.8886  |    -    |       Y           |           | |  CrackForest |      -     |       0.9796   |      0.8173     |      0.7897 |       0.7995  |    -    |       Y           |           | |  CrackTree   |      -     |       -        |      0.9013     |      0.8763 |       0.8886  |    -    |       Y           |           |             


* **CNN&ipp:** Eftychios Protopapadakis1 & Athanasios Voulodimos2, Eftychios Protopapadakis1 & Athanasios Voulodimos2.<br />
  "Automatic crack detection for tunnel inspection using deep learning and heuristic image post-processing." 
  [[paper]()]
  [[code]()]
* **U-net:** Zhenqing Liua,⁎ , Yiwen Caoa, Yize Wanga,⁎ , Wei Wangb.<br />
  "Computer vision-based concrete crack detection using U-net fully convolutional networks." 
  [[paper]()]
  [[code]()]
* **DeepCrack1:** Yahui Liu, Jian Yao ∗, Xiaohu Lu, Renping Xie, Li Li.<br />
  "DeepCrack: A deep hierarchical feature learning architecture for crack segmentation." 
  [[paper]()]
  [[code](https://github.com/yhlleo/DeepCrack/blob/master/dataset/DeepCrack.zip)]
* **DeepCrack2:** Qin Zou , Member, IEEE, Zheng Zhang, Qingquan Li, Xianbiao Qi , Qian Wang , and Song Wang, Senior Member, IEEE,<br />
  "DeepCrack: Learning Hierarchical Convolutional Features for Crack Detection."
  [[paper]()]
  [[code]()]
* **FCN:** Xincong Yang,Heng Li*, Yantao Yu, Xiaochun Luo & Ting Huang,<br />
  "Automatic Pixel-Level Crack Detection and Measurement Using Fully Convolutional Network"
  [[paper]()]
  [[code]()]
* **CrackNet:**  
  
  
  
  
  
  
  
  

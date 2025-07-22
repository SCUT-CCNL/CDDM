# Car Damage Detection Based on Multi-View Fusion and Alignment: Dataset and Method

This is the official code of Car Damage Detection Multi-view (CDDM) dataset. 
Paper web page: [Car Damage Detection Based on Multi-View Fusion and Alignment: Dataset and Method](https://ieeexplore.ieee.org/document/10904063).

## Dataset 
The CDDM is the first publicly available multiview dataset, which combines the following properties:

1) Paired multi-view image: Each car in the CDDM dataset is accompanied by multiple images captured from different perspectives, including at least one distant-view and one close-up view, in a one-to-one correspondence.

2) Damage severity type: 9 damaged components (front bumper, rear bumper, front fender, rear fender, hood, rear door, front door, trunk lid, headlights) and 3 damage severity types (scratches, dents, cracks), resulting in comprehensive coverage of 27 (9 × 3) annotation types.

3) Data volume: It contains 4414 pairs, each consisting of one close-up image and one distant-view image.

4) Multiple tasks: Our dataset encompasses three distinct tasks: classification of damage types, detection of damage components, and segmentation of damage areas.

## Dataset DOWNLOADING

NOTE: For downloading the data, please first fill in the licensing form and send it to us to receive the link: [CDDM DATASET LICENSING](https://github.com/SCUT-CCNL/CDDM/blob/main/CDDM%20DATASET%20LICENSING.docx)


## Dataset Directoty
```

CDDM
├── Train               #Train dataset total 3107 pairs                  
│   ├── XX.jpg                   #image
│   ├── XX.json                  #annotation
│   ├── ...
│   └── ...
├── Test&Val            #Test and Val dataset total 1307 pairs                   
│   ├── YY.jpg                   #image
│   ├── YY.json                  #annotation
│   ├── ...
│   └── ...
└── train.txt           #Train image number
└── test.txt            #Test  image number
└── val.txt             #Val   image number
    
```

## Citation
```

@ARTICLE{10904063,
  author={Peng, Jinbo and Dong, Shoubin and Yuan, Hua and Zheng, Xiaorou},
  journal={IEEE Transactions on Intelligent Transportation Systems}, 
  title={Car Damage Detection Based on Multi-View Fusion and Alignment: Dataset and Method}, 
  year={2025},
  volume={26},
  number={4},
  pages={4717-4730},
  keywords={Automobiles;Solid modeling;Classification algorithms;Image segmentation;Feature extraction;Multitasking;Location awareness;Data mining;Three-dimensional displays;Insurance;Multi-view car damage detection;multi-view dataset;paired distant-view and close-up images;car’s component alignment;multiple tasks},
  doi={10.1109/TITS.2025.3542174}}

```

## Acknowledgment

The preparation of the dataset used in this study—including data cleaning, annotation, and post-processing for sensitive information masking—required substantial manual effort. We gratefully acknowledge the contributions of the master's students, interns, and doctoral candidates from the Guangdong Provincial Key Laboratory of Multimodal Big Data Intelligent Analysis (MBDIA) for their dedicated work throughout this process.

It is also important to note that the training set used in this study did not undergo sensitive information masking, whereas the publicly released dataset—including both the validation and test sets—was rigorously processed with masking procedures to ensure data compliance and security.


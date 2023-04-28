# DeepEyeNet

"DeepOpht: Medical Report Generation for Retinal Images via Deep Models and Visual Explanation"; Jia-Hong Huang, C.-H. Huck Yang, Fangyu Liu, Meng Tian, Yi-Chieh Liu, Ting-Wei Wu, I-Hung Lin, Kang Wang, Hiromasa Morikawa, Hernghua Chang, Jesper Tegner, and Marcel Worring; Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV), 2021, pp. 2442-2452.

Click [here](https://openaccess.thecvf.com/content/WACV2021/html/Huang_DeepOpht_Medical_Report_Generation_for_Retinal_Images_via_Deep_Models_WACV_2021_paper.html) to read the DeepEyeNet paper. 


**Open-access DeepEyeNet (DEN) Dataset** request email for Terms of Use/Non-disclosure agreement (NDA): 

- Submit your request [here](https://docs.google.com/forms/d/1MVUEGG7YA6LHKDBK7Ny7TQf5IOI_xBlcvvcQI0S2fOI/edit) for the dataset


Other questions to: deepeyenet.den@gmail.com. We usualy check the NDA and reply within one to two business days. 

**Keywords**: Vision and Language, Medical Image Captioning/Medical Report Generation, Large-scale Retinal Images Dataset

## Dataset Examples
Each image in the dataset has three types of expert-defined annotations, i.e., the name of disease/symptom, keywords, and clinical description.

<img src="https://github.com/Jhhuangkay/DeepOpht-Medical-Report-Generation-for-Retinal-Images-via-Deep-Models-and-Visual-Explanation/blob/main/demo.png" width="500">

## Dataset Visualization - Venn-style word cloud

<img src="https://github.com/Jhhuangkay/DeepOpht-Medical-Report-Generation-for-Retinal-Images-via-Deep-Models-and-Visual-Explanation/blob/main/word_cloud.png" width="500">

## Flowchart of the proposed method

![Screenshot](flowchart.png)

## Retinal disease treatment procedure

![Screenshot](retinal_disease_treatment_procedure.png)

## Dataset format

Two examples from the DeepEyeNet dataset json file:
The key "eyenet0420/train_set/suspected-multiple-evanescent-white-dot-syndrome-4.jpg" is YOUR-PATH + a name of disease.
The corresponding value of the key is a dictionary, i.e., {"keywords": "uveitis, dry age-related macular degeneration (dry amd), punctate inner choroidopathy (pic), multiple evanescent white dot syndrome (mewds)", "clinical-description": "20 degree view, red free image of left macula of a 28-year-old caucasian female."}. The corresponding value of the key contains two dictionaries, i.e., the keys "keywords" and "clinical-description" with the corresponding vlaues "uveitis, dry age-related macular degeneration (dry amd), punctate inner choroidopathy (pic), multiple evanescent white dot syndrome (mewds)" and "20 degree view, red free image of left macula of a 28-year-old caucasian female.", respectively.


[

  {
    "eyenet0420/train_set/suspected-multiple-evanescent-white-dot-syndrome-4.jpg": {
      "keywords": "uveitis, dry age-related macular degeneration (dry amd), punctate inner choroidopathy (pic), multiple evanescent white dot syndrome (mewds)",
      "clinical-description": "20 degree view, red free image of left macula of a 28-year-old caucasian female."},
    
    "eyenet0420/train_set/group41-177.jpg": {
      "keywords": "macular hole",
      "clinical-description": "43-year-old female, macular hole."}
  }
  
]

## Related works


1. "Expert-defined Keywords Improve Interpretability of Retinal Image Captioning". Ting-Wei Wu*, Jia-Hong Huang*, Joseph Lin, Marcel Worring. IEEE/CVF Winter Conference on Applications of Computer Vision (WACV), 2023. [Oral presentation]
2. "Non-Local Attention Improves Description Generation for Retinal Images". Jia-Hong Huang, Ting-Wei Wu, Chao-Han Huck Yang, Zenglin Shi, I-Hung Lin, Jesper Tegner, Marcel Worring. IEEE/CVF Winter Conference on Applications of Computer Vision (WACV), 2022. [Oral presentation]
3. "DeepOpht: Medical Report Generation for Retinal Images via Deep Models and Visual Explanation". Jia-Hong Huang, Chao-Han Huck Yang, Fangyu Liu, Meng Tian, Yi-Chieh Liu, Ting-Wei Wu, I-Hung Lin, Kang Wang, Hiromasa Morikawa, Hernghua Chang, Jesper Tegner, Marcel Worring. IEEE/CVF Winter Conference on Applications of Computer Vision (WACV), 2021.
4. "Deep context-encoding network for retinal image captioning". Jia-Hong Huang, Ting-Wei Wu, Chao-Han Huck Yang, Marcel Worring. IEEE International Conference on Image Processing (ICIP), 2021.
5. "Contextualized Keyword Representations for Multi-modal Retinal Image Captioning". Jia-Hong Huang, Ting-Wei Wu, Marcel Worring. ACM International Conference on Multimedia Retrieval (ICMR), 2021.
6. "A Novel Hybrid Machine Learning Model for Auto-Classification of Retinal Diseases". C-H Huck Yang, Jia-Hong Huang, Fangyu Liu, Fang-Yi Chiu, Mengya Gao, Weifeng Lyu, Jesper Tegner. Workshop on Computational Biology, International Conference on Machine Learning (ICML), 2018.
7. "Auto-Classification of Retinal Diseases in the Limit of Sparse Data Using a Two-Streams Machine Learning Model". C-H Huck Yang, Fangyu Liu, Jia-Hong Huang, Meng Tian, Yi-Chieh Liu, I-Hung Lin, Jesper Tegner. AIRIA: AI for Retinal Image Analysis Workshop, Asian Conference on Computer Vision (ACCV), 2018.
8. "Synthesizing New Retinal Symptom Images by Multiple Generative Models". Yi-Chieh Liu, Hao-Hsiang Yang, Chao-Han Huck Yang, Jia-Hong Huang, Meng Tian, Hiromasa Morikawa, Yi-Chang James Tsai, Jesper Tegner. AIRIA: AI for Retinal Image Analysis Workshop, Asian Conference on Computer Vision (ACCV), 2018 [Oral presentation]

## Citation
@inproceedings{huang2021deepopht,
  title={DeepOpht: medical report generation for retinal images via deep models and visual explanation},
  author={Huang, Jia-Hong and Yang, C-H Huck and Liu, Fangyu and Tian, Meng and Liu, Yi-Chieh and Wu, Ting-Wei and Lin, I-Hung and Wang, Kang and Morikawa, Hiromasa and Chang, Hernghua and Tegner, Jesper and Worring, Marcel},
  booktitle={Proceedings of the IEEE/CVF winter conference on applications of computer vision},
  pages={2442--2452},
  year={2021}
}


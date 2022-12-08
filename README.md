# :artificial_satellite: Augmented Convolutional Neural Networks for Remote Sensing Change Detection 

:card_index_dividers: Code Repository for CS ECE 5834 - Advanced Machine Learning 

:black_nib: Authors: [Canvas Group: Remote Sensing Change Detection]
1. Sarvesh Patil (sarveshpatil@vt.edu) 
2. Pranjal Ranjan (pranjalranjan@vt.edu)
3. Ankit Parekh (ankitparekh@vt.edu)
4. Badhrinarayan Malolan (badhrinarayan@vt.edu) 

## Repository Index

|              **File**             |                              **Description**                             |                                         **Model**                                         |                                 **Challenge**                                |
|:---------------------------------:|:------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| AML_Initial_Model_Selection.ipynb |            Notebook for initial baselining and model selection           |                         Unaugmented: EF, Siam-Conc.   & Siam-Diff                         |                               Original Dataset                               |
|       AML_Unaugmented.ipynb       |     Notebook for training unaugmented networks for few-shot learning     |                                      Unaugmented: EF                                      |                               Few-shot learning                              |
|    AML_Data_Augmentation.ipynb    |      Notebook for training augmented network with edge maps and MRA      |                                 Augmented: EF (Edge & MRA)                                |                     Original Dataset & Few-shot learning                     |
|         AML_Pretrain.ipynb        | Notebook for training augmented network with pretrained imagenet encoder |                            Augmneted: EF (Pretrained   Encoder)                           |                     Original Dataset & Few-shot learning                     |
|        AML_Evaluation.ipynb       |              Notebook for evaluating results for all phases              | Unaugmented: EF, Siam-Conc.   & Siam-Diff & Augmented models: EF (Edge, MRA & Pretrained) | Original Dataset, Few-shot learning, Noise Robustification & Dataset   Shift |
|             README.md             |                    Description file for the repository                   |                                            ---                                            |                                      ---                                     |                                 

# What is this d4p_v1?

<img src="https://github.com/Amincheminfom/d4p_v1/blob/main/d4p_logo.jpg?raw=1" alt= “Amincheminfom_logo” width="200" align="right">

It is an online tool hosted on Google Colab [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1f0A1_ipI2JIKSs04LUTKznqyWNTMG2kl#scrollTo=0g7WDOiYFCyF) that predict the dipeptidyl peptidase-4 inhibitory property (1 = Active, 0 = Inactive) of a small molecule and also visualize the molecule.

**d4p** stands for **d**ipeptidyl peptidase-**4** **p**redictor.

This Google Colab notebook is associated with the article "AI-driven DPP-4 predictor: Insights into fingerprints and electrostatic potential (ESP) maps for enhanced type 2 diabetes mellitus management" (under preparation) and we encourage you to read it before using this pipeline.


---
Please follow these steps to execute the notebook.

<img src="https://github.com/Amincheminfom/Amincheminfom/blob/main/Amincheminfom1.gif?raw=1" alt= “Amincheminfom_logo” width="300" align="right">

1: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1f0A1_ipI2JIKSs04LUTKznqyWNTMG2kl#scrollTo=0g7WDOiYFCyF)

2: Install and import required packages

2: Provide the Smiles of your query moleucle and run the cell

3: Click the icon to visualize the Chemical Space

------
Example Smiles:
1. Known DPP-4 Active molecule: 
c1(c(c(c(c(n1)C)CC(=O)Nc1cc(ccc1)C(=O)C)c1ccc(cc1)C)C[NH3+])CC(C)C
2. Known DPP-4 Inactive molecule: 
s1c(c2sc(cc2)CO)ccc1c1sccc1
3. Imatinib: 
Cc1ccc(NC(=O)c2ccc(CN3CCN(C)CC3)cc2)cc1Nc1nccc(-c2cccnc2)n1

---
Bugs: If you encounter any bugs, please report the issue to my mail id pharmacist.amin@gmail.com or askabdul@unisa.it

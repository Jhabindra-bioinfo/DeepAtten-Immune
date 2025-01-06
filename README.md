# Identification of Immunogenic Peptides Using Deep Learning for MHC Class I and II

This repository provides tools for the identification of immunogenic peptides using deep learning models, specifically designed for MHC class I and MHC class II molecules.  

## Testing with New Data
To test the models with your data, ensure the following input formats:  

### **MHC Class I Requirements**
1. **HLA Allele Type:** Header format (e.g., `HLA-A-2402`).
2. **Peptide Length:** 9 amino acids (e.g., `MYHNKEFDF`).
3. **Immunogenic Information:** Label indicating immunogenicity (`1` for immunogenic, `0` for non-immunogenic).## optional

#### **Example Data Format (MHC Class I)**  
```
HLA-A-2402	MYHNKEFDF	1  
HLA-A-0201	TLHGPTPLL	1  
HLA-B-0801	MPAWRTRGA	0  
```

### **MHC Class II Requirements**
1. **HLA Allele Type:** 
   - Single allele format (e.g., `HLA-DRB1-0101`), or  
   - Double allele format (e.g., `HLA-DQA1-0102/DQB1`).
2. **Peptide Length:** 15 amino acids (e.g., `KAGVYKLTGAIMHYG`).
3. **Immunogenic Information:** Label indicating immunogenicity (`1` for immunogenic, `0` for non-immunogenic).## Optional

#### **Example Data Format (MHC Class II)**  
```
HLA-DRB1-0101	KAGVYKLTGAIMHYG	0  
HLA-DQA1-0102/DQB1-0602	RKKTSLCLMMMLPAT	0  
HLA-DRB5-0101	RFSWGAEGQRPGFGY	0  
```

## Dependencies
For details on additional files and dependencies, please refer to the **Notebook Description **  for each items, included in this repository.

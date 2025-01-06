# Deep learning-driven immunogenic neoepitope identification based on structural features 

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

## Dependencies
For details on additional files and dependencies required for testing, please refer to the **Notebook Description Section** included in this repository.

Key Dependencies:
- TensorFlow (2.16.2) # with GPU
- Keras (3.4.1)
- NumPy
- SciPy
- scikit-learn
- matplotlib
## Utilized versions
**Python Version**: 3.11.9  
**TensorFlow Version**: 2.16.2  
**Keras Version**: 3.4.1


## Contact
For any questions or issues, feel free to reach out via email at (jhabindra@jbnu.ac.kr or 91979@ncc.re.kr).


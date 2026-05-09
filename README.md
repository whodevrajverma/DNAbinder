# DNAbinder: Prediction of DNA-Binding Proteins

**DNAbinder** is a specialized computational resource developed to identify and analyze DNA-binding proteins from their amino acid sequences.
These proteins are essential for fundamental biological processes, including gene expression regulation, DNA repair, and replication.
The platform addresses the challenge of identifying DNA-binding proteins in the post-genomic era, where protein sequences are accumulating much faster than their functions can be experimentally determined.

**Web Server:** https://webs.iiitd.edu.in/raghava/dnabinder/


## Citation

Kumar, M., Gromiha, M. M., & Raghava, G. P. S. (2007).

**Identification of DNA-binding proteins using support vector machines and evolutionary profiles.** *BMC Bioinformatics*, 8:463. 
[https://doi.org/10.1186/1471-2105-8-463](https://www.google.com/search?q=https://doi.org/10.1186/1471-2105-8-463)

This dataset can also be found on Zenodo

## About the Research

The prediction of DNA-binding proteins is complex because these proteins are structurally and functionally diverse.
DNAbinder utilizes sophisticated machine learning techniques to discriminate between DNA-binding and non-binding proteins based on their primary sequence and evolutionary information.

* **Dataset:** The models were trained and tested on two major datasets: a main dataset consisting of 1,153 DNA-binding and 1,153 non-binding proteins, and a more realistic dataset with a 1:10 ratio of binding to non-binding proteins.


* **Methodology:** The platform uses Support Vector Machines (SVM) based on several protein features, including amino acid composition and PSSM (Position-Specific Scoring Matrix) profiles.



## Key Features

### 1. Robust Predictive Models

The platform offers different prediction modules based on various input features:

* **Amino Acid Composition:** Differentiates proteins based on the frequency of the 20 standard amino acids.


* **Evolutionary Information (PSSM):** Utilizes PSI-BLAST profiles to capture conserved residues across homologous proteins, significantly improving prediction accuracy.


* **Physicochemical Properties:** Analyzes properties such as charge, hydrophobicity, and molecular weight.



### 2. High Performance

* **Accuracy:** The PSSM-based SVM model achieved a maximum accuracy of **90.32%** and a Matthews Correlation Coefficient (MCC) of 0.81.


* **Reliability:** The models were rigorously validated using five-fold cross-validation to ensure consistent performance across different protein classes.



### 3. Integrated Analysis Tools

* **Search and Browse:** Users can query the database for information on known DNA-binding proteins.


* **Sequence Submission:** Allows users to submit a single sequence or multiple sequences in FASTA format for prediction.


* **User-Friendly Output:** Provides a probability score for each protein, indicating the likelihood of it being a DNA-binding protein.




## Applications

* **Functional Annotation:** Identifying potential DNA-binding proteins in newly sequenced genomes.


* **Mechanism Studies:** Understanding the sequence-level features that drive protein-DNA interactions.


* **Drug Discovery:** Identifying target proteins for treatments involving gene regulation or viral replication.



## Contact & Authors

**Prof. Gajendra P. S. Raghava** (Corresponding Author)

raghava@iiitd.ac.in

Department of Computational Biology, Indraprastha Institute of Information Technology (IIIT Delhi), New Delhi, India.


## Support

This study and the development of DNAbinder were supported by the **Council of Scientific and Industrial Research (CSIR)** and the **Department of Biotechnology (DBT)**, Government of India.

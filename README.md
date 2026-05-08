Alzheimer’s Disease Hub Gene Identification using GCNN

Overview
This project focuses on identifying important hub genes associated with Alzheimer’s Disease (AD) using a Graph Convolutional Neural Network (GCNN)-based framework. The study integrates gene expression analysis, protein–protein interaction (PPI) networks, and graph deep learning techniques to analyze complex biological interactions and discover disease-related genes.

The framework uses publicly available GEO datasets and graph-based learning to improve the identification of biologically meaningful genes related to Alzheimer’s disease progression.

Problem Statement
Alzheimer’s disease is a progressive neurodegenerative disorder that causes memory loss and cognitive decline. Traditional gene analysis approaches often fail to capture complex relationships among genes and proteins. This project addresses the problem using graph-based deep learning methods.

Objectives
1.Analyze Alzheimer’s disease gene expression datasets
2.Perform preprocessing and normalization
3.Construct a unified gene interaction network
4.Apply Graph Convolutional Neural Network (GCNN)
5.Identify important Alzheimer’s-related hub genes
6.Perform cross-dataset validation

Datasets Used
Public datasets obtained from the Gene Expression Omnibus (GEO):
GSE48350
GSE11882

Technologies & Tools
Python
Graph Convolutional Neural Network (GCNN)
Pandas
NumPy
Scikit-learn
NetworkX
PyTorch / TensorFlow
Bioinformatics techniques

Methodology
1. Data Collection
Gene expression datasets were collected from GEO.

2. Data Preprocessing
Probe-to-gene mapping
Batch correction
Min–Max normalization
Common gene intersection

3. Gene Interaction Network Construction
A unified graph was created using:
Gene co-expression relationships
Protein–Protein Interaction (PPI) information
Where:
Nodes → Genes
Edges → Interactions

4. Feature Extraction
Each gene node includes features such as:
Average expression level
Log₂ fold change
Expression variance

5. GCNN Model Training
The GCNN model was trained using semi-supervised learning with known Alzheimer’s-related genes as seed genes.

6. Validation
Cross-dataset validation was performed:
Train on one dataset
Test on another dataset

7. Hub Gene Identification
Hub genes were identified using:
GCNN prediction scores
Attribution analysis

Results
The identified hub genes showed strong association with:
Synaptic signaling
Neuroinflammation
Mitochondrial dysfunction
These biological processes are closely related to Alzheimer’s disease progression.

Advantages
Handles complex biological relationships effectively
Better graph-based learning capability
Improved disease-related gene identification
Useful for future therapeutic research

Future Scope
Use larger biological datasets
Improve model accuracy
Integrate multi-omics data
Apply advanced graph neural networks
Support drug target discovery

Conclusion
This project demonstrates the effectiveness of Graph Convolutional Neural Networks in identifying biologically meaningful hub genes related to Alzheimer’s disease. The proposed framework can support future research in diagnosis and therapeutic target identification.

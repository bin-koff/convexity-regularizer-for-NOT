### **Project's name: Convexity Regularizer for Neural Optimal Transport**

### **Member of Project**
- Nikita Gushchin-TA

Team's name: BinKoff (Group 31)
- Bintang Alam Semesta W.A.M-1st year master student, ACS
- Fidele Koffivi Gbagbe-1st year master student, ACS
 
### **Research Idea**
The method proposed in the research paper uses adversarial training (kind of GANs). which is not very stable to compute the optimal transport map $T$. From the theory, the method's optimal "discriminator" must be convex, and its gradient can be used for inverse mapping from the target distribution to the source distribution.

### **Objectives**
Add a convexity regularizer in the loss of neural optimal transport algorithm to improve its stability during transport training and the high-quality of the inverse target-to-input mapping.

### **Environment (Dependencies)**
- [POT](https://pythonot.github.io/)
- [wandb](https://wandb.ai/site)
- [torch](https://pytorch.org/docs/stable/torch.html)
- [torchvision](https://pytorch.org/vision/stable/index.html)
- [numpy](https://numpy.org/)
- [tqdm](https://tqdm.github.io/)
- [matplotlib](https://matplotlib.org/)

how to install:
- `pip3 install -r dependencies.txt`
or
- `pip install -r dependencies.txt`

### **Folder Structure**
- images---documentation for snippet figures (format: `.jpeg` or `.png`)
   - ddd
   - ddd
   - dd
   
- models---documentation of the outputs (format:) 
  - ddd
  - ddd
  - ddd

- notebooks---documentation of source codes (format: `.ipynb`)
  - ddd
  - ddd
  - ddd

- resources---documentation of scientific papers from journals/conferences
  - dddd
  - dddd
  - ddd

- LICENSE
- README.md

### **Datasets**

### **Running an Experiment**
- Training a model

- Evaluating a model

- Full Experiment:
  - pre-processing
  - training
  - saving
  - testing


### **Acknowledgements**
(give credit here,........)

### **References**
Alexander Korotin, Daniil Selikhanovych, Evgeny Burnaev. [Neural Optimal Transport](https://arxiv.org/pdf/2201.12220.pdf).Eleventh International Conference on Learning Representations.arXiv:2201.12220v3 [cs.LG] 1 Mar 2023

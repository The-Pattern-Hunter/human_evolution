# 🧬 Human Evolution: Interactive Learning Notebooks

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/python-3.7%2B-blue)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)

**Interactive Jupyter notebooks for teaching human evolution and molecular phylogenetics**

---

## 👥 Authors

**Ms. Susama Kar**  
Department of Zoology  
Kuchinda College, Kuchinda  
Sambalpur University, Odisha, India

**Dr. Alok Patel**  
Head, Department of Zoology  
Kuchinda College, Kuchinda  
Sambalpur University, Odisha, India

---

## 📖 About This Project

This repository contains a comprehensive series of interactive Jupyter notebooks designed for BSc Zoology students studying human evolution and molecular phylogenetics. Following the **Pattern Hunters** educational philosophy, these notebooks emphasize discovery-based learning where students analyze real data, observe patterns, and build understanding through hands-on exploration.

### Key Features

✨ **Interactive visualizations** with sliders and controls  
🔬 **Real and simulated data** based on published research  
📊 **Step-by-step analysis** with detailed explanations  
🎯 **Pattern-based learning** - discover principles through observation  
🌍 **Evidence-based approach** - fossils, DNA, and modern populations  
☁️ **Cloud-ready** - runs directly in Google Colab, no installation needed

---

## 📚 Notebooks

### Part A: Human Evolution (Unit 4.1 - 4.2)

#### 01. Human Evolution Part 1: Fossil Evidence
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/The-Pattern-Hunter/human_evolution/blob/main/code/01_Human_Evolution_Part1_Fossils.ipynb)

**Topics Covered:**
- Primate characteristics and evolutionary adaptations
- Hominin fossil record from *Sahelanthropus* to *Homo sapiens*
- Interactive timeline of human evolution
- Morphological trends: brain size, bipedalism, tool use
- Comparative analysis between species (Lucy, *Homo erectus*, etc.)
- Geographic expansion patterns ("Out of Africa")

**Learning Outcomes:**
- Identify key primate characteristics
- Trace the evolutionary lineage of hominins
- Analyze trends in morphological evolution
- Compare and contrast different hominin species
- Understand the fossil evidence for human origins

---

#### 02. Human Evolution Part 2: Molecular Evidence
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/The-Pattern-Hunter/human_evolution/blob/main/code/02_Human_Evolution_Part2_Molecular.ipynb)

**Topics Covered:**
- DNA as a molecular clock
- Calculating genetic distances from sequences
- Molecular phylogenetic tree construction
- Interactive divergence time calculator
- Mitochondrial Eve and Y-chromosome Adam
- Neanderthal DNA in modern human populations
- Evidence for interbreeding between hominin species

**Learning Outcomes:**
- Understand molecular clock principles
- Calculate genetic distances from DNA sequences
- Build phylogenetic trees from molecular data
- Estimate divergence times using mutation rates
- Interpret population genetic evidence for human origins
- Analyze ancient DNA evidence

---

### Part B: Phylogenetic Methods (Unit 4.3 - 4.5)

#### 03. Introduction to Sequences
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/The-Pattern-Hunter/human_evolution/blob/main/code/03_Introduction_to_Sequences.ipynb)

**Topics Covered:**
- DNA and protein sequence basics
- Sequence formats (FASTA, GenBank)
- Reading and writing sequences
- Sequence databases (NCBI, UniProt)
- Basic sequence operations

**Learning Outcomes:**
- Work with biological sequence data
- Understand sequence file formats
- Access public sequence databases
- Perform basic sequence manipulations

---

#### 04. Multiple Sequence Alignment
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/The-Pattern-Hunter/human_evolution/blob/main/code/04_Multiple_Sequence_Alignment.ipynb)

**Topics Covered:**
- Pairwise sequence alignment
- Multiple sequence alignment (MSA)
- Alignment algorithms (Needleman-Wunsch, Smith-Waterman)
- Gap penalties and scoring matrices
- Visualizing and interpreting alignments
- Conservation analysis

**Learning Outcomes:**
- Perform pairwise and multiple sequence alignments
- Understand alignment algorithms
- Interpret alignment quality and conservation
- Recognize homologous regions in sequences

---

#### 05. Phylogenetic Tree Construction
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/The-Pattern-Hunter/human_evolution/blob/main/code/05_Phylogenetic_Tree_Construction.ipynb)

**Topics Covered:**
- Distance-based methods (UPGMA, Neighbor-Joining)
- Character-based methods (Maximum Parsimony)
- Model-based methods (Maximum Likelihood basics)
- Building trees from sequence alignments
- Comparing different tree-building methods

**Learning Outcomes:**
- Construct phylogenetic trees using different methods
- Understand the principles behind each method
- Calculate genetic distances
- Build and visualize evolutionary trees

---

#### 06. Tree Interpretation
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/The-Pattern-Hunter/human_evolution/blob/main/code/06_Tree_Interpretation.ipynb)

**Topics Covered:**
- Reading phylogenetic tree topology
- Branch lengths and evolutionary time
- Rooted vs. unrooted trees
- Bootstrap values and tree confidence
- Common mistakes in tree interpretation
- Comparing trees and testing hypotheses

**Learning Outcomes:**
- Correctly interpret phylogenetic trees
- Understand branch lengths and topology
- Assess tree reliability using bootstrap values
- Avoid common misinterpretations
- Extract evolutionary information from trees

---

## 🚀 Getting Started

### Option 1: Google Colab (Recommended - No Installation Required!)

Simply click the "Open in Colab" badge above any notebook. The notebook will open in Google Colab and you can run it immediately in your browser.

**Advantages:**
- ✅ No installation needed
- ✅ Free GPU access
- ✅ Automatic package installation
- ✅ Save your work to Google Drive
- ✅ Share with students easily

### Option 2: Local Installation

If you prefer to run notebooks locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/The-Pattern-Hunter/human_evolution.git
   cd human_evolution/code
   ```

2. **Create a virtual environment (recommended):**
   ```bash
   python -m venv evolution_env
   source evolution_env/bin/activate  # On Windows: evolution_env\Scripts\activate
   ```

3. **Install required packages:**
   ```bash
   pip install jupyter numpy matplotlib pandas seaborn scipy ipywidgets
   ```

4. **Enable Jupyter widgets:**
   ```bash
   jupyter nbextension enable --py widgetsnbextension
   ```

5. **Launch Jupyter:**
   ```bash
   jupyter notebook
   ```

6. **Open any notebook** from the file browser

---

## 📦 Dependencies

All notebooks use the following Python packages:
- `jupyter` - Interactive notebook environment
- `numpy` - Numerical computations
- `matplotlib` - Plotting and visualization
- `pandas` - Data manipulation and analysis
- `seaborn` - Statistical visualization
- `scipy` - Scientific computing (clustering, statistics)
- `ipywidgets` - Interactive controls and sliders

**Note:** When using Google Colab, all dependencies are pre-installed or installed automatically!

---

## 🎓 Who Is This For?

### **Students:**
- Undergraduate biology/zoology majors studying human evolution
- Students learning molecular phylogenetics and evolutionary biology
- Anyone interested in understanding human origins through data

### **Educators:**
- University instructors teaching evolution, anthropology, or molecular biology
- Teachers looking for interactive, hands-on learning materials
- Curriculum developers creating engaging educational content

### **Self-Learners:**
- Anyone curious about human evolution and our place in the tree of life
- Those wanting to learn bioinformatics approaches to evolutionary questions
- People interested in analyzing real scientific data

---

## 📖 Recommended Learning Path

We recommend working through the notebooks in the following order:

1. **Start here:** `01_Human_Evolution_Part1_Fossils.ipynb`
   - Builds foundation with fossil evidence
   - Introduces key concepts and species
   - Essential background for molecular analysis

2. **Then:** `02_Human_Evolution_Part2_Molecular.ipynb`
   - Reinforces fossil evidence with DNA data
   - Shows how molecular and morphological evidence converge
   - Introduces molecular clock concepts

3. **Technical foundation:** `03_Introduction_to_Sequences.ipynb`
   - Learn to work with sequence data
   - Understand file formats and databases

4. **Core methods:** `04_Multiple_Sequence_Alignment.ipynb`
   - Essential skill for all molecular phylogenetics
   - Practice with real sequences

5. **Tree building:** `05_Phylogenetic_Tree_Construction.ipynb`
   - Apply alignment skills to build trees
   - Compare different methods

6. **Advanced interpretation:** `06_Tree_Interpretation.ipynb`
   - Master reading and analyzing trees
   - Avoid common pitfalls

---

## 🎯 Pedagogical Approach: Pattern Hunters

These notebooks follow the **Pattern Hunters** philosophy:

### Traditional Approach
❌ Memorize characteristics  
❌ Accept conclusions without evidence  
❌ Passive consumption of information  

### Pattern Hunters Approach
✅ **Observe data first** - Look at fossil measurements, DNA sequences  
✅ **Discover patterns** - What trends emerge?  
✅ **Build understanding** - Construct explanations from evidence  
✅ **Think like scientists** - Use the same methods researchers use  
✅ **Ask questions** - Why? How do we know? What evidence supports this?  

**Result:** Deep understanding, critical thinking, and genuine scientific literacy.

---

## 📚 Key References

### Human Evolution and Fossil Record

1. **Wood, B.** (2010). Reconstructing human evolution: Achievements, challenges, and opportunities. *Proceedings of the National Academy of Sciences*, 107(supplement_2), 8902-8909.

2. **Klein, R. G.** (2009). *The Human Career: Human Biological and Cultural Origins* (3rd ed.). University of Chicago Press.

3. **Stringer, C.** (2016). The origin and evolution of Homo sapiens. *Philosophical Transactions of the Royal Society B: Biological Sciences*, 371(1698), 20150237.

4. **Johanson, D. C., & Edgar, B.** (2006). *From Lucy to Language: Revised, Updated, and Expanded*. Simon and Schuster.

5. **Brunet, M., et al.** (2002). A new hominid from the Upper Miocene of Chad, Central Africa. *Nature*, 418(6894), 145-151.

6. **White, T. D., et al.** (2009). Ardipithecus ramidus and the paleobiology of early hominids. *Science*, 326(5949), 64-86.

7. **Leakey, M. G., et al.** (1995). New four-million-year-old hominid species from Kanapoi and Allia Bay, Kenya. *Nature*, 376(6541), 565-571.

### Molecular Evolution and Ancient DNA

8. **Green, R. E., et al.** (2010). A draft sequence of the Neandertal genome. *Science*, 328(5979), 710-722.

9. **Prüfer, K., et al.** (2014). The complete genome sequence of a Neanderthal from the Altai Mountains. *Nature*, 505(7481), 43-49.

10. **Reich, D., et al.** (2010). Genetic history of an archaic hominin group from Denisova Cave in Siberia. *Nature*, 468(7327), 1053-1060.

11. **Meyer, M., et al.** (2012). A high-coverage genome sequence from an archaic Denisovan individual. *Science*, 338(6104), 222-226.

12. **Sankararaman, S., et al.** (2014). The genomic landscape of Neanderthal ancestry in present-day humans. *Nature*, 507(7492), 354-357.

### Mitochondrial DNA and Human Origins

13. **Cann, R. L., Stoneking, M., & Wilson, A. C.** (1987). Mitochondrial DNA and human evolution. *Nature*, 325(6099), 31-36.

14. **Ingman, M., et al.** (2000). Mitochondrial genome variation and the origin of modern humans. *Nature*, 408(6813), 708-713.

15. **Behar, D. M., et al.** (2008). The dawn of human matrilineal diversity. *American Journal of Human Genetics*, 82(5), 1130-1140.

### Y-Chromosome Studies

16. **Poznik, G. D., et al.** (2013). Sequencing Y chromosomes resolves discrepancy in time to common ancestor of males versus females. *Science*, 341(6145), 562-565.

17. **Underhill, P. A., & Kivisild, T.** (2007). Use of Y chromosome and mitochondrial DNA population structure in tracing human migrations. *Annual Review of Genetics*, 41, 539-564.

18. **Cruciani, F., et al.** (2011). A revised root for the human Y chromosomal phylogenetic tree: the origin of patrilineal diversity in Africa. *American Journal of Human Genetics*, 88(6), 814-818.

### Population Genetics and Human Diversity

19. **Tishkoff, S. A., & Verrelli, B. C.** (2003). Patterns of human genetic diversity: implications for human evolutionary history and disease. *Annual Review of Genomics and Human Genetics*, 4(1), 293-340.

20. **Ramachandran, S., et al.** (2005). Support from the relationship of genetic and geographic distance in human populations for a serial founder effect originating in Africa. *Proceedings of the National Academy of Sciences*, 102(44), 15942-15947.

21. **Li, J. Z., et al.** (2008). Worldwide human relationships inferred from genome-wide patterns of variation. *Science*, 319(5866), 1100-1104.

22. **1000 Genomes Project Consortium.** (2015). A global reference for human genetic variation. *Nature*, 526(7571), 68-74.

### Molecular Phylogenetics Methods

23. **Felsenstein, J.** (2004). *Inferring Phylogenies*. Sinauer Associates.

24. **Yang, Z.** (2014). *Molecular Evolution: A Statistical Approach*. Oxford University Press.

25. **Nei, M., & Kumar, S.** (2000). *Molecular Evolution and Phylogenetics*. Oxford University Press.

26. **Hall, B. G.** (2017). *Phylogenetic Trees Made Easy: A How-To Manual* (5th ed.). Sinauer Associates.

27. **Mount, D. W.** (2004). *Bioinformatics: Sequence and Genome Analysis* (2nd ed.). Cold Spring Harbor Laboratory Press.

### Sequence Alignment

28. **Needleman, S. B., & Wunsch, C. D.** (1970). A general method applicable to the search for similarities in the amino acid sequence of two proteins. *Journal of Molecular Biology*, 48(3), 443-453.

29. **Smith, T. F., & Waterman, M. S.** (1981). Identification of common molecular subsequences. *Journal of Molecular Biology*, 147(1), 195-197.

30. **Thompson, J. D., Higgins, D. G., & Gibson, T. J.** (1994). CLUSTAL W: improving the sensitivity of progressive multiple sequence alignment. *Nucleic Acids Research*, 22(22), 4673-4680.

31. **Edgar, R. C.** (2004). MUSCLE: multiple sequence alignment with high accuracy and high throughput. *Nucleic Acids Research*, 32(5), 1792-1797.

### Phylogenetic Tree Construction

32. **Saitou, N., & Nei, M.** (1987). The neighbor-joining method: a new method for reconstructing phylogenetic trees. *Molecular Biology and Evolution*, 4(4), 406-425.

33. **Fitch, W. M., & Margoliash, E.** (1967). Construction of phylogenetic trees. *Science*, 155(3760), 279-284.

34. **Sokal, R. R., & Michener, C. D.** (1958). A statistical method for evaluating systematic relationships. *University of Kansas Science Bulletin*, 38, 1409-1438.

### Molecular Clock

35. **Zuckerkandl, E., & Pauling, L.** (1965). Evolutionary divergence and convergence in proteins. In *Evolving Genes and Proteins* (pp. 97-166). Academic Press.

36. **Kumar, S., & Hedges, S. B.** (2016). Advances in time estimation methods for molecular data. *Molecular Biology and Evolution*, 33(4), 863-869.

37. **Bromham, L., & Penny, D.** (2003). The modern molecular clock. *Nature Reviews Genetics*, 4(3), 216-224.

### Online Resources and Databases

38. **NCBI GenBank** - https://www.ncbi.nlm.nih.gov/genbank/  
    Benson, D. A., et al. (2013). GenBank. *Nucleic Acids Research*, 41(D1), D36-D42.

39. **UniProt** - https://www.uniprot.org/  
    The UniProt Consortium. (2021). UniProt: the universal protein knowledgebase in 2021. *Nucleic Acids Research*, 49(D1), D480-D489.

40. **Ensembl** - https://www.ensembl.org/  
    Cunningham, F., et al. (2022). Ensembl 2022. *Nucleic Acids Research*, 50(D1), D988-D995.

41. **Human Origins Program (Smithsonian)** - https://humanorigins.si.edu/

42. **UCSC Genome Browser** - https://genome.ucsc.edu/  
    Kent, W. J., et al. (2002). The human genome browser at UCSC. *Genome Research*, 12(6), 996-1006.

---

## 🤝 Contributing

We welcome contributions! If you find errors, have suggestions for improvements, or want to add new content:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Create a Pull Request

---

## 📧 Contact

**Ms. Susama Kar**  
Department of Zoology  
Kuchinda College, Kuchinda  
Sambalpur University, Odisha, India

**Dr. Alok Patel**  
Head, Department of Zoology  
Kuchinda College, Kuchinda  
Sambalpur University, Odisha, India

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- Kuchinda College and Department of Zoology for supporting this educational initiative
- Sambalpur University for academic guidance
- Students who provided feedback during development
- The open-source scientific Python community
- All researchers whose work formed the foundation of these materials

---

## 📊 Repository Statistics

![GitHub stars](https://img.shields.io/github/stars/The-Pattern-Hunter/human_evolution?style=social)
![GitHub forks](https://img.shields.io/github/forks/The-Pattern-Hunter/human_evolution?style=social)
![GitHub issues](https://img.shields.io/github/issues/The-Pattern-Hunter/human_evolution)
![GitHub last commit](https://img.shields.io/github/last-commit/The-Pattern-Hunter/human_evolution)

---

## 🌟 Citation

If you use these notebooks in your teaching or research, please cite:

```bibtex
@misc{kar2025humanevolution,
  author = {Kar, Susama and Mohanty, Alok Kumar},
  title = {Human Evolution: Interactive Learning Notebooks},
  year = {2025},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/The-Pattern-Hunter/human_evolution}},
  note = {Department of Zoology, Kuchinda College, Sambalpur University, Odisha, India}
}
```

---

<div align="center">

**Made with ❤️ for students exploring human origins**

*"Understanding where we came from helps us understand who we are"*

---

**Kuchinda College | Department of Zoology | Sambalpur University**

</div>

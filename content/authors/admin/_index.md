---
# Display name
title: Omid Shams Solari

# Name pronunciation (optional)
name_pronunciation: ɔːmɪ̈d ʃæms sɔːlɑːrɪ

# Full name (for SEO)
first_name: Omid
last_name: Shams Solari

# Status emoji
status:
#  icon: ☕️icon

# Is this the primary user of the site?
superuser: true

# Highlight the author in author lists? (true/false)
highlight_name: true

# Role/position/tagline
role: Lead AI Research Scientist

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: University of California, Berkeley
    url: https://www.berkeley.edu/
  - name: Natera Inc.
    url: https://www.natera.com/

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'mailto:solari@berkeley.edu'
    label: E-mail Me
  - icon: brands/x
    url: https://twitter.com/omidsolari
#  - icon: brands/instagram
#    url: https://www.instagram.com/
  - icon: brands/github
    url: https://github.com/osolari
  - icon: brands/linkedin
    url: https://www.linkedin.com/in/osolari
  - icon: academicons/google-scholar
    url: https://scholar.google.com/citations?user=duHKwCMAAAAJ&hl=en
#  - icon: academicons/orcid
#    url: https://orcid.org/

interests:
  - Explainable AI, Multi-Modal AI, Sequence Models
  - Language Models, e.g. DNA/protein Language Models
  - Statistical/Machine Learning 
  - Biomarker Discovery

education:
  - area: PhD Statistics (Emphasis on Optimization and Machine learning)
    institution: University of California, Berkeley
    date_start: 2014-09-30
    date_end: 2020-05-31
    summary:
      |
      Large Scale Interpretable Multi-View Learning with Application To High-Dimensional Multi-Omics 
      Advisors & Thesis Committee: Prof. Peter J. ***Bickel***, Dr. James B. ***Brown***, Prof. Gary ***Karpen*** & Prof. Haiyan ***Huang***.
      
      - **MuLe**: Formulated and implemented a novel large-scale interpretable and stable multi-view learning method for high-dimensional datasets with low sample size and utilized it to infer co-regulated modules between Metabolomics, Trasciptomics, and Microbiomics data collected on fruitfly samples in a treatment/control experiment.
      - **BLOCCS**: Extended **MuLe** to perform block matrix decomposition leading to more interpretable orthogonal canonical covariates.  
      - **SparKLe**: Formulated and implemented a novel multiple kernel learning approach applied to kernel dimensionality reduction, implemented in.
      -  Implemented a spark implementation of the three previous packages on **Spark-MLlib**.
#      Thesis on _Why LLMs are awesome_. Supervised by [Prof Joe Smith](https://example.com). Presented papers at 5 IEEE conferences with the contributions being published in 2 Springer journals.
    button:
      text: 'Read Thesis'
      url: 'https://www.proquest.com/openview/fe9e3cfba5a78cb0f17d30379d7fa887/1?pq-origsite=gscholar&cbl=51922&diss=y'
    
  - area: MA Applied Mathematics
    institution: University of California, Berkeley
    date_start: 2012-01-01
    date_end: 2014-12-31
    summary: |
      Thesis Advisers: Prof. Per-Olof ***Persson*** & Prof. Alberto ***Grunbaum***.
      - Numerically efficient implementation and benchmarking of second-order PDE solutions, specifically the wave equation (**Python** and **C++**).
      - **Advection-Corrected Correlation Image Velocimetry**: Numerical Computation of the velocity fields of Saturn's surface vortices from Cassini images.
  - area: B.Sc. Computational Fluid Dynamics
    institution: Sharif University of Technology
    date_start: 2006-08-01
    date_end: 2011-06-30
    summary: |
      Computational patricle image velocimetry, modeling the transfer and deposition patterns 
      of aerosols in the upper airways via finite volume analysis in C++ and OpenFoam.
work:
  - position: Lead AI Research Scientist, Precision Oncotherapeutics AI Modeling Lead
    company_name: Natera Inc.
    company_url: ''
    company_logo: ''
    date_start: 2024-09-01
    date_end: ''
    summary: |2-
      **(Ranked _exceeding_ (top 10%) for 2 consecutive years)**
        - Implemented a end-to-end **Vision Transformer (ViT)** pipline for neoantigen prioritization which predicts the HLA binding likelihood of a given neopeptide.
        - Developed a protein **language model** to predict post-translational modification likelihoods from short protein sequences.
        - Designed and developed a data pipeline and a **survival prediction** model to infer patient-specific somatic mutations associated with differential response to platinum-based therapies.
  - position: 
            |
          Lead Statistician and Machine Learning Research Scientist, Head of MCED/ECD/tfMRD/COO Biomarker Discovery Algorithms
    company_name: Natera Inc.
    company_url: ''
    company_logo: ''
    date_start: 2022-03-15
    date_end: 2024-09-01
    summary: |
      **(Ranked _exceeding_ (top 10%) for 2 consecutive years)**
        - Designed and implemented **CpGTools** which is the software infrastructure and the computational pipeline of the newly established Early Cancer Detection (**ECD**) and tissue-free Minimal Residual Disease (**tf-MRD**) program which is now the basis for all computational methylation efforts at Natera.
        - Designed and implemented the first completely reference-free methylation biomarker discovery pipeline. (Patent Application Submitted)
        - Developed a novel **Hierarchical Bariational Bayes** model to infer differentially methylated biomarkers from deep whole genome bsulfite sequencing data. (Patent Application Submitted)
        - Implemented a **transformer VAE** to learn the whole genome methylation patterns of healthy cfDNA samples.
        - Designed Natera's CRC ECD/tfMRD methylation biomarker panel. (Patent Application Submitted)
        - Formed and directed the Cell-Type of Origin Pursuit Group (C2pG). A team of 4 dedicated to the **cancer cell of origin** problem.
        - Designed Natera's first **MCED** biomarker panel
  - position: 
            |
          AI Lead Scientist
    company_name: Ravel Biotechnology Inc.
    company_url: ''
    company_logo: ''
    date_start: 2021-04-15
    date_end: 2022-03-01
    summary: |
      Cancer Prediction Model, Seq2Seq modeling and motif discovery, Cell-type Decomposition
      - Developed deep **Seq2Seq** models to infer functional events, e.g. histone modifications from accessibility patterns in cfDNA and utilized attribution priors to discover highly predictive motifs from **regularized attributions**.
      - Developed a **variational Bayes** model to infer cell-type of origin from functional events e.g. methylation and histone modification.
  - position: 
            |
          Senior Machine Learning Research Scientist
    company_name: Ravel Biotechnology Inc.
    company_url: ''
    company_logo: ''
    date_start: 2020-03-15
    date_end: 2021-03-15
    summary: |
      Fragmentomics panel design, cancer prediction modeling
      - Designed Ravel's fragmentomics targeted panel
      - Developed Ravel's main **high-dimensional** low sample size cancer prediction framework.
      - Utilized **integrated gradients** to find cancer predictive DNA fragmentation patterns
  - position: 
            |
          Post-Doctoral Associate
    company_name: Chan Zuckerberg BioHub Initiative (CZI)
    company_url: ''
    company_logo: ''
    date_start: 2019-10-01
    date_end: 2020-03-15
    summary: |
      Developed Explainable AI models for Genomic Data
      
  - position: 
            |
          Contract/Non-Profit Machine Learning \& Data Science Consultant
    company_name: Department of Statistics, University of California, Berkeley
    company_url: ''
    company_logo: ''
    date_start: 2017-09-01
    date_end: 2020-03-15
    summary: |
      Provided consulting services on a variety of topics e.g. Deep Learning, Neuroscience, Linguistics, Public Health, 
      International Development, Genomics, Bio-chemistry etc. to academic and industrial clients.
      
  - position: 
            |
          Statistical Learning Research Associate
    company_name: Lawrence Berkeley National Laboratory 
    company_url: ''
    company_logo: ''
    date_start: 2015-10-01
    date_end: 2020-03-15
    summary: |
        Collaborated with the  Molecular Eco-Systems Biology Division and the Daphnia Consortium in mining, modeling and interpretation of genomic data.
  - position: 
            |
          Ensemble Machine Learning Research Intern
    company_name: Illumina Inc.
    company_url: ''
    company_logo: ''
    date_start: 2017-06-01
    date_end: 2017-09-15
    summary: |
      Designed and implemented **DEnsLe**, a deep variational ensemble learner, in **PyTorch**, 
      to construct a ensemble learner that models the dependence structure between multiple different SNV callers.
      
  - position: 
            |
          Lead Data Analyst
    company_name: Genapsys Inc.
    company_url: ''
    company_logo: ''
    date_start: 2014-01-01
    date_end: 2014-07-01
    summary: |
        - Implemented a **MATLAB** pipeline to perform QC of raw output signals of Genius&trade; short-read genome sequencers.
        - Statistical analysis of the sensor array network output, e.g. clustering, correlation analysis, and base-calling.

# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: Technical Skills
    items:
      - name: Pytorch Ecosystem (Lightning, Geometric, Ray, Pyro, fastai, Captum)
        description: ''
        percent: 80
        icon: code-bracket
      - name: Statistical Modeling and Inference (Multi-View Learning, High-Dimensional Learning, Variational Inference)
        description: ''
        percent: 100
        icon: chart-bar
#      - name: 
#        description: ''
#        percent: 40
#        icon: circle-stack
  - name: Hobbies
    color: '#eeac02'
    color_border: '#f0bf23'
    items:
      - name: Welding (MIG, TIG, Stick, Spot)
        description: ''
        percent: 60
        icon: wrench
      - name: Algorithmic Trading
        description: ''
        percent: 100
        icon:  variable
      - name: Motorcycles
        description: ''
        percent: 80
        icon: wrench-screwdriver
      - name: Dog-walking
        description: ''
        percent: 80
        icon: 

languages:
  - name: English
    percent: 100
  - name: Farsi
    percent: 100
  - name: Arabic
    percent: 50
  - name: French
    percent: 50
  - name: German
    percent: 25

# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
awards:
  - title: Chan Zuckerberg Biohub Initiative Award
    awarder: CZI
    date: 2019-08-01
  - title: Sally \& Terry Speed Award
    awarder: UC Berkeley
    date: 2018-09-01
  - title: UC Berkeley Excellence Award
    awarder: University of California
    date: 2012-07-01
  - title: UC Berkeley Fellowship for Graduate Studies
    awarder: University of California
  - title: UC San Diego Fellowship
    awarder: University of California
  - title: University of British Columbia Scholarship
    date: 
    awarder: University of British Columbia

#  - title: Neural Networks and Deep Learning
#    url: https://www.coursera.org/learn/neural-networks-deep-learning
#    date: '2023-11-25'
#    awarder: Coursera
#    icon: coursera
#    summary: |
#      I studied the foundational concept of neural networks and deep learning. By the end, I was familiar with the significant technological trends driving the rise of deep learning; build, train, and apply fully connected deep neural networks; implement efficient (vectorized) neural networks; identify key parameters in a neural network’s architecture; and apply deep learning to your own applications.
#  - title: Blockchain Fundamentals
#    url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#    date: '2023-07-01'
#    awarder: edX
#    icon: edx
#    summary: |
#      Learned:
#      - Synthesize your own blockchain solutions
#      - Gain an in-depth understanding of the specific mechanics of Bitcoin
#      - Understand Bitcoin’s real-life applications and learn how to attack and destroy Bitcoin, Ethereum, smart contracts and Dapps, and alternatives to Bitcoin’s Proof-of-Work consensus algorithm
#  - title: 'Object-Oriented Programming in R'
#    url: https://www.datacamp.com/courses/object-oriented-programming-with-s3-and-r6-in-r
#    certificate_url: https://www.datacamp.com
#    date: '2023-01-21'
#    awarder: datacamp
#    icon: datacamp
#    summary: |
#      Object-oriented programming (OOP) lets you specify relationships between functions and the objects that they can act on, helping you manage complexity in your code. This is an intermediate level course, providing an introduction to OOP, using the S3 and R6 systems. S3 is a great day-to-day R programming tool that simplifies some of the functions that you write. R6 is especially useful for industry-specific analyses, working with web APIs, and building GUIs.
---

## About Me

Dr. Omid Shams Solari is currently the Lead AI Research Scientist and Statistician at Natera Inc. His research interests include AI language models,
e.g. DNA/protein language models, multi-modal AI, interpretable AI, high-dimensional statistical learning and inference.
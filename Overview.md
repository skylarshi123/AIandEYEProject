# AI Detection for Age-Related Macular Degeneration (AMD) - Documentation

## Statistics (From a 2020 report on South India)

- **Cataract**: 58.6%
- **Refractive error**: 30.2%
- **Conjunctivitis**: 15.2%
- **Glaucoma**: 5.1%
- **Age-related macular degeneration (AMD)**: 3.1%
- **Diabetic retinopathy**: 2.8%
- **Ophthalmic trauma**: 2.6%
- **Corneal opacity**: 2.4%
- **Pterygium**: 1.9%
- **Uveitis**: 1.8%
- **Retinal artery occlusion**: 1.2%
- **Central serous chorioretinopathy (CSC)**: 1.1%

## General Idea

- The current cutting-edge for eye disease detection models relies on deep learning, particularly convolutional neural networks (CNNs).
- CNNs are highly effective for image recognition tasks and have achieved high accuracy in detecting eye diseases from retinal images.

## Current Areas for Improvement

- Challenges include computational cost, overfitting, variation in retinal images, and early disease detection.

## Feasibility and Current Obstacles

- Developing a detection model for AMD is feasible due to available research and publicly available datasets.
- Challenges include the complexity of the task, the need for an understanding of eye biology, and the time-consuming nature of model development.

## Disease to Focus on

- Focusing on age-related macular degeneration (AMD) is recommended due to its prevalence and lack of a cure.
- Key features for AMD detection include drusen, retinal pigment epithelium (RPE) atrophy, and choroidal neovascularization (CNV).

## Timeline and Goals

- Goal: Develop an AMD detection model with at least 90% accuracy on the AREDS dataset.
- Steps:
    1. Data preparation
    2. Model selection (CNNs recommended)
    3. Model training
    4. Model evaluation
    5. Model deployment

## Required Data, Models, and Skills/Technologies

### Data:

- Retinal images from the AREDS dataset.

### Machine Learning Models:

- CNNs are recommended for AMD detection.

### Programming Languages:

- Python is commonly used for machine learning development.

### Deep Learning Frameworks:

- TensorFlow and PyTorch are popular choices.

### Computing Platform:

- A GPU cluster is recommended for training and evaluating large deep learning models.

### Other Skills/Technologies:

- Image processing is essential for preprocessing retinal images and segmenting the macula.
- Knowledge of statistics is important.

## Current AMD Research

- Ongoing research aims to improve accuracy and specificity while handling variations in retinal images.
- Multimodal imaging, AI, and high accuracy models are active areas of study.

## How AI Detection Can Be Used for AMD

AI detection for AMD can be employed in various ways, including:

1. **Screening**: AI-powered algorithms can analyze retinal images from large populations to identify individuals at risk of developing AMD, enabling early intervention.
2. **Diagnosis**: AI assists doctors in diagnosing AMD by identifying early signs such as drusen and geographic atrophy.
3. **Prognosis**: AI can predict disease progression, aiding in the development of personalized treatment plans.
4. **Monitoring**: AI can track treatment responses and detect complications early on.

AI detection for AMD typically looks for the following features in retinal images:

- **Drusen**: Small yellow deposits on the retina, characteristic of early AMD.
- **Geographic atrophy (GA)**: A type of AMD causing thinning and irregular patches of bare retina.
- **Choroidal neovascularization (CNV)**: A type of AMD leading to new blood vessels under the retina, which can cause damage and vision loss.

AI algorithms can identify these features accurately, facilitating screening, diagnosis, and monitoring in clinical settings.

## Recent Research

Recent studies demonstrate significant progress in AMD detection:

1. A study in Nature Medicine (2023) reported a deep learning model detecting AMD with 98.6% accuracy and 99.4% specificity.
   [Read more](https://pubmed.ncbi.nlm.nih.gov/37023082/)

2. An Ophthalmology study (2022) showed a multimodal deep learning model achieving 99.2% accuracy and 99.1% specificity.
   [Read more](https://www.nature.com/articles/s41598-022-06273-w)

3. In IEEE Transactions on Medical Imaging (2023), an AI-powered AMD detection model achieved 97.8% accuracy and 99.5% specificity.
   [Read more](https://pubmed.ncbi.nlm.nih.gov/35204621)

Overall, the current state of AMD detection research is very promising, with room for further improvement.

## Datasets for AMD

There are several publicly available datasets suitable for developing and evaluating AI algorithms for AMD detection, including:

- **Northumbria University AMD Dataset**: Contains optical coherence tomography (OCT) images with labels indicating AMD type and stage, along with clinical data.
- **Duke AMD Dataset**: Comprises OCT images and clinical data, including visual acuity.
- **Heidelberg AMD Dataset**: Includes OCT images and clinical information such as age and gender.
- **AREDS2 Dataset**: Contains OCT images from participants in the Age-Related Eye Disease Study 2 (AREDS2) clinical trial.
- **IMAGE-AMD Dataset**: Offers OCT images, clinical data, and labels for the presence or absence of CNV.

In addition to these datasets, ongoing research projects are collecting innovative data for AMD detection, such as the AMD Biomarker Discovery Challenge. This competition encourages the development of new biomarkers for AMD using various data sources, including OCT images, fundus images, and genetic data.

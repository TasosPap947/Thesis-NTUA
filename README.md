# Abstract

Detecting brain disorders is critical to understanding and managing changes that
affect human consciousness and behavior. Normative modeling offers a breakthrough
approach by enabling the detection of pathologies through comparison with normal brain
functional patterns. The integration of artificial intelligence and machine learning, in
particular autoencoders, greatly enhances the accuracy and efficiency of this technique.
This thesis presents the development of two normative modeling frameworks: one using
an autoencoder architecture and the other using a variational autoencoder. These models
were trained on data from healthy individuals in the UK Biobank. After adjustment
for confounders using linear regression and standard scaling, a normative pattern was
established. The normative pattern was based on healthy subjects. The models were
then tested on semi-synthetic data with simulated atrophy to assess deviations using
reconstruction error. Furthermore, the models were evaluated on the ADNI dataset,
which includes individuals with normal cognitive function, mild cognitive impairment, and
Alzheimer’s disease. The results showed that these models can effectively discriminate
between healthy and pathological brain states, paving the way for early diagnosis and
treatment of brain disorders. In addition, the models can classify diseases with minimal
labeled data for training, providing significant advantages over traditional methods that
require extensive labeled datasets.

**Keywords:** Normative Modeling, Autoencoders, Variational Autoencoders, Mild Cognitive Impairment,
Alzheimer’s disease, Computational Neuroscience, Atrophy, Brain, Neurodegenerative
Diseases, Machine Learning

Problem
In a developing Nation like India Medical Image samples are often less in number than required for various research and clinical studies. Small data sets are major obstacles, in particular for supervised machine learning. To overcome this hurdle, some efforts have turned to the augmentation of existing data.

Gan Architecture
image

A normal ML has only one Neural Network .But Gans consist of two neural networks

GENERATOR Model that is used to generate new plausible examples from the problem domain.

DISCRIMINATOR Model that is used to classify examples as real (from the domain) or fake (generated).

Trainig a gan on Brain MRI dataset
Input:

nonDem40 jpg_resized mildDem700 jpg_resized

Output:

testing_18 testing_56

Advantages
Cross modality image synthesis and image fusion. images from CT, PET, and MR images differ from each other in terms of complexity and dimensionality to incorporate modalityspecific information which ultimately assists in better diagnosis. However, these diversities create a major constrain when it comes to cross-modality image synthesis. For instance, hybrid imaging involves simultaneous imaging from two modalities like MRI/PET, CT/PET imaging. The extraction of information of one modality from the hybrid images is usually a tough exercise.
Reduced radiation dose with minimal loss of image quality in radiation dependent imaging modalities.
Overall Cost effectivity

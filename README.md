# Problem
In a developing Nation like India Medical Image samples are often less in number than required for various research and clinical studies. Small data sets are major obstacles, in particular for supervised machine learning. To overcome this hurdle, some efforts have turned to the augmentation of existing data.

## GAN Architecture
![Typical-structure-of-vanilla-GAN](https://github.com/user-attachments/assets/c5ff8ff9-3716-4b9b-b089-74986d6f490a)



A normal ML has only one Neural Network .But Gans consist of two neural networks

<ol>
  <li>GENERATOR Model that is used to generate new plausible examples from the problem domain.</li>
  <li>DISCRIMINATOR Model that is used to classify examples as real (from the domain) or fake (generated).</li>
</ol>

## Trainig a gan on Brain MRI dataset
Input:

![inp 1](https://github.com/user-attachments/assets/1ea17b46-efb6-4316-a16a-c74fa6d5b95a) ![inp 2](https://github.com/user-attachments/assets/d65fa97b-f137-4080-a752-daf58b73f0e9)


Output:

![out 1](https://github.com/user-attachments/assets/d02f3bcb-33d7-41b7-a4ea-ff230fe754e7) ![out 2](https://github.com/user-attachments/assets/e2a86812-0431-4b54-8e1b-81d148abb278)

## Advantages
<ul>
  <li>Cross modality image synthesis and image fusion. images from CT, PET, and MR images differ from each other in terms of complexity and dimensionality to incorporate modalityspecific information which ultimately assists in better diagnosis. However, these diversities create a major constrain when it comes to cross-modality image synthesis. For instance, hybrid imaging involves simultaneous imaging from two modalities like MRI/PET, CT/PET imaging. The extraction of information of one modality from the hybrid images is usually a tough exercise.
  </li>
  <li>Reduced radiation dose with minimal loss of image quality in radiation dependent imaging modalities.
  </li>
  <li>Overall Cost effectivity
  </li>
</ul>

## GAN Evaluation Metrics
Inception Score (IS), Fréchet Inception Distance (FID), Largest Inception Distance (LID), Precision and Recall for Distributions (PRD), Geometric Score (GS) etc.


The rapid advancement of medical imaging technologies has revolutionized diagnostics and treatment planning in healthcare. However, the increasing complexity and volume of medical images pose significant challenges in their analysis and interpretation. This project aims to address these challenges by exploring and comparing innovative approaches to medical image analysis.

The main objective of this project is to compare four models: two of them based on KDM (Kernel Density Matrices), one based on MLE (Maximum Likelihood Estimation) using KDM, and the final one based on a typical convolutional neural network (CNN). This comprehensive comparison will provide insights into the effectiveness of different methodologies in medical image analysis. To ensure a thorough evaluation, each of the four models will be implemented and tested on four distinct datasets:

28 x 28 pixel RGB images
28 x 28 pixel grayscale images
64 x 64 pixel RGB images
64 x 64 pixel grayscale images
This diverse range of image sizes and color formats will allow us to assess the models' performance across different resolutions and color complexities, providing a more comprehensive understanding of their capabilities and limitations.

Kernel Density Matrices (KDM) represent a novel approach in the field, offering potential advantages in capturing complex spatial relationships within medical images. By incorporating two KDM-based models, we aim to explore the versatility and robustness of this method. The inclusion of an MLE model using KDM further extends our investigation into probabilistic approaches to image analysis.

Convolutional neural networks have become a standard in image processing tasks, including medical applications. By comparing a CNN model with the KDM-based approaches, we seek to benchmark the performance of these novel methods against an established technique.

This project's findings will contribute to the growing body of knowledge in medical image analysis, potentially offering new tools and insights for healthcare professionals. The comparative analysis across different image types and sizes will shed light on the strengths and limitations of each approach, paving the way for more accurate and efficient diagnostic processes in the medical field.

The data used in this project is obtained from MedMNIST and MedMNIST+. We use the PathMNIST dataset concerning colon pathologies.

The datasets consist of images of size 28x28 for MedMNIST and of sizes 64x64 and 128x128 for MedMNIST+. Our models will be evaluated with these three datasets.

The task will concern multiclass clasification (9 classes).

Theoric aproach
The theoric aproach of this project can be obteined in the following link: https://arxiv.org/abs/2305.18204

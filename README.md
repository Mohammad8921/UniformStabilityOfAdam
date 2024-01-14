# Uniform Stability of Adam Algorithm and its Effect on Generalization Error of Deep Neural Networks
## Info
This repo contains all of the codes of my master theoretical thesis supervised by [Dr. Amin Gheibi](https://scholar.google.ca/citations?user=7Eng5oAAAAAJ&hl=en), conducted at Amirkabir University of Technology (Tehran Polytechnic).
  
## Abstract
* We theoretically connected the Lipschitz constant and maximum value of a loss function to the generalization error of deep learning models trained by the Adam and AdamW optimizers under the uniform stability theory.
* Using the theoretical results, we proposed a novel loss function for training deep classification models to improve the generalization performance and overcome the over-fitting issue.
* We assessed our theorems in human age estimation based on face images.
* We trained deep neural networks using our new loss function in the image and node classification problems in order to stabilize the output models and increase their accuarcy.
* Requirements:
  - Python 3.7.8
  - SciPy 1.7.3
  - OpenCV 4.5.5
  - PyTorch 1.11
  - CUDA 11.3
  - Torchvision 0.12
  - PyTorch Geometric 2.1
## Paper
* An original paper contains the theorems, proofs, and experiments on age estimation has been accepted for publication in Amirkabir Journal of Mathematics and Computing (AJMC);
* the article on the journal website: https://ajmc.aut.ac.ir/article_5213.html;
* PDF on arxiv: https://arxiv.org/abs/2303.16464.

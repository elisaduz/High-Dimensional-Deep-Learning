## <a href="http://www.insa-toulouse.fr/" ><img src="http://www.math.univ-toulouse.fr/~besse/Wikistat/Images/Logo_INSAvilletoulouse-RVB.png" style="float:left; max-width: 80px; display: inline" alt="INSA"/> |  [*Mathématiques Appliquées*](http://www.math.insa-toulouse.fr/fr/index.html), [`Science des Données`](http://www.math.insa-toulouse.fr/fr/enseignement.html) 

# High Dimensional and Deep Learning

## Presentation :

The main theme of the course is learning methods, especially deep neural networks, for  processing  high dimensional  data, such as signals or images. We will cover the following topics:

 
* Neural networks and introduction to deep learning: definition of neural networks, activation functions, multilayer perceptron, backpropagation algorithms, optimization algorithms, regularization  
**Application** : [Implementation of a mlp with one layer with `Numpy`](https://github.com/wikistat/High-Dimensional-Deep-Learning/tree/master/BackPropagation)


* Convolutional neural networks: convolutional layer, pooling, dropout, convolutional network architectures (ResNet, Inception), transfer learning and fine tuning, applications for image or signal classification.  
**Application** : [Image classification on *MNIST* and *CatsVsDogs* data with `Tensorflow`](https://github.com/wikistat/High-Dimensional-Deep-Learning/tree/master/ImageClassification)


* Encoder-decoder, Variational auto-encoder, Generative adversarial networks

* Functional decomposition on splines, Fourier or wavelets bases: cubic splines, penalized least squares criterion, Fourier basis, wavelet bases, applications to nonparametric regression, linear estimators and nonlinear estimators by thresholding, links with the LASSO method.

* Anomaly detection for functional data: One Class SVM, Random Forest, Isolation Forest, Local Outlier Factor. Applications to  anomaly detection in functional data.
 
* Deep learning for time series forecasting
 
* Object detection / image segmentation

------------
 

## Organisation : 

* Lectures : 15 H .

* Practical works : 28 H applications on real data sets with the softwares R and Python's libraries Scikit Learn and Keras -Tensorflow. 

## Evaluation

* written exam (50 %) - 

* project (oral presentation 25%  + notebook (25%) <br>The main of this project is to apply the knowledge you acquired during this course by:

    * Selecting a deep learning algorithm you haven't seen in this course.
    * Explaining how this algorithm works (oral presentation).
    * Apply these algorithm on a dataset and explain their performances (notebook and oral presentation).

You can choose a deep learning algorithm among the following list. <br>
This list is not exhaustive and you can suggest other algorithms (that's actually a good idea). <br>
Also, the code proposed on those examples are not necessarily the official code nor the one propose by the authors. <br>


**Example of algorithms**
 
* Detection & segmentation
    * U-net [paper](https://arxiv.org/abs/1505.04597), [code](https://www.tensorflow.org/tutorials/images/segmentation)
    * Focal Loss for Dense Object Detection [paper](https://arxiv.org/abs/1708.02002), [code](https://github.com/fizyr/keras-retinanet)

* One shot learning
    * Siamese Network [paper](https://www.cs.cmu.edu/~rsalakhu/papers/oneshot1.pdf), [code](https://github.com/tensorfreitas/Siamese-Networks-for-One-Shot-Learning)
 
* Style Transfer 
    * A Neural Algorithm of Artistic Style [paper](https://arxiv.org/abs/1508.06576), [code](https://www.tensorflow.org/tutorials/generative/style_transfer)
    * Cycle gan [paper](https://arxiv.org/pdf/1703.10593.pdf), [code](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix)
 
* Generative model
    * Pixel Cnn/++ [paper](https://arxiv.org/abs/1606.05328), [code](https://github.com/openai/pixel-cnn)
    * Gan variation [paper](https://arxiv.org/abs/1701.07875), [code](https://github.com/martinarjovsky/WassersteinGAN)
    * NetGAN without GAN: From Random Walks to Low-Rank Approximations [paper](https://www.tml.cs.uni-tuebingen.de/team/luxburg/publications/RensburgLuxburg_Netgan_without_Gan2020.pdf), [code](https://github.com/hheidrich/CELL)
  
* Contrastive learning 
   * Supervized contrastive learning [paper](https://arxiv.org/pdf/2004.11362v5.pdf), [code](https://github.com/HobbitLong/SupContrast) in Pytorch 
 
* Fairness
    * Achieving Equalized Odds by Resampling Sensitive Attributes [paper](https://arxiv.org/abs/2006.04292), [code](https://github.com/yromano/fair_dummies)
    
* Unsupervised learning:
    * Unsupervised Representation Learning by Predicting Image Rotations [paper](https://openreview.net/forum?id=S1v4N2l0-), [code](https://github.com/gidariss/FeatureLearningRotNet)
    * Self-supervised Label Augmentation via Input Transformations [paper](https://arxiv.org/abs/1910.05872), [code](https://github.com/hankook/SLA)
    * A Simple Framework for Contrastive Learning of Visual Representations [paper](https://arxiv.org/abs/2002.05709), [code](https://github.com/sthalles/SimCLR)
    * Exploring Simple Siamese Representation Learning [paper](https://arxiv.org/abs/2011.10566)
, [code](https://github.com/facebookresearch/simsiam)

* Domain adaptation/generalisation:
    * Domain Generalization by Solving Jigsaw Puzzles [paper](https://arxiv.org/pdf/1903.06864.pdf), [code](https://github.com/fmcarlucci/JigenDG)
    * Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks [paper](https://arxiv.org/pdf/1703.10593.pdf), [code](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix)

* Regularization:
    * mixup: Beyond Empirical Risk Minimization [paper](https://arxiv.org/abs/1710.09412), [code](https://github.com/facebookresearch/mixup-cifar10)

* Time series
    * GP-VAE: Deep Probabilistic Time Series Imputation [paper](https://arxiv.org/abs/1907.04155), [code](https://github.com/ratschlab/GP-VAE)
 
 * Interpretability
    * SHAP: A Unified Approach to Interpreting Model Predictions [paper](https://arxiv.org/pdf/1705.07874.pdf), [code](https://github.com/slundberg/shap)

* Others:
    * Distilling the Knowledge in a Neural Network [paper](https://arxiv.org/abs/1503.02531), [code](https://github.com/peterliht/knowledge-distillation-pytorch)

   
   


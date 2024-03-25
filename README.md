**Introduction**

CRVAE t-SNE for Unsupervised Feature Learning: Image Classification of Flower 
This project explores the utilization of machine learning (ML) strategies for unsupervised feature learning and classification of flower images. Leveraging the capabilities of a Convolutional ResNet Variational AutoEncoder (CRVAE) combined with t-Distributed Stochastic Neighbour Embedding (t-SNE) clustering, we aim to derive meaningful and separable feature representations of flower datasets.
The dataset contains 2,669 unlabelled images of flowers (and junk images) that fit into one 5 classes in the training set and the test set has 1,000 labelled images, 200 from each category.

**AutoEncoders**

Sources: https://paperswithcode.com/method/autoencoder ; https://arxiv.org/pdf/2003.05991.pdf

An autoencoder is a bottleneck architecture that turns a high-dimensional input into a latent low-dimensional code (encoder), and then performs a reconstruction of the input with this latent code (the decoder). Their main purpose is learning in an unsupervised manner an “informative” representation of the data that can be used for various implications such as clustering.4

**VAE**

Sources: https://www.techtarget.com/searchenterpriseai/definition/variational-autoencoder-VAE

A variational autoencoder (VAE) is a generative AI algorithm that uses deep learning to generate new content, detect anomalies and remove noise.

**ResNet**

Sources: https://par.nsf.gov/servlets/purl/10225365 ; https://github.com/JayPatwardhan/ResNet-PyTorch/tree/master

Efficient modeling of high-dimensional data requires extracting only relevant dimensions through feature learning. The advantage of RAE and C-RAE is that it enables the user to add residual connections for increased network capacity without incurring the cost of degradation for unsupervised feature learning compared to standard AEs.

**t-SNE**

Sources: https://www.datacamp.com/tutorial/introduction-t-sne ; https://www.kaggle.com/code/rohitgr/autoencoders-tsne

t-SNE is an unsupervised non-linear dimensionality reduction technique for data exploration and visualizing high-dimensional data. Non-linear dimensionality reduction means that the algorithm allows us to separate data that cannot be separated by a straight line. The t-SNE algorithm finds the similarity measure between pairs of instances in higher and lower dimensional space. After that, it tries to optimize two similarity measures.

# Supervised Vector-Quantized Autoencoder (S-VQ-VAE)

Learning interpretable representations of data remains a central challenge in deep learning. When training a deep generative model, the observed data are often associated with certain categorical labels, and, in parallel with learning to regenerate data and simulate new data, learning an interpretable representation of each class of data is also a process of acquiring knowledge. Here we develped the **Supervised Vector Quantized Variational AutoEncoder (S-VQ-VAE)**, which combines the power of supervised and unsupervised learning to obtain a unique, interpretable global representation for each class of data. Compared with conventional generative models, our model has three key advantages: first, it is an integrative model that can simultaneously learn a feature representation for individual data point and a global representation for each class of data; second, the learning of global representations with embedding codes is guided by supervised information, which clearly defines the interpretation of each code; and third, the global representations capture crucial characteristics of different classes, which reveal similarity and differences of statistical structures underlying different groups of data.

This reporsitory provides a tutorial of using S-VQ-VAE for learning global representations for each type of digit from the MNIST dataset.

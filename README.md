# Generative AI For Reservoir Characterization: Parameterization and Facies Modeling with GANs and VAEs (SPE paper OTC-36887-MS )



## Summary

Reliable reservoir characterization requires geological models that preserve complex facies structures and connectivity while remaining computationally efficient for uncertainty quantification and iterative model calibration. Conventional geological modeling approaches such as object-based modeling and multiple-point geostatistics are capable of reproducing realistic, discrete, and connected facies architectures, but they lack compact low-dimensional parameterizations and are computationally expensive to condition and update in inverse workflows. In contrast, linear parameterization methods such as principal component analysis (PCA) provide computational efficiency and dimensionality reduction but often fail to preserve sharp facies boundaries and geological realism in channelized systems.
This study develops a deep generative workflow for low-dimensional parameterization and generation of channelized facies models using Generative Adversarial Networks (GANs) and Variational Autoencoders (VAEs). A representative two-dimensional training image is sampled to construct a dataset of facies realizations from which deep generative models learn compact latent representations of geological patterns. The trained generators are then used to rapidly produce multiple unconditional facies realizations.
Model performance is evaluated through quantitative comparison of first- and second-order statistics, including pixel-wise mean, variance, and global facies proportions, together with qualitative assessment of channel geometry and connectivity. Sensitivity analyses investigate the effects of training data volume, image resolution, and latent space dimensionality, with results benchmarked against PCA-based parameterization.
The results show that GAN-based parameterization provides a favorable balance between geological realism, facies discreteness, connectivity preservation, and computational efficiency. GAN-generated realizations reproduce sharp, binary channel patterns and preserve key statistical characteristics of the training data, while maintaining substantially improved connectivity relative to VAE-based models. VAEs produce discrete but fragmented channel structures, whereas PCA preserves large-scale continuity at the expense of excessive smoothing and loss of geological detail. Overall, the proposed workflow demonstrates that GANs offer an effective low-dimensional parameterization for channelized facies systems, making them well suited for rapid ensemble generation in uncertainty quantification and history-matching workflows.


## Workflow
![workflow_and_components](https://user-images.githubusercontent.com/68789630/147446231-558eb35c-81fd-47d1-a4ae-9b7a56bd3c07.jpg)

## Files
- project presentation
- project report
- code for GAN-based model generation
- code for VAE-based model generation
- code for PCA-based model generation






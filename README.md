# Pretrained Models

This repository contains the most relevant models used in the experiments of our paper. 

The 'Poisson_Baseline.pth' and 'Video_only_ZIG.pth` are the used baseline models.

 The `Latent_ZIG_12dim.pth` is a latent model, as described in Figure 2 of the paper, with a latent dimension of $k=12$. Those models were used for most of the experiments. Specifically, this includes Tables 1 and 3 and Figures 3 and 4.

For Table 2, we used different mice, where out-of-distribution stimuli with different spatiotemporal statistics, like pink noise, was available. These mice can be found [here](https://gin.g-node.org/pollytur/sensorium_2023_data). 

For Table 3 and 4, we additionally used a latent model without access to cortical data and with 500 neurons held-out from training for the extrapolation experiment (last paragraph before Discussion). 




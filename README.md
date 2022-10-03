# Biases of Training Recurrent Neural Networks via Backpropagation-through-time

Artificial Recurrent Neural Networks (RNNs) are increasingly used in neuroscience research to explain neurobiological phenomena while considering the architectural and computational constraints of biological networks. Such an approach trains networks using machine learning tools and compares it to the network dynamics observed in the brain. RNNs are usually trained using backpropagation-through-time (BPTT), the analog of the standard backpropagation-of-error algorithm. 

This fitting procedure returns a solution in terms of weights, from which task-relevant features are identified ([Runyan et al. 2017](https://www.nature.com/articles/nature23020)) or the dynamics of latent features are studied ([Mante & Sussillo 2013](https://www.nature.com/articles/nature12742)). Here, it is necessary to know if and under which conditions BPTT biases this solution.

We address this fundamental question by exploring the spectral structure of discrete-time RNNs trained via BPTT on temporal tasks trained to recreate the dynamics of a given teacher model. Specifically, we characterize how faithfully BPTT finds the desired solution for linear and nonlinear filters.

This work was done at the Institute of Neuroinformatics, University of Zurich and ETH Zurich under the supervision of [Prof. Dr. Benjamin F. Grewe](https://scholar.google.de/citations?user=ZA-1rh8AAAAJ&hl=en) and the direct supervision of  [Dr. Pau Vilimelis Aceituno](https://scholar.google.com/citations?user=dahpSB8AAAAJ&hl=en). 

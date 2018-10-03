# Graph-neural-networks


<p align="center"> 
  <img src=gnn.png width="600">
</p>

Image source : https://arxiv.org/abs/1705.07664

I've been using graph neural networks (GNN) mainly for molecular applications because molecular structures can be represented in graph structures. GNN is interesting in that it can effectively model relationships or interactions between objects in a system. There are various applications of GNN such as molecular applications, network analysis, and physics modeling.

I will introduce GNN in this repository: from theoretical backgrounds to implementations using TensorFlow. I hope you enjoy GNN from this moment.

## References (continually updated) :
### Geometric Deep Learning and Surveys on Graph Neural Networks
* Bronstein, Michael M., et al. "Geometric deep learning: going beyond euclidean data." IEEE Signal Processing Magazine 34.4 (2017): 18-42.
* [NIPS 2017] Tutorial - Geometric deep learning on graphs and manifolds, https://nips.cc/Conferences/2017/Schedule?showEvent=8735
* Goyal, Palash, and Emilio Ferrara. "Graph embedding techniques, applications, and performance: A survey." Knowledge-Based Systems 151 (2018): 78-94., https://github.com/palash1992/GEM
* Awesome Graph Embedding And Representation Learning Papers, https://github.com/benedekrozemberczki/awesome-graph-embedding
* Battaglia, Peter W., et al. "Relational inductive biases, deep learning, and graph networks." arXiv preprint arXiv:1806.01261 (2018).

### Graph Convolution Network (GCN)
* Defferrard, Michaël, Xavier Bresson, and Pierre Vandergheynst. "Convolutional neural networks on graphs with fast localized spectral filtering." Advances in Neural Information Processing Systems. 2016.
* Kipf, Thomas N., and Max Welling. "Semi-supervised classification with graph convolutional networks." arXiv preprint arXiv:1609.02907 (2016).
* van den Berg, Rianne, Thomas N. Kipf, and Max Welling. "Graph Convolutional Matrix Completion." stat 1050 (2017): 7.
* Schlichtkrull, Michael, et al. "Modeling relational data with graph convolutional networks." European Semantic Web Conference. Springer, Cham, 2018.
* Levie, Ron, et al. "Cayleynets: Graph convolutional neural networks with complex rational spectral filters." arXiv preprint arXiv:1705.07664 (2017).

### Attention mechanism in GNN
* Velickovic, Petar, et al. "Graph attention networks." arXiv preprint arXiv:1710.10903 (2017).
* GRAM: Graph-based Attention Model for Healthcare Representation Learning
* Lee, John Boaz, et al. "Attention Models in Graphs: A Survey." arXiv preprint arXiv:1807.07984 (2018).

### Message Passing Neural Network (MPNN)
* Li, Yujia, et al. "Gated graph sequence neural networks." arXiv preprint arXiv:1511.05493 (2015).
* Gilmer, J., Schoenholz, S. S., Riley, P. F., Vinyals, O., & Dahl, G. E. (2017). Neural message passing for quantum chemistry. arXiv preprint arXiv:1704.01212.

### Graph Autoencoder and Graph Generative Models
* Kipf, Thomas N., and Max Welling. "Variational graph auto-encoders." arXiv preprint arXiv:1611.07308 (2016).
* Simonovsky, Martin, and Nikos Komodakis. "GraphVAE: Towards Generation of Small Graphs Using Variational Autoencoders." arXiv preprint arXiv:1802.03480 (2018).
* Liu, Qi, et al. "Constrained Graph Variational Autoencoders for Molecule Design." arXiv preprint arXiv:1805.09076 (2018).
* Pan, Shirui, et al. "Adversarially Regularized Graph Autoencoder." arXiv preprint arXiv:1802.04407 (2018).
* Li, Y., Vinyals, O., Dyer, C., Pascanu, R., & Battaglia, P. (2018). Learning deep generative models of graphs. arXiv preprint arXiv:1803.03324.


### Applications of GNN
* Duvenaud, David K., et al. "Convolutional networks on graphs for learning molecular fingerprints." Advances in neural information processing systems. 2015.
* Kearnes, Steven, et al. "Molecular graph convolutions: moving beyond fingerprints." Journal of computer-aided molecular design 30.8 (2016): 595-608.
* Schütt, K. T., Arbabzadah, F., Chmiela, S., Müller, K. R., & Tkatchenko, A. (2017). Quantum-chemical insights from deep tensor neural networks. Nature communications, 8, 13890.
* Wu, Z., Ramsundar, B., Feinberg, E. N., Gomes, J., Geniesse, C., Pappu, A. S., ... & Pande, V. (2018). MoleculeNet: a benchmark for molecular machine learning. Chemical Science, 9(2), 513-530.
* Shang, C., Liu, Q., Chen, K. S., Sun, J., Lu, J., Yi, J., & Bi, J. (2018). Edge Attention-based Multi-Relational Graph Convolutional Networks. arXiv preprint arXiv:1802.04944.
* Feinberg, Evan N., et al. "Spatial Graph Convolutions for Drug Discovery." arXiv preprint arXiv:1803.04465 (2018).
* Jin, Wengong, Regina Barzilay, and Tommi Jaakkola. "Junction Tree Variational Autoencoder for Molecular Graph Generation." arXiv preprint arXiv:1802.04364 (2018).
* Liu, Qi, et al. "Constrained Graph Variational Autoencoders for Molecule Design." arXiv preprint arXiv:1805.09076 (2018).
* De Cao, Nicola, and Thomas Kipf. "MolGAN: An implicit generative model for small molecular graphs." arXiv preprint arXiv:1805.11973 (2018).
* Selvan, Raghavendra, et al. "Extraction of Airways using Graph Neural Networks." arXiv preprint arXiv:1804.04436 (2018).
* Kipf, Thomas, et al. "Neural relational inference for interacting systems." arXiv preprint arXiv:1802.04687 (2018).

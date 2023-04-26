# Application-of-Deep-Learning-on-GED

## Abstract

The term graph similarity search is an important technique in any graph based
applications. This technique can be applied in many scenarios, such as finding
diseases in a bunch of graph based molecules, finding similarities in social graphs,
identifying chemical compounds and its similarities, and many more. In addition to
the abundance of applications that graph similarity search can be used for, there are
plenty of ways in which it can be implemented. Some ways are advantageous for
simple search, but would not work well on heavy workload for the more difficult
tasks. While other techniques might be too computationally extensive when used,
and may require expensive hardware as well as plenty of time for it to run properly.
In this research, the method of SimGNN neural network will be implemented for a
deep learning approach to solve for Graph Edit Distance (GED). GED is one of the
basis and most frequently used methods for any graph similarity search. However,
GED can be very computationally extensive, and become an NP-Hard problem as it
lacks the ability to adapt to different sets of data structures. In this research, the aim
is to solve this by using the deep learning approach in implementing the SimGNN
[9].
The neural network of SimGNN takes a couple of approaches. Firstly, the
entire pair of graphs is mapped into an embedding vector by using a learnable
embedding function. This provides information on the graphs being learned as a
whole. Following this, node comparisons of node pairs are done in each graph level
embedding. For the purpose of this research, the model is implemented on
synthetically generated graph pairs for its simplicity and future adaptability of other
datasets. The performance of the model itself is then measured by using mean
squared error to measure its performance as well as its efficiency in solving for GED.
Upon running the model, it can be seen to be able to achieve a small number of
errors, making it insignificant. This shows that the model is capable of performing
GED on the given dataset with ease. Since the entire research is done by only using
the hardware from Google Colab, it shows that the model itself does not require
intensive computing power in order to achieve these results. This also gives the
opportunity for further research to be done based on SimGNN for future works that
may require a more thorough model for a more complex dataset. An example of this
2 [Project Title]
would be the combination of TagSim with SimGNN, for a type aware graph
similarity deep learning model [9].

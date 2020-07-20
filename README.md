## Network Compression using SVD

Trained a teacher model on MNIST dataset.<br>
Applied SVD on the weight matrices to reduce dimensionality of the weight matrices by trying various D values for decomposition. <br>
Retrained the compressed network using a custom gradient function.<br>
Achieved test accuracy of 96% for student network and test accuracy of 98% for teacher network. <br>
Student network is 5% the size of Teacher network. <br>

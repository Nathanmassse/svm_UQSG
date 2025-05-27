# svm_UQSG
Implementation of a SVM based on variational universal quantum state genrator. 
The project aim to reproduce the results produced by the paper "Variational quantum support vector machine based on Ŵ matrix expansion and variational universal‑quantum‑state generator" by Motohiko Ezawa.
We implement a support vector machine to do binary classification by using a variational quantum linear solver (that we coded).
However, it appears that there were several errors in the paper and the method is not efficient as is requires to use a classical optimisation process each time we use the variational universal quantum-sate genereator.

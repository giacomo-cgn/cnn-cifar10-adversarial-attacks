# CNN for CIFAR10 and adversarial attacks

This project was done for the ISPR course for the MCS course at University of Pisa.

A simple CNN architecture (built with PyTorch) is identified through grid search and is trained to recognize the 10 classes of CIFAR10 dataset. Performance on test set is 69%.

Then, using the CleverHans Python library, adversarial attacks are tried on the CNN. A performance decrease is observed with increasing values of epsilon of the adversarial attack.

All code and considerations are reported in the notebook.


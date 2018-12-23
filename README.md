
22 December 2018

This repo supports the paper "Biological Mechanisms for Learning: A Computational Model of Olfactory Learning in the Manduca sexta Moth, with Applications to Neural Nets", by CB Delahunt, JA Riffell, and JN Kutz, Frontiers in Computational Neuroscience, December 2018.

It will soon contain:
1. The full code used in the "Biological Mechanisms for Learning" experiments. 
2. The datasets of electrode readings from Antennal Lobes of live moths during learning, plus Matlab extraction code for these datasets.

Until then:
A full version of the moth simulation codebase is available now at github/charlesDelahunt/PuttingABugInML.
 
That version, "MothNet", simulates a moth olfactory network as it learns to read MNIST digits. It generates a model of the Manduca sexta moth olfactory network, then runs a time-stepped evolution of SDEs to train the network to read downsampled MNIST digits.

The mechanics of neural architecture generation and SDE evolution in MothNet are almost identical to those of the version that will live here.

If you have questions or comments, please email Charles Delahunt at delahunt@uw.edu.

Thank you!

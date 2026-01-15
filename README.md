# hh_model_interac
# demo for Docs in DS
A simple version of the neuron action potential simulation originally developed by Alan Lloyd Hodgkin and Andrew Fielding Huxley in this [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1392413/).

The equations were developed in 1952 and are were based on experimental evidence generated from using a giant squid axon. This notebook uses the same equations and constants they suggested along with a manually defined current impulse.

Instead of using an ODE solver, just use the Euler method and a for-loop. Hence, simple. Obviously, it won't be as robust or detailed, but it's good enough to show how the equations they thought of can actually produce a similar result to the ones we see in real neurons.

Change any variables you wish to see how it affects the model.

# roughness-inverse-ml
A machine learning (ML)-based framework for the inverse design of the surface milling process

This project presents an inverse design framework for machining parameters using Machine Learning (ML) and Bayesian Optimization (BO). High-fidelity datasets are first generated via forward simulations to model surface topography and extract surface roughness metrics. Six input parameters—including cutting speed, feed rate, number of inserts, insert radius, and installation errors—are varied. A multiplicity analysis addresses the many-to-one mapping issue, avoiding direct inverse model training.

Deep Neural Networks (DNN) and Random Forests (RF) are trained and optimized for single- and multi-output predictions. BO is then used to identify optimal machining and tool parameters for target surface roughness metrics. Case studies demonstrate that the framework reliably provides diverse design solutions with low prediction errors.

# A collection of small extensions to Keras 1.0

Adapted from [wuaalb/keras_extension](https://github.com/wuaalb/keras_extensions)

Extensions

- Restricted Boltzmann Machine (RBM)
- Gaussian-Bernoulli Restricted Boltzmann Machine (GB-RBM)
- Momentum schedule
- Logging helpers (simultaneous logging to console and log file)

Note that some of these extensions are very coupled to Keras' internals which change from time to time. Whenever these extensions break due to changes in Keras, either the extensions need to be updated to reflect the changes, or an older version of Keras should be used. 
**Here the original version is built on Keras 0.3, only minor changes made to make it run with minimal modification under Keras 1.0, nameley the following have been updated so far:**

- [x] RBM models
- [x] rbm_example.py working
- [ ] DBN models
- [ ] dbn_example.py working

# C-SWM in Knet

This is the repo for COMP 550 Deep Learning term project. This work consist of the replication of ICLR 2020 paper:

**Contrastive Learning of Structured World Models.**  
Thomas Kipf, Elise van der Pol, Max Welling.  
http://arxiv.org/abs/1911.12247

and some experiments on the top of it.

C-SWM is a model for learning latent state representations from observations (images) in an environment. Environment transitions are modeled via a graph neural network. Given an observation encoded by the model and action, the network can predict the latent representation of the next state.

This model is trained and tested on 2D Shapes dataset. As the future work, it's representational power is analyzed on Moving MNIST dataset.

Check the [data sheet](https://docs.google.com/spreadsheets/d/1wYI-_FWTBgDlxHX-uPAnNcHAzOcH0QJt4pPUsqMDhUY/edit#gid=0) for additional information about training and testing.

## Usage

To run the tests, generate the datasets via the original repository. Then, use the provided notebooks.

### Reference

```
@article{kipf2019contrastive,
  title={Contrastive Learning of Structured World Models}, 
  author={Kipf, Thomas and van der Pol, Elise and Welling, Max}, 
  journal={arXiv preprint arXiv:1911.12247}, 
  year={2019} 
}
```


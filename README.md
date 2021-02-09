## Graph-based Unsupervised Metric Learning (GUML)
```
Github repository containing a precursor for the paper cited below.
```

The Repository contains:
```
1. GUML_demo.ipynb : Demostrates how to learn a metric using 
   Riemannian optimization with Pymanopt+Autograd
   
2. GUML_demo_PyTorch.ipynb : Demostrates how to learn a metric using
   Riemannian optimization with Pymanopt+PyTorch
   
3. Triplet_net_sGUML_demo.ipynb: Demostrates how to learn a deep metric using 
   Riemannian optimization with Pymanopt+PyTorch, in an end-to-end manner using 
   stochastic optimization. 
   The backbone neural network has a Triplet Network architecture.
   (Inspired by https://github.com/harveyslash/Facial-Similarity-with-Siamese-Networks-in-Pytorch)
   
4. sGUML_CUB_demo.ipynb: Demostrates how to learn a deep metric using 
   Riemannian optimization with Pymanopt+PyTorch, in an end-to-end manner using 
   stochastic optimization. The experiment is performed on the popular CUB dataset,
   which is a benchmark for the Fine-Grained Visual Categorization (FGVC) task
   in deep metric learning. This code is built following https://github.com/gtolias/mom
   and can easily be extended for other benchmark
   datasets like Cars196, SOP etc.
 
5. rdml.yml: Contains the required conda environment to be cloned.
```
## Citation

If you find the code useful, kindly consider citing the following paper that inspired the repo :
```
@article{dutta2020unsupervised,
  title={Unsupervised Deep Metric Learning via Orthogonality Based Probabilistic Loss},
  author={Dutta, Ujjal Kr and Harandi, Mehrtash and Sekhar, Chellu Chandra},
  journal={IEEE Transactions on Artificial Intelligence},
  volume={1},
  number={1},
  pages={74--84},
  year={2020},
  publisher={IEEE}
}
```

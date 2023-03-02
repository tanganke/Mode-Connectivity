# Mode-Connectivity and Model-Merging

This repo is a collection of AWESOME things about recent researches about Mode Connectivity, mainly about the linear connectivity. For the detailed methods side, we include papers which try to rebasin the different learned models. Obviously, model merging is a downstream taks which may benefit from the advances of the model connectivity research. Waited to be researched...

Please feel free to fork.

![](https://img.shields.io/badge/Resources-@CLeaR_Unimelb-red.svg) ![](https://img.shields.io/badge/License-@MIT-green.svg)

## The concept of LMC
- **Linear mode connectivity and the lottery ticket hypothesis.**

  *Jonathan Frankle, Gintare Karolina Dziugaite, Daniel Roy, Michael Carbin* [[ICML20]](http://proceedings.mlr.press/v119/frankle20a/frankle20a.pdf)[[codes]](https://github.com/facebookresearch/open_lth)

## Geometric Properties
- **Loss Surfaces, Mode Connectivity, and Fast Ensembling of DNNs.** [Neurips18]
  
  *Timur Garipov, Pavel Izmailov, Dmitrii Podoprikhin, Dmitry Vetrov, Andrew Gordon Wilson* [[pdf]](https://proceedings.neurips.cc/paper/2018/file/be3087e74e9100d4bc4c6268cdbe8456-Paper.pdf)[[codes]](https://github.com/timgaripov/dnn-mode-connectivity)

- **Essentially No Barriers in Neural Network Energy Landscape.** [icml18]

  *Felix Draxler, Kambis Veschgini, Manfred Salmhofer, Fred A. Hamprecht* [[pdf]](http://proceedings.mlr.press/v80/draxler18a/draxler18a.pdf)[[codes]](https://github.com/fdraxler/PyTorch-AutoNEB)
 
- **Geometry of the Loss Landscape in Overparameterized Neural Networks: Symmetries and Invariances.** [icml21]

  *Berfin Şimşek, François Ged, Arthur Jacot, Francesco Spadaro, Clément Hongler, Wulfram Gerstner, Johanni Brea* [[paper]](https://proceedings.mlr.press/v139/simsek21a/simsek21a.pdf)[[codes]](https://github.com/EPFL-LCN/pub_simsek2021_icml)
  
- (Width, Depth)(Simulated Annealing) **The Role of Permutation Invariance in Linear Mode Connectivity of Neural Networks.** [iclr22]

  *Rahim Entezari, Hanie Sedghi, Olga Saukh, Behnam Neyshabur* [[paper]](https://openreview.net/forum?id=dNigytemkL)[[codes]](https://github.com/rahimentezari/PermutationInvariance)
  
- (Initialisations) Random initialisations performing above chance and how to find them. [[Neurips22 OPT]](https://arxiv.org/pdf/2209.07509.pdf)[[codes]](https://github.com/freedbee/permuted_initialisations)
- (Functional behaviors of end points) On Convexity and Linear Mode Connectivity in Neural Networks. [[neurips22 OPT]](https://openreview.net/pdf?id=TZQ3PKL3fPr)
- Plateau in Monotonic Linear Interpolation -- A "Biased" View of Loss Landscape for Deep Networks. [[iclr23]](https://arxiv.org/abs/2210.01019)
- Analyzing Monotonic Linear Interpolation in Neural Network Loss Landscapes. [[icml21]](http://proceedings.mlr.press/v139/lucas21a/lucas21a.pdf)[[codes]](https://github.com/AtheMathmo/mli-release)

## Methods for rebasin
- 🔥 (Three methods) Git Re-Basin: Merging Models modulo Permutation Symmetries. [[iclr23]](https://openreview.net/forum?id=CQsmMYmlP5T)[[codes]](https://github.com/samuela/git-re-basin)
- Re-basin via implicit Sinkhorn differentiation. [[paper22]](https://arxiv.org/pdf/2212.12042.pdf) 
  - (Ref paper) A Unified Framework for Implicit Sinkhorn Differentiation. [[cvpr22]](https://openaccess.thecvf.com/content/CVPR2022/papers/Eisenberger_A_Unified_Framework_for_Implicit_Sinkhorn_Differentiation_CVPR_2022_paper.pdf)[[codes]](https://github.com/marvin-eisenberger/implicit-sinkhorn)
- Linear Mode Connectivity of Deep Neural Networks via Permutation Invariance and Renormalization. [[iclr23]](https://openreview.net/forum?id=gU5sJ6ZggcX)[[codes]](https://github.com/KellerJordan/REPAIR)

## Model merging
- [Averaging merge] **Model soups: averaging weights of multiple fine-tuned models improves accuracy without increasing inference time.** [icml22]

  *Mitchell Wortsman, Gabriel Ilharco, Samir Yitzhak Gadre, Rebecca Roelofs, Raphael Gontijo-Lopes, Ari S. Morcos, Hongseok Namkoong, Ali Farhadi, Yair Carmon, Simon Kornblith, Ludwig Schmidt* [[paper]](https://proceedings.mlr.press/v162/wortsman22a/wortsman22a.pdf)[[codes]](https://github.com/mlfoundations/model-soups)

- **Loss Surface Simplexes for Mode Connecting Volumes and Fast Ensembling.** [icml21]
  
  *Gregory W. Benton, Wesley J. Maddox, Sanae Lotfi, Andrew Gordon Wilson* [[paper]](http://proceedings.mlr.press/v139/benton21a/benton21a.pdf)[[codes]](https://github.com/g-benton/loss-surface-simplexes)
 
- :thumbsup: **Learning Neural Network Subspaces.** [icml21]

  *Mitchell Wortsman, Maxwell Horton, Carlos Guestrin, Ali Farhadi, Mohammad Rastegari* [[paper]](http://proceedings.mlr.press/v139/wortsman21a/wortsman21a.pdf)[[codes]](https://github.com/apple/learning-subspaces)

- [Fisher merge] Merging Models with Fisher-Weighted Averaging. [[neurips22]](https://openreview.net/pdf?id=LSKlp_aceOC)[[codes]](https://github.com/mmatena/model_merging)
- [Regression Mean merge] Dataless Knowledge Fusion by Merging Weights of Language Models. [[iclr2023]](https://openreview.net/forum?id=FCnohuR6AnM)
- Wasserstein Barycenter-based Model Fusion and Linear Mode Connectivity of Neural Networks. [[paper23]](https://openreview.net/pdf?id=qHbyR1MKG8K)[[codes]](https://openreview.net/forum?id=qHbyR1MKG8K)

## Pretrained model connectivity
- What is being transferred in transfer learning? [[neurips20]](https://proceedings.neurips.cc/paper/2020/file/0607f4c705595b911a4f3e7a127b44e0-Paper.pdf)[[codes]](https://github.com/google-research/understanding-transfer-learning)
- Exploring Mode Connectivity for Pre-trained Language Models. [[EMNLP22]](https://arxiv.org/pdf/2210.14102.pdf)[[codes]](https://github.com/thunlp/Mode-Connectivity-PLM)
- Knowledge is a Region in Weight Space for Fine-tuned Language Models. [[paper23]](https://arxiv.org/pdf/2302.04863.pdf)

## Equivariant Network Design
- 👀 Equivariant Architectures for Learning in Deep Weight Spaces. [[paper23]](https://arxiv.org/pdf/2301.12780.pdf)[[codes]](https://github.com/AvivNavon/DWSNets)
- 👀 Permutation Equivariant Neural Functionals. [[paper23]](https://arxiv.org/pdf/2302.14040.pdf)

## Related paper
- Linear Connectivity Reveals Generalization Strategies. [[iclr23]](https://arxiv.org/pdf/2205.12411.pdf)[[codes]](https://github.com/anonwhymoos/connectivity)
- Model Ratatouille: Recycling Diverse Models for Out-of-Distribution Generalization. [[paper23]](https://arxiv.org/pdf/2212.10445.pdf)[[codes]](https://github.com/facebookresearch/ModelRatatouille)

## Applications
- (FL) Connecting Low-Loss Subspace for Personalized Federated Learning. [[kdd22]](https://dl.acm.org/doi/pdf/10.1145/3534678.3539254)[[codes]](https://github.com/vaseline555/SuPerFed)
- Linear Mode Connectivity in Multitask and Continual Learning. [[iclr21]](https://openreview.net/forum?id=Fmg_fQYUejf)[[codes]](https://github.com/imirzadeh/MC-SGD)
- All Roads Lead to Rome? On Invariance of BERT Representations. [[TACL23]](http://zhijing-jin.com/files/papers/BERTSimilarity_TACL2023.pdf)
- :thumbsup: (Sparsity) Unmasking the Lottery Ticket Hypothesis: What's Encoded in a Winning Ticket's Mask? [[iclr23]](https://openreview.net/pdf?id=xSsW2Am-ukZ)

## Tools
- Loss landscapes. [[pypi]](https://pypi.org/project/loss-landscapes)

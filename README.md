# Mode-Connectivity and Model-Merging

This repo is a collection of AWESOME things about recent researches about Mode Connectivity, mainly about the linear connectivity. For the detailed methods side, we include papers which try to rebasin the different learned models. Obviously, model merging is a downstream taks which may benefit from the advances of the model connectivity research. Waited to be researched...

Please feel free to fork.

![](https://img.shields.io/badge/Resources-@CLeaR_Unimelb-red.svg) ![](https://img.shields.io/badge/License-@MIT-green.svg)

## The concept of LMC
- Linear mode connectivity and the lottery ticket hypothesis. [[icml20]](http://proceedings.mlr.press/v119/frankle20a/frankle20a.pdf)

## Findings
- Geometry of the Loss Landscape in Overparameterized Neural Networks: Symmetries and Invariances. [[icml21]](https://proceedings.mlr.press/v139/simsek21a/simsek21a.pdf)
- (Width, Depth)(Simulated Annealing) The Role of Permutation Invariance in Linear Mode Connectivity of Neural Networks. [[iclr22]](https://openreview.net/forum?id=dNigytemkL)[[codes]](https://github.com/rahimentezari/PermutationInvariance)
- (Initialisations) Random initialisations performing above chance and how to find them. [[Neurips22 OPT]](https://arxiv.org/pdf/2209.07509.pdf)[[codes]](https://github.com/freedbee/permuted_initialisations)
- (Functional behaviors of end points) On Convexity and Linear Mode Connectivity in Neural Networks. [[neurips22 OPT]](https://openreview.net/pdf?id=TZQ3PKL3fPr)
- Plateau in Monotonic Linear Interpolation -- A "Biased" View of Loss Landscape for Deep Networks. [[iclr23]](https://arxiv.org/abs/2210.01019)

## Methods for rebasin
- (Three methods) Git Re-Basin: Merging Models modulo Permutation Symmetries. [[iclr23]](https://openreview.net/forum?id=CQsmMYmlP5T)[[codes]](https://github.com/samuela/git-re-basin)
- Re-basin via implicit Sinkhorn differentiation. [[paper22]](https://arxiv.org/pdf/2212.12042.pdf) 
  - (Ref paper) A Unified Framework for Implicit Sinkhorn Differentiation. [[cvpr22]](https://openaccess.thecvf.com/content/CVPR2022/papers/Eisenberger_A_Unified_Framework_for_Implicit_Sinkhorn_Differentiation_CVPR_2022_paper.pdf)[[codes]](https://github.com/marvin-eisenberger/implicit-sinkhorn)
- Linear Mode Connectivity of Deep Neural Networks via Permutation Invariance and Renormalization. [[iclr23]](https://openreview.net/forum?id=gU5sJ6ZggcX)[[codes]](https://github.com/KellerJordan/REPAIR)

## Model merging
- [Averaging merge] Model soups: averaging weights of multiple fine-tuned models improves accuracy without increasing inference time. [[icml22]](https://proceedings.mlr.press/v162/wortsman22a/wortsman22a.pdf)[[codes]](https://github.com/mlfoundations/model-soups)
- [Fisher merge] Merging Models with Fisher-Weighted Averaging. [[neurips22]](https://openreview.net/pdf?id=LSKlp_aceOC)[[codes]](https://github.com/mmatena/model_merging)
- [Regression Mean merge] Dataless Knowledge Fusion by Merging Weights of Language Models. [[iclr2023]](https://openreview.net/forum?id=FCnohuR6AnM)
- Wasserstein Barycenter-based Model Fusion and Linear Mode Connectivity of Neural Networks. [[paper23]](https://openreview.net/pdf?id=qHbyR1MKG8K)[[codes]](https://openreview.net/forum?id=qHbyR1MKG8K)

## Pretrained model connectivity
- What is being transferred in transfer learning? [[neurips20]](https://proceedings.neurips.cc/paper/2020/file/0607f4c705595b911a4f3e7a127b44e0-Paper.pdf)[[codes]](https://github.com/google-research/understanding-transfer-learning)
- Exploring Mode Connectivity for Pre-trained Language Models. [[EMNLP22]](https://arxiv.org/pdf/2210.14102.pdf)[[codes]](https://github.com/thunlp/Mode-Connectivity-PLM)
- Knowledge is a Region in Weight Space for Fine-tuned Language Models. [[paper23]](https://arxiv.org/pdf/2302.04863.pdf)

## Related paper
- Linear Connectivity Reveals Generalization Strategies. [[iclr23]](https://arxiv.org/pdf/2205.12411.pdf)[[codes]](https://github.com/anonwhymoos/connectivity)
- Model Ratatouille: Recycling Diverse Models for Out-of-Distribution Generalization. [[paper23]](https://arxiv.org/pdf/2212.10445.pdf)[[codes]](https://github.com/facebookresearch/ModelRatatouille)

## Applications
- (FL) Connecting Low-Loss Subspace for Personalized Federated Learning. [[kdd22]](https://dl.acm.org/doi/pdf/10.1145/3534678.3539254)[[codes]](https://github.com/vaseline555/SuPerFed)
- Linear Mode Connectivity in Multitask and Continual Learning. [[iclr21]](https://openreview.net/forum?id=Fmg_fQYUejf)[[codes]](https://github.com/imirzadeh/MC-SGD)

## Tools
- Loss landscapes. [[pypi]](https://pypi.org/project/loss-landscapes)

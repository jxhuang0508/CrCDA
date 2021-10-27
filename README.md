# Contextual-Relation Consistent Domain Adaptation
Jiaxing Huang, Shijian Lu, Dayan Guan, Xiaobing Zhang. "Contextual-Relation Consistent Domain Adaptation for Semantic Segmentation", ECCV 2020
## Updates
- *07/2020*: Accepted to ECCV 2020.
- *10/2021*: This technique was done with the company (patent number: 10202003057S), so no plan to release code. 

## Paper
![](./0001.jpg)

## Abstract
Recent advances in unsupervised domain adaptation for semantic segmentation have shown great potentials to relieve the demand of expensive per-pixel annotations. However, most existing works address the domain discrepancy by aligning the data distributions of two domains at a global image level whereas the local consistencies are largely neglected. This paper presents an innovative local contextual-relation consistent domain adaptation (CrCDA) technique that aims to achieve local-level consistencies during the global-level alignment. The idea is to take a closer look at region-wise feature representations and align them for local-level consistencies. Specifically, CrCDA learns and enforces the prototypical local contextual-relations explicitly in the feature space of a labelled source domain while transferring them to an unlabelled target domain via backpropagation-based adversarial learning. An adaptive entropy max-min adversarial learning scheme is designed to optimally align these hundreds of local contextual-relations across domain without requiring discriminator or extra computation overhead. The proposed CrCDA has been evaluated extensively over two challenging domain adaptive segmentation tasks (e.g., GTA5 to Cityscapes and SYNTHIA to Cityscapes), and experiments demonstrate its superior segmentation performance as compared with state-of-the-art methods.

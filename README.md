# awesome-vertical-federated-learning
A curated list of advancements in Vertical Federated Learning (VFL), frameworks and libraries.

## Table of Contents
<!-- MarkdownTOC depth=4 -->
- [Publications in Top-tier Conferences](#top-tier-conf)
  - [VFL benchmarks (benchmarks with VFL tasks)](#vfl-bench)
  - [VFL algorithms](#vfl-algo)
  - [VFL privacy](#vfl-privacy)
  - [VFL feature importance estimation](#vfl-feature-imp)
  - [VFL metrics](#vfl-metric)
- [VFL Datasets](#vfl-datasets)
- [Frameworks and Libraries with VFL support](#frameworks-and-libraries)
  - [Flower](#flower-framework)
  - [FATE](#fate)
  - 

<a name="top-tier-conf"></a>
## Publications in Top-tier Conferences
<a name="vfl-bench"></a>
### VFL benchmarks (benchmarks with VFL tasks)
| Title | Year | Conference | Links | Description |
|---|---|---|---|---|
| VertiBench: Advancing Feature Distribution Diversity in Vertical Federated Learning Benchmarks | 2024 | ICLR | --- | --- |
| VFLAIR: A Research Library and Benchmark for Vertical Federated Learning | 2024 | ICLR | [link to repository](https://github.com/flair-thu/vflair) | --- |
| The OARF Benchmark Suite: Characterization and Implications for Federated Learning Systems | 2022 | | [link to repository](https://github.com/Xtra-Computing/OARF?tab=readme-ov-file#the-oarf-benchmark-suite-characterization-and-implications-for-federated-learning-systems) | --- |

<a name="vfl-algo"></a>
### VFL algorithms
| Algorithm | Model | Category | Title | Code | Year | Conference / Journal |
|---|---|---|---|---|---|---|
| AL | Any | Ensemble-based | [Assisted learning: A framework for multiorganization learning](https://proceedings.neurips.cc/paper/2020/file/a7b23e6eefbe6cf04b8e62a6f0915550-Paper.pdf) | - | 2020 | Neurips |
| GAL | Any | Ensemble-based | [Gal: Gradient assisted learning for decentralized multi-organization collaborations](https://proceedings.neurips.cc/paper_files/paper/2022/file/4d6938f94ab47d32128c239a4bfedae0-Paper-Conference.pdf) | [Code](https://github.com/diaoenmao/GAL-Gradient-Assisted-Learning-for-Decentralized-Multi-Organization-Collaborations) | 2022 | Neurips |
| SplitNN | NN | Split-based | [Split learning for health: Distributed deep learning without sharing raw patient data](https://arxiv.org/abs/1812.00564) | - | 2018 | Arxiv |
| C-VFL | NN | Split-based | [Compressed-VFL: Communication-efficient learning with vertically partitioned data](https://proceedings.mlr.press/v162/castiglia22a/castiglia22a.pdf) | [Code](https://github.com/timcast725/C-VFL) | 2022 | ICML |
| BlindFL | NN | Split-based | [Vertical federated machine learning without peeking into your data](https://dl.acm.org/doi/abs/10.1145/3514221.3526127) | - | 2022 | SIGMOD |
| FedOnce | NN | Split-based |  [Practical vertical federated learning with unsupervised representation learning](https://www.computer.org/csdl/journal/bd/5555/01/09789268/1DZ7SAQydO0) | [Code](https://github.com/JerryLife/FedOnce) | 2022 | IEEE Transactions on Big Data |
| SecureBoost | GBDT | Split-based |  [Secureboost: A lossless federated learning framework](https://www.computer.org/csdl/magazine/ex/2021/06/09440789/1tTpiuHh3zi) | - | 2021 | IEEE Intelligent Systems |
| Pivot | GBDT | Split-based |  [Privacy preserving vertical federated learning for tree-based models](https://dl.acm.org/doi/10.14778/3407790.3407811) | [Code](https://github.com/nusdbsystem/pivot) | 2020 | VLDB |
| FedTree | GBDT | Split-based |  [Fedtree: A federated learning system for trees](https://proceedings.mlsys.org/paper_files/paper/2023/hash/3430e7055936cb8e26451ed49fce84a6-Abstract-mlsys2023.html) | [Code](https://github.com/Xtra-Computing/FedTree) | 2023 | MLSyS |



<a name="vfl-privacy"></a>
### VFL privacy
| Title | Year | Conference / Journal | Description |
|---|---|---|---|

<a name="vfl-feature-imp"></a>
### VFL metrics
| Title | Year | Conference / Journal | Description |
|---|---|---|---|
| Fair and Efficient Contribution Valuation for Vertical Federated Learning | 2024 | ICLR | Clients' contribution valuation metric - vertical federated Shapley value (VerFedSV) |

<a name="vfl-metric"></a>
### VFL metrics
| Title | Year | Conference / Journal | Description |
|---|---|---|---|
| Fair and Efficient Contribution Valuation for Vertical Federated Learning | 2024 | ICLR | Clients' contribution valuation metric - vertical federated Shapley value (VerFedSV) |

<a name="vfl-datasets"></a>
## VFL Datasets
| Type | Dataset | Modality | Link | Paper |
|---|---|---|---| --- |
|  | NUS-WIDE | Image | - | - |
|  | FedAds | | [Link](https://github.com/alibaba/Elastic-Federated-Learning-Solution/blob/FedAds/docs/efls-dataset/dataset.md) | FedAds: A Benchmark for Privacy-Preserving CVR Estimation with Vertical Federated Learning (SIGIR'23) |



<a name="frameworks-and-libraries"></a>
## Frameworks and Libraries with VFL support

<a name="flower-framework"></a>
#### Flower
* Flower description

<a name="fate"></a>
#### FATE
* FATE description

# Awesome-Mamba-360
The Mamba-360 framework is a collection of State Space Models in various Domains.

## Mamba360 Daily Discoveries: Daily Rhythms of State Space Model Discoveries

## Contents
- [Basic Of SSM](#basic-of-ssm)
- [Survey Paper](#survey-paper)
- [Core SSM](#core-ssm)
- [Applications of SSMs](#application-of-ssms)
  - [Vision Domain](#vision-domain)
  - [Langauge Domain](#Language-domain)
  - [Time Series Domain](#Time-series-domain)
  - [Video Domain](#video-domain)
  - [Audio and Speech Domain](#audio-speech-domain)
  - [Tabular Domain](#Tabular-domain)
  - [Reinforcement Learning](#reinforcement-learning)
  - [Graph Learning](#graph-learning)
  - [Multi-Modal](#multi-modal)
  - [Mixture of Experts](#moe)
  - [Point Cloud](#point-cloud)

## Basic of SSM
|       |  |  | 
| :-------- | :---- | :-------- |
|[New-Generation Network Architectures]|<img width="361" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/694d84aa-4f9c-445d-a918-5a2495603360">| |
|[Basic State Space Model ]|<img width="361" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/925c7605-2a05-444d-be2d-d2333f5f7b3f">| |
|[Mamba Structure of Selective SSM]|<img width="361" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/cf754e60-f674-4957-acbe-5dfab5e9cc42">| |
|[Mamba Structure of Selective SSM Algo]|<img width="361" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/dbafec5e-2201-4394-a42a-a25b8512162b">| |
|Mamba-360: Survey of State Space Models as Transformer Alternative| <img width="361" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/6d2ec8e1-c499-4ec1-bcd1-afb321070f82">||

## Survey Paper

| Publication      | Paper | Github | 
| :-------- | :---- | :-------- |
| Arxiv 24.04.15|[State Space Model for New-Generation Network Alternative to Transformers: A Survey](https://arxiv.org/pdf/2404.09516) | [Github](https://github.com/Event-AHU/Mamba_State_Space_Model_Paper_List) |
| Arxiv 24.04.24|[A Survey on Visual Mamba](https://arxiv.org/pdf/2404.15956v2)  | [Github]| 
| Arxiv 24.04.24|[Mamba-360: Survey of State Space Models as Transformer Alternative for Long Sequence Modelling: Methods, Applications, and Challenges](https://arxiv.org/pdf/2404.16112)| [Github](https://github.com/badripatro/mamba360) | 
| Arxiv 24.04.29|[A Survey on Vision Mamba: Models, Applications and Challenges](https://arxiv.org/abs/2404.18861)| [Github](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models) | 




## Core SSM
| Publication           | Paper | Figure | Github |
| :--------------------- | :---- | :------ | :----- |
| Arxiv 20.08.17 | [HiPPO: Recurrent Memory with Optimal Polynomial Projections](https://arxiv.org/abs/2008.07669)|<img width="684" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/c27e1b4a-1c3d-4a7b-8dee-252f745d9e4e"> |[Github](https://github.com/HazyResearch/hippo-code)|
| Arxiv 21.10.31 | [S4: Efficiently Modeling Long Sequences with Structured State Spaces](https://arxiv.org/abs/2111.00396v3) | <img width="806" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/64ee75ce-f186-4bff-836f-56403d14fcb9">  | [Github](https://github.com/state-spaces/s4) |
| Arxiv 22.12.28 | [H3: Hungry Hungry Hippos: Toward Language Modeling with State Space Models](https://arxiv.org/abs/2212.14052)| <img width="712" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/23facffa-6f9f-48fd-87ed-d9137e81e8b5"> |  [Github](https://github.com/HazyResearch/H3) |
| Arxiv 24.01.31 | [LOCOST: State-Space Models for Long Document Abstractive Summarization](https://arxiv.org/abs/2401.17919)| <img width="710" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/2d1e35c7-4b57-4083-afe5-dde1997c0493"> <img width="710" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/1fd57c06-1f59-4a1e-a003-d52d6ab47c8f"> |  [Github](https://github.com/flbbb/locost-summarization) |
| Arxiv 23.09.23 | [S4++: Elevating Long Sequence Modeling with State Memory Reply](https://openreview.net/pdf?id=bdnw4qjfH9) | <img width="622" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/50486393-240a-4c9d-ad9f-41d50233dd5d"> | - |
| Arxiv 23.09.23 | [Hieros: Hierarchical Imagination on Structured State Space Sequence World Models](https://openreview.net/forum?id=5j6wtOO6Fk) | <img width="713" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/d5261639-4aa9-40b7-bc56-91dfece97811"> |  [Github](https://github.com/snagnar/hieros) |
| Arxiv 23.07.17 | [Retentive Network: A Successor to Transformer for Large Language Models](https://arxiv.org/abs/2307.08621)| <img width="712" alt="image" src="!https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/f06e5472-648b-47df-a64a-7c2115b0bfb5"> |  [Github](https://github.com/microsoft/unilm/tree/master/retnet) |
| Arxiv 23.10.30 | [Convolutional State Space Models for Long-Range Spatiotemporal Modeling](https://arxiv.org/abs/2310.19694)| <img width="710" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/8d42bfcf-2c7d-479c-a375-57860693218f">  <img width="710" alt="image" src="[https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/8d42bfcf-2c7d-479c-a375-57860693218f](https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/de381aac-55e6-4275-b980-4a53b97040aa)">|  [Github](https://github.com/NVlabs/ConvSSM) |
| Arxiv 23.10.28 | [Laughing Hyena Distillery: Extracting Compact Recurrences From Convolutions](https://arxiv.org/abs/2310.18780) | <img width="719" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/efbb213f-729d-4dd8-be33-6f5442714e6f"> | [Github](https://github.com/togethercomputer/stripedhyena) |
| Arxiv 23.07.23 | [LRU:Resurrecting Recurrent Neural Networks for Long Sequences](https://proceedings.mlr.press/v202/orvieto23a/orvieto23a.pdf) | <img width="622" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/f8a5c484-07fd-4c6b-8810-d824682206e1"> | - |
| Arxiv 23.02.21 | [HH: Hyena Hierarchy: Towards Larger Convolutional Language Models](https://arxiv.org/abs/2302.10866) | <img width="713" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/6f24d965-ff3b-4eca-bbe0-65120686f140"> |  [Github](https://github.com/hazyresearch/safari) |




## Applications of SSMs

### Vision Domain

| Publication           | Paper | Figure | Github |
| :--------------------- | :---- | :------ | :----- |
| Arxiv 24.01.17 | [Vision Mamba: Efficient Visual Representation Learning with Bidirectional State Space Model](https://arxiv.org/abs/2401.09417)|<img width="684" alt="vim" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/15d0033c-daf5-4409-bf0a-b1b2daf27103">|[Github](https://github.com/hustvl/Vim)|
| Arxiv 24.01.18 | [VMamba: Visual State Space Model](https://arxiv.org/abs/2401.10166) |<img width="806" alt="vmamba" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/354bd8ba-b1c6-45fc-8c54-04409a900ac9"><img width="833" alt="vmamba_1" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/d66d5623-b1f6-4208-83c0-e3c4a86e2e15">| [Github](https://github.com/MzeroMiko/VMamba) |
| Arxiv 24.02.08 | [Mamba-ND: Selective State Space Modeling for Multi-Dimensional Data](https://arxiv.org/pdf/2402.05892)| <img width="712" alt="mamba_nd" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/61592509-c4c3-4894-a3fc-e34eb1cf844f"> ![mamba_nd_1](https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/37d112db-7563-46bf-8513-7f014a197f50) |  [Github](https://github.com/jacklishufan/Mamba-ND) |
| Arxiv 24.03.14 | [LocalMamba: Visual State Space Model with Windowed Selective Scan](https://arxiv.org/pdf/2403.09338)| <img width="710" alt="localmamba" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/72267f14-64b5-45de-84e4-71950682b68e"> |  [Github](https://github.com/hunto/LocalMamba) |
| Arxiv 24.03.15 | [EfficientVMamba: Atrous Selective Scan for Light Weight Visual Mamba](https://arxiv.org/pdf/https://arxiv.org/pdf/2403.09977) | <img width="719" alt="efficientmamba" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/1421195a-e233-4e70-b7f4-fdf57319bbeb"> | [Github](https://github.com/TerryPei/EfficientVMamba) |
| Arxiv 24.03.22 | [SiMBA: Simplified Mamba-based Architecture for Vision and Multivariate Time series](https://arxiv.org/pdf/2403.15360) | <img width="622" alt="simba" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/79d26806-8d9d-4a16-bacf-2fc1745473af"> | [Github](https://github.com/badripatro/Simba) |
| Arxiv 24.03.26 | [PlainMamba: Improving Non-Hierarchical Mamba in Visual Recognition](https://arxiv.org/pdf/2403.17695) | <img width="713" alt="plainmamba" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/d9b9fa28-a398-4bbe-9097-e848acb51f38"> |  [Github](https://github.com/ChenhongyiYang/PlainMamba) |






### Time Series

| Publication           | Paper | Figure | Github |
| :--------------------- | :---- | :------ | :----- |
| Arxiv 24.03.22 | [SiMBA: Simplified Mamba-based Architecture for Vision and Multivariate Time series](https://arxiv.org/pdf/2403.15360) | <img width="622" alt="simba" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/79d26806-8d9d-4a16-bacf-2fc1745473af"> | [Github](https://github.com/badripatro/Simba) |
| Arxiv 24.03.17 | [S-mamba: Is Mamba Effective for Time Series Forecasting?](https://arxiv.org/pdf/2403.11144v2) | <img width="806" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/cc1509f6-7d04-42fc-837f-ef76b41a7266">| [Github](https://github.com/wzhwzhwzh0921/S-D-Mamba) |
| Arxiv 24.04.14 | [TimeMachine: A Time Series is Worth 4 Mambas for Long-term Forecasting](https://arxiv.org/abs/2403.09898v1)| <img width="712" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/d22c4cfb-cea3-406b-a4d1-91037a33e7be"> |  [Github](https://github.com/Atik-Ahamed/TimeMachine) |
| Arxiv 24.02.29 | [MambaStock: Selective state space model for stock prediction](https://arxiv.org/abs/2402.18959v1)| <img width="710" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/929909a9-5b57-42c0-b003-2e4d68f25dc7"> |  [Github](https://github.com/zshicode/MambaStock) |
| Arxiv 24.04.24 | [Bi-Mamba4TS: Bidirectional Mamba for Time Series Forecasting](https://arxiv.org/abs/2404.15772) | <img width="719" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/d000c666-e86e-41b5-a6fd-c955e6e842df"> | - |


### Graph Domain

| Publication           | Paper | Figure | Github |
| :--------------------- | :---- | :------ | :----- |
| Arxiv 24.03.19 | [STG-Mamba: Spatial-Temporal Graph Learning via Selective State Space Model](https://arxiv.org/abs/2403.12418v2)|<img width="684" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/0c9ee8fa-f827-4154-b2b2-cf0bc75a8a2f"> |-|
| Arxiv 24.02.13 | [Graph Mamba: Towards Learning on Graphs with State Space Models ](https://arxiv.org/abs/2402.08678v2) | <img width="806" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/02f58b4f-3fdb-489a-a025-5a5fb4744804">| [Github](https://github.com/GraphMamba/GMN) |
| Arxiv 24.02.01 | [Graph-Mamba: Towards long-range graph sequence modeling with selective state spaces](https://arxiv.org/abs/2402.00789v1)| <img width="712" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/165bc7e9-f605-4906-9743-b47822423123"> |  [Github](https://github.com/bowang-lab/Graph-Mamba) |
| Arxiv 23.12.03 | [Recurrent Distance Filtering for Graph Representation Learning](https://arxiv.org/abs/2312.01538)| <img width="710" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/12168900-c47b-4e8f-807c-373505ede11a"> |  - |
| Arxiv 22.11.21 | [Modeling multivariate biosignals with graph neural networks and structured state space models](https://arxiv.org/abs/2211.11176) | <img width="719" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/49657219-2569-485b-a131-783e06e93295"> | [Github](https://github.com/tsy935/graphs4mer) |




## Tabular Domain

| Publication           | Paper | Figure | Github |
| :--------------------- | :---- | :------ | :----- |
| Arxiv 24.01.16 | [MambaTab: A Simple Yet Effective Approach for Handling Tabular Data](https://arxiv.org/abs/2401.08867v1)|<img width="684" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/aad3e1ec-eac3-4874-89ff-dd7060b6be19"> |[Github](https://github.com/hustvl/Vim)|



### Video Domain

| Publication           | Paper | Figure | Github |
| :--------------------- | :---- | :------ | :----- |
| Arxiv 24.01.25| [Vivim: a Video Vision Mamba for Medical Video Object Segmentation](https://arxiv.org/pdf/2401.14168) | <img width="596" alt="vivim" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/1a67c8b9-ee42-419b-8429-2c76927affa9">|  [Github](https://github.com/scott-yjyang/Vivim) | 
| Arxiv 24.03.11| [VideoMamba: State Space Model for Efficient Video Understanding](https://arxiv.org/pdf/2403.06977)| <img width="728" alt="videomamba" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/12233741-88b6-4f85-abf4-98c1b285ec1a">|  [Github](https://github.com/OpenGVLab/VideoMamba) | 
| Arxiv 24.03.14| [Video Mamba Suite: State Space Model as a Versatile Alternative for Video Understanding](https://arxiv.org/pdf/2403.09626)| <img width="704" alt="video-mamba" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/84f1f28f-0084-4c1e-98a6-6575c70d3e33">| [Github](https://github.com/OpenGVLab/video-mamba-suite) | 
| Arxiv 24.04.09| [RhythmMamba: Fast Remote Physiological Measurement with Arbitrary Length Videos](https://arxiv.org/pdf/2404.06483) | <img width="881" alt="rythymamba" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/ae4f2cc3-1723-40d1-a75b-3089dd6bc5b5">|  [Github](https://github.com/zizhengguo/RhythmMamba) | 
| Arxiv 24.04.11| [Simba: Mamba augmented U-ShiftGCN for Skeletal Action Recognition in Videos](https://arxiv.org/pdf/2404.07645) | <img width="697" alt="simba_new" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/61462792-7183-42cb-91ef-7fe80bb02e23"> |  | 
| Arxiv 24.04.01| [SpikeMba: Multi-Modal Spiking Saliency Mamba for Temporal Video Grounding](https://arxiv.org/abs/2404.01174v1) | <img width="697" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/d9c13efa-a3a9-4ca8-aadc-d97b62d46187" |  [Github](https://github.com/zizhengguo/RhythmMamba) | 
| Arxiv 24.03.12| [SSM Meets Video Diffusion Models: Efficient Video Generation with Structured State Spaces](https://arxiv.org/abs/2403.07711v3) | <img width="697" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/33637069-10b5-4d7a-bc0a-6d1ee7df0cde"> | [Github](https://github.com/shim0114/SSM-Meets-Video-Diffusion-Models) | 


### Speech Domain

| Publication           | Paper | Figure | Github |
| :--------------------- | :---- | :------ | :----- |
| Arxiv 24.04.02| [SPMamba: State-space model is all you need in speech separation](https://arxiv.org/abs/2404.02063) | <img width="596" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/c900bfb8-ce9f-4605-8679-5cd936f984e7"> |  [Github](https://github.com/JusperLee/SPMamba) | 
| Arxiv 24.03.27| [Dual-path Mamba: Short and Long-term Bidirectional Selective Structured State Space Models for Speech Separation](https://arxiv.org/abs/2403.18257v1)| <img width="704" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/68a2f9f8-ba85-46e7-89dc-7165e069dbe9"> | | 



### Activity Recognition
| Publication           | Paper | Figure | Github |
| :--------------------- | :---- | :------ | :----- |
| Arxiv 24.03.29| [HARMamba: Efficient Wearable Sensor Human Activity Recognition Based on Bidirectional Selective SSM](https://arxiv.org/abs/2403.20183v1) | <img width="596" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/c114e734-1633-4b89-b6f6-fc7e3b679d8c"> |  [Github](https://github.com/scott-yjyang/Vivim) | 
| Arxiv 24.03.25| [VMRNN: Integrating Vision Mamba and LSTM for Efficient and Accurate Spatiotemporal Forecasting](https://arxiv.org/abs/2403.16536)| <img width="704" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/30331407-b2c3-4676-b07b-aa6e5a86c9e3"> |[Github](https://github.com/yyyujintang/VMRNN-PyTorch) | 


### Natural Language Processing
| Publication           | Paper | Figure | Github |
| :--------------------- | :---- | :------ | :----- |
| Arxiv 24.03.27| [RankMamba Benchmarking Mamba's Document Ranking Performance in the Era of Transformers](https://arxiv.org/abs/2403.18276v1) | <img width="596" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/9374245d-597f-47d1-b1a6-220f1734b86e"> |  [Github](https://github.com/zhichaoxu-shufe/RankMamba) | 
| Arxiv 24.02.26| [Densemamba: State space models with dense hidden connection for efficient large language models](https://arxiv.org/abs/2403.00818v2)| <img width="704" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/b542446d-09c4-4be6-939c-d2285889d6db"> |  [Github] (https://github.com/WailordHe/DenseSSM) | 
| Arxiv 24.02.05| [Is Mamba Capable of In-Context Learning?](https://arxiv.org/abs/2402.03170v1)| <img width="704" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/70fb7829-d28e-4bbc-b326-fcb167dad979"> |  [Github] (https://github.com/yyyujintang/VMRNN-PyTorch) | 



### Reinforcement Learning 
| Publication           | Paper | Figure | Github |
| :--------------------- | :---- | :------ | :----- |
| Arxiv 24.03.29| [Decision Mamba: Reinforcement Learning via Sequence Modeling with Selective State Spaces](https://arxiv.org/abs/2403.19925v1) | <img width="596" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/ed1c6ba2-1c56-4ba5-9390-68a3662c7091"> |  [Github](https://github.com/Toshihiro-Ota/decision-mamba) | 



### Multi-Modal

| Publication      | Paper | Figure    |  Github         | 
| :-------- | :---- | :-------- | :----------- |
| Arxiv 24.03.20| [VL-Mamba: Exploring State Space Models for Multimodal Learning](https://arxiv.org/pdf/2403.13600) |<img width="718" alt="vl-mamba" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/bbf9bb6c-6c76-4775-86a6-329aa8190287">|  [Github](https://yanyuanqiao.github.io/vl-mamba) |  
| Arxiv 24.03.21| [Cobra: Extending Mamba to Multi-Modal Large Language Model for Efficient Inference](https://arxiv.org/pdf/2403.14520) | <img width="626" alt="cobra" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/fca6056b-41a0-42b3-8202-a558f9585bdc"> |[Github](https://sites.google.com/view/cobravlm) | 
| Arxiv 24.04.05| [Sigma: Siamese Mamba Network for Multi-Modal Semantic Segmentation](https://arxiv.org/pdf/2404.04256) | <img width="702" alt="sigma" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/6ebed8b1-c3c3-46c6-841d-10337a5da019">| [Github](https://github.com/zifuwan/Sigma) | 
| Arxiv 24.04.07| [VMambaMorph: a Multi-Modality Deformable Image Registration Framework based on Visual State Space Model with Cross-Scan Module](https://arxiv.org/pdf/2404.05105) |<img width="711" alt="vmamba_morph" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/77a2632b-b32e-4406-9a9a-a2d36c3acf08"> | [Github](https://github.com/ziyangwang007/VMambaMorph) |
| Arxiv 24.04.11| [SurvMamba: State Space Model with Multi-grained Multi-modal Interaction for Survival Prediction](https://arxiv.org/pdf/2404.08027)| <img width="813" alt="survmamba" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/69a3511d-ef3a-4134-9872-79aeb716eb5d">|  | 
| Arxiv 24.04.11| [FusionMamba: Efficient Image Fusion with State Space Model](https://arxiv.org/pdf/2404.07932)| <img width="816" alt="fusionmamba" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/524db3f2-ea55-4aa2-bc2b-1a13a816770a">|  | 
| Arxiv 24.04.12| [MambaDFuse: A Mamba-based Dual-phase Model for Multi-modality Image Fusion](https://arxiv.org/pdf/2404.08406)| <img width="1035" alt="mamba_defuse" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/8aec11ed-3030-4910-b665-92556ed3e443">| | 
| Arxiv 24.04.14|[Fusion-Mamba for Cross-modality Object Detection](https://arxiv.org/pdf/2404.09146) | <img width="902" alt="fusion-mamba" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/5b4d7551-7ef6-48b0-896f-e50aa7e55b22">| |
| Arxiv 24.04.14|[A Novel State Space Model with Local Enhancement and State Sharing for Image Fusion](https://arxiv.org/pdf/2404.09293)| <img width="1013" alt="levm" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/94d92ae9-7ef3-45ce-9afa-bceacba917f4">| |
| Arxiv 24.04.15| [FusionMamba: Dynamic Feature Enhancement for Multimodal Image Fusion with Mamba](https://arxiv.org/pdf/2404.09498) | <img width="906" alt="fusionmamba_dynamic" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/8e08130c-b32e-4738-a61b-0dc5cf4b457f">
 | [Github](https://github.com/millieXie/FusionMamba) | 
| Arxiv 24.04.17| [Text-controlled Motion Mamba: Text-Instructed Temporal Grounding of Human Motion](https://arxiv.org/pdf/2404.11375) | <img width="810" alt="motion" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/abc94560-b21b-4d33-8585-0d6d218d76dc">|  |
| Arxiv 24.04.24| [CFMW: Cross-modality Fusion Mamba for Multispectral Object Detection under Adverse Weather Conditions](https://arxiv.org/pdf/2404.16302) | <img width="705" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/07310952-0b24-478b-a84b-c6bef996d327">| [Github](https://github.com/lhy-zjut/CFMW) | 
| Arxiv 24.01.25| [MambaMorph: a Mamba-based Framework for Medical MR-CT Deformable Registration](https://arxiv.org/pdf/2401.13934) |<img width="705" alt="mambamorph" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/7446b1ac-a230-4dee-ba51-c2789bee04db">| [Github](https://github.com/Guo-Stone/MambaMorph) |
| Arxiv 24.03.12| [Motion Mamba: Efficient and Long Sequence Motion Generation with Hierarchical and Bidirectional Selective SSM](https://arxiv.org/pdf/2403.07487) | <img width="910" alt="motion_mamba" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/937fc30e-b2d8-46b9-be70-f16613e9dda1"> | [Github](https://steve-zeyu-zhang.github.io/MotionMamba) | 
| Arxiv 24.03.16| [ReMamber: Referring Image Segmentation with Mamba Twister](https://arxiv.org/pdf/2403.17839) | <img width="715" alt="image" src="https://github.com/badripatro/Awesome-Mamba-360/assets/16630972/75fa20aa-ad69-4015-a4eb-480cce77fc5e"> |  | 







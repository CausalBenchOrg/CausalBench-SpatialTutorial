# Spatio-Causal Modeling and Applications

[![ACM SIGSPATIAL Logo](resources/images/sigspatial2026.png)](https://sigspatial2026.sigspatial.org/)

## Schedule

This 180-minute tutorial will take place during the [34th ACM SIGSPATIAL International Conference on Advances in Geographic Information Systems](https://sigspatial2026.sigspatial.org/), held **Tuesday, November 3 through Friday, November 6, 2026**, in **Riverside, California, USA**. The tutorial's exact date, time, room, and designated in-person presenters will be announced when confirmed.

## Tutorial

Understanding spatial phenomena is critical in application domains ranging from predicting the spatial evolution of epidemics to improving sustainability through effective water-resource management. This tutorial introduces causal and spatio-causal foundations, surveys algorithms for four major decision-support tasks, and concludes with hands-on spatio-causal modeling through CausalBench.

### Tutorial Abstract

Understanding spatial phenomena is critical in various application domains, from predicting spatial evolution of epidemics to helping improve sustainability through effective management of water resources. In this tutorial, we first argue that these necessitate the ability to use spatial information to gain causal situational awareness and also to leverage such causal information to tackle both aleatoric and epistemic uncertainties in decision making. In particular, we will introduce seminal as well as cutting-edge techniques for:

- uncovering causal relationships among diverse, spatially and temporally distributed entities; and
- developing causally informed algorithms to make recommendations, forecast future outcomes, and transfer knowledge from data-rich spatio-temporal contexts to data-poor scenarios.

We conclude the tutorial with hands-on experience in spatio-causal modeling using the CausalBench framework.

### Learning Outcomes

Participants will learn how to:

- explain fundamental concepts in causality, causal discovery, and causal effect estimation;
- describe spatial, global, and causal contexts in a complex spatial system;
- distinguish spatial adjacency or correlation from causality;
- identify methods for spatio-causal structure discovery, recommendation, forecasting, and knowledge transfer;
- reason about interventions, counterfactuals, confounding, and uncertainty in spatial applications; and
- use CausalBench to explore existing spatio-causal tasks, datasets, and models and define new ones.

## Tutorial Material

Tutorial materials will be shared here as they become available. These materials may be updated to provide the best hands-on CausalBench experience.

### Slides

Slides will be posted before the tutorial.

### Hands-on Notebook (Google Colab)

The hands-on exercises will use Google Colab to provide attendees with a standardized execution environment. The notebook link will be posted before the tutorial.

## Authors and Presenters

Designated in-person presenters will be announced on this website.

|  |  |  |  |
|:--:|:--:|:--:|:--:|
|![](resources/images/azad.jpg)|![](resources/images/kapkic.jpg)|![](resources/images/mandal.jpg)|![](resources/images/gorantla.jpg)|
|Fahim Tasneema Azad|[Ahmet Kapkiç](https://kapkic.github.io)|Pratanu Mandal|Abhinav Gorantla|
|Arizona State University|Arizona State University|Arizona State University|Arizona State University|
|![](resources/images/wan.jpg)|![](resources/images/mlsapino.png)|![](resources/images/liu.jpg)|![](resources/images/candan.jpg)|
|Shu Wan|Maria Luisa Sapino|Huan Liu|K. Selçuk Candan|
|Arizona State University|University of Torino|Arizona State University|Arizona State University|

Azad, Kapkiç, Mandal, Gorantla, and Wan are graduate students in computer science at Arizona State University. Their research investigates causal dynamics across data, model, and system characteristics and uses this knowledge to improve machine-learning approaches.

Maria Luisa Sapino is a Full Professor of Computer Science at the University of Torino and an Adjunct Professor at Arizona State University. Her research focuses on heterogeneous and multimedia data management and interdisciplinary, smart-data-driven applications.

Huan Liu is a Professor of Computer Science and Engineering at Arizona State University. His research spans data mining, machine learning, social computing, and artificial intelligence. He is a Fellow of ACM, AAAI, AAAS, and IEEE.

K. Selçuk Candan is a Professor of Computer Science and Engineering at Arizona State University and Director of ASU's Center for Assured and Scalable Data Engineering (CASCADE). His research focuses on managing and analyzing non-traditional, heterogeneous, and imprecise data.

## Program Outline

The tutorial consists of two 90-minute sessions. The timing below is approximate.

| Part | Topic | Duration |
|:--:|:--|--:|
| I | Introduction to Causality | 30 minutes |
| II | Spatio-Causality | 20 minutes |
| III | Spatio-Causal Algorithms | 60 minutes |
| IV | Hands-on Spatio-Causal Modeling with CausalBench | 50 minutes |
| V | Discussion and Conclusion | 20 minutes |
|  | **Total** | **180 minutes** |

## Covered Topics

### Part I: Introduction to Causality

- Fundamental concepts in causality
- Models for representing causal knowledge
- Causal discovery and causal effect estimation
- State of the art in causal discovery and inference
- Counterfactual and "what-if" reasoning

### Part II: Spatio-Causality

- Spatial, global, and causal contexts in complex spatial systems
- Representing causal strength, lag, and likelihood
- Focused and diffused causal effects
- Context-dependent and emergent causality
- Motivating applications in hydrology, water sustainability, and epidemic modeling

### Part III: Spatio-Causal Algorithms

1. **Spatio-causal structure discovery**
    - Recovering causal structure from spatial and temporal data
    - Estimating the strength of causal relationships
    - Handling the lack of ground-truth causal structures
2. **Spatio-causal recommendations**
    - Causally grounded location and intervention recommendations
    - Reducing dependence on observational correlations
    - Intervention and counterfactual analysis
3. **Spatio-causal forecasting**
    - Using physical and relational networks as inductive biases
    - Distinguishing valid causal priors from correlational structure
    - Explainable forecasting for epidemics, hydrology, and other spatial systems
4. **Spatio-causal knowledge transfer**
    - Transferring invariant causal structure across regions
    - Domain generalization, adaptation, and disentanglement
    - Learning from data-rich contexts for data-poor communities

### Part IV: Hands-on Spatio-Causal Modeling with CausalBench

Participants will use CausalBench, a task-agnostic platform for transparent and reproducible evaluation of machine-learning and causal-learning methods. The exercises will introduce standardized tasks, datasets, models, metrics, evaluation protocols, provenance tracking, and reproducible experiment environments. Participants will explore existing spatio-causal components and learn how to define new spatio-causal tasks and models.

### Part V: Discussion and Conclusion

The tutorial concludes with a discussion of spatio-causal decision-making workflows, open research challenges, and the societal impact of spatio-causality in high-impact domains such as public health and sustainability.

## Audience and Prerequisites

The tutorial is intended for researchers, students, and practitioners interested in causality, spatial domains, and their intersection. Prior exposure to causal inference, spatial analysis, statistics, machine learning, or related computational methods will help participants engage more deeply, but advanced expertise in causality or spatial modeling is not required.

Participants need:

- a basic understanding of quantitative reasoning;
- a laptop or tablet;
- a stable internet connection; and
- access to Google Colab for the hands-on exercises.

## Documentation

You can access the [CausalBench documentation](https://docs.causalbench.org), the primary knowledge base for installing and using CausalBench.

## Selected References

1. Azad, F. T., et al. (2024). (Vision Paper) A Vision for Spatio-Causal Situation Awareness, Forecasting, and Planning. *ACM Transactions on Spatial Algorithms and Systems*, 10(2), 14:1-14:42.
2. Kapkiç, A., et al. (2024). Introducing CausalBench: A Flexible Benchmark Framework for Causal Analysis and Machine Learning. In *Proceedings of CIKM '24*, 5220-5224.
3. Kapkic, A., et al. (2026). CausalBench+: Causal-Informed Machine Learning Benchmarking. In *Proceedings of the WSDM Companion '26*, 120-122.
4. Guo, R., Cheng, L., Li, J., Hahn, P. R., and Liu, H. (2020). A Survey of Learning Causality with Data: Problems and Methods. *ACM Computing Surveys*, 53(4), 1-37.
5. Pearl, J. (2009). *Causality*. Cambridge University Press.
6. Pearl, J., Glymour, M., and Jewell, N. P. (2016). *Causal Inference in Statistics: A Primer*. Wiley.
7. Sheth, P., et al. (2022). STCD: A Spatio-Temporal Causal Discovery Framework for Hydrological Systems. In *Proceedings of IEEE Big Data*, 5578-5583.
8. Sheth, P., et al. (2023). STREAMS: Towards Spatio-Temporal Causal Discovery with Reinforcement Learning for Streamflow Rate Prediction. In *Proceedings of CIKM '23*, 4815-4821.
9. Wan, S., et al. (2024). Spatio-Temporal Causal Learning for Streamflow Forecasting. In *Proceedings of IEEE Big Data*, 6161-6170.
10. Ali, S., and Wang, J. (2024). Tutorial on Causal Inference with Spatiotemporal Data. In *Proceedings of STCausal '24*, 23-25.

## Contact

For questions about the tutorial, please contact Fahim Tasneema Azad at [fazad@asu.edu](mailto:fazad@asu.edu), Ahmet Kapkiç at [akapkic@asu.edu](mailto:akapkic@asu.edu), or the CausalBench team at [support@causalbench.org](mailto:support@causalbench.org).

## Acknowledgments

This work is supported in part by NSF grants #2311716, #2230748, and #2412115, and USACE #GR40695. We thank all contributors and the CausalBench community for their continued support and feedback.

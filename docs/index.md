<!-- # Presenters’ names and bibliography, tutorial outline and what will the participants learn from the tutorial. -->

# CausalBench: Causal Learning Research Streamlined
[![KDD Logo](resources/images/kddlogo.jpg)](https:..kdd2025.kdd.org/)
## Schedule
The tutorial **took** place at [KDD'25](https://kdd2025.kdd.org/), on Monday, August 4, 8:00 AM – 11:00 AM, in Toronto Convention Centre, Room 707. Thank you for attending! Please enjoy the video recording of the tutorial below.

### Tutorial Video
[![Watch the video](https://img.youtube.com/vi/oGA2kf4Trg4/0.jpg)](https://youtu.be/oGA2kf4Trg4)

## Tutorial
In this 3-hour long tutorial, we will explore the field of Causality, the state of the art, difficulties in benchmarking studies, and learn how to utilize CausalBench to facilitate comparative and transparent benchmarking.
Read the tutorial paper [here](https://docs.causalbench.org/files/papers/CausalBench_Tutorial.pdf).

### Tutorial Abstract
Recent advances in causal machine learning introduced a plethora of new causal discovery and causal inference models to tackle decision support problems. Yet, these models exhibit different performance when they train on different data, and even different hardware/software platforms, making it challenging for users to select the appropriate setup pertinent to their specific problem instance. The situation is complicated by the fact that, until recently, the field lacked a unified, publicly available, and configurable platform that supports all major causal inference tasks, including causal discovery, causal effect estimation, and causal inference. CausalBench is a comprehensive benchmarking tool for causal machine learning that facilitates accurate and reproducible benchmarking of causal models across metrics and deployment contexts and helps users to select the most appropriate set up (such as hyper-parameter configuration) for the specific problem setting. This tutorial is intended to familiarize attendees from diverse backgrounds, who are interested in causal learning models and with the capabilities of CausalBench. The tutorial begins with an introduction to "causality" and causal machine learning, and then provides hands-on experience with CausalBench to equip attendees with the knowledge necessary to utilize CausalBench for their causal learning problems.

## Tutorial Material
We provide several tutorial materials below for your convenience and reference. These materials may be updated in the future to provide the best CausalBench experience.

### Slides
You may access the [slides](/resources/KDD25_Tutorial_Deck.pdf) here.

###  Quickstart file (Google Colab)
For your convenience, we have provided two Python Notebook files that can be run on Google Colab.

- [CausalBench Tutorial File](https://colab.research.google.com/drive/1BxN6ol7hVi66tifZ0WRlPgmbsr8w0lY6), *this file will be utilized through the hands-on tutorial.

## Presenters
|  |  | | |
|:--:|:--:|:--:|:--:|
|![](resources/images/kapkic.jpg)|![](resources/images/mandal.jpg)|![](resources/images/gorantla.jpg)|![](resources/images/liu.jpg)|
|[Ahmet Kapkiç](https://kapkic.github.io)|Pratanu Mandal|Abhinav Gorantla|Huan Liu|
|Arizona State University|Arizona State University|Arizona State University|Arizona State University|

## Contributors
|  |  | | |
|:--:|:--:|:--:|:--:|
|![](resources/images/wan.jpg)|![](resources/images/coban.jpg)|![](resources/images/sheth.jpg)|![](resources/images/candan.jpg)|
|Shu Wan|Ertuğrul Çoban|Paras Sheth|K. Selçuk Candan|
|Arizona State University|Arizona State University|Amazon|Arizona State University|

### Program Outline
|  | |
|:--:|:--:|
|**Time**|**Content**	|
|08:00-08:05|	Introduction to the Tutorial|
|08:05-08:25|	Introduction to CausalBench|
|08:25-08:55|	Introduction to Causality and Causal Learning|
|08:55-09:30|	Delve into the CasualBench framework to create and execute benchmarks|
|09:30-10:00|	Coffee break|
|10:00-10:10|	Shorter introduction to CausalBench|
|10:10-10:35|	Explore published benchmarks and reproduce experiments|
|10:35-10:50|	Gain further insights using Causal Analysis and Recommendations|
|10:50-11:00|	CausalBench: What's Next?|

### Covered Topics
1. **CausalBench**
	- Introduction to CausalBench
	- Installing CausalBench and setting up a benchmark
	- Benchmark contexts: details and configuration files
	- Creating and executing a benchmark context
	- Analyzing and interpreting the results
	- Challenges ahead and contributing to CausalBench
2. **Causality**
	- Introduction to causality [6, 7]
	- Models for representing causal knowledge [3, 5]
	- State-of-the art in causal discovery and causal effect estimation [1, 2, 8] 

### Documentation
You can access CausalBench documentation at [docs.causalbench.org](https://docs.causalbench.org), which is the acting knowledge base for CausalBench.

## References
 1. Azad, F. T., Candan, K. S., Kapkiç, A., Li, M.-L., Liu, H., Mandal, P., Sheth, P., Arslan, B., Chowell-Puente, G., Sabo, J., et al. (vision paper) a vision for spatio-causal situation awareness, forecasting, and planning. ACM Transactions on Spatial Algorithms and Systems 10, 2 (2024), 1–42. 
2. Guo, R., Cheng, L., Li, J., Hahn, P. R., and Liu, H. A survey of learning causality with data: Problems and methods. ACM Computing Surveys (CSUR) 53, 4 (2020), 1–37. 
3. Hoyle, R. H. Handbook of structural equation modeling. Guilford press, 2012. 
4. Kapkiç, A., Mandal, P., Wan, S., Sheth, P., Gorantla, A., Choi, Y., Liu, H., and Candan, K. S. Introducing causalbench: A flexible benchmark framework for causal analysis and machine learning. In Proceedings of the 33rd ACM International Conference on Information and Knowledge Management (2024), pp. 5220–5224. 
5. Pearl, J. Graphs, causality, and structural equation models. Sociological Methods & Research 27, 2 (1998), 226–284. 
6. Pearl, J. Causality. Cambridge university press, 2009. 
7. Pearl, J., Glymour, M., and Jewell, N. P. Causal inference in statistics: A primer. John Wiley & Sons, 2016. 
8. Wan, S., Shah, R., Deng, Q., Sabo, J., Liu, H., and Candan, K. S. Spatio-temporal causal learning for streamflow forecasting. In 2024 IEEE International Conference on Big Data (BigData) (2024), IEEE, pp. 6161–6170.

## Contact
For questions regarding tutorial, please contact us at support@causalbench.org or akapkic@asu.edu.

## Acknowledgments
We thank all the contributors and the community for their continuous support and feedback in making CausalBench a reliable and valuable resource for causal learning research.
This research is funded by NSF Grant 2311716, "CausalBench: A Cyberinfrastructure for Causal-Learning Benchmarking for Efficacy, Reproducibility, and Scientific Collaboration", and NSF Grants #2230748, "PIRE: Building Decarbonization via AI-empowered District Heat Pump Systems", #2412115, "PIPP Phase II: Analysis and Prediction of Pandemic Expansion (APPEX)" and USACE #GR40695, "Designing nature to enhance resilience of built infrastructure in western US landscapes".
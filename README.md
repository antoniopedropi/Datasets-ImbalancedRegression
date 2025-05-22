# Imbalanced Regression Dataset Repository

This repository provides access to datasets tailored for benchmarking regression models under imbalanced target distributions.

The datasets include metadata such as feature types, presence of missing values, and relevance of extreme values.

## Available Datasets

| Dataset | Description | Features | Nominal | Numeric | Instances | Missing | Type of Extreme | Relevance Threshold | # Rare | % Rare | Target Variable | Source |
|---------|-------------|----------|---------|---------|-----------|---------|------------------|---------------------|--------|--------|------------------|--------|
| a1 | The data points are taken on an annual basis from various streams / rivers in Europe, compiling features aimed at predicting the concentrations of seven algae species. | 11 | 3 | 8 | 198 | No | Both | 0.8 | 0 | 0.00% | a1 | [1] |
| a2 | The data points are taken on an annual basis from various streams / rivers in Europe, compiling features aimed at predicting the concentrations of seven algae species. | 11 | 3 | 8 | 198 | No | Both | 0.8 | 0 | 0.00% | a2 | [1] |
| a3 | The data points are taken on an annual basis from various streams / rivers in Europe, compiling features aimed at predicting the concentrations of seven algae species. | 11 | 3 | 8 | 198 | No | Both | 0.8 | 0 | 0.00% | a3 | [1] |
| a4 | The data points are taken on an annual basis from various streams / rivers in Europe, compiling features aimed at predicting the concentrations of seven algae species. | 11 | 3 | 8 | 198 | No | Both | 0.8 | 0 | 0.00% | a4 | [1] |
| a6 | The data points are taken on an annual basis from variousstreams / rivers in Europe, compiling features aimed at predicting the concentrations of seven algae species. | 11 | 3 | 8 | 198 | No | Both | 0.8 | 0 | 0.00% | a6 | [1] |
| a7 | The data points are taken on an annual basis from various streams / rivers in Europe, compiling features aimed at predicting the concentrations of seven algae species. | 11 | 3 | 8 | 198 | No | High | 0.8 | 14 | 7.07% | a7 | [1] |
| abalone | Predict the age of abalone from physical measurements. | 8 | 1 | 7 | 4177 | No | Both | 0.8 | 1033 | 24.73% | Rings | [2] |
| acceleration | Dataset with acceleration statistics. | 14 | 3 | 11 | 1732 | No | Both | 0.8 | 158 | 9.12% | acceleration | [3] |
| ailerons | The attributes describe the status of the aeroplane, while the goal is to predict the control action on the ailerons of the aircraft. | 40 | 0 | 40 | 13515 | No | Both | 0.8 | 1622 | 11.80% | Goal | [4] |
| airfoil | NASA data set, obtained from a series of aerodynamic and acoustic tests of two and three-dimensional airfoil blade sections conducted in an anechoic wind tunnel. | 5 | 0 | 5 | 1503 | No | High | 0.8 | 80 | 5.32% | scaled-sound-pressure | [5] |
| anacalt | The data contains information about the decisions taken by a supreme court. | 7 | 0 | 7 | 4052 | No | Both | 0.8 | 0 | 0.00% | Log_exposure | [4] |
| appliances_energy | Experimental data used to create regression models of appliances energy use in a low energy building. | 27 | 0 | 27 | 19735 | No | Both | 0.8 | 8212 | 41.61% | Appliances | [6] |
| autoprices | Dataset with feature leading to the prediction of its price. | 16 | 1 | 15 | 159 | No | Both | 0.8 | 0 | 0.00% | class | [7] |
| availablePower | Dataset with power statistics. | 15 | 7 | 8 | 1802 | No | Both | 0.8 | 305 | 16.93% | available.power | [8] |
| bank8FM | Part of a family of datasets synthetically generated from a simulation of how bank-customers choose their banks. | 8 | 0 | 8 | 4499 | No | Both | 0.8 | 0 | 0.00% | rej | [9] |
| baseball | This dataset contains the 1992 salaries of the set of Major League Baseball players who played at least one game in both the 1991 and 1992 seasons, excluding pitchers. | 16 | 0 | 16 | 337 | No | Both | 0.8 | 0 | 0.00% | Salary | [10] |
| californiaHousing | This data set contains information about all the block groups in California from the 1990 Census. | 8 | 0 | 8 | 20640 | No | Low | 0.8 | 1802 | 8.73% | MedianHouseValue | [11] |
| cocomo | Software Engineering Repository data set made publicly available in order to encourage repeatable, verifiable, refutable, and/or improvable predictive models of software engineering. | 16 | 1 | 1 | 60 | No | Low | 0.8 | 14 | 23.33% | ACT_EFFORT | [12] |
| concrete | Concrete Compressive Strength data set | 8 | 0 | 8 | 1030 | No | Low | 0.8 | 0 | 0.00% | ConcreteCompressiveStrength | [13] |
| cpuActiv | Computer activity data set | 21 | 0 | 21 | 8192 | No | Low | 0.8 | 371 | 4.53% | Usr | [9] |
| cpuSm | The Computer Activity databases are a collection of computer systems activity measures. The data was collected from a Sun Sparcstation 20/712 with 128 Mbytes of memory running in a multi-user university department. The final dataset is taken from both occasions with equal numbers of observations coming from each collection epoch. | 12 | 0 | 12 | 8192 | No | Low | 0.8 | 371 | 4.53% | usr | [9] |
| debutanizer | This dataset aims to predict the butane concentration on a Debutanizer column. | 7 | 0 | 7 | 2394 | No | High | 0.8 | 212 | 8.86% | y | [14] |
| deltaAirlerons | This data set is also obtained from the task of controlling the ailerons of a F16 aircraft. | 5 | 0 | 5 | 7129 | No | Both | 0.8 | 1206 | 16.92% | Sa | [4] |
| deltaElevators | This data set is also obtained from the task of controlling the elevators of a F16 aircraft. | 60 | 0 | 6 | 9517 | No | High | 0.8 | 4785 | 50.28% | Se | [4] |
| diabetes | This data set concerns the study of the factors affecting patterns of insulin-dependent diabetes mellitus in children. | 2 | 0 | 2 | 43 | No | High | 0.8 | 6 | 13.95% | C_peptide | [4] |
| ele-1 | Electrical Length data set | 2 | 0 | 2 | 495 | No | High | 0.8 | 21 | 4.24% | Length | [4] |
| ele-2 | Electrical-Maintenance data set | 4 | 0 | 4 | 1056 | No | Both | 0.8 | 0 | 0.00% | Y | [4] |
| elevators | The attributes describe the status of the aeroplane, while the goal is to predict the control action on the ailerons of the aircraft. | 18 | 0 | 18 | 16599 | No | Both | 0.8 | 4390 | 26.45% | Goal | [15] |
| forestFires | Forest Fires data set | 12 | 0 | 12 | 517 | No | High | 0.8 | 15 | 2.90% | Area | [16] |
| friedman | Friedman Benchmark Function data set | 5 | 0 | 5 | 1200 | No | Both | 0.8 | 0 | 0.00% | Output | [4] |
| fuelConsumption | The data contains information about car’s emissions and fuel consumption. | 37 | 12 | 25 | 1764 | No | Both | 0.8 | 167 | 9.47% | fuel.counsumption.country | [17] |
| geographical_origin_music | Instances in this dataset contain audio features extracted from 1059 wave files. The task associated with the data is to predict the geographical origin of music. | 117 | 0 | 117 | 1059 | No | Both | 0.8 | 104 | 9.82% | V100 | [18] |
| heat | Dataset with heating statistics. | 11 | 3 | 8 | 7400 | No | Both | 0.8 | 833 | 11.26% | heat | [8] |
| house16H | This database was designed on the basis of data provided by US Census Bureau. | 16 | 0 | 16 | 22784 | No | Both | 0.8 | 6098 | 26.76% | Price | [9] |
| housing | The Ames Housing Dataset is a well-known dataset in the field of machine learning and data analysis. It contains various features and attributes of residential homes in Ames, Iowa, USA. | 79 | 43 | 36 | 1460 | Yes (7829) | Both | 0.8 | 179 | 12.26% | SalePrice | [19] |
| housingBoston | This dataset contains information collected by the U.S Census Service concerning housing in the area of Boston Mass. | 13 | 0 | 13 | 506 | No | Both | 0.8 | 105 | 20.75% | HousValue | [20] |
| kdd_coil_1 | This data set is from the 1999 Computational Intelligence and Learning (COIL) competition. The data contains measurements of river chemical concentrations and algae densities. | 11 | 3 | 8 | 316 | Yes (56) | Both | 0.8 | 0 | 0.00% | algae_1 | [21] |
| kinematics8nm | This is data set is concerned with the forward kinematics of an 8 link robot arm. | 8 | 0 | 8 | 8192 | No | Both | 0.8 | 0 | 0.00% | y | [9] |
| laser | Laser generated data set | 4 | 0 | 4 | 993 | No | Both | 0.8 | 0 | 0.00% | Output | [4] |
| lungcancer-shedden | Prediction in Lung Adenocarcinoma | 23 | 3 | 20 | 442 | No | High | 0.8 | 12 | 2.71% | OS_years | [22] |
| machineCPU | Machine CPU Performance data set | 6 | 0 | 6 | 209 | No | Both | 0.8 | 46 | 22.01% | PRP | [4] |
| maxTorque | Dataset with torque statistics. | 32 | 13 | 19 | 1802 | No | Both | 0.8 | 235 | 13.04% | maximal.torque | [23] |
| meta | Meta-Data was used in order to give advice about which classification method is appropriate for a particular dataset. | 21 | 2 | 19 | 528 | Yes (504) | Both | 0.8 | 165 | 31.25% | class | [24] |
| mortgage | Mortgage data set | 15 | 0 | 15 | 1049 | No | Low | 0.8 | 133 | 12.68% | 30Y-CMortgageRate | [25] |
| pdgfr | This is one of 41 drug design datasets. | 320 | 0 | 320 | 79 | No | High | 0.8 | 15 | 18.99% | oz322 | [26] |
| pollen | This dataset is synthetic. It was generated by David Coleman at RCA Laboratories in Princeton, N.J. | 5 | 0 | 5 | 3848 | No | Both | 0.8 | 242 | 6.29% | DENSITY | [27] |
| puma32NH | This is a family of datasets synthetically generated from a realistic simulation of the dynamics of a Unimation Puma 560 robot arm. | 32 | 0 | 32 | 8192 | Yes (33) | Both | 0.8 | 0 | 0.00% | thetadd6 | [9] |
| puma8NH | This is a family of datasets synthetically generated from a realistic simulation of the dynamics of a Unimation Puma 560 robot arm. | 8 | 0 | 8 | 8192 | Yes (9) | Both | 0.8 | 0 | 0.00% | thetadd3 | [9] |
| quake | Quake data set | 3 | 0 | 3 | 2178 | No | Both | 0.8 | 0 | 0.00% | Richter | [4] |
| sensory | Data for the sensory evaluation experiment in Brien, C.J. and Payne, R.W. (1996) Tiers, structure formulae and the analysis of complicated experiments. | 11 | 0 | 11 | 576 | No | Both | 0.8 | 69 | 11.98% | Score | [28] |
| servo | This is an interesting collection of data provided by Karl Ulrich. It covers an extremely non-linear phenomenon - predicting the rise time of a servomechanism in terms of two (continuous) gain settings and two (discrete) choices of mechanical linkages. | 4 | 4 | 0 | 167 | No | Both | 0.8 | 59 | 35.33% | class | [15] |
| space_ga | The dataset contains 3,107 observations on U.S. county votes cast in the 1980 presidential election. | 6 | 0 | 6 | 3107 | No | Both | 0.8 | 182 | 5.86% | ln_votes_pop | [29] |
| stock | Stock Prices data set | 9 | 0 | 9 | 950 | No | Both | 0.8 | 0 | 0.00% | Company10 | [30] |
| strikes | The data consist of annual observations on the level of strike volume (days lost due to industrial disputes per 1000 wage salary earners), and their covariates in 18 OECD countries from 1951-1985. | 6 | 0 | 6 | 625 | No | High | 0.8 | 15 | 2.40% | strike_volume | [31] |
| sulfer_1 | The sulfur recovery unit (SRU) removes environmental pollutants from acid gas streams before they are released into the atmosphere. Furthermore, elemental sulfur is recovered as a valuable by-product. | 5 | 0 | 5 | 10081 | No | Both | 0.8 | 1117 | 11.08% | y1 | [32] |
| sulfer_2 | The sulfur recovery unit (SRU) removes environmental pollutants from acid gas streams before they are released into the atmosphere. Furthermore, 0.8elemental sulfur is recovered as a valuable by-product. | 5 | 0 | 5 | 10081 | No | Both | 0.8 | 1444 | 14.32% | y2 | [32] |
| supercondutivity | Two files contain data on 21263 superconductors and their relevant features. | 81 | 0 | 81 | 21263 | No | Both | 0.8 | 0 | 0.00% | critical_temp | [33] |
| treasury | This file contains the Economic data information of USA from 01/04/1980 to 02/04/2000 on a weekly basis. | 15 | 0 | 15 | 1049 | No | Low | 0.8 | 137 | 13.06% | 1MonthCDRate | [4] |
| triazines | A triazine dataset. The goal is to predict the inhibition of dihydrofolate reductase by triazines. | 60 | 0 | 60 | 186 | No | Both | 0.8 | 23 | 12.37% | activity | [34] |
| wankara | This file contains the weather information of Ankara from 01/01/1994 to 28/05/1998. | 9 | 0 | 9 | 1609 | No | Both | 0.8 | 0 | 0.00% | Mean_temperature | [4] |
| wine-quality | The two datasets are combined and related to red and white variants of the Portuguese "Vinho Verde" wine. | 12 | 1 | 11 | 6497 | No | High | 0.8 | 4113 | 63.31% | quality | [35] |
| yachtHydrodynamics | Delft data set, used to predict the hydodynamic performance of sailing yachts from dimensions and velocity. | 6 | 0 | 6 | 308 | No | Both | 0.8 | 0 | 0.00% | Residuary_Resistance | [36] |

## References

[1] Torgo, L. (2016). Data mining with R: Learning with case studies (2nd ed.). Chapman & Hall/CRC. http://ltorgo.github.io/DMwR2
[2] Nash, W., Sellers, T., Talbot, S., Cawthorn, A., & Ford, W. (1994). Abalone. UCI Machine Learning Repository. https://doi.org/10.24432/C55C7W
[3] Moniz, N., Ribeiro, R. P., & Margarido, M. (2023). accel: Acceleration dataset [Dataset in the IRon R package, version 0.1.4]. https://CRAN.R-project.org/package=IRon
[4] Alcalá-Fdez, J., Fernández, A., Luengo, J., Derrac, J., García, S., Sánchez, L., & Herrera, F. (2011). KEEL data-mining software tool: Data set repository, integration of algorithms and experimental analysis framework. Journal of Multiple-Valued Logic and Soft Computing, 17(2–3), 255–287.
[5] Brooks, T., Pope, D., & Marcolini, M. (1989). Airfoil self-noise [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5VW2C
[6] Candanedo, L. (2017). Appliances energy prediction [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5VC8G
[7] Schlimmer, J. (1985). Automobile [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5B01C
[8] Camacho, L., & Bação, F. (2024). WSMOTER: A novel approach for imbalanced regression. Applied Intelligence, 54, 1–11. https://doi.org/10.1007/s10489-024-05608-6
[9] Rasmussen, C. E., Neal, R. M., Hinton, G. E., et al. (1996). DELVE: Data for evaluating learning in valid experiments[Software and dataset repository]. University of Toronto. https://www.cs.toronto.edu/~delve/
[10] Journal of Statistics Education. (1992). Pay for play: Are baseball salaries based on performance? [Dataset]. Dataset available from the Journal of Statistics Education. https://jse.amstat.org/datasets/baseball.dat.txt
[11] Carnegie Mellon University. (2016). StatLib: A data and software archive [Online dataset repository]. https://lib.stat.cmu.edu
[12] OpenML contributors. (2025). OpenML dataset 1051 [Dataset]. OpenML: An open platform for machine learning. https://www.openml.org/d/1051
[13] Yeh, I.-C. (1998). Concrete compressive strength [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5PK67
[14] Fortuna, L., Graziani, S., Rizzo, A., & Xibilia, M. G. (2007). Soft sensors for monitoring and control of industrial processes. In Advances in Industrial Control. Springer London. https://doi.org/10.1007/978-1-84628-480-9
[15] Torgo, L. (2019). Regression data sets [Online dataset repository]. LIACC / University of Porto. https://www.dcc.fc.up.pt/~ltorgo/Regression/DataSets.html
[16] Cortez, P., & Morais, A. (2007). Forest fires [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5D88D
[17] University of Toronto, DELVE Project. (2003). DELVE: Data for evaluating learning in valid experiments [Online dataset repository]. https://www.cs.toronto.edu/~delve/
[18] Zhou, F., Claire, Q., & King, R. D. (2014). Geographical origin of music [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5VK5D
[19] Necrothapa, S. (2020). Ames housing dataset [Dataset]. Kaggle. https://www.kaggle.com/datasets/shashanknecrothapa/ames-housing-dataset
[20] Schirmer, C. (2020). Boston housing [Dataset]. Kaggle. https://www.kaggle.com/datasets/schirmerchad/bostonhoustingmlnd
[21] Elkan, C. (2001). Magical thinking in data mining: Lessons from CoIL Challenge 2000. In Proceedings of the seventh ACM SIGKDD international conference on Knowledge discovery and data mining (pp. 426–431). ACM. https://doi.org/10.1145/502512.502576
[22] Director's Challenge Consortium for the Molecular Classification of Lung Adenocarcinoma, Shedden, K., Taylor, J. M., Enkemann, S. A., Tsao, M. S., Yeatman, T. J., Gerald, W. L., Eschrich, S., Jurisica, I., Giordano, T. J., Misek, D. E., Chang, A. C., Zhu, C. Q., Strumpf, D., Hanash, S., & Shepherd, F. A. (2008). Shedden_2008: Gene expression–based survival prediction in lung adenocarcinoma [Dataset]. Lung Cancer Explorer, UT Southwestern. https://lce.biohpc.swmed.edu/lungcancer/datasetsearch.php?datasetid=1
[23] Branco, P., Torgo, L., & Ribeiro, R. P. (2025). Imbalanced regression data sets [Online dataset repository]. University of Porto. https://paobranco.github.io/Imbalanced-Regression-DataSets/
[24] Meta-data. (1994). Meta-data [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5X31P
[25] Board of Governors of the Federal Reserve System. (2025). H.15 selected interest rates [Statistical release and dataset repository]. https://www.federalreserve.gov/releases/h15/
[26] OpenML contributors. (2025). OpenML dataset 409 [Dataset]. OpenML platform. https://www.openml.org/d/409
[27] Coleman, D. (1986). pollen: Geometric features of pollen grains [Dataset]. StatLib Archive, Carnegie Mellon University. https://lib.stat.cmu.edu/data-expo/pollen.data
[28] Brien, C. J., & Payne, R. W. (1999). Tiers, structure formulae and the analysis of complicated experiments. Journal of the Royal Statistical Society: Series D (The Statistician), 48(1), 41–52.
[29] OpenML contributors. (n.d.). space_ga [Dataset]. OpenML. https://www.openml.org/d/507
[30] Carnegie Mellon University, Department of Statistics. (2016). StatLib: A data and software archive [Online dataset repository]. https://lib.stat.cmu.edu/datasets/
[31] Tibshirani, R. J. (2015). strike: Annual strikes data for OECD countries (1951–1985) [Dataset]. Dataset used in course “Statistical Computing,” Carnegie Mellon University. http://www.stat.cmu.edu/~ryantibs/statcomp-F15/homework/strike.txt
[32] OpenML contributors. (2025). sulfur [Dataset]. OpenML. https://www.openml.org/d/23515
[33] Hamidieh, K. (2018). Superconductivity data [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C53P47
[34] King, R. D., Hurst, J. D., & Sternberg, M. J. E. (1994). A comparison of artificial intelligence methods for modelling QSARs. Applied Artificial Intelligence, 9, 213–234. / Hirst, J. D., King, R. D., & Sternberg, M. J. E. (1994). Quantitative structure–activity relationships by neural networks and inductive logic programming: II. The inhibition of dihydrofolate reductase by triazines. Journal of Computer-Aided Molecular Design, 8(4), 421–432. https://doi.org/10.1007/BF00125376
[35] Cortez, P., Cerdeira, A., Almeida, F., Matos, T., & Reis, J. (2009). Wine Quality [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C56S3T.
[36] Gerritsma, J., Onnink, R., & Versluis, A. (1981). Yacht Hydrodynamics [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5XG7R.

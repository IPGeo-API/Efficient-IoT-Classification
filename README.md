# About
\t This study investigated the performance differences between convolutional computational models for fingerprinting Internet of Things (IoT) devices. A review of prior work exemplified the use of computational models to classify a small number of IoT devices on local networks with high accuracy, yet more recent work provided a precedent for internet-scale IoT classification. While this precedent was set, no further work has extended on this proof-of-concept and thus this study is designed to investigate that gap by comparing specific performances between convolutional models to classify IoT devices across the whole internet. The models differed in their network structure (sequential versus windowed) and their kernel structure (1-Dimensional versus 2-Dimensional). The models tested were first optimized to ensure peak performance and then were put through general runs and 20-fold cross validation to collect data representative of the model’s performance. One-way analysis of variance (one-way ANOVA) was used to determine significant differences within performances between all models in general and post hoc two sample T-Tests were performed to determine significant differences between the two specific groups. Run times of the models during the packet restriction tests were used to determine the most efficient model for internet wide IoT classification and determine a critical value for each model where it performs at its maximum capability at the shortest time cost. The combination of high accuracy and performance along with the low run time at its critical value suggests that the 1D Convolutional Neural Network is the most efficient model for the classification of Internet-Scale Internet of Things devices. Suggestions were made by the researcher to examine this phenomenon further by exploring both the classification of distinct cyber threats and the long-term classification performance of the model.

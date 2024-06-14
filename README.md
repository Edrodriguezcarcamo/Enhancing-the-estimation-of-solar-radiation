Code developed for the paper: In revision
# Introduction
The evaluation of solar radiation is essential for large-scale solar energy systems, as assessing economic feasibility early on depends on accurate solar radiation data. Accurate sensors are needed to characterize the solar resource. Due to a scarcity of solar radiation data, numerical models are commonly used to estimate solar radiation components using meteorological variables that are simple or cheap to measure. In recent years, the use of machine learning (ML) algorithms has gained significant popularity in the estimation of solar radiation components. In this study it is proposed a post-processing approach using the separation model outcomes as input variables to estimate the diffuse fraction. Three ML models are employed (XGBoost, Random Forest, and Multilayer Perceptron) to boost the accuracy in terms of three statistical indicators: nRMSE, nMBE, and $R^2$. The employed technique takes a distinctive approach by using reference stations to train the machine learning models and, afterward, make the assessment at the site under study. The results show an improvement in terms of precision of individual separation model outcomes. Thus, the proposed methodology may serve as a reliable approach for estimating solar radiation components in cases where historical data for a specific place of interest is not accessible.

# How to use it
First, it is necessary to identify to which Köppen climate zone [1] the station to be evaluated belongs. One way to identify which zone the station belongs to is to use the code made by Chen et al. [2] at http://hanschen.org/koppen.
# References
[1] Köppen, W., Geiger, R.. Handbuch der Klimatologie. 1930. doi:10.2307/200498.

[2] Chen, D. and H. W. Chen (2013): Using the Köppen classification to quantify climate variation and change: An example for 1901–2010. Environmental Development, 6, 69-79, doi:10.1016/j.envdev.2013.03.007.

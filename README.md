# Wide-Deep-based-on-Tensorflow2
In this repo, I will introduce what is Wide&amp;Deep model, and why Wide&amp;Deep model through reading the paper of "Wide and Deep". And I will also introduce how to build a Wide&amp;Deep model by using Tensorflow2. 

Wide and deep model was proposed by Google in DLRS 2016.  In this paper(“Wide & Deep learning for recommender system”), the researchers(Cheng et al., 2016) introduced a recommender system, by combining the linear model (wide part) and deep neural network model (deep part).  。Cheng et al(2016) pointed out that the “memorisation” and “generalisation” are the two important things we want to achieve in the recommender system. They also gave the definitions for both “memorization” and “generalisation”.  As Cheng at al(2016) said, ”Memorization can be loosely defined as learning the frequent co-occurrence of items or features and exploiting the correlation available in the historical data. Generalization, on the other hand, is based on transitivity of correlation and explores new feature combinations that have never or rarely occurred in the past.” Thus, their aim is to use linear model to achieve good memorization and use deep neural network to achieve good generalization.  The *joint training* is used in this paper rather than ensemble.

![](https://github.com/GuanLong-Lyu/Wide-and-Deep-based-on-Tensorflow2/blob/main/IMG/%E6%88%AA%E5%B1%8F2021-01-26%2017.45.00.png)
Figure1. The structure of Wide & Deep learning (Cheng et al.,2016)


# memory-based collaborative filtering implementation along with a missing data predictive model.
Fully implemented the memory-based collaborative filtering approach, an innovative solution from the 
published research paper "Effective Missing Data Prediction for Collaborative Filtering", authored by Hao Ma, Irwin King, Yongli Ren, and Michael R. Lyu.

Collaborative Filtering is an unsupervised machine learning technique that automatically predicts the interest of a user by gathering rating information of other similar users or items. It is a technique used by recommender systems in applications such as Netflix, YouTube, and Amazon products.

This memory-based collaborative filtering solution is unique for multiple reasons:<br />
1- It utilizes an enhanced Pearson Correlation Coefficient (PCC) with extra parameters to overcome any potential decrease in accuracy.<br />
2- A Significance Weighting equation is utilized to devalue possible overestimations by the Pearson Correlation Coefficient (PCC).<br />
3- It implements an effective predictive algorithm for missing values in the matrix.<br />
4- The utilization of the Top-N Neighbors Selection algorithm, except with newly introduced thresholds to optimize the selection. <br />
5- The predictive algorithm takes advantage of both user-based and item-based matrices to make a better prediction, instead of using one matrix as most collaborative filtering algorithms do. 

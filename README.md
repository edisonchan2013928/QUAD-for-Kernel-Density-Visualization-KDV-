# QUAD-for-Kernel-Density-Visualization-KDV-

QUAD is the short form of quadratic bound functions, which mainly support kernel density visualization (abbrev. KDV) and kernel density estimation (with low-dimensional setting, d<10). In this work, we show that the quadratic bound functions can be efficiently evaluated in O(d^2) time and are theoretically tighter than the state-of-the-art linear bound functions of previous work, called KARL [1] (For more details about [1], please refer to https://github.com/edisonchan2013928/KARL-Fast-Kernel-Aggregation-Queries). As such, QUAD can achieve one-order-of-magnitude speedup, compared with the state-of-the-art method KARL.

In the future, we will further support other types of kernel functions. In addition, we hope to develop the efficient algorithms for training the kernel-based machine learning models, e.g., kernel SVM classification and kernel regression. Moreover, we also want to provide the library to help some domain experts (e.g., in geography/ social science domain) for using our method to visualize their large-scale datasets. Furthermore, we will make the KDV system, based on our solution QUAD, for efficiently solving the real life problems in real-time.

If you have any problem about this work, please contact me (just call me Edison) via the following email addresses "edisonchan2013928@gmail.com", "tnchan@cs.hku.hk" or "tnchan2@hku.hk". For more details about my recent publications, please refer to this webpage "https://edisonchan2013928.github.io/My-homepage/".

[1] T. N. Chan, M. L. Yiu, and L. H. U. KARL: fast kernel aggregation queries. In ICDE, pages 542–553, 2019

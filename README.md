# scVMAD
This is the implementation of scVMAD


 By adopting a multi-view-multi-scale fusion approach, precisely  aligning features between different views, and implementing adaptive weighted fusion, it effectively overcomes the limitations of information bias inherent in single-view or single-scale analysis. This significantly enhances the ability to capture complex intercellular relationships, providing more comprehensive features for subsequent clustering analysis.
The proposed Multi-scale Cross-group Adaptive Collaborative Augmentation module (MCGA) integrates features from encoder/decoder layers with dual-view fusion representations across multiple scales. Simultaneously, it employs group-adaptive enhancement strategies to selectively strengthen distinct feature clusters, further improving the accuracy of cell clustering.
The improved adaptive fuzzy K-means clustering module dynamically learns robust reweighted distances and soft membership matrices to synergistically optimize centroids. This achieves precise beta cell subtype segmentation and enhances the biological interpretability of clustering results.
item The introduction of a joint constraint mechanism combining ZINB reconstruction, gating, and cross-view alignment loss guides the model toward learning more robust feature representations through multi-objective optimization, effectively enhancing the stability and reliability of clustering results.

Python --- 3.7.4

torch --- 1.13.1

scanpy --- 1.8.2

numpy --- 1.19.5

pandas --- 1.1.5

# Robust Low-rank Tensor Ring Completion


Low-rank tensor completion recovers missing entries based on different tensor decompositions. Due to its outstanding performance in exploiting some higher-order data structure, low rank tensor ring has been applied in tensor completion. To further deal with its sensitivity to sparse component as it does in tensor principle component analysis, we propose robust tensor ring completion (RTRC), which separates latent low-rank tensor component from sparse component with limited number of measurements. The low rank tensor component is constrained by the weighted sum of nuclear norms of its balanced unfoldings, while the sparse component is regularized by its l1 norm. We analyze the RTRC model and gives the exact recovery guarantee. The alternating direction method of multipliers is used to divide the problem into several sub-problems with fast solutions. In numerical experiments, we verify the recovery condition of the proposed method on synthetic data, and show the proposed method outperforms the state-of-the-art ones in terms of both accuracy and computational complexity in a number of real-world data based tasks, i.e., light-field image recovery, shadow removal in face images, and background extraction in color video.



Huyan Huang, Yipeng Liu, Zhen Long, Ce Zhu, "Robust Low-Rank Tensor Ring Completion," IEEE Transactions on Computational Imaging, vol. 6, pp. 1117-1126, 2020. 

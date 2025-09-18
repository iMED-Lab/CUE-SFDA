<span id="jump1"></span>
# CUE-SFDA
CUE-SFDA: Consistency-guided Uncertainty Estimation for Source-Free Medical Image Segmentation

Consistency-guided Uncertainty Estimation for Source-Free Medical Image Segmentation<br>

[Leilei Yuan](#jump1),  [Yuhui Ma](#jump1),  [Shaodong Ma](#jump1),  [Yitian Zhao](#jump1)<br> 

## Condensed Abstract

Pseudo-label self-training, which underpins most Source-Free Domain Adaptation (SFDA) methods, has garnered increasing attention in medical image segmentation due to its ability to iteratively improve pseudo-labels without requiring access to the original source data. However, this paradigm relies on two tenuous assumptions: that source models are trained on noise-free annotations, and that standard uncertainty measures can reliably detect all pseudo-label errors. In reality, medical labels often exhibit structural noise due to inter-observer variability, and common uncertainty estimators fail to identify high-confidence internal errors such as over-segmentations or anatomically implausible predictions. To address these challenges, we propose a novel two-stage SFDA framework that enhances pseudo-label quality through consistency-guided uncertainty estimation and structure-aware refinement. First, we use aggressively augmented and mixed views of target images to estimate prediction stability via Chebyshev’s inequality, automatically partitioning the target domain into high- and low-confidence subsets. Second, we apply tailored strategies for each subset: high-confidence images undergo instance-specific style normalization and are refined using affinity graphs with random walk propagation to improve structural coherence, while low-confidence images are regularized via multi-view consistency to encourage prediction stability. Extensive experiments on multiple datasets spanning three imaging modalities (color fundus photography, endoscopy, and MRI) demonstrate the superiority of our method over state-of-the-art approaches, even under significant domain shift and label noise. Our approach exhibits strong robustness and generalizability, making it well-suited for real-world clinical applications where annotation quality is variable. 

## The code is coming soon. 

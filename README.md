# PI-SDE： a physics-informed neural SDE network for learning cellular dynamics from time-series scRNA-seq data

**Authour**: Qi Jiang and Lin Wan
![Overview](./assets/overview.jpg)

Learning cellular dynamics through reconstruction of the underlying cellular potential energy landscape (aka Waddington landscape) from time-series single-cell RNA sequencing (scRNA-seq) data is a current challenge. Prevailing data-driven computational methods can be hampered by the lack of physical principles to guide learning from complex data, resulting in reduced prediction accuracy and interpretability when applied to infer cell population dynamics. Here, we propose PI-SDE, a physics-informed neural stochastic differential equation (SDE) framework that combines the Hamilton-Jacobi (HJ) equation and neural SDE to learn cellular dynamics. Grounded in potential energy theory of biological systems, PI-SDE integrates the principle of least action by enforcing the HJ equation when reconstructing cellular potential energy function. This approach not only facilitates accurate predictions, but also improves interpretability, especially in the reconstructed potential energy landscape. Through benchmarking on two real scRNA-seq datasets, we demonstrate the importance of incorporating the HJ regularization term in dynamic inference, especially in predicting gene expression at held-out time points. Meanwhile, the learned potential energy landscape provides biologically interpretable insights into the process of cell differentiation. 



# Datasets

# Experiments

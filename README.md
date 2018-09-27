# devdan
Autonomous Deep Learning: Incremental Learning of Denoising Autoencoder for Evolving Data Streams
Mahardhika Pratama, Andri Ashfahani, Yew Soon Ong, Savitha Ramasamy, Edwin Lughofer

Abstract

The generative learning phase of Autoencoder (AE) and its successor Denosing Autoencoder (DAE) enhances the flexibility of data stream method in exploiting unlabelled samples. Nonetheless, the feasibility of DAE for data stream analytic deserves in-depth study because it characterizes a fixed network capacity which cannot adapt to rapidly changing environments. An automated construction of a denoising autoeconder, namely deep evolving denoising autoencoder (DEVDAN), is proposed in this paper. DEVDAN features an open structure both in the generative phase and in the discriminative phase where input features can be automatically added and discarded on the fly. A network significance (NS) method is formulated in this paper and is derived from the bias-variance concept. This method is capable of estimating the statistical contribution of the network structure and its hidden units which precursors an ideal state to add or prune input features. Furthermore, DEVDAN is free of the problem- specific threshold and works fully in the single-pass learning fashion. The efficacy of DEVDAN is numerically validated using nine non-stationary data stream problems simulated under the prequential test-then-train protocol where DEVDAN is capable of delivering an improvement of classification accuracy to recently published online learning works while having flexibility in the automatic extraction of robust input features and in adapting to rapidly changing environments.

This has been submitted to AAAI 2019, the code will be published after it is accepted.

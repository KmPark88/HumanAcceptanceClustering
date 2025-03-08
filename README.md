# Design of Data Driven Automated Driving Control Algorithm for Enhanced Human Acceptance

This paper presents a data-driven automated driving control algorithm designed to enhance human acceptance in autonomous vehicles. To achieve this, we utilize an LSTM autoencoder to extract latent driving features from collected data, which are then clustered into lateral and longitudinal behaviors. These clustered behaviors serve as the foundation for generating steering and acceleration profiles, enabling the automated driving system to replicate individualized human driving styles. By incorporating three distinct driving behaviors, the proposed approach effectively mitigates potential sources of discomfort, such as excessive jerk and abrupt accelerations, ensuring a smoother ride experience. Additionally, we introduce a comprehensive ride quality evaluation metric that considers both trajectory similarity (trajectory score) and passenger comfort (comfort energy expression). The effectiveness of the proposed algorithm is validated through real-world vehicle tests, focusing on driving scenarios known to cause ride discomfort. Experimental results demonstrate that the automated driving control framework successfully enhances ride quality while adapting to individual passenger driving preferences, thus improving overall human acceptance of autonomous vehicles.

![Figure 1](Figures/fig.%201.png)
Fig. 1. Architecture of LSTM AutoEncoder

![Figure 1](Figures/Fig.%202.png)
Fig. 1. Architecture of LSTM AutoEncoder

# Design of Data Driven Automated Driving Control Algorithm for Enhanced Human Acceptance

This paper presents a data-driven automated driving control algorithm designed to enhance human acceptance in autonomous vehicles. To achieve this, we utilize an LSTM autoencoder to extract latent driving features from collected data, which are then clustered into lateral and longitudinal behaviors. These clustered behaviors serve as the foundation for generating steering and acceleration profiles, enabling the automated driving system to replicate individualized human driving styles. By incorporating three distinct driving behaviors, the proposed approach effectively mitigates potential sources of discomfort, such as excessive jerk and abrupt accelerations, ensuring a smoother ride experience. Additionally, we introduce a comprehensive ride quality evaluation metric that considers both trajectory similarity (trajectory score) and passenger comfort (comfort energy expression). The effectiveness of the proposed algorithm is validated through real-world vehicle tests, focusing on driving scenarios known to cause ride discomfort. Experimental results demonstrate that the automated driving control framework successfully enhances ride quality while adapting to individual passenger driving preferences, thus improving overall human acceptance of autonomous vehicles.

![Figure 1](Figures/fig.%201.png)
Fig. 1. Architecture of LSTM AutoEncoder

![Figure 2](Figures/Fig.%2022.png)
Fig. 2. To match trajectories T_1 and T_2, each point p_n^1 from T_1 is paired with the nearest point p_n^2 in T_2 based on Euclidean distance.

![Figure 3](Figures/Fig.%202.png)
Fig. 3. An example driving course for data collection in FMTC

![Figure 4](Figures/Fig.%2044.png)
Fig. 4. Test vehicle experimental setup

![Figure 5](Figures/Fig.%203.png)
Fig. 5. Feature extraction results - Driver 1 (Created by the authors)

![Figure 6](Figures/Fig.%204.png)
Fig. 6. Feature extraction results - Driver 2 (Created by the authors)

![Figure 7](Figures/Fig.%205.png)
Fig. 7. Feature extraction results - Expert driver (Created by the authors)

![Figure 8](Figures/Fig.%206.png)
Fig. 8. Longitudinal acceleration fitting function of expert driver (Created by the authors)

![Figure 9a](Figures/Fig.%207(a).png)
![Figure 9b](Figures/Fig.%207(b).png)
Fig. 9. Behavior transition strategy results: Longitudinal Acceleration (Created by the authors)

![Figure 10a](Figures/Fig.%208(a).png)
![Figure 10b](Figures/Fig.%208(b).png)
![Figure 10c](Figures/Fig.%208(c).png)
Fig. 10.  Comparison of Expert Driver's Manual Driving Data with AI Agent and Rule-Based Algorithm.

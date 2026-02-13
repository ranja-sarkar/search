💡 **Things I got to know in 2016**

<img width="122" height="97" alt="m1" src="https://github.com/user-attachments/assets/fae87d8f-3fe8-4b83-95c5-d309e0b1ac2c" />
<img width="88" height="54" alt="m2" src="https://github.com/user-attachments/assets/9c53b643-e784-4661-ab7a-d1e0d9493cc0" />


[Robetta](https://pmc.ncbi.nlm.nih.gov/articles/PMC441606/) is a tool that utilizes comparative modeling or *de novo* methods ([Rosetta](https://www.sciencedirect.com/science/chapter/bookseries/abs/pii/S0076687904830040?via%3Dihub)) to predict the structure of a protein. It was back in 2004 when the Robetta web service was available. 

The [newest version](https://robetta.bakerlab.org/) of Robetta uses a deep learning method called [RoseTTAFold](https://www.ipd.uw.edu/2021/07/rosettafold-accurate-protein-structure-prediction-accessible-to-all/), which arrived in [2021](https://www.science.org/doi/10.1126/science.abj8754) just after DeepMind published the [paper](https://www.nature.com/articles/s41586-021-03819-2?fromPaywallRec=false) titled 'Highly accurate protein structure prediction with AlphaFold'. 

Later in 2021, [AlphaFold2](https://pmc.ncbi.nlm.nih.gov/articles/PMC8592092/) was published by the research group at Georgia Institute of Technology, USA. The open-soucrce code for AlphaFold2 is available [here](https://github.com/google-deepmind/alphafold) and the high-level overview [here](https://www.ebi.ac.uk/training/online/courses/alphafold/inputs-and-outputs/a-high-level-overview/).

<img width="467" height="272" alt="af2" src="https://github.com/user-attachments/assets/a4f1492e-77f8-4827-87d1-74d3af50c8d1" />


But before this in [2018](https://www.nature.com/articles/s41598-018-24760-x), the paper about computationally designing proteins with deep learning neural networks was published. In this study, the neural network or deep learning approach was taken to design a protein for predicting the probability of 20 natural amino acids on each residue in it. 

<img width="592" height="173" alt="res" src="https://github.com/user-attachments/assets/e4257dee-d4ac-4daf-8167-44893276749a" />


# My work 

In 2016 and 2017, I had tried to design the full structure of human retinoblastoma (Rb) protein from parts, using Robetta. The linker (RbPL) between two domains A and B of this protein is highly dynamic and its structure was not known.	

<img width="486" height="314" alt="01" src="https://github.com/user-attachments/assets/2875e8d6-75bb-43de-9e77-0b5d6a494185" />
<img width="263" height="103" alt="02" src="https://github.com/user-attachments/assets/fcf4cfb3-7e3b-4b5b-a768-001a65055f50" />

I managed to model a full-length linker structure utilizing what was available then, like Robetta and [ITASSER](https://link.springer.com/article/10.1186/1471-2105-9-40).
The web service [ITASSER](https://aideepmed.com/I-TASSER/) is accessible since 2008. I could not publish my work though, there was not much I could do to validate and evaluate the predicted structures and arrive at the optimal one. 

<img width="308" height="96" alt="03" src="https://github.com/user-attachments/assets/b1b3755b-a505-4f84-8b9a-679665f57c13" />

In 2024, [AlphaFold3](https://www.nature.com/articles/s41586-024-07487-w) arrived with a substantially updated [diffusion-based architecture](https://www.ibm.com/think/topics/diffusion-models) that is capable of predicting the joint structure of complexes including proteins, nucleic acids, small molecules, ions and modified residues. And it is highly accurate. The [AlphaFold Server](https://alphafoldserver.com/welcome) is a web service made available to all by **Google Deepmind**, it is powered by the newest **AlphaFold3 model**.

In 2017, neither did I know much about [neural networks or deep learning](https://ranja-sarkar.github.io/2026/02/12/neural-network.html) nor did I have AlphaFold to use for prediction of the RbPL structure. Maybe, now is a good time to restart the work utilizing AlphaFold, or it might already have been published! 






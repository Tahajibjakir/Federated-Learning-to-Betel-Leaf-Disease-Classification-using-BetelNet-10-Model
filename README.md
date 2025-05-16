### A research paper on this project is about to be published. So, the code of the project has been kept hidden.

# Federated-Learning-to-Betel-Leaf-Disease-Classification-using-BetelNet-10-Model

This project, titled "Federated Learning to Betel Leaf Disease Analysis by BetelNet-10," aims to diagnose diseases in 
betel leaves and vines using a customized model called BetelNet-10. Unlike previous research, which focuses primarily on 
leaves, this work includes betel vines, broadening its scope and practical utility. This research proposes a federated 
learning framework to preserve data privacy while accurately classifying diseases in both betel leaves and vines. It aims 
to develop a robust model capable of learning from diverse morphological data, ensuring adaptability and reliability across
decentralized environments. The dataset, collected in Rajshahi, Bangladesh, consists of approximately 5,500 augmented 
images that have been labeled from 3000 raw images divided into five categories: Healthy Leaf, Healthy Betel Vine, Rot Disease, 
Spot Disease and Dried Leaf. Five client-specific datasets were preprocessed, visualized, and trained locally using 
federated learning, resulting in five unique BetelNet-10 models. These locally trained models were then aggregated at a 
global server, combining their weights to create a single global model, and the cycle of weight transfer between local 
and global environments continued three times. The global model was then evaluated on a test dataset, demonstrating its 
efficacy in disease detection. 

## Demo (Performance)
The UI has been designed by Gradio
![Image](https://github.com/user-attachments/assets/9147ddac-031a-4c45-94dd-c931b9cff9ab)



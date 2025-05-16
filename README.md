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

## Project Methodology Diagram
![Image](https://github.com/user-attachments/assets/1528283d-f6da-48a0-bac2-1b8641ee84e0)

## Features
🔒 Federated Learning Framework: Trains models on decentralized client data to ensure data privacy and security.

🧠 Custom BetelNet-10 Model: Lightweight CNN optimized for detecting diseases in both betel leaves and vines using variable kernel sizes.

🌿 Comprehensive Dataset: ~6,000 augmented images collected from real betel farms, categorized into 5 disease classes.

📱 Web & Mobile App Integration: Real-time disease prediction through an intuitive Gradio-based interface.

📈 High Accuracy: Achieves up to 99% accuracy on local models and 89% on the global model with strong generalization.

🧪 Robust Evaluation: Includes precision, recall, F1-score, confusion matrix, and comparative performance analysis.

🔄 Scalable Architecture: Easily extendable to more clients or different crops while preserving performance and privacy.

## Installation
Not allowed at this time.

## Model Details
![Image](https://github.com/user-attachments/assets/4f7b4760-062f-4c50-a806-294d110a3703)

## Contact / Credits
Developed by Tahajib Jakir Khan  
📧 tahajibjakirkhan00@gmail.com 
📎 [LinkedIn](https://www.linkedin.com/in/tahajib-jakir-khan-53b30822b/)
















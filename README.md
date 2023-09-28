# A Machine Learning Approach to assess the interlocutor's attention and understanding during robotic interactions

Computer Vision project on the implementation of a solution for an interlocutor's attention detection task in Human-Computer Interactions (HCI) and Human-Robot-Interaction (HRI). - AI for Visual Perception in HCI & HRI course at La Sapienza

## Collaborators
Caterina Borzillo, Federica Cocci

## Project details
We address the problem of interlocutor's attention and understanding when interacting with a robotic device. The domain of interest is the social robots industry, while both machine learning and image processing algorithms are applied. This project is a continuation and extension of the paper *"Human attention assessment using a machine learning approach with gan-based data augmentation technique trained using a custom dataset"*[^1].

### Brief introduction
Assessing interlocutor attention in social interactions is crucial for enhancing the quality of the communication, understanding human behavior and developing intelligent systems such as social robots. Attention detection, in fact, plays a vital role in various aspects of human life because it allows to establish strong, meaningful and effective communication. An attention detection system, in fact, finds applications in numerous real-life situations across different relevant domains such as in the Driver Monitoring, in the Education domain but also in Healthcare domains. 
To tackle this issue, in 2022 [^1] attempts to partially solve the problem of data scarcity by creating a large dataset for the attention recognition task: in particular they address the problem of attention detection based on the face orientation of users. In this paper, we worked to improve and to explore the core foundation of this project by starting from its fundamental elements and expanding it. Firstly, we have doubled our dataset for the task of classifying facial orientations, creating approximately 120k additional images containing 5 different face orientations. Secondly, we have studied and analyzed another problem concerning attention detection, specifically the analysis of attention based on eye orientation.

## Dataset
The custom dataset (120k images) of [^1] is available online, while the bigger dataset expanded by us (approximately 240k images) is currently not available online. 

[^1]: S. Pepe, S. Tedeschi, N. Brandizzi, S. Russo, L. Iocchi, C. Napoli, Human attention assessment using a machine learning approach with gan-based data augmentation technique trained using a custom dataset, OBM Neurobiology 6 (2022). doi: 10.21926/obm.neurobiol.2204139 
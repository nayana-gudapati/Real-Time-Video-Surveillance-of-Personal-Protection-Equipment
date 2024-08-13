In an industry, preserving worker safety is of essential significance. Personal protective equipment
(PPE) plays a key part in sustaining safety standards, yet monitoring and verifying its compliance
can prove to be difficult and time-consuming. This suggested system proposes a new solution: an
Automated Protective gear detection and monitoring system that not only fosters workplace safety
but also the compliance of the safety equipment and supervision. Leveraging cutting-edge
technology such as the YOLO (You Only Look Once) model, computer vision, and deep learning,
the system automates the identification and monitoring of personal protective equipment usage.
Furthermore, the implementation of an email notification system ensures that any identified
infractions are instantly communicated, permitting fast corrective measures. By adding the YOLO
paradigm, the system boosts its potential to recognize several personal protective equipment items
within a single picture, thereby simplifying compliance and monitoring. The system's flexibility
to shifting situations allows for the recognition of different forms.

The dataset used in this study serves as an integral part of the analysis and building of our
model. It was obtained by combining multiple images from various publicly available
datasets, mostly from Roboflow, an open repository known for its quality and relevance to
the research topic. The data set has a total of 11385 picture samples out of which 8458 or
74% are the training set, 1954 are part of the valid set and the remaining 972 images are part
of the test set. Each image has been annotated in a .yaml format to mark the different classes
present in the model. The given images are classified into 4 classes.
They are 
1. helmet
2. no-helmet
3. vest
4. no-vest

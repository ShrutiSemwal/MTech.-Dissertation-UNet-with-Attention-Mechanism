# MTech.-Dissertation-UNet-with-Attention-Mechanism

### This is the Mtech Dissertation work titled "Optimizing Green Building Implementation via Deep Learning Powered-Segmentation Techniques" contributed to the integration of green building domain and deep learning domain for sustainable development using AI.

### Problem Statement
The construction industry is a significant contributor to environmental degradation, and green buildings are a major solution. A building’s façade plays a key role in sustainability by improving air, look of the buildings, and usage of energy. However, traditional building tools lack precision, impacting sustainable building design efforts. My research work addresses this gap by using deep learning to accurately segment and analyze façade components for optimized green building designs. 

### Motivation
- This study is motivated by the growing need for durable and eco-friendly metropolitan places transformation. By focusing on building exteriors as promising green spaces, this research envisions transforming building components to support plants and greenery. Through deep learning, we can identify optimal areas on building for vegetation placement based on factors like sunlight and water availability. This approach has the potential to improve urban air quality, increase biodiversity, and promote healthier metropolitan living.
- Generally, green building evaluation tools are specially tailored for future building projects where all these criteria are followed from stage 1 itself. But what if a building is already built and we want to apply gb standards on those buildings? Therefore, my work is going to target that research area, where with the use of a deep learning model, we will be applying gb design on such buildings that can be beneficial in the field of structural planning.

#### Objectives:
Three objectives were defined for this thesis based on gaps identified with the help of comprehensive literature review.\
        1. *Create a robust UNet-based deep learning model accurate for building segmentation.*\
        2. *Enhance the dataset using some advanced pre-processing techniques like **binary mask splitting**, **data augmentation** and then further improve it by creating a new dataset using **canny edge detection algorithm**.*\
        3. *Implement Labelling section for the model to highlight 5 most relevant building components that are aligned with green building standards or integrating vegetation.*
#### Dataset:
The dataset that has been used for this thesis is [CMP FACADE DATASET](https://www.researchgate.net/profile/Radim-Tylecek-2/publication/267764713_CMP_Facade_Database/links/545a2e5e0cf26d5090ad70c2/CMP-Facade-Database.pdf). This dataset was further improved by creating a new dataset [CED DATASET](https://github.com/ShrutiSemwal/MTech.-Dissertation-UNet-with-Attention-Mechanism/tree/main/CED%20dataset) by employing canny edge detection on building images for edge clarity and using data augmentation techniques to increase its size and solve class imbalance.
#### Model:
Model has been defined using **UNet structure incorporating Spatial Multiplicative Cross Attention Mechanism**. Total 9 fits were implementated for model training. It was evaluated using Accuracy, Mean Intersection over Union, Precision, Recall and F1-Score. Predictions have been depicted in plots.

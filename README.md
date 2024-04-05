# Detection of Rice and Potato Plant Diseases Using Image Processing

## Abstract

Ensuring global food security requires innovative solutions for early detection and accurate classification of diseases in staple crops such as rice. This project presents an advanced approach for automated rice plant disease detection and classification by combining deep learning with metaheuristic optimization techniques. A deep dense neural network (DNN) is utilized for its ability to discern intricate patterns in images, while Extreme Learning Machine (ELM) is employed for classification purposes. To improve the optimization process, an innovative variant of the Shuffled Shepherd Optimization (SSO) algorithm, termed Enhanced Artificial Shuffled Shepherd Optimization (EASSO), is introduced. EASSO integrates adaptive strategies and enhanced exploration-exploitation mechanisms, facilitating more efficient convergence during DNN training.

The proposed system functions by analyzing high-resolution images of rice plants through the DNN, extracting subtle features indicative of various diseases like blast, bacterial blight, and brown spot. EASSO fine-tunes the DNN's parameters, maximizing its accuracy in disease classification. The synergy between DNN and EASSO ensures a robust and adaptable model capable of handling diverse and complex disease patterns. This automated approach reduces dependence on manual inspection, enabling timely intervention and enhancing overall agricultural productivity.

Experimental results demonstrate the superiority of the DNN-EASSO framework over traditional methods, exhibiting higher accuracy rates and faster convergence. The incorporation of Enhanced Artificial Shuffled Shepherd Optimization enhances the precision and reliability of disease classification, making this integrated system a valuable tool for farmers and agricultural practitioners. This research represents a significant step toward sustainable agriculture, showcasing the potential of advanced technologies in ensuring food security worldwide.

## Keywords

Optimization Algorithms, Precision Agriculture, Rice Plant, Disease Detection, EASSO, Agricultural Technology.

## Requirements
```
pip install notebook
pip install tensorflow
pip install matplotlib
```

## Use
Open the root directory in VS Code

### or
Open the root directory in Terminal and run
```
python -m notebook
```
![directory](https://user-images.githubusercontent.com/87483526/191987365-8cf52091-474e-499d-857f-31506056570c.png)

Open `training.ipynb` and hit `Run All` to train the model

Open `testing.ipynb` and hit `Run All` to test the model


## Update
Rice dataset has been added to `development` branch


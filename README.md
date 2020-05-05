# Image-Classifier-using-Deep-Learning
An image classifier build using Deep Learning based on the Transfer Learning model vgg16

### Requirements:
Python 3.7
Pytorch

### Usage

### Training
python3 train.py
--data_dir       "Directory of Dataset"
--save_dir       "Directory to Save the model checkpoint"
--arch           "Transfer Learning Model to Use"
--lr             "Learning Rate"
--epochs         "Epochs"
--hidden_layers  "No. of Hiddent Layers to use"
--gpu            "CUDA or CPU"

### Prediction
python3 predict.py
--inp_image     "Image to Predict"
--checkpoint    "Checkpoint file Directory i.e model"
--gpu           "CUDA OR CPU"
--json_class    "Labels in json"
--top_k         "Print the top k and probabilities i.e the prediction"

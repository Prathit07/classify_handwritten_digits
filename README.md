## classify_handwritten_digits
Build a CNN that classifies hand written digits 

### Architecture 
Input <-- CNN_1_BatchNorm_ReLU (8 feature maps) <-- MaxPool (8 feature maps) <-- CNN_2_BatchNorm_ReLU (32 fearture maps) <-- MaxPool (32 feature maps) <-- FC1 (600 neurons) <--FC2 (10 classes/output)

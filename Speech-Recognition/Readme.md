#### Speech Recognition Using DeepLearning

Download Dataset : <a href="https://github.com/Jakobovski/free-spoken-digit-dataset">Data</a>

### Simple Neural Networks
#### Step1: Data Preprocessing
Read the audio files (in .wav format), calculate the MFCC features for each file, flatten the (20,20) features to a 400 long array {This length is fixed for this data}. This is the input to the neural neural network.

#### Step2 : ANN architecture
* Input size = 400
* Layer input sizes : 400 (input) -> 256(1st layer) -> 128(2nd layer) -> 64(3rd layer) ->2 (output layer)
* Every layer has batch normalization and dropout enabled.

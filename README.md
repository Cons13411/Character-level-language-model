# Character-level-language-model
This is a simple character-level language model using GRU's cells. This model is developed using PyTorch and I use notebook to write the code so I can
evaluate and trace the inputs, step by step. 

The code is pretty strightforward. I first load the train and test data, preprocess them and then using pytorch.Dataset, I create a class to generate the batches
for the model. Then using torch.nn, I defined my network and its parameters. The rest is training, evaluating and at the end the prediction function. 


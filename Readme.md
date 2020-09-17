# Ask_It-assistant concept Using Transformer implemented in Tensorflow On Dataset Google's TASKMASTER-2

A dialogue model using  basic implementation of transformer at the core level.
The transformers from the paper "Attention is all you need" have been used here in tensorflow.The reference code is taken from https://medium.com/tensorflow/a-transformer-chatbot-tutorial-with-tensorflow-2-0-88bf59e66fe2 which uses the Cornell movie dataset. but this repo's aim was to see the feasibility of transformers for General purpose assistants so Google's Taskmaster dataset https://github.com/google-research-datasets/Taskmaster/tree/master/TM-2-2020 has been used to train the Ask_It. Since it was just for concept proving , it has been trained for 2 hours on Colab TPU .For production version more data and more training time is needed. For speech to text Gtts has been used. Also since colab doesnt capture your mic directly,javascript code has been implemented ,the reference of which can be found in Colab.

Would love to see the extension of this work by community.

!!Happy Coding

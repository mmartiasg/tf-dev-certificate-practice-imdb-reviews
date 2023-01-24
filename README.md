Experiments:
  - How does the number of words affect the algorithm's capacity to learn
  - Or maybe increasing or decreasing the max sequence has a negative impact at some point
  - Network size is better to have a bigger one. How will that overfit the dataset?
  - So far I'm using hot encoding I wonder if using a TF-IDF will help because I only have if that token appears or not but all of them weigh the same!
  - Maybe embeddings will make an improvement?
  - Another model like LSTM, GRU or Transformers could be better for this task and if that is how much better?
  - It is interesting to understand the power of the representation it is possible to achieve by increasing the size of the network o by some restrictions
  or increasing the limits of the inductive bias the model introduces by limiting the amount of data it sees at once, in cases such as fully connected layers or sequence models.

Implementation will be carried on 
 - Keras
 - Tensorflow 2
 - JAX
 - Pythorch

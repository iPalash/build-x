# Makemore 
### Source
- https://github.com/karpathy/makemore
- Part 1 : Counts
  - https://www.youtube.com/watch?v=PaCmpygFfXo&ab_channel=AndrejKarpathy
- Part 2: MLP
  - https://www.youtube.com/watch?v=TCH_1BHY58I&ab_channel=AndrejKarpathy
  - [ ] Read the linked paper
  - [ ] http://blog.ezyang.com/2019/05/pytorch-internals/
- Part 3: Activations, gradients and batch normalization
  - https://www.youtube.com/watch?v=P6sfmUTpUmc
  - Init impact on nn
    - Fixed softmax (logits) by making b2 zero and w2 smaller
    - Fixed tanh layer being too saturated b2 smaller and w2 smaller
  - batch normalization
    - stabilize deep NNs
  - Introduced pytorch like modules to stack up into NNs
  - Diagnosing the NN : activations, gradients , weights and learning rates
    - Focus on the update ratio to see if the LR is correct : should be around a 1000 times

## Objective
- "Make more" of what you give it
- Character-level language model
- Approaches
  - Bigram
  - Bag of words
  - MLP
## This folder will present my progress in learning how to write a Recurrent Neural Network from Scratch without external libraries
- This is intended on providing my future self with how I went about learning this topic
- Starting my journey with this article [Building RNN From Scratch] (https://medium.com/@thisislong/building-a-recurrent-neural-network-from-scratch-ba9b27a42856)

***

**First Let me start with "What is a RNN?"**

- Recurrent Neural Network

Think of an RNN like a human reading a book, one word at a time. Instead of forgetting previous words, it remembers what came before to understand the next word better.

Unlike normal neural networks, which process each input independently, an RNN loops past information back into itself, allowing it to make sense of sequences.

```
For example, if you read:
"The cat sat on the..."
Your brain expects "mat" because you remember the earlier words.

...but Mat was never mentioned in the previous words?

Exactly! But based on context, your brain predicts "mat" because you've seen similar sentences before. That's what an RNN does—it remembers past inputs to make better predictions about what comes next.

If you just gave a regular neural network the word "the", it wouldn't know what comes after. But an RNN remembers previous words like "The cat sat on the...", so it can make an educated guess that "mat" (or something similar) should come next.

It’s like having memory that helps understand sequences instead of looking at words (or numbers) one by one without context.
```

RNNs work the same way by keeping track of past words (or numbers in a sequence), they make better predictions for what comes next.



***Core Idea of an RNN***

An RNN (Recurrent Neural Network) is a type of neural network that remembers past inputs while processing new ones. Unlike traditional neural networks that handle inputs independently, RNNs cycle information through a loop, allowing them to process sequential data like text, speech, or time series.

***


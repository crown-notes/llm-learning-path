# Transformers

Foundation models are a type of `Large Language Model` that are pre-trained on massive text datasets and serve as the base for a wide range of language-related tasks. They are highly potent and versatile, capable of various tasks like question answering, text generation, and translation, and can be fine-tuned for specific applications. 

>[!NOTE]
> The terms "foundation model" and "LLM" are often used interchangeably but that "foundation model" can sometimes refer to a specific model that acts as a core for others.


Neural-networks and deep learning are the underlying technologies that power LLMs. Neural networks are computational models inspired by the human brain, composed of interconnected nodes organized in layers. Deep learning is defined as the use of neural networks with multiple hidden layers, enabling them to learn complex patterns.

The training process involving `forward-propagation` and `back-propagation.` Deep learning is a subfield of machine learning that utilizes these multi-layered networks for higher abstraction and feature learning, which is crucial for LLMs to process vast text data.

The transformer architecture is a revolutionary design in natural language processing that addressed limitations of previous sequential models. The key innovation of the Transformer is the `self-attention mechanism`, which allows the model to consider the entire context of a sentence or document simultaneously, capturing relationships between words regardless of their distance. 

- **Attention:** Focusing on important parts of a sentence.
- *Multi-head attention:** Looking at the sequence from multiple perspectives.
- *Encoder:** Processing the input sentence to create a representation.
-  **Decoder:** Generating the output sentence based on the encoded representation.
- *Self-attention:** Understanding relationships between words within the same sentence.
-  **Feed-forward neural network:** Applying transformations to the attention output.
-  **Positional encoding:** Understanding the order of words.
-  **Masking:** Preventing the model from seeing future words during training.

> [!NOTE]
>Transformer is a specific type of neural network architecture, while LLMs are a broader category of models that are often built upon the Transformer architecture. 




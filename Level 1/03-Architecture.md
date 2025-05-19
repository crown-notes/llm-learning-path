# LLM Architecture

Transfer learning is the process of using a pre-trained model as a starting point for a new task. Instead of training a new model from scratch, the pre-trained model's learned knowledge is transferred and then fine-tuned on a smaller, task-specific dataset. This is particularly beneficial when labeled data for the new task is limited.

`Adaptation`, also known as `domain adaptation`, is a related concept that specifically addresses differences between the data the model was initially trained on and the data for the new task. The goal of adaptation is to ensure the model performs well on the target domain despite these differences.

- Finding common features between the source and target domains.
- Giving more importance to data instances in the source domain that are similar to the target domain.
- Adjusting parts of the model to be more specific to the target domain.

In the context of LLMs, `fine-tuning` is described as an advanced form of adaptation. It takes a generally pre-trained LLM and specializes it for specific tasks, styles, personalities, or domain-specific knowledge using task-specific data.

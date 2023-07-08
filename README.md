## Introduction

According to [1] there are two types of Large Language Models (LLMs), Base LLM and Instruction Tune LLM.
* Base LLM: Trained to predict the next world, based on text training data
* Instruction Tune LLM: Trained to follow instructions

IT-LLMs are typically the result of a Base LLM that was **fine-tune with instructions** and "good attempts at following those instructions". These models are also refined with Reinforcement Learning by Human Feedback (RLHF), in order to make it better at follow those instructions. One Note is that big companies are more focus or have more capacity to develop B-LLMs and therefore, more practical applications are found in IT-LLMs.

### Best practices for IT-LLMs
As Andrew mentioned in [1], when using IT-LLMs we should think of giving instructions to another smart person. Many times when the answers are not good is because the instruction was NOT clear enough. Think that with IT-LLMs we can especify even the Tone of the output text, e.g. like a professional journalist would write, or like a casual note.

The course in [1] refers to two basic principles:
1. To write clear and specific instructions
In the course example, the model summarizes it like this: "To guide a model towards the desired output and reduce irrelevant or incorrect responses, it is important to provide clear and specific instructions, which can be achieved through longer prompts that offer more clarity and context."
2. Give the model time to think

As the fir

## References
1. **CHATGPT Prompt Engineering for Developers**, Andrew Ng, DeepLearning.AI; Isa Fulford, OpenAI.

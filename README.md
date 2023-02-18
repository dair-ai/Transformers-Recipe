# Transformer Recipe

![](/images/transformer.jpeg)

$$\operatorname{Attention}(Q, K, V)=\operatorname{softmax}\left(\frac{Q K^{T}}{\sqrt{d_{k}}}\right) V$$

Transformers have accelerated the development of new techniques and models for natural language processing (NLP) tasks. While it has mostly been used for NLP tasks, it is now seeing heavy adoption in other areas such as computer vision and reinforcement learning. That makes it one of the most important modern concepts to understand and be able to apply.

I am aware that a lot of machine learning and NLP students and practitioners are keen on learning about transformers. Therefore, I have prepared a study guide in the form of a list of resources and study materials to help guide students interested in learning about the world of Transformers.

To begin with, I have prepared a few links to materials that I used to better understand and implement transformer models from scratch.

## High-level Introduction
First, try to get a very high-level introduction about transformers. Some references worth looking at:

🔗 [Introduction to Transformer - Lecture Notes](https://www.notion.so/dair-ai/Introduction-to-Transformers-4b869c9595b74f72b088e5f2793ece80) (Elvis Saravia)

🔗 [Transformers From Scratch](https://e2eml.school/transformers.html) (Brandon Rohrer)

🔗 [How Transformers work in deep learning and NLP: an intuitive introduction](https://theaisummer.com/transformer/) (AI Summer)

🔗 [Stanford CS25 - Transformers United](https://www.youtube.com/playlist?list=PLoROMvodv4rNiJRchCzutFw5ItR_Z27CM)

🔗 [Deep Learning for Language Understanding](https://youtu.be/8zAP2qWAsKg) (DeepMind)

🔗 [Transformer models: an introduction and catalog](https://arxiv.org/abs/2302.07730v2) (Xavier Amatriain)

## The Transformer Explained
Jay Alammar's illustrated explanations are exceptional. Once you get that high-level understanding of transformers, you can jump into this popular detailed and illustrated explanation of transformers:

🔗 [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/)

This next article also breaks down Transformers into its components, explaining and illustrating in detail what each part does:

🔗 [Breaking Down the Transformer](https://aman.ai/primers/ai/transformers/)

## Technical Summary
At this point, you may be looking for a technical summary and overview of transformers. Lilian Weng's blog posts are a gem and provide concise technical explanations/summaries:

🔗 [The Transformer Family](https://lilianweng.github.io/lil-log/2020/04/07/the-transformer-family.html)

🔗 [The Transformer Family Version 2.0](https://lilianweng.github.io/posts/2023-01-27-the-transformer-family-v2/)

## Implementation
After the theory, it's important to test the knowledge. I typically prefer to understand things in more detail so I prefer to implement algorithms from scratch. For implementing transformers, I mainly relied on this tutorial:

🔗 [The Annotated Transformer](https://nlp.seas.harvard.edu/2018/04/03/attention.html) | ([Google Colab](https://colab.research.google.com/drive/1xQXSv6mtAOLXxEMi8RvaW8TW-7bvYBDF) | [GitHub](https://github.com/harvardnlp/annotated-transformer))

🔗 [Language Modeling with nn.Transformer and TorchText](https://pytorch.org/tutorials/beginner/transformer_tutorial.html)

If you are looking for in-depth implementations on some of the latest transformers, you might also find the Papers with Code methods [collection for Transformers](https://paperswithcode.com/methods/category/transformers) useful. 

## Attention Is All You Need
This paper by Vaswani et al. introduced the Transformer architecture. Read it after you have a high-level understanding and want to get into the details. Pay attention to other references in the paper for diving deep.

🔗 [Attention Is All You Need](https://arxiv.org/pdf/1706.03762v5.pdf)

## Applying Transformers
After some time studying and understanding the theory behind transformers, you may be interested in applying them to different NLP projects or research. At this time, your best bet is the Transformers library by HuggingFace.

🔗 [Transformers](https://github.com/huggingface/transformers)

The Hugging Face Team has also published a new book on NLP with Transformers, so you might want to check that out [here](https://www.oreilly.com/library/view/natural-language-processing/9781098103231/).

## Reading List on LLMs

As a bonus, here is a great reading list on LLMs by Sebastian Raschka. 

🔗 [Understanding Large Language Models -- A Transformative Reading List](https://github.com/huggingface/transformers)

---

Feel free to suggest study material. In the next update, I am looking to add a more comprehensive collection of Transformer applications and papers. In addition, a code implementation for easy experimentation is coming as well. Stay tuned!

*To get regular updates on new ML and NLP resources, [follow me on Twitter](https://twitter.com/omarsar0).*

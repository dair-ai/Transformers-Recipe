# Transformer Recipe

![](/images/transformer.jpeg)

Transformers have accelerated the development of new techniques and models for natural language processing (NLP) tasks. While it has mostly been used for NLP tasks, it is now seeing heavy adoption in other areas such as computer vision and reinforcement learning. That makes it one of the most important modern concepts to understand and be able to apply.

I am aware that a lot of machine learning and NLP students and practitioners are keen on learning about transformers. Therefore, I have prepared this recipe of resources and study materials to help guide students interested in learning about the world of Transformers.

To begin with, I have prepared a few links to materials that I used to better understand and implement transformer models from scratch.

## 🧠 High-level Introduction
First, try to get a very high-level introduction about transformers. Some references worth looking at:

🔗 [Transformers From Scratch](https://e2eml.school/transformers.html) (Brandon Rohrer)

🔗 [How Transformers work in deep learning and NLP: an intuitive introduction](https://theaisummer.com/transformer/) (AI Summer)

🔗 [Deep Learning for Language Understanding](https://youtu.be/8zAP2qWAsKg) (DeepMind)

## 🎨 The Illustrated Transformer
Jay Alammar's illustrated explanations are exceptional. Once you get that high-level understanding of transformers, you can jump into this popular detailed and illustrated explanation of transformers:

🔗 http://jalammar.github.io/illustrated-transformer/

![](/images/illustration.jpeg)

*Figure source: http://jalammar.github.io/illustrated-transformer/*

## 🔖 Technical Summary
At this point, you may be looking for a technical summary and overview of transformers. Lilian Weng's blog posts are a gem and provide concise technical explanations/summaries:

🔗 https://lilianweng.github.io/lil-log/2020/04/07/the-transformer-family.html

![](/images/math.png)

*Figure source: https://lilianweng.github.io/lil-log/2020/04/07/the-transformer-family.html*

## 👩🏼‍💻 Implementation
After the theory, it's important to test the knowledge. I typically prefer to understand things in more detail so I prefer to implement algorithms from scratch. For implementing transformers, I mainly relied on this tutorial:

🔗 https://nlp.seas.harvard.edu/2018/04/03/attention.html

([Google Colab](https://colab.research.google.com/drive/1xQXSv6mtAOLXxEMi8RvaW8TW-7bvYBDF) | [GitHub](https://github.com/harvardnlp/annotated-transformer))

![](/images/code.jpeg)

*Figure source: https://nlp.seas.harvard.edu/2018/04/03/attention.html*

If you are looking for in-depth implementations on some of the latest transformers, you might also find the Papers with Code methods [collection for Transformers](https://paperswithcode.com/methods/category/transformers) useful. 

## 📄 Attention Is All You Need
This paper by Vaswani et al. introduced the Transformer architecture. Read it after you have a high-level understanding and want to get into the details. Pay attention to other references in the paper for diving deep.

🔗 https://arxiv.org/pdf/1706.03762v5.pdf

![](/images/paper.jpeg)

*Figure source: https://arxiv.org/pdf/1706.03762v5.pdf*

## 👩🏼‍💻 Applying Transformers
After some time studying and understanding the theory behind transformers, you may be interested in applying them to different NLP projects or research. At this time, your best bet is the Transformers library by HuggingFace.

🔗 https://github.com/huggingface/transformers

![](/images/hf.jpeg)

The Hugging Face Team is also publishing a new book on NLP with Transformers, so you might want to check that out [here](https://www.oreilly.com/library/view/natural-language-processing/9781098103231/).

---

Feel free to suggest study material. In the next update, I am looking to add a more comprehensive collection of Transformer applications and papers. In addition, a code implementation for easy experimentation is coming as well. Stay tuned!

*To get regular updates on new ML and NLP resources, [follow me on Twitter](https://twitter.com/omarsar0).*

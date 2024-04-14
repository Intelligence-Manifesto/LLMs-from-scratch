# Build a Large Language Model (From Scratch)
# 从零开始构建一个大语言模型

---
## Fork from "Build A Large Language Model From Scratch" with Chinese Translation

\[ [English](README.md) | 中文 \]

## “从头构建大语言模型”项目的中文翻译分支
- 这个仓库是原始项目“从头构建大型语言模型”的一个分支，目的是提供中文翻译。请注意，这个分支旨在提供中文内容，以满足更广泛的受众需求。对于英文原始项目，请参考 [https://github.com/rasbt/LLMs-from-scratch](https://github.com/rasbt/LLMs-from-scratch)。
- This repository is a fork of the original project "Build A Large Language Model From Scratch," with the intention of providing a Chinese translation. Please note that this fork aims to offer the content in Chinese to cater to a broader audience. For the original project in English, please refer to the [https://github.com/rasbt/LLMs-from-scratch](https://github.com/rasbt/LLMs-from-scratch).

- 为了营造一个双语学习的环境，我将为本书提供完整的中文译本。在翻译的同时，还会根据个人理解适当添加注释，以帮助读者更好地理解和掌握内容。
- In order to create a bilingual learning environment, I will provide a complete Chinese translation for this book. During the translation, I will also add comments based on my personal understanding to help readers better comprehend and master the content.

- 如果文本顺序为先英文，后中文，则为原文翻译；先中文，后英文，则为译者后期注释。
- If the text order is English first, then Chinese, it will be the original text; if Chinese comes first, followed by English, then it will be translator's annotations later.

---

This repository contains the code for coding, pretraining, and finetuning a GPT-like LLM and is the official code repository for the book [Build a Large Language Model (From Scratch)](http://mng.bz/orYv).

该仓库包含了编码、预训练和微调类似GPT的大型语言模型(LLM)的代码，是书籍 [Build a Large Language Model (From Scratch)](http://mng.bz/orYv) 的官方代码仓库。

(If you downloaded the code bundle from the Manning website, please consider visiting the official code repository on GitHub at [https://github.com/rasbt/LLMs-from-scratch](https://github.com/rasbt/LLMs-from-scratch).)

如果您从曼宁网站下载了代码包，请考虑访问GitHub上的官方代码仓库 [https://github.com/rasbt/LLMs-from-scratch](https://github.com/rasbt/LLMs-from-scratch)。）
<br>
<br>

<a href="http://mng.bz/orYv"><img src="https://sebastianraschka.com/images/LLMs-from-scratch-images/cover.jpg" width="250px"></a>

In [*Build a Large Language Model (from Scratch)*](http://mng.bz/orYv), you'll discover how LLMs work from the inside out. In this book, I'll guide you step by step through creating your own LLM, explaining each stage with clear text, diagrams, and examples.

在 [*Build a Large Language Model (from Scratch)*](http://mng.bz/orYv) 中，你将从内到外了解LLMs的工作原理。在这本书中，我将一步一步指导你创建自己的LLM，每个阶段都会用清晰的文本、图表和示例进行解释。

The method described in this book for training and developing your own small-but-functional model for educational purposes mirrors the approach used in creating large-scale foundational models such as those behind ChatGPT.

本书中描述的训练和开发自己的小型但功能性模型的方法，用于教育目的，反映了创建大规模基础模型（如ChatGPT背后的模型）所使用的方法。

- Link to the official [source code repository](https://github.com/rasbt/LLMs-from-scratch)
- 官方[源代码仓库](https://github.com/rasbt/LLMs-from-scratch)链接

- [Link to the early access version](http://mng.bz/orYv) at Manning
- 曼宁[早期访问版本链接](http://mng.bz/orYv)

- ISBN 9781633437166
- ISBN 9781633437166

- Publication in Early 2025 (estimated)
- 预计2025年初出版

<br>
<br>


# Table of Contents

Please note that the `Readme.md` file is a Markdown (`.md`) file. If you have downloaded this code bundle from the Manning website and are viewing it on your local computer, I recommend using a Markdown editor or previewer for proper viewing. If you haven't installed a Markdown editor yet, [MarkText](https://www.marktext.cc) is a good free option.

请注意，`Readme.md` 文件是一个 Markdown（`.md`）文件。如果您已经从曼宁网站下载了这个代码包并在您的本地计算机上查看它，我推荐使用 Markdown 编辑器或预览器以便正确查看。如果您还没有安装 Markdown 编辑器，[MarkText](https://www.marktext.cc) 是一个不错的免费选择。

Alternatively, you can view this and other files on GitHub at [https://github.com/rasbt/LLMs-from-scratch](https://github.com/rasbt/LLMs-from-scratch).

或者，您也可以在 GitHub 上查看这个以及其他文件，网址为 [https://github.com/rasbt/LLMs-from-scratch](https://github.com/rasbt/LLMs-from-scratch)。

<br>
<br>

| Chapter Title                                  | Main Code (for quick access)                                                                                                    | All Code + Supplementary      |
|------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| Ch 1: Understanding Large Language Models      | No code                                                                                                                         | No code                       |
| Ch 2: Working with Text Data                   | - [ch02.ipynb](ch02/01_main-chapter-code/ch02.ipynb)<br/>- [dataloader.ipynb](ch02/01_main-chapter-code/dataloader.ipynb) (summary)<br/>- [exercise-solutions.ipynb](ch02/01_main-chapter-code/exercise-solutions.ipynb) | [./ch02](./ch02)              |
| Ch 3: Coding Attention Mechanisms              | - [ch03.ipynb](ch03/01_main-chapter-code/ch03.ipynb)<br/>- [multihead-attention.ipynb](ch03/01_main-chapter-code/multihead-attention.ipynb) (summary) | [./ch03](./ch03)              |
| Ch 4: Implementing a GPT Model from Scratch    | - [ch04.ipynb](ch04/01_main-chapter-code/ch04.ipynb)<br/>- [gpt.py](ch04/01_main-chapter-code/gpt.py) (summary) | [./ch04](./ch04)           |
| Ch 5: Pretraining on Unlabeled Data            | Q1 2024                                                                                                                         | ...                           |
| Ch 6: Finetuning for Text Classification       | Q2 2024                                                                                                                         | ...                           |
| Ch 7: Finetuning with Human Feedback           | Q2 2024                                                                                                                         | ...                           |
| Ch 8: Using Large Language Models in Practice  | Q2/3 2024                                                                                                                       | ...                           |
| Appendix A: Introduction to PyTorch*           | - [code-part1.ipynb](appendix-A/03_main-chapter-code/code-part1.ipynb)<br/>- [code-part2.ipynb](appendix-A/03_main-chapter-code/code-part2.ipynb)<br/>- [DDP-script.py](appendix-A/03_main-chapter-code/DDP-script.py)<br/>- [exercise-solutions.ipynb](appendix-A/03_main-chapter-code/exercise-solutions.ipynb) | [./appendix-A](./appendix-A) |

(* Please see [this](appendix-A/01_optional-python-setup-preferences) and [this](appendix-A/02_installing-python-libraries) folder if you need more guidance on installing Python and Python packages.)

（* 如果您需要更多关于安装 Python 和 Python packages 的指导，请查看 [这个](appendix-A/01_optional-python-setup-preferences) 和 [这个](appendix-A/02_installing-python-libraries) 文件夹。）


<br>
<br>

<img src="https://sebastianraschka.com/images/LLMs-from-scratch-images/mental-model.jpg" width="650px">

(A mental model summarizing the contents covered in this book.)

（一个总结本书内容的心智模型。）

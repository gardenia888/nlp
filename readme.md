### 常用链接
[李沐-论文精读系列](https://github.com/mli/paper-reading)

[教材：动手学深度学习](https://zh-v2.d2l.ai/)

[论文阅读：readpaper](https://readpaper.com/)

[论文阅读：paperswithcode](https://paperswithcode.com/sota)

### CCKS2022 TOP方案总结

[任务八：面向金融领域的Few-Shot事件抽取](ccks/tasks/task%208.md)

[任务十：面向金融领域的因果事件要素抽取](ccks/tasks/task%2010.md)

### MODELS

#### RNN

[代码实现](models/RNN/RNN.ipynb)

#### GRU

[模型介绍](models/GRU/GRU.md)

[代码实现](models/GRU/GRU.ipynb)

#### LSTM

[模型介绍](models/LSTM/LSTM.md)

[代码实现](models/LSTM/LSTM.ipynb)

#### seq2seq

[模型介绍](models/seq2seq/seq2seq.md)

[代码实现](models/seq2seq/seq2seq.ipynb)

#### Attention

[注意力机制介绍](models/Attention/Attention.md)

[注意力分数介绍](models/Attention/Attention%20Scoring.md)

[注意力分数代码实现](models/Attention/Attention%20Scoring.ipynb)

[带注意力机制的seq2seq介绍](models/Attention/Bahdanau.md)

[带注意力机制的seq2seq代码实现](models/Attention/Bahdanau.ipynb)

[自注意力机制介绍](models/Attention/Self-Attention.md)

#### Transformer

模型介绍

代码实现

#### BERT

模型介绍

代码实现

### 论文精读

Transformer(Attention Is All You Need)

BERT(Pre-training of Deep Bidirectional Transformers for Language Understanding)

GPT(Improving Language Understanding
by Generative Pre-Training)

GPT-2(Language Models are Unsupervised Multitask Learners)

GPT-3(Language Models are Few-Shot Learners)

#### Open-Domain Question Answering

##### Early QA work
1. [Answering English questions by computer: a survey](docs/simmons1965.pdf). R.F.Simmons. 1965
1. [The Structure and Performance of an Open-domain Question Answering System](https://www.aclweb.org/anthology/P00-1071.pdf). Dan Moldovan, Sanda Harabagiu, Marius Pasca, Rada Mihalcea, Roxana Girju, Richard Goodrum, Vasile Rus. ACL 2000
1. [An Analysis of the AskMSR Question-answering System](https://www.aclweb.org/anthology/W02-1033.pdf). Eric Brill, Susan Dumais and Michele Banko. EMNLP 2002.
1. [Open-Domain Question–Answering](https://wiki.eecs.yorku.ca/course_archive/2012-13/F/6328/_media/ibm-ai-qna.pdf). John Prage. 2007
1. [An Exploration of the Principles Underlying Redundancy-Based Factoid Question Answering](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.294.4576&rep=rep1&type=pdf). Jimmy Lin. 2007.
1. [Building Watson: An Overview of the DeepQA Project](https://www.aaai.org/ojs/index.php/aimagazine/article/view/2303/2165). David Ferrucci, Eric Brown, Jennifer Chu-Carroll et al. 2010

##### Recent work (2017+)
1. **[Reading Wikipedia to Answer Open-Domain Questions](https://arxiv.org/pdf/1704.00051.pdf). Danqi Chen, Adam Fisch, Jason Weston, Antoine Bordes. ACL 2017.**
1. **[R^3: Reinforced Reader-Ranker for Open-Domain Question Answering](https://arxiv.org/pdf/1709.00023.pdf).
Shuohang Wang, Mo Yu, Xiaoxiao Guo, Zhiguo Wang, Tim Klinger, Wei Zhang, Shiyu Chang, Gerald Tesauro, Bowen Zhou, Jing Jiang. AAAI 2018.**
1. [Evidence Aggregation for Answer Re-Ranking in Open-Domain Question Answering](https://arxiv.org/pdf/1711.05116.pdf).
Shuohang Wang, Mo Yu, Jing Jiang, Wei Zhang, Xiaoxiao Guo, Shiyu Chang, Zhiguo Wang, Tim Klinger, Gerald Tesauro, Murray Campbell. ICLR 2018.
1. [Denoising Distantly Supervised Open-domain Question Answering](https://www.aclweb.org/anthology/P18-1161.pdf). Yankai Lin, Haozhe Ji, Zhiyuan Liu, Maosong Sun. ACL 2018.
1. **[Open Domain Question Answering Using Early Fusion of Knowledge Bases and Text](https://www.aclweb.org/anthology/D18-1455.pdf). Haitian Sun, Bhuwan Dhingra, Manzil Zaheer, Kathryn Mazaitis, Ruslan Salakhutdinov, William Cohen. EMNLP 2018.**
1. [Language Models are Unsupervised Multitask Learners](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf). Alec Radford, Jeffrey Wu, Rewon Child, David Luan, Dario Amodei, Ilya Sutskever. OpenAI 2019.
1. [End-to-end Open-domain Question Answering with BERTserini](https://arxiv.org/pdf/1902.01718.pdf). Wei Yang, Yuqing Xie, Aileen Lin, Xingyu Li, Luchen Tan, Kun Xiong, Ming Li, Jimmy Lin. NAACL 2019 (demonstration).
1. **[Latent Retrieval for Weakly Supervised Open Domain Question Answering](https://www.aclweb.org/anthology/P19-1612.pdf). Kenton Lee, Ming-Wei Chang, Kristina Toutanova. ACL 2019.**
1. **[Real-Time Open-Domain Question Answering with Dense-Sparse Phrase Index](https://arxiv.org/pdf/1906.05807.pdf). Minjoon Seo, Jinhyuk Lee, Tom Kwiatkowski, Ankur P. Parikh, Ali Farhadi, Hannaneh Hajishirzi. ACL 2019.**
1. [Improving Question Answering over Incomplete KBs with Knowledge-Aware Reader](https://www.aclweb.org/anthology/P19-1417.pdf). Wenhan Xiong, Mo Yu, Shiyu Chang, Xiaoxiao Guo, William Yang Wang. ACL 2019.
1. [A Discrete Hard EM Approach for Weakly Supervised Question Answering](https://arxiv.org/pdf/1909.04849.pdf). Sewon Min, Danqi Chen, Hannaneh Hajishirzi, Luke Zettlemoyer. EMNLP 2019.
1. [Multi-passage BERT: A Globally Normalized BERT Model for Open-domain Question Answering](https://arxiv.org/pdf/1908.08167.pdf). Zhiguo Wang, Patrick Ng, Xiaofei Ma, Ramesh Nallapati, Bing Xiang. EMNLP 2019.
1. **[PullNet: Open Domain Question Answering with Iterative Retrieval on Knowledge Bases and Text](https://arxiv.org/pdf/1904.09537.pdf). Haitian Sun, Tania Bedrax-Weiss, William W. Cohen. EMNLP 2019.**
1. **[Knowledge Guided Text Retrieval and Reading for Open Domain Question Answering](https://arxiv.org/pdf/1911.03868.pdf). Sewon Min, Danqi Chen, Luke Zettlemoyer, Hannaneh Hajishirzi. arXiv 2019.**
1. [Contextualized Sparse Representations for Real-Time Open-Domain Question Answering](https://arxiv.org/pdf/1911.02896.pdf). Jinhyuk Lee, Minjoon Seo, Hannaneh Hajishirzi, Jaewoo Kang. ACL 2020.
1. [Learning to Retrieve Reasoning Paths over Wikipedia Graph for Question Answering](https://arxiv.org/pdf/1911.10470.pdf). Akari Asai, Kazuma Hashimoto, Hannaneh Hajishirzi, Richard Socher, Caiming Xiong. ICLR 2020.
1. **[REALM: Retrieval-Augmented Language Model Pre-Training](https://arxiv.org/pdf/2002.08909.pdf).
Kelvin Guu, Kenton Lee, Zora Tung, Panupong Pasupat, Ming-Wei Chang. ICML 2020.**
1. **[Dense Passage Retrieval for Open-Domain Question Answering](https://arxiv.org/pdf/2004.04906.pdf).
Vladimir Karpukhin, Barlas Oğuz, Sewon Min, Patrick Lewis, Ledell Wu, Sergey Edunov, Danqi Chen, Wen-tau Yih. EMNLP 2020.**
1. **[How Much Knowledge Can You Pack Into the Parameters of a Language Model?](https://arxiv.org/pdf/2002.08910.pdf). Adam Roberts, Colin Raffel, Noam Shazeer. EMNLP 2020.**
1. [Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks](https://arxiv.org/pdf/2005.11401.pdf). Patrick Lewis, Ethan Perez, Aleksandara Piktus, Fabio Petroni, Vladimir Karpukhin, Naman Goyal, Heinrich Küttler, Mike Lewis, Wen-tau Yih, Tim Rocktäschel, Sebastian Riedel, Douwe Kiela. NeurIPS 2020.
1. [Language Models are Few-Shot Learners](https://arxiv.org/pdf/2005.14165.pdf). Tom B. Brown, Benjamin Mann, Nick Ryder et al. NeurIPS 2020.
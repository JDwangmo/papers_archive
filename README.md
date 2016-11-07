# papers_archive
### archive some related papers of interests
> - general works
> - sentiment_analysis
> - math_basic
> - NN_basic




##### general works: including some basic knowledge about NLP, Image ...

1、Association for Computational Linguistics (ACL) papers collections: http://www.aclweb.org/anthology/

2、Advances in Neural Information Processing Systems (NIPS) papers collections: http://papers.nips.cc/

3、如何查找NLP文献： http://blog.sina.com.cn/s/blog_574a437f01019poo.html


##### sentiment_analysis : more detail about this domain in [here](https://github.com/JDwangmo/sentiment_classification)
1、[MGNC-CNN:A Simple Approach to Exploiting Multiple Word Embeddings for Sentence Classification](https://raw.githubusercontent.com/JDwangmo/papers_archive/master/sentiment_analysis/N16-1178-MGNC-CNN:A-Simple-Approach-to-Exploiting-Multiple-Word-Embeddings-for-Sentence-Classification.pdf)

2、[(Rotaru, University of Pittsburgh-Term project 2002)Dialog Act Tagging using Memory-Based Learning](https://raw.githubusercontent.com/JDwangmo/papers_archive/master/sentiment_analysis/Dialog-Act-Tagging-using-Memory-Based-Learning.pdf)


##### math_basic : 数学基础
1、[Calculus on Computational Graphs_ Backpropagation -- colah's blog](https://raw.githubusercontent.com/JDwangmo/papers_archive/master/math_basic/Calculus-on-Computational-Graphs_Backpropagation--colah's_blog.pdf):图的导数求导，讲的很详细。

##### NN_basic : 神经网络基础
- 1、[Recurrent Neural Networks Tutorial, Part 3 – Backpropagation Through Time and Vanishing Gradients – WildML](https://raw.githubusercontent.com/JDwangmo/papers_archive/master/NN_basic/Recurrent-Neural-Networks-Tutorial-Part-3–Backpropagation-Through-Time-and-Vanishing-Gradients–WildML.pdf)
    - RNN原理、梯度消失问题。
    - tanh derivative is  <1  for all inputs except 0; sigmoid is even worse and is always  ≤ 0.25.
    - more detail from [Wild's blog](http://www.wildml.com/2015/10/recurrent-neural-networks-tutorial-part-3-backpropagation-through-time-and-vanishing-gradients/)

- 2、[Understanding LSTM Networks -- colah's blog](https://raw.githubusercontent.com/JDwangmo/papers_archive/master/NN_basic/Understanding-LSTM-Networks--colah's-blog.pdf)
    - RNN，LSTM，原理讲得很详细，推荐LSTM入门文章。
    - 我们知道RNN有梯度消失的问题，即对很久时间前的更新很弱，也就是会忘记前面的上下文，所以 LSTM 提供的解决方法就是引入了一个“笔记本”（记忆单元）来记忆信息/state，这就是LSTM的核心。
    - [More](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)
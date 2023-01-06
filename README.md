# shallow-Q-learning

这个项目Fork自<[deep-q-learning](https://github.com/keon/deep-q-learning)>, 使用这个项目来了解Q-learning的原理和基于Python的简单实现。最初目的是为了完成一门Introduction课程<机器学习>的课程作业。

这是原项目的简要介绍
> Introduction to Making a Simple Game AI with Deep Reinforcement Learning

<p align = "center">
	<img alt="animation" src="./assets/animation.gif" height="300px" width="400px">
<br><br>
nothing...
<br><br>
</p>

`dqn.py`,`ddqn.py`,`dqn_batch.py`是原作者的文件,我将在`ipynb`重新完成它。

以下是该项目的原文档
---
Minimal and Simple Deep Q Learning Implemenation in Keras and Gym. Under 100 lines of code!

The explanation for the `dqn.py` code is covered in the blog article
[https://keon.io/deep-q-learning/](https://keon.io/deep-q-learning/)

I made minor tweaks to this repository such as `load` and `save` functions for convenience.

I also made the `memory` a deque instead of just a list.
This is in order to limit the maximum number of elements in the memory.


The training might be unstable for `dqn.py`. This problem is mitigated in `ddqn.py`.
I'll cover `ddqn` in the next article.

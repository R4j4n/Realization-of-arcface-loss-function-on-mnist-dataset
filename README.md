# Realization of arcface loss function on mnist dataset


[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)

[![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1zI2dFgxwWqFba8DdHu-i5_7TqNu-NSbZ?usp=sharing)

Arcface loss is a loss function in face recognition. For face recognition, there is also a commonly used loss function centerloss, but centerloss has a relatively large defect, that is, when there are more categories, GPU memory requirements are relatively high, which is more expensive. And the effect of arcface loss is better than centerloss, becauseThe former is based on angle, while the latter is based on distance,For classification, the impact of arcfaceloss is more direct.



![Alt Text](visulization.gif) <br>

![Alt Text](lf.png) <br>
![Alt Text](newplot.png) <br>


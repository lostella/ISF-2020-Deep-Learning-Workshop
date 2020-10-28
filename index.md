---
layout: default
---

**Thursday, October 29th, 2020** <br>
**19:00–22:00 GMT** <br>
**Chime ID: 6165 55 7960**

In this virtual workshop, we aim at covering neural forecasting methods from the ground up, starting from the very basics of deep learning up to recent forecasting model improvements such as [5].
Given that the workshop is fully virtual, we will primarily rely on lectures.
In these, we will focus on the fundamentals of deep learning such as the various architecture types (e.g. feed-forward, convolutional and recurrent neural networks) and the most important breakthroughs that established the strength of neural networks.
Then, we will see how deep learning can be applied to forecasting by reviewing several state-of-the-art neural forecasting models (e.g., WaveNet [8], DeepAR [6], NBEATS [3] and the sequence-to-sequence model family [7, 10]).
Furthermore, we will dive into recent work that combines neural networks with probabilistic models such as deep state space [4] and deep factor [9] models, and bayesian techniques such as [2].
Finally, we will introduce GluonTS [1], a time series modelling toolkit primarily aimed at forecasting which is available as open source.
To complement the lectures, we will provide notebooks for the workshop participants to interactively explore some of these ideas themselves.
Given that the workshop is virtual, this will be self-study largely.
Notebooks will rely on GluonTS [1].

## Presenters

<p><img align="left" src="./assets/img/januschowski.jpeg" style="padding-right: 15px; padding-top: 5px;"/>
<b>Tim Januschowski</b> is a Machine Learning Science Manager in Amazon AI Labs. He has worked on forecasting since starting his professional career. At Amazon, he has produced end-to-end solutions for a wide variety of forecasting problems, from demand forecasting to server capacity forecasting. Tim’s personal interests in forecasting span applications, system, algorithm and modeling aspects and the downstream mathematical programming problems. He studied Mathematics at TU Berlin, IMPA, Rio de Janeiro, and Zuse-Institute Berlin and holds a PhD from University College Cork.
</p>

<p><img align="left" src="./assets/img/stella.jpeg" style="padding-right: 15px; padding-top: 5px;"/>
<b>Lorenzo Stella</b> is an Applied Scientist at Amazon AI Labs, where he works on deep learning architectures for forecasting models, and their application to a variety of business problems. He is one of the core developers of GluonTS, and his scientific interests include mathematical programming problems and numerical optimization algorithms. He studied Computer Science at the University of Florence, and holds a PhD from IMT School for Advanced Studies Lucca (Italy) and KU Leuven (Belgium).
</p>

## Schedule

* time: description
* time: description
* time: description

## Material

TBD -- links to the workshop material will be added in this section.

## Pre-requisites

This workshop is appropriate for anyone with a solid programming background and a general interest in neural networks. Prior knowledge in neural networks is recommended but not necessary.
Knowledge of forecasting, basic statistical and machine learning knowledge are a pre-requistite.
For the practical material, Python programming knowledge is essential.

The hands-on segment of the workshop will require Jupyter to be installed, with a Python 3.6 or 3.7 kernel.
The required packages are installed with the following commands (this may vary depending on your OS and Python distribution).

```
pip install --upgrade mxnet==1.6.0 torch==1.6.0
pip install git+https://github.com/awslabs/gluon-ts.git
```

## References

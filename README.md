# Fundamentals of Deep Learning (MADE S02E02)
This repository contains notebooks for the Fundamentals of Deep Learning course.

**Tip #1:**

Loading the entire repository can take a considerable amount of time. A single folder can be downloaded via [DownGit](https://downgit.github.io/).

**Tip #2:**

Sometimes GitHub failes to render a notebook. In that case use [nbviewer](https://nbviewer.jupyter.org/) — it works like a charm!

**Tip #3:**

In those cases when *nbviewer* fails to find a notebook whereas GitHub finds it just fine, try to add `?flush_cache=false` at the end of the *nbviewer* link.

### Lectures

Legend: ![](./icons/pdf.png) — slides, ![](./icons/jupyter.png) — code, ![](./icons/youtube.png) — video.

Week | What | Where | When
:--: | :--: | :---: | :--:
[1](https://data.mail.ru/curriculum/program/lesson/16355/) | Введение в глубокое обучение: нейрон, перекрёстная энтропия, градиентный спуск, Numpy, логистическая регрессия. | [![](./icons/pdf.png)](https://github.com/Illumaria/made-deep-learning/blob/master/01-intro-dl-logreg/01_intro_dl_logreg.pdf) [![](./icons/jupyter.png)](https://nbviewer.jupyter.org/github/Illumaria/made-deep-learning/blob/master/01-intro-dl-logreg/01_numpy.ipynb) [![](./icons/jupyter.png)](https://nbviewer.jupyter.org/github/Illumaria/made-deep-learning/blob/master/01-intro-dl-logreg/01_logreg.ipynb) [![](./icons/youtube.png)](https://youtu.be/WiFQF8sTxko) | 20.01.2021
[2](https://data.mail.ru/curriculum/program/lesson/16356/) | Полносвязные сети, метод обратного распространения ошибки, стохастический градиентный спуск, производные по матрицам. | [![](./icons/pdf.png)](https://github.com/Illumaria/made-deep-learning/blob/master/02-fc-nets-backprop/02_fc_nets_backprop.pdf) [![](./icons/jupyter.png)](https://nbviewer.jupyter.org/github/Illumaria/made-deep-learning/blob/master/02-fc-nets-backprop/02_fc_nets_backprop.ipynb) [![](./icons/youtube.png)](https://youtu.be/OUsKEHaOLtE) | 27.01.2021
[3](https://data.mail.ru/curriculum/program/lesson/16357/) | Особенности и методы оптимизации в глубоком обучении, методы регуляризации, transfer learning. Основы PyTorch. | [![](./icons/pdf.png)](https://github.com/Illumaria/made-deep-learning/blob/master/03-optimization/03_optimization.pdf) [![](./icons/jupyter.png)](https://nbviewer.jupyter.org/github/Illumaria/made-deep-learning/blob/master/03-optimization/03_pytorch_workshop.ipynb) [![](./icons/youtube.png)](https://youtu.be/D_gZEeTw_m8) | 03.02.2021
[4](https://data.mail.ru/curriculum/program/lesson/16358/) | Свёртки и свёрточные нейронные сети. CNN в PyTorch. | [![](./icons/pdf.png)](https://github.com/Illumaria/made-deep-learning/blob/master/04-convolutional-networks/04_convolutional_networks.pdf) [![](./icons/jupyter.png)](https://nbviewer.jupyter.org/github/Illumaria/made-deep-learning/blob/master/04-convolutional-networks/04_convolutional_networks.ipynb) [![](./icons/youtube.png)](https://youtu.be/alHypNTzFfE) | 10.02.2021
[5](https://data.mail.ru/curriculum/program/lesson/16359/) | Процесс разработки в ML, разбиение данных, компромисс отклонение-дисперсия, метрики, ускорение моделей, квантование сетей, QAT. PyTorch Lightning, Optuna. | [![](./icons/pdf.png)](https://github.com/Illumaria/made-deep-learning/blob/master/05-recap-speedup-hopt/05_recap_speedup_hopt.pdf) [![](./icons/jupyter.png)](https://nbviewer.jupyter.org/github/Illumaria/made-deep-learning/blob/master/05-recap-speedup-hopt/05_testset_size_evaluation.ipynb) [![](./icons/jupyter.png)](https://nbviewer.jupyter.org/github/Illumaria/made-deep-learning/blob/master/05-recap-speedup-hopt/05_lightning_optuna.ipynb) [![](./icons/youtube.png)](https://youtu.be/iFJ7wfq0BuM) | 17.02.2021
[6](https://data.mail.ru/curriculum/program/lesson/16360/) | Языковые модели, рекуррентные архитектуры, работа с памятью. Применение RNN для генерации имён. | [![](./icons/pdf.png)](https://github.com/Illumaria/made-deep-learning/blob/master/06-recurrent-networks/06_language_models_and_rnn.pdf) [![](./icons/jupyter.png)](https://nbviewer.jupyter.org/github/Illumaria/made-deep-learning/blob/master/06-recurrent-networks/06_rnn_practice.ipynb) [![](./icons/youtube.png)](https://youtu.be/fYSeSeVGFpk) | 25.02.2021
[7](https://data.mail.ru/curriculum/program/lesson/17623/) | Повторение основных методов и подходов в глубоком обучении, а также основ PyTorch. | [![](./icons/pdf.png)](https://github.com/Illumaria/made-deep-learning/blob/master/07-general-recap/07_general_recap.pdf) [![](./icons/jupyter.png)](https://nbviewer.jupyter.org/github/Illumaria/made-deep-learning/blob/master/07-general-recap/07_pytorch_recap.ipynb?flush_cache=false) [![](./icons/youtube.png)](https://youtu.be/tn5aEG9SFBQ) | 03.03.2021

Additional materials on the topic of recurrent neural networks:
* [What Every Computer Scientist Should Know About Floating-Point Arithmetic](https://docs.oracle.com/cd/E19957-01/806-3568/ncg_goldberg.html)
* [Understanding LSTMs](http://colah.github.io/posts/2015-08-Understanding-LSTMs/) (by Christopher Olah)
* [The Unreasonable Effectiveness of Recurrent Neural Networks](http://karpathy.github.io/2015/05/21/rnn-effectiveness/) (by Andrej Karpathy)
<!-- markdownlint-disable -->
<h1 align="center">
    Best-of Machine Learning with Python
    <br>
</h1>

<p align="center">
    <strong>🏆&nbsp; A ranked list of awesome machine learning Python libraries. Updated weekly.</strong>
</p>

<p align="center">
    <a href="https://github.com/ml-tooling/best-of" title="Best-of-badge"><img src="http://bit.ly/3o3EHNN"></a>
    <a href="#Contents" title="Project Count"><img src="https://img.shields.io/badge/projects-920-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="Contributions are welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/ml-tooling/best-of-ml-python/releases" title="Best-of Updates"><img src="https://img.shields.io/github/release-date/ml-tooling/best-of-ml-python?color=green&label=updated"></a>
    <a href="https://mltooling.substack.com/subscribe" title="Subscribe to newsletter"><img src="http://bit.ly/2Md9rxM"></a>
    <a href="https://twitter.com/mltooling" title="Follow on Twitter"><img src="https://img.shields.io/twitter/follow/mltooling.svg?style=social&label=Follow"></a>
</p>

This curated list contains 920 awesome open-source projects with a total of 3.3M stars grouped into 34 categories. All projects are ranked by a project-quality score, which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/ml-tooling/best-of-ml-python/issues/new/choose), submit a [pull request](https://github.com/ml-tooling/best-of-ml-python/pulls), or directly edit the [projects.yaml](https://github.com/ml-tooling/best-of-ml-python/edit/main/projects.yaml). Contributions are very welcome!

---

<p align="center">
     🧙‍♂️&nbsp; Discover other <a href="https://best-of.org">best-of lists</a> or create <a href="https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md">your own</a>.<br>
    📫&nbsp; Subscribe to our <a href="https://mltooling.substack.com/subscribe">newsletter</a> for updates and trending projects.
</p>

---


## Contents

- [Machine Learning Frameworks](#machine-learning-frameworks) _55 projects_
- [Data Visualization](#data-visualization) _50 projects_
- [Text Data & NLP](#text-data--nlp) _96 projects_
- [Image Data](#image-data) _60 projects_
- [Graph Data](#graph-data) _36 projects_
- [Audio Data](#audio-data) _28 projects_
- [Geospatial Data](#geospatial-data) _22 projects_
- [Financial Data](#financial-data) _25 projects_
- [Time Series Data](#time-series-data) _23 projects_
- [Medical Data](#medical-data) _19 projects_
- [Tabular Data](#tabular-data) _4 projects_
- [Optical Character Recognition](#optical-character-recognition) _11 projects_
- [Data Containers & Structures](#data-containers--structures) _31 projects_
- [Data Loading & Extraction](#data-loading--extraction) _1 projects_
- [Web Scraping & Crawling](#web-scraping--crawling) _1 projects_
- [Data Pipelines & Streaming](#data-pipelines--streaming) _43 projects_
- [Distributed Machine Learning](#distributed-machine-learning) _32 projects_
- [Hyperparameter Optimization & AutoML](#hyperparameter-optimization--automl) _47 projects_
- [Reinforcement Learning](#reinforcement-learning) _23 projects_
- [Recommender Systems](#recommender-systems) _15 projects_
- [Privacy Machine Learning](#privacy-machine-learning) _6 projects_
- [Workflow & Experiment Tracking](#workflow--experiment-tracking) _38 projects_
- [Model Serialization & Deployment](#model-serialization--deployment) _15 projects_
- [Model Interpretability](#model-interpretability) _50 projects_
- [Vector Similarity Search (ANN)](#vector-similarity-search-ann) _12 projects_
- [Probabilistics & Statistics](#probabilistics--statistics) _22 projects_
- [Adversarial Robustness](#adversarial-robustness) _9 projects_
- [GPU Utilities](#gpu-utilities) _19 projects_
- [Tensorflow Utilities](#tensorflow-utilities) _15 projects_
- [Jax Utilities](#jax-utilities) _2 projects_
- [Sklearn Utilities](#sklearn-utilities) _17 projects_
- [Pytorch Utilities](#pytorch-utilities) _32 projects_
- [Database Clients](#database-clients) _1 projects_
- [Others](#others) _60 projects_

## Explanation
- 🥇🥈🥉&nbsp; Combined project-quality score
- ⭐️&nbsp; Star count from GitHub
- 🐣&nbsp; New project _(less than 6 months old)_
- 💤&nbsp; Inactive project _(6 months no activity)_
- 💀&nbsp; Dead project _(12 months no activity)_
- 📈📉&nbsp; Project is trending up or down
- ➕&nbsp; Project was recently added
- ❗️&nbsp; Warning _(e.g. missing/risky license)_
- 👨‍💻&nbsp; Contributors count from GitHub
- 🔀&nbsp; Fork count from GitHub
- 📋&nbsp; Issue count from GitHub
- ⏱️&nbsp; Last update timestamp on package manager
- 📥&nbsp; Download count from package manager
- 📦&nbsp; Number of dependent projects
- <img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13">&nbsp; Tensorflow related project
- <img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13">&nbsp; Sklearn related project
- <img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13">&nbsp; PyTorch related project
- <img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13">&nbsp; MxNet related project
- <img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13">&nbsp; Apache Spark related project
- <img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13">&nbsp; Jupyter related project
- <img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13">&nbsp; PaddlePaddle related project
- <img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13">&nbsp; Pandas related project
- <img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13">&nbsp; Jax related project

<br>

## Machine Learning Frameworks

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_General-purpose machine learning and deep learning frameworks._

<details><summary><b><a href="https://github.com/tensorflow/tensorflow">Tensorflow</a></b> (🥇55 ·  ⭐ 160K) - An Open Source Machine Learning Framework for Everyone. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tensorflow) (👨‍💻 3.9K · 🔀 86K · 📦 180K · 📋 34K - 7% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/tensorflow/tensorflow
	```
- [PyPi](https://pypi.org/project/tensorflow) (📥 17M / month · 📦 14K · ⏱️ 02.02.2022):
	```
	pip install tensorflow
	```
- [Conda](https://anaconda.org/conda-forge/tensorflow) (📥 3M · ⏱️ 06.02.2022):
	```
	conda install -c conda-forge tensorflow
	```
- [Docker Hub](https://hub.docker.com/r/tensorflow/tensorflow) (📥 64M · ⭐ 2K · ⏱️ 10.02.2022):
	```
	docker pull tensorflow/tensorflow
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn/scikit-learn">scikit-learn</a></b> (🥇50 ·  ⭐ 49K) - scikit-learn: machine learning in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn/scikit-learn) (👨‍💻 2.5K · 🔀 22K · 📥 770 · 📦 310K · 📋 10K - 24% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/scikit-learn/scikit-learn
	```
- [PyPi](https://pypi.org/project/scikit-learn) (📥 27M / month · 📦 24K · ⏱️ 25.12.2021):
	```
	pip install scikit-learn
	```
- [Conda](https://anaconda.org/conda-forge/scikit-learn) (📥 11M · ⏱️ 26.12.2021):
	```
	conda install -c conda-forge scikit-learn
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/pytorch">PyTorch</a></b> (🥇49 ·  ⭐ 54K) - Tensors and Dynamic neural networks in Python with strong GPU.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/pytorch) (👨‍💻 3.1K · 🔀 15K · 📥 1.7K · 📋 28K - 40% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/pytorch/pytorch
	```
- [PyPi](https://pypi.org/project/torch) (📥 6M / month · 📦 6.8K · ⏱️ 27.01.2022):
	```
	pip install torch
	```
- [Conda](https://anaconda.org/pytorch/pytorch) (📥 15M · ⏱️ 27.01.2022):
	```
	conda install -c pytorch pytorch
	```
</details>
<details><summary><b><a href="https://github.com/keras-team/keras">Keras</a></b> (🥇44 ·  ⭐ 54K) - Deep Learning for humans. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/keras-team/keras) (👨‍💻 1K · 🔀 19K · 📋 11K - 2% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/keras-team/keras
	```
- [PyPi](https://pypi.org/project/keras) (📥 8.1M / month · 📦 220 · ⏱️ 31.01.2022):
	```
	pip install keras
	```
- [Conda](https://anaconda.org/conda-forge/keras) (📥 2M · ⏱️ 04.02.2022):
	```
	conda install -c conda-forge keras
	```
</details>
<details><summary><b><a href="https://github.com/dmlc/xgboost">XGBoost</a></b> (🥇44 ·  ⭐ 22K) - Scalable, Portable and Distributed Gradient Boosting (GBDT, GBRT or.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dmlc/xgboost) (👨‍💻 550 · 🔀 8.3K · 📥 3.7K · 📦 27K · 📋 4.3K - 6% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/dmlc/xgboost
	```
- [PyPi](https://pypi.org/project/xgboost) (📥 8.5M / month · 📦 1.3K · ⏱️ 17.01.2022):
	```
	pip install xgboost
	```
- [Conda](https://anaconda.org/conda-forge/xgboost) (📥 2.3M · ⏱️ 26.01.2022):
	```
	conda install -c conda-forge xgboost
	```
</details>
<details><summary><b><a href="https://github.com/statsmodels/statsmodels">StatsModels</a></b> (🥇44 ·  ⭐ 7.1K) - Statsmodels: statistical modeling and econometrics in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/statsmodels/statsmodels) (👨‍💻 360 · 🔀 2.4K · 📥 26 · 📦 57K · 📋 4.8K - 47% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/statsmodels/statsmodels
	```
- [PyPi](https://pypi.org/project/statsmodels) (📥 7.5M / month · 📦 4.5K · ⏱️ 08.02.2022):
	```
	pip install statsmodels
	```
- [Conda](https://anaconda.org/conda-forge/statsmodels) (📥 5.6M · ⏱️ 13.11.2021):
	```
	conda install -c conda-forge statsmodels
	```
</details>
<details><summary><b><a href="https://github.com/apache/spark">PySpark</a></b> (🥈42 ·  ⭐ 32K) - Apache Spark Python API. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/apache/spark) (👨‍💻 2.6K · 🔀 25K · ⏱️ 10.02.2022):

	```
	git clone https://github.com/apache/spark
	```
- [PyPi](https://pypi.org/project/pyspark) (📥 17M / month · 📦 760 · ⏱️ 26.01.2022):
	```
	pip install pyspark
	```
- [Conda](https://anaconda.org/conda-forge/pyspark) (📥 1.5M · ⏱️ 26.01.2022):
	```
	conda install -c conda-forge pyspark
	```
</details>
<details><summary><b><a href="https://github.com/PyTorchLightning/pytorch-lightning">pytorch-lightning</a></b> (🥈42 ·  ⭐ 17K) - The lightweight PyTorch wrapper for high-performance.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyTorchLightning/pytorch-lightning) (👨‍💻 620 · 🔀 2.2K · 📥 5.4K · 📦 6.8K · 📋 4.6K - 10% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/PyTorchLightning/pytorch-lightning
	```
- [PyPi](https://pypi.org/project/pytorch-lightning) (📥 1.1M / month · 📦 310 · ⏱️ 09.02.2022):
	```
	pip install pytorch-lightning
	```
- [Conda](https://anaconda.org/conda-forge/pytorch-lightning) (📥 390K · ⏱️ 21.01.2022):
	```
	conda install -c conda-forge pytorch-lightning
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/LightGBM">LightGBM</a></b> (🥈42 ·  ⭐ 13K) - A fast, distributed, high performance gradient boosting (GBT, GBDT, GBRT,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/LightGBM) (👨‍💻 250 · 🔀 3.5K · 📥 140K · 📦 11K · 📋 2.5K - 6% open · ⏱️ 01.02.2022):

	```
	git clone https://github.com/microsoft/LightGBM
	```
- [PyPi](https://pypi.org/project/lightgbm) (📥 9.7M / month · 📦 580 · ⏱️ 07.01.2022):
	```
	pip install lightgbm
	```
- [Conda](https://anaconda.org/conda-forge/lightgbm) (📥 890K · ⏱️ 08.01.2022):
	```
	conda install -c conda-forge lightgbm
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/Paddle">PaddlePaddle</a></b> (🥈41 ·  ⭐ 18K) - PArallel Distributed Deep LEarning: Machine Learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/Paddle) (👨‍💻 700 · 🔀 4.3K · 📥 15K · 📦 91 · 📋 15K - 18% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/PaddlePaddle/Paddle
	```
- [PyPi](https://pypi.org/project/paddlepaddle) (📥 100K / month · 📦 44 · ⏱️ 20.01.2022):
	```
	pip install paddlepaddle
	```
</details>
<details><summary><b><a href="https://github.com/catboost/catboost">Catboost</a></b> (🥈41 ·  ⭐ 6.3K) - A fast, scalable, high performance Gradient Boosting on Decision.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/catboost/catboost) (👨‍💻 950 · 🔀 950 · 📥 74K · 📋 1.7K - 20% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/catboost/catboost
	```
- [PyPi](https://pypi.org/project/catboost) (📥 3.3M / month · 📦 210 · ⏱️ 14.01.2022):
	```
	pip install catboost
	```
- [Conda](https://anaconda.org/conda-forge/catboost) (📥 920K · ⏱️ 04.02.2022):
	```
	conda install -c conda-forge catboost
	```
</details>
<details><summary><b><a href="https://github.com/apache/incubator-mxnet">MXNet</a></b> (🥈40 ·  ⭐ 20K) - Lightweight, Portable, Flexible Distributed/Mobile Deep Learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/apache/incubator-mxnet) (👨‍💻 970 · 🔀 6.9K · 📥 25K · 📋 9.7K - 20% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/apache/incubator-mxnet
	```
- [PyPi](https://pypi.org/project/mxnet) (📥 290K / month · 📦 280 · ⏱️ 18.12.2021):
	```
	pip install mxnet
	```
- [Conda](https://anaconda.org/anaconda/mxnet) (📥 7K · 📦 5 · ⏱️ 29.02.2020):
	```
	conda install -c anaconda mxnet
	```
</details>
<details><summary><b><a href="https://github.com/google/jax">jax</a></b> (🥈40 ·  ⭐ 16K) - Composable transformations of Python+NumPy programs: differentiate,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/jax) (👨‍💻 360 · 🔀 1.5K · 📦 3.4K · 📋 3.1K - 31% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/google/jax
	```
- [PyPi](https://pypi.org/project/jax) (📥 290K / month · 📦 260 · ⏱️ 18.01.2022):
	```
	pip install jax
	```
- [Conda](https://anaconda.org/conda-forge/jaxlib) (📥 270K · ⏱️ 10.12.2021):
	```
	conda install -c conda-forge jaxlib
	```
</details>
<details><summary><b><a href="https://github.com/jina-ai/jina">Jina</a></b> (🥈38 ·  ⭐ 13K) - Cloud-native neural search framework for kind of data. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jina-ai/jina) (👨‍💻 140 · 🔀 1.8K · 📦 220 · 📋 1.3K - 5% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/jina-ai/jina
	```
- [PyPi](https://pypi.org/project/jina) (📥 36K / month · ⏱️ 07.02.2022):
	```
	pip install jina
	```
- [Conda](https://anaconda.org/conda-forge/jina-core) (📥 2.2K · ⏱️ 01.11.2021):
	```
	conda install -c conda-forge jina-core
	```
- [Docker Hub](https://hub.docker.com/r/jinaai/jina) (📥 1M · ⭐ 6 · ⏱️ 07.02.2022):
	```
	docker pull jinaai/jina
	```
</details>
<details><summary><b><a href="https://github.com/fastai/fastai">Fastai</a></b> (🥈37 ·  ⭐ 22K) - The fastai deep learning library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/fastai/fastai) (👨‍💻 600 · 🔀 7.1K · 📋 1.5K - 6% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/fastai/fastai
	```
- [PyPi](https://pypi.org/project/fastai) (📥 230K / month · 📦 290 · ⏱️ 23.10.2021):
	```
	pip install fastai
	```
</details>
<details><summary><b><a href="https://github.com/Theano/Theano">Theano</a></b> (🥈37 ·  ⭐ 9.5K) - Theano was a Python library that allows you to define, optimize, and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Theano/Theano) (👨‍💻 380 · 🔀 2.5K · 📦 12K · 📋 2.8K - 24% open · ⏱️ 23.11.2021):

	```
	git clone https://github.com/Theano/Theano
	```
- [PyPi](https://pypi.org/project/theano) (📥 270K / month · 📦 2.8K · ⏱️ 27.07.2020):
	```
	pip install theano
	```
- [Conda](https://anaconda.org/conda-forge/theano) (📥 1.8M · ⏱️ 10.11.2021):
	```
	conda install -c conda-forge theano
	```
</details>
<details><summary><b><a href="https://github.com/apache/flink">PyFlink</a></b> (🥈36 ·  ⭐ 18K) - Apache Flink Python API. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/flink) (👨‍💻 1.5K · 🔀 10K · ⏱️ 10.02.2022):

	```
	git clone https://github.com/apache/flink
	```
- [PyPi](https://pypi.org/project/apache-flink) (📥 9K / month · 📦 9 · ⏱️ 17.01.2022):
	```
	pip install apache-flink
	```
</details>
<details><summary><b><a href="https://github.com/chainer/chainer">Chainer</a></b> (🥈36 ·  ⭐ 5.7K) - A flexible framework of neural networks for deep learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/chainer/chainer) (👨‍💻 320 · 🔀 1.4K · 📦 2.5K · 📋 2K - 0% open · ⏱️ 05.01.2022):

	```
	git clone https://github.com/chainer/chainer
	```
- [PyPi](https://pypi.org/project/chainer) (📥 22K / month · 📦 400 · ⏱️ 05.01.2022):
	```
	pip install chainer
	```
- [Conda](https://anaconda.org/conda-forge/chainer) (📥 6.7K · ⏱️ 21.01.2022):
	```
	conda install -c conda-forge chainer
	```
</details>
<details><summary><b><a href="https://github.com/explosion/thinc">Thinc</a></b> (🥈36 ·  ⭐ 2.4K) - A refreshing functional take on deep learning, compatible with your favorite.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/explosion/thinc) (👨‍💻 45 · 🔀 230 · 📦 19K · 📋 120 - 17% open · ⏱️ 04.02.2022):

	```
	git clone https://github.com/explosion/thinc
	```
- [PyPi](https://pypi.org/project/thinc) (📥 3.6M / month · 📦 610 · ⏱️ 17.12.2021):
	```
	pip install thinc
	```
- [Conda](https://anaconda.org/conda-forge/thinc) (📥 1.8M · ⏱️ 08.12.2021):
	```
	conda install -c conda-forge thinc
	```
</details>
<details><summary><b><a href="https://github.com/VowpalWabbit/vowpal_wabbit">Vowpal Wabbit</a></b> (🥈34 ·  ⭐ 7.9K) - Vowpal Wabbit is a machine learning system which pushes the.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/VowpalWabbit/vowpal_wabbit) (👨‍💻 310 · 🔀 1.8K · 📋 1.2K - 11% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/VowpalWabbit/vowpal_wabbit
	```
- [PyPi](https://pypi.org/project/vowpalwabbit) (📥 53K / month · 📦 29 · ⏱️ 01.02.2022):
	```
	pip install vowpalwabbit
	```
- [Conda](https://anaconda.org/conda-forge/vowpalwabbit) (📥 55K · ⏱️ 02.02.2022):
	```
	conda install -c conda-forge vowpalwabbit
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/ignite">Ignite</a></b> (🥈33 ·  ⭐ 3.9K) - High-level library to help with training and evaluating neural.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/ignite) (👨‍💻 160 · 🔀 520 · 📋 1K - 13% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/pytorch/ignite
	```
- [PyPi](https://pypi.org/project/pytorch-ignite) (📥 120K / month · 📦 76 · ⏱️ 10.02.2022):
	```
	pip install pytorch-ignite
	```
- [Conda](https://anaconda.org/pytorch/ignite) (📥 79K · ⏱️ 17.01.2022):
	```
	conda install -c pytorch ignite
	```
</details>
<details><summary><b><a href="https://github.com/google/flax">Flax</a></b> (🥈33 ·  ⭐ 2.6K) - Flax is a neural network library for JAX that is designed for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google/flax) (👨‍💻 130 · 🔀 290 · 📥 31 · 📦 660 · 📋 490 - 36% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/google/flax
	```
- [PyPi](https://pypi.org/project/flax) (📥 88K / month · 📦 57 · ⏱️ 27.01.2022):
	```
	pip install flax
	```
- [Conda](https://anaconda.org/conda-forge/flax) (📥 2.2K · ⏱️ 27.01.2022):
	```
	conda install -c conda-forge flax
	```
</details>
<details><summary><b><a href="https://github.com/ROCmSoftwarePlatform/tensorflow-upstream">tensorflow-upstream</a></b> (🥈33 ·  ⭐ 580) - TensorFlow ROCm port. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ROCmSoftwarePlatform/tensorflow-upstream) (👨‍💻 3.9K · 🔀 67 · 📥 17 · 📋 320 - 17% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/ROCmSoftwarePlatform/tensorflow-upstream
	```
- [PyPi](https://pypi.org/project/tensorflow-rocm) (📥 41K / month · 📦 5 · ⏱️ 17.12.2021):
	```
	pip install tensorflow-rocm
	```
</details>
<details><summary><b><a href="https://github.com/ludwig-ai/ludwig">Ludwig</a></b> (🥉32 ·  ⭐ 8.1K · 📈) - Data-centric declarative deep learning framework. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ludwig-ai/ludwig) (👨‍💻 110 · 🔀 960 · 📦 99 · 📋 680 - 26% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/ludwig-ai/ludwig
	```
- [PyPi](https://pypi.org/project/ludwig) (📥 2.9K / month · 📦 8 · ⏱️ 01.02.2022):
	```
	pip install ludwig
	```
</details>
<details><summary><b><a href="https://github.com/tensorpack/tensorpack">tensorpack</a></b> (🥉32 ·  ⭐ 6.2K) - A Neural Net Training Interface on TensorFlow, with focus.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorpack/tensorpack) (👨‍💻 58 · 🔀 1.8K · 📥 130 · 📦 930 · 📋 1.3K - 0% open · ⏱️ 27.11.2021):

	```
	git clone https://github.com/tensorpack/tensorpack
	```
- [PyPi](https://pypi.org/project/tensorpack) (📥 22K / month · 📦 46 · ⏱️ 22.01.2021):
	```
	pip install tensorpack
	```
- [Conda](https://anaconda.org/conda-forge/tensorpack) (📥 200 · ⏱️ 06.02.2022):
	```
	conda install -c conda-forge tensorpack
	```
</details>
<details><summary><b><a href="https://github.com/apple/turicreate">Turi Create</a></b> (🥉31 ·  ⭐ 11K) - Turi Create simplifies the development of custom machine learning.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/apple/turicreate) (👨‍💻 85 · 🔀 1.1K · 📥 5K · 📦 290 · 📋 1.8K - 27% open · ⏱️ 29.11.2021):

	```
	git clone https://github.com/apple/turicreate
	```
- [PyPi](https://pypi.org/project/turicreate) (📥 28K / month · 📦 19 · ⏱️ 30.09.2020):
	```
	pip install turicreate
	```
</details>
<details><summary><b><a href="https://github.com/arogozhnikov/einops">einops</a></b> (🥉31 ·  ⭐ 4.4K) - Deep learning operations reinvented (for pytorch, tensorflow, jax and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/arogozhnikov/einops) (👨‍💻 14 · 🔀 180 · 📦 1.9K · 📋 100 - 33% open · ⏱️ 03.02.2022):

	```
	git clone https://github.com/arogozhnikov/einops
	```
- [PyPi](https://pypi.org/project/einops) (📥 700K / month · 📦 190 · ⏱️ 18.01.2022):
	```
	pip install einops
	```
- [Conda](https://anaconda.org/conda-forge/einops) (📥 10K · ⏱️ 18.01.2022):
	```
	conda install -c conda-forge einops
	```
</details>
<details><summary><b><a href="https://github.com/mlpack/mlpack">mlpack</a></b> (🥉31 ·  ⭐ 3.9K) - mlpack: a scalable C++ machine learning library --. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mlpack/mlpack) (👨‍💻 280 · 🔀 1.4K · 📋 1.5K - 7% open · ⏱️ 30.01.2022):

	```
	git clone https://github.com/mlpack/mlpack
	```
- [PyPi](https://pypi.org/project/mlpack) (📥 250 / month · 📦 1 · ⏱️ 28.10.2020):
	```
	pip install mlpack
	```
- [Conda](https://anaconda.org/conda-forge/mlpack) (📥 97K · ⏱️ 09.11.2021):
	```
	conda install -c conda-forge mlpack
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/sonnet">Sonnet</a></b> (🥉30 ·  ⭐ 9.2K) - TensorFlow-based neural network library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmind/sonnet) (👨‍💻 53 · 🔀 1.3K · 📦 760 · 📋 170 - 13% open · ⏱️ 01.02.2022):

	```
	git clone https://github.com/deepmind/sonnet
	```
- [PyPi](https://pypi.org/project/dm-sonnet) (📥 23K / month · 📦 52 · ⏱️ 27.03.2020):
	```
	pip install dm-sonnet
	```
- [Conda](https://anaconda.org/conda-forge/sonnet) (📥 13K · ⏱️ 14.11.2020):
	```
	conda install -c conda-forge sonnet
	```
</details>
<details><summary><b><a href="https://github.com/sony/nnabla">Neural Network Libraries</a></b> (🥉30 ·  ⭐ 2.5K) - Neural Network Libraries. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/sony/nnabla) (👨‍💻 64 · 🔀 310 · 📥 530 · 📋 77 - 41% open · ⏱️ 26.01.2022):

	```
	git clone https://github.com/sony/nnabla
	```
- [PyPi](https://pypi.org/project/nnabla) (📥 4.6K / month · 📦 51 · ⏱️ 26.01.2022):
	```
	pip install nnabla
	```
</details>
<details><summary><b><a href="https://github.com/skorch-dev/skorch">skorch</a></b> (🥉29 ·  ⭐ 4.4K) - A scikit-learn compatible neural network library that wraps.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/skorch-dev/skorch) (👨‍💻 48 · 🔀 300 · 📦 430 · 📋 420 - 12% open · ⏱️ 18.01.2022):

	```
	git clone https://github.com/skorch-dev/skorch
	```
- [PyPi](https://pypi.org/project/skorch) (📥 20K / month · 📦 33 · ⏱️ 31.10.2021):
	```
	pip install skorch
	```
- [Conda](https://anaconda.org/conda-forge/skorch) (📥 500K · ⏱️ 30.11.2021):
	```
	conda install -c conda-forge skorch
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/dm-haiku">Haiku</a></b> (🥉29 ·  ⭐ 1.7K · 📈) - JAX-based neural network library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/deepmind/dm-haiku) (👨‍💻 57 · 🔀 130 · 📦 320 · 📋 130 - 25% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/deepmind/dm-haiku
	```
- [PyPi](https://pypi.org/project/dm-haiku) (📥 80K / month · 📦 24 · ⏱️ 01.11.2021):
	```
	pip install dm-haiku
	```
- [Conda](https://anaconda.org/conda-forge/dm-haiku) (📥 1.9K · ⏱️ 03.11.2021):
	```
	conda install -c conda-forge dm-haiku
	```
</details>
<details><summary><b><a href="https://github.com/amaiya/ktrain">ktrain</a></b> (🥉29 ·  ⭐ 950) - ktrain is a Python library that makes deep learning and AI more.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/amaiya/ktrain) (👨‍💻 13 · 🔀 230 · 📦 260 · 📋 390 - 0% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/amaiya/ktrain
	```
- [PyPi](https://pypi.org/project/ktrain) (📥 33K / month · 📦 2 · ⏱️ 09.02.2022):
	```
	pip install ktrain
	```
</details>
<details><summary><b><a href="https://github.com/XiaoMi/mace">mace</a></b> (🥉25 ·  ⭐ 4.6K) - MACE is a deep learning inference framework optimized for mobile.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/XiaoMi/mace) (👨‍💻 63 · 🔀 780 · 📥 1.4K · 📋 650 - 6% open · ⏱️ 13.01.2022):

	```
	git clone https://github.com/XiaoMi/mace
	```
</details>
<details><summary><b><a href="https://github.com/google/neural-tangents">Neural Tangents</a></b> (🥉25 ·  ⭐ 1.7K) - Fast and Easy Infinite Neural Networks in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/neural-tangents) (👨‍💻 21 · 🔀 190 · 📥 190 · 📦 29 · 📋 110 - 32% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/google/neural-tangents
	```
- [PyPi](https://pypi.org/project/neural-tangents) (📥 490 / month · 📦 1 · ⏱️ 17.11.2021):
	```
	pip install neural-tangents
	```
</details>
<details><summary><b><a href="https://github.com/nubank/fklearn">fklearn</a></b> (🥉24 ·  ⭐ 1.4K) - fklearn: Functional Machine Learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nubank/fklearn) (👨‍💻 41 · 🔀 160 · 📦 11 · 📋 42 - 50% open · ⏱️ 04.02.2022):

	```
	git clone https://github.com/nubank/fklearn
	```
- [PyPi](https://pypi.org/project/fklearn) (📥 4K / month · ⏱️ 30.12.2021):
	```
	pip install fklearn
	```
</details>
<details><summary><b><a href="https://github.com/google/objax">Objax</a></b> (🥉23 ·  ⭐ 680) - Objax is a machine learning framework that provides an Object.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google/objax) (👨‍💻 22 · 🔀 59 · 📦 18 · 📋 100 - 44% open · ⏱️ 01.02.2022):

	```
	git clone https://github.com/google/objax
	```
- [PyPi](https://pypi.org/project/objax) (📥 490 / month · 📦 2 · ⏱️ 31.01.2022):
	```
	pip install objax
	```
</details>
<details><summary><b><a href="https://github.com/Xtra-Computing/thundersvm">ThunderSVM</a></b> (🥉21 ·  ⭐ 1.4K · 💤) - ThunderSVM: A Fast SVM Library on GPUs and CPUs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Xtra-Computing/thundersvm) (👨‍💻 33 · 🔀 180 · 📥 2.3K · 📋 200 - 28% open · ⏱️ 10.02.2021):

	```
	git clone https://github.com/Xtra-Computing/thundersvm
	```
- [PyPi](https://pypi.org/project/thundersvm) (📥 830 / month · ⏱️ 13.03.2020):
	```
	pip install thundersvm
	```
</details>
<details><summary><b><a href="https://github.com/pytorchbearer/torchbearer">Torchbearer</a></b> (🥉21 ·  ⭐ 620 · 💤) - torchbearer: A model fitting library for PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorchbearer/torchbearer) (👨‍💻 13 · 🔀 68 · 📦 59 · 📋 240 - 3% open · ⏱️ 26.03.2021):

	```
	git clone https://github.com/pytorchbearer/torchbearer
	```
- [PyPi](https://pypi.org/project/torchbearer) (📥 670 / month · 📦 4 · ⏱️ 31.01.2020):
	```
	pip install torchbearer
	```
</details>
<details><summary><b><a href="https://github.com/neoml-lib/neoml">NeoML</a></b> (🥉19 ·  ⭐ 660) - Machine learning framework for both deep learning and traditional.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/neoml-lib/neoml) (👨‍💻 29 · 🔀 100 · 📋 70 - 40% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/neoml-lib/neoml
	```
- [PyPi](https://pypi.org/project/neoml) (📥 87 / month · ⏱️ 21.06.2021):
	```
	pip install neoml
	```
</details>
<details><summary><b><a href="https://github.com/poets-ai/elegy">elegy</a></b> (🥉18 ·  ⭐ 320) - A High Level API for Deep Learning in JAX. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/poets-ai/elegy) (👨‍💻 14 · 🔀 21 · 📋 85 - 25% open · ⏱️ 14.12.2021):

	```
	git clone https://github.com/poets-ai/elegy
	```
- [PyPi](https://pypi.org/project/elegy) (📥 170 / month · ⏱️ 14.12.2021):
	```
	pip install elegy
	```
</details>
<details><summary>Show 14 hidden projects...</summary>

- <b><a href="https://github.com/davisking/dlib">dlib</a></b> (🥈39 ·  ⭐ 11K) - A toolkit for making real world machine learning and data analysis.. <code><a href="https://tldrlegal.com/search?q=BSL-1.0">❗️BSL-1.0</a></code>
- <b><a href="https://github.com/tflearn/tflearn">TFlearn</a></b> (🥉32 ·  ⭐ 9.6K · 💀) - Deep learning library featuring a higher-level API for TensorFlow. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/microsoft/CNTK">CNTK</a></b> (🥉31 ·  ⭐ 17K · 💀) - Microsoft Cognitive Toolkit (CNTK), an open source deep-learning toolkit. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/clab/dynet">dyNET</a></b> (🥉31 ·  ⭐ 3.3K · 💀) - DyNet: The Dynamic Neural Network Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/Lasagne/Lasagne">Lasagne</a></b> (🥉29 ·  ⭐ 3.8K · 💀) - Lightweight library to build and train neural networks in Theano. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/numenta/nupic">NuPIC</a></b> (🥉28 ·  ⭐ 6.3K · 💀) - Numenta Platform for Intelligent Computing is an implementation.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/mindsdb/mindsdb">MindsDB</a></b> (🥉28 ·  ⭐ 5.4K) - In-Database Machine Learning. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/shogun-toolbox/shogun">SHOGUN</a></b> (🥉27 ·  ⭐ 2.9K · 💀) - Unified and efficient Machine Learning. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/aksnzhy/xlearn">xLearn</a></b> (🥉25 ·  ⭐ 3K · 💀) - High performance, easy-to-use, and scalable machine learning (ML).. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/itdxer/neupy">NeuPy</a></b> (🥉25 ·  ⭐ 700 · 💀) - NeuPy is a Tensorflow based python library for prototyping and building.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/NervanaSystems/neon">neon</a></b> (🥉23 ·  ⭐ 3.9K · 💀) - Intel Nervana reference deep learning framework committed to best.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/serengil/chefboost">chefboost</a></b> (🥉20 ·  ⭐ 300) - A Lightweight Decision Tree Framework supporting regular algorithms:.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Xtra-Computing/thundergbm">ThunderGBM</a></b> (🥉16 ·  ⭐ 620 · 💀) - ThunderGBM: Fast GBDTs and Random Forests on GPUs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/facebookresearch/StarSpace">StarSpace</a></b> (🥉15 ·  ⭐ 3.7K · 💀) - Learning embeddings for classification, retrieval and ranking. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Data Visualization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_General-purpose and task-specific data visualization libraries._

<details><summary><b><a href="https://github.com/matplotlib/matplotlib">Matplotlib</a></b> (🥇49 ·  ⭐ 15K) - matplotlib: plotting with Python. <code><a href="http://bit.ly/35wkF7y">Python-2.0</a></code></summary>

- [GitHub](https://github.com/matplotlib/matplotlib) (👨‍💻 1.3K · 🔀 6.2K · 📦 500K · 📋 8.6K - 20% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/matplotlib/matplotlib
	```
- [PyPi](https://pypi.org/project/matplotlib) (📥 27M / month · 📦 52K · ⏱️ 11.12.2021):
	```
	pip install matplotlib
	```
- [Conda](https://anaconda.org/conda-forge/matplotlib) (📥 11M · ⏱️ 13.12.2021):
	```
	conda install -c conda-forge matplotlib
	```
</details>
<details><summary><b><a href="https://github.com/bokeh/bokeh">Bokeh</a></b> (🥇43 ·  ⭐ 16K) - Interactive Data Visualization in the browser, from Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bokeh/bokeh) (👨‍💻 600 · 🔀 3.9K · 📦 45K · 📋 6.8K - 10% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/bokeh/bokeh
	```
- [PyPi](https://pypi.org/project/bokeh) (📥 2.8M / month · 📦 3.5K · ⏱️ 27.01.2022):
	```
	pip install bokeh
	```
- [Conda](https://anaconda.org/conda-forge/bokeh) (📥 6.5M · ⏱️ 22.11.2021):
	```
	conda install -c conda-forge bokeh
	```
</details>
<details><summary><b><a href="https://github.com/plotly/plotly.py">Plotly</a></b> (🥇42 ·  ⭐ 11K) - The interactive graphing library for Python (includes Plotly Express). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/plotly/plotly.py) (👨‍💻 190 · 🔀 2.1K · 📦 9 · 📋 2.3K - 48% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/plotly/plotly.py
	```
- [PyPi](https://pypi.org/project/plotly) (📥 7.2M / month · 📦 3.8K · ⏱️ 09.02.2022):
	```
	pip install plotly
	```
- [Conda](https://anaconda.org/conda-forge/plotly) (📥 2.2M · ⏱️ 21.12.2021):
	```
	conda install -c conda-forge plotly
	```
- [npm](https://www.npmjs.com/package/plotlywidget) (📥 52K / month · 📦 4 · ⏱️ 12.01.2021):
	```
	npm install plotlywidget
	```
</details>
<details><summary><b><a href="https://github.com/mwaskom/seaborn">Seaborn</a></b> (🥇41 ·  ⭐ 9.1K) - Statistical data visualization in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mwaskom/seaborn) (👨‍💻 160 · 🔀 1.5K · 📥 210 · 📦 140K · 📋 2K - 5% open · ⏱️ 18.01.2022):

	```
	git clone https://github.com/mwaskom/seaborn
	```
- [PyPi](https://pypi.org/project/seaborn) (📥 6.9M / month · 📦 8.8K · ⏱️ 16.08.2021):
	```
	pip install seaborn
	```
- [Conda](https://anaconda.org/conda-forge/seaborn) (📥 3.3M · ⏱️ 16.08.2021):
	```
	conda install -c conda-forge seaborn
	```
</details>
<details><summary><b><a href="https://github.com/altair-viz/altair">Altair</a></b> (🥇39 ·  ⭐ 7.3K) - Declarative statistical visualization library for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/altair-viz/altair) (👨‍💻 130 · 🔀 630 · 📦 22K · 📋 1.6K - 15% open · ⏱️ 07.02.2022):

	```
	git clone https://github.com/altair-viz/altair
	```
- [PyPi](https://pypi.org/project/altair) (📥 4.7M / month · 📦 340 · ⏱️ 29.12.2021):
	```
	pip install altair
	```
- [Conda](https://anaconda.org/conda-forge/altair) (📥 1.1M · ⏱️ 29.12.2021):
	```
	conda install -c conda-forge altair
	```
</details>
<details><summary><b><a href="https://github.com/plotly/dash">dash</a></b> (🥈38 ·  ⭐ 16K) - Analytical Web Apps for Python, R, Julia, and Jupyter. No JavaScript Required. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/plotly/dash) (👨‍💻 100 · 🔀 1.6K · 📦 180 · 📋 1.2K - 47% open · ⏱️ 31.01.2022):

	```
	git clone https://github.com/plotly/dash
	```
- [PyPi](https://pypi.org/project/dash) (📥 930K / month · 📦 1.1K · ⏱️ 28.01.2022):
	```
	pip install dash
	```
- [Conda](https://anaconda.org/conda-forge/dash) (📥 350K · ⏱️ 29.01.2022):
	```
	conda install -c conda-forge dash
	```
</details>
<details><summary><b><a href="https://github.com/xflr6/graphviz">Graphviz</a></b> (🥈37 ·  ⭐ 1.1K) - Simple Python interface for Graphviz. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/xflr6/graphviz) (👨‍💻 18 · 🔀 170 · 📦 28K · 📋 130 - 5% open · ⏱️ 20.01.2022):

	```
	git clone https://github.com/xflr6/graphviz
	```
- [PyPi](https://pypi.org/project/graphviz) (📥 9M / month · 📦 2.9K · ⏱️ 12.12.2021):
	```
	pip install graphviz
	```
- [Conda](https://anaconda.org/anaconda/python-graphviz) (📥 17K · ⏱️ 04.02.2021):
	```
	conda install -c anaconda python-graphviz
	```
</details>
<details><summary><b><a href="https://github.com/pandas-profiling/pandas-profiling">pandas-profiling</a></b> (🥈36 ·  ⭐ 8.5K) - Create HTML profiling reports from pandas DataFrame.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pandas-profiling/pandas-profiling) (👨‍💻 85 · 🔀 1.2K · 📦 6.6K · 📋 540 - 19% open · ⏱️ 26.01.2022):

	```
	git clone https://github.com/pandas-profiling/pandas-profiling
	```
- [PyPi](https://pypi.org/project/pandas-profiling) (📥 930K / month · 📦 140 · ⏱️ 27.09.2021):
	```
	pip install pandas-profiling
	```
- [Conda](https://anaconda.org/conda-forge/pandas-profiling) (📥 190K · ⏱️ 28.09.2021):
	```
	conda install -c conda-forge pandas-profiling
	```
</details>
<details><summary><b><a href="https://github.com/lmcinnes/umap">UMAP</a></b> (🥈36 ·  ⭐ 5.4K) - Uniform Manifold Approximation and Projection. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lmcinnes/umap) (👨‍💻 98 · 🔀 610 · 📦 4.5K · 📋 600 - 52% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/lmcinnes/umap
	```
- [PyPi](https://pypi.org/project/umap-learn) (📥 1M / month · 📦 290 · ⏱️ 29.10.2021):
	```
	pip install umap-learn
	```
- [Conda](https://anaconda.org/conda-forge/umap-learn) (📥 890K · ⏱️ 15.01.2022):
	```
	conda install -c conda-forge umap-learn
	```
</details>
<details><summary><b><a href="https://github.com/pyecharts/pyecharts">pyecharts</a></b> (🥈35 ·  ⭐ 12K) - Python Echarts Plotting Library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pyecharts/pyecharts) (👨‍💻 30 · 🔀 2.6K · 📦 2K · 📋 1.5K - 1% open · ⏱️ 16.11.2021):

	```
	git clone https://github.com/pyecharts/pyecharts
	```
- [PyPi](https://pypi.org/project/pyecharts) (📥 41K / month · 📦 210 · ⏱️ 16.11.2021):
	```
	pip install pyecharts
	```
</details>
<details><summary><b><a href="https://github.com/pyqtgraph/pyqtgraph">PyQtGraph</a></b> (🥈34 ·  ⭐ 2.7K) - Fast data visualization and GUI tools for scientific / engineering.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyqtgraph/pyqtgraph) (👨‍💻 220 · 🔀 900 · 📋 990 - 31% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/pyqtgraph/pyqtgraph
	```
- [PyPi](https://pypi.org/project/pyqtgraph) (📥 77K / month · 📦 760 · ⏱️ 11.10.2021):
	```
	pip install pyqtgraph
	```
- [Conda](https://anaconda.org/conda-forge/pyqtgraph) (📥 220K · ⏱️ 11.10.2021):
	```
	conda install -c conda-forge pyqtgraph
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/holoviews">HoloViews</a></b> (🥈34 ·  ⭐ 2.1K) - With Holoviews, your data visualizes itself. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/holoviz/holoviews) (👨‍💻 120 · 🔀 350 · 📋 2.7K - 30% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/holoviz/holoviews
	```
- [PyPi](https://pypi.org/project/holoviews) (📥 230K / month · 📦 200 · ⏱️ 21.01.2022):
	```
	pip install holoviews
	```
- [Conda](https://anaconda.org/conda-forge/holoviews) (📥 630K · ⏱️ 13.01.2022):
	```
	conda install -c conda-forge holoviews
	```
- [npm](https://www.npmjs.com/package/@pyviz/jupyterlab_pyviz) (📥 1.8K / month · ⏱️ 24.05.2020):
	```
	npm install @pyviz/jupyterlab_pyviz
	```
</details>
<details><summary><b><a href="https://github.com/amueller/word_cloud">wordcloud</a></b> (🥈33 ·  ⭐ 8.6K) - A little word cloud generator in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/amueller/word_cloud) (👨‍💻 64 · 🔀 2.1K · 📋 470 - 23% open · ⏱️ 13.11.2021):

	```
	git clone https://github.com/amueller/word_cloud
	```
- [PyPi](https://pypi.org/project/wordcloud) (📥 600K / month · 📦 710 · ⏱️ 11.11.2020):
	```
	pip install wordcloud
	```
- [Conda](https://anaconda.org/conda-forge/wordcloud) (📥 260K · ⏱️ 15.11.2021):
	```
	conda install -c conda-forge wordcloud
	```
</details>
<details><summary><b><a href="https://github.com/finos/perspective">Perspective</a></b> (🥈33 ·  ⭐ 4.2K) - A data visualization and analytics component, especially.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/finos/perspective) (👨‍💻 65 · 🔀 440 · 📦 220 · 📋 500 - 14% open · ⏱️ 06.02.2022):

	```
	git clone https://github.com/finos/perspective
	```
- [PyPi](https://pypi.org/project/perspective-python) (📥 4.2K / month · 📦 9 · ⏱️ 02.02.2022):
	```
	pip install perspective-python
	```
- [Conda](https://anaconda.org/conda-forge/perspective) (📥 40K · ⏱️ 02.02.2022):
	```
	conda install -c conda-forge perspective
	```
- [npm](https://www.npmjs.com/package/@finos/perspective-jupyterlab) (📥 2.2K / month · ⏱️ 01.02.2022):
	```
	npm install @finos/perspective-jupyterlab
	```
</details>
<details><summary><b><a href="https://github.com/bqplot/bqplot">bqplot</a></b> (🥈32 ·  ⭐ 3.2K) - Plotting library for IPython/Jupyter notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/bqplot/bqplot) (👨‍💻 56 · 🔀 460 · 📦 30 · 📋 580 - 38% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/bqplot/bqplot
	```
- [PyPi](https://pypi.org/project/bqplot) (📥 65K / month · 📦 90 · ⏱️ 07.01.2022):
	```
	pip install bqplot
	```
- [Conda](https://anaconda.org/conda-forge/bqplot) (📥 920K · ⏱️ 07.01.2022):
	```
	conda install -c conda-forge bqplot
	```
- [npm](https://www.npmjs.com/package/bqplot) (📥 24K / month · 📦 10 · ⏱️ 07.01.2022):
	```
	npm install bqplot
	```
</details>
<details><summary><b><a href="https://github.com/vispy/vispy">VisPy</a></b> (🥈32 ·  ⭐ 2.8K) - High-performance interactive 2D/3D data visualization library. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/vispy/vispy) (👨‍💻 170 · 🔀 580 · 📦 680 · 📋 1.3K - 21% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/vispy/vispy
	```
- [PyPi](https://pypi.org/project/vispy) (📥 41K / month · 📦 94 · ⏱️ 04.02.2022):
	```
	pip install vispy
	```
- [Conda](https://anaconda.org/conda-forge/vispy) (📥 200K · ⏱️ 05.02.2022):
	```
	conda install -c conda-forge vispy
	```
- [npm](https://www.npmjs.com/package/vispy) (📥 10 / month · ⏱️ 15.03.2020):
	```
	npm install vispy
	```
</details>
<details><summary><b><a href="https://github.com/pyvista/pyvista">PyVista</a></b> (🥈32 ·  ⭐ 1.1K) - 3D plotting and mesh analysis through a streamlined interface for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pyvista/pyvista) (👨‍💻 70 · 🔀 210 · 📥 490 · 📦 600 · 📋 690 - 25% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/pyvista/pyvista
	```
- [PyPi](https://pypi.org/project/pyvista) (📥 42K / month · 📦 85 · ⏱️ 11.01.2022):
	```
	pip install pyvista
	```
- [Conda](https://anaconda.org/conda-forge/pyvista) (📥 140K · ⏱️ 11.01.2022):
	```
	conda install -c conda-forge pyvista
	```
</details>
<details><summary><b><a href="https://github.com/voxel51/fiftyone">FiftyOne</a></b> (🥈31 ·  ⭐ 980) - Visualize, create, and debug image and video datasets.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/voxel51/fiftyone) (👨‍💻 25 · 🔀 120 · 📦 80 · 📋 680 - 31% open · ⏱️ 07.02.2022):

	```
	git clone https://github.com/voxel51/fiftyone
	```
- [PyPi](https://pypi.org/project/fiftyone) (📥 22K / month · 📦 1 · ⏱️ 07.02.2022):
	```
	pip install fiftyone
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/datashader">datashader</a></b> (🥈30 ·  ⭐ 2.7K) - Quickly and accurately render even the largest data. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/holoviz/datashader) (👨‍💻 45 · 🔀 330 · 📦 950 · 📋 480 - 26% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/holoviz/datashader
	```
- [PyPi](https://pypi.org/project/datashader) (📥 46K / month · 📦 74 · ⏱️ 09.06.2021):
	```
	pip install datashader
	```
- [Conda](https://anaconda.org/conda-forge/datashader) (📥 260K · ⏱️ 10.06.2021):
	```
	conda install -c conda-forge datashader
	```
</details>
<details><summary><b><a href="https://github.com/santosjorge/cufflinks">Cufflinks</a></b> (🥈30 ·  ⭐ 2.5K · 💤) - Productivity Tools for Plotly + Pandas. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/santosjorge/cufflinks) (👨‍💻 38 · 🔀 580 · 📦 5.2K · 📋 220 - 42% open · ⏱️ 25.02.2021):

	```
	git clone https://github.com/santosjorge/cufflinks
	```
- [PyPi](https://pypi.org/project/cufflinks) (📥 280K / month · 📦 160 · ⏱️ 15.12.2021):
	```
	pip install cufflinks
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/data-validation">data-validation</a></b> (🥈30 ·  ⭐ 600) - Library for exploring and validating machine learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/data-validation) (👨‍💻 23 · 🔀 110 · 📥 300 · 📦 380 · 📋 150 - 24% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/tensorflow/data-validation
	```
- [PyPi](https://pypi.org/project/tensorflow-data-validation) (📥 7.3M / month · 📦 26 · ⏱️ 21.01.2022):
	```
	pip install tensorflow-data-validation
	```
</details>
<details><summary><b><a href="https://github.com/ResidentMario/missingno">missingno</a></b> (🥉29 ·  ⭐ 3.1K · 💤) - Missing data visualization module for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ResidentMario/missingno) (👨‍💻 17 · 🔀 380 · 📦 6.2K · 📋 110 - 10% open · ⏱️ 04.07.2021):

	```
	git clone https://github.com/ResidentMario/missingno
	```
- [PyPi](https://pypi.org/project/missingno) (📥 810K / month · 📦 110 · ⏱️ 04.07.2021):
	```
	pip install missingno
	```
- [Conda](https://anaconda.org/conda-forge/missingno) (📥 140K · ⏱️ 15.02.2020):
	```
	conda install -c conda-forge missingno
	```
</details>
<details><summary><b><a href="https://github.com/man-group/dtale">D-Tale</a></b> (🥉29 ·  ⭐ 3.1K) - Visualizer for pandas data structures. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/man-group/dtale) (👨‍💻 20 · 🔀 230 · 📦 280 · 📋 440 - 9% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/man-group/dtale
	```
- [PyPi](https://pypi.org/project/dtale) (📥 56K / month · 📦 11 · ⏱️ 18.11.2021):
	```
	pip install dtale
	```
- [Conda](https://anaconda.org/conda-forge/dtale) (📥 100K · ⏱️ 18.11.2021):
	```
	conda install -c conda-forge dtale
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/hvplot">hvPlot</a></b> (🥉28 ·  ⭐ 520) - A high-level plotting API for pandas, dask, xarray, and networkx built on.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/holoviz/hvplot) (👨‍💻 35 · 🔀 64 · 📦 1K · 📋 410 - 35% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/holoviz/hvplot
	```
- [PyPi](https://pypi.org/project/hvplot) (📥 96K / month · 📦 55 · ⏱️ 09.12.2021):
	```
	pip install hvplot
	```
- [Conda](https://anaconda.org/conda-forge/hvplot) (📥 150K · ⏱️ 23.07.2021):
	```
	conda install -c conda-forge hvplot
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/facets">Facets Overview</a></b> (🥉27 ·  ⭐ 6.8K · 💤) - Visualizations for machine learning datasets. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PAIR-code/facets) (👨‍💻 28 · 🔀 830 · 📦 100 · 📋 150 - 50% open · ⏱️ 06.05.2021):

	```
	git clone https://github.com/pair-code/facets
	```
- [PyPi](https://pypi.org/project/facets-overview) (📥 150K / month · 📦 4 · ⏱️ 24.07.2019):
	```
	pip install facets-overview
	```
</details>
<details><summary><b><a href="https://github.com/ContextLab/hypertools">HyperTools</a></b> (🥉26 ·  ⭐ 1.7K) - A Python toolbox for gaining geometric insights into high-dimensional.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ContextLab/hypertools) (👨‍💻 21 · 🔀 150 · 📥 8 · 📦 160 · 📋 190 - 35% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/ContextLab/hypertools
	```
- [PyPi](https://pypi.org/project/hypertools) (📥 1.5K / month · 📦 9 · ⏱️ 15.06.2021):
	```
	pip install hypertools
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/pythreejs">pythreejs</a></b> (🥉26 ·  ⭐ 790) - A Jupyter - Three.js bridge. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jupyter-widgets/pythreejs) (👨‍💻 29 · 🔀 160 · 📦 19 · 📋 210 - 31% open · ⏱️ 06.12.2021):

	```
	git clone https://github.com/jupyter-widgets/pythreejs
	```
- [PyPi](https://pypi.org/project/pythreejs) (📥 39K / month · 📦 34 · ⏱️ 26.02.2021):
	```
	pip install pythreejs
	```
- [Conda](https://anaconda.org/conda-forge/pythreejs) (📥 360K · ⏱️ 02.03.2021):
	```
	conda install -c conda-forge pythreejs
	```
- [npm](https://www.npmjs.com/package/jupyter-threejs) (📥 5.6K / month · 📦 7 · ⏱️ 26.02.2021):
	```
	npm install jupyter-threejs
	```
</details>
<details><summary><b><a href="https://github.com/JetBrains/lets-plot">lets-plot</a></b> (🥉26 ·  ⭐ 720) - An open-source plotting library for statistical data. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/JetBrains/lets-plot) (👨‍💻 16 · 🔀 32 · 📥 200 · 📦 13 · 📋 230 - 30% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/JetBrains/lets-plot
	```
- [PyPi](https://pypi.org/project/lets-plot) (📥 2.5K / month · 📦 1 · ⏱️ 10.12.2021):
	```
	pip install lets-plot
	```
</details>
<details><summary><b><a href="https://github.com/spotify/chartify">Chartify</a></b> (🥉25 ·  ⭐ 3.1K · 💤) - Python library that makes it easy for data scientists to create.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/spotify/chartify) (👨‍💻 21 · 🔀 280 · 📦 61 · 📋 72 - 56% open · ⏱️ 05.02.2021):

	```
	git clone https://github.com/spotify/chartify
	```
- [PyPi](https://pypi.org/project/chartify) (📥 1.8K / month · 📦 5 · ⏱️ 02.11.2020):
	```
	pip install chartify
	```
- [Conda](https://anaconda.org/conda-forge/chartify) (📥 18K · ⏱️ 07.11.2020):
	```
	conda install -c conda-forge chartify
	```
</details>
<details><summary><b><a href="https://github.com/vega/ipyvega">vega</a></b> (🥉25 ·  ⭐ 320) - IPython/Jupyter notebook module for Vega and Vega-Lite. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/vega/ipyvega) (👨‍💻 11 · 🔀 59 · 📋 94 - 12% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/vega/ipyvega
	```
- [PyPi](https://pypi.org/project/vega) (📥 9.6K / month · 📦 84 · ⏱️ 10.02.2022):
	```
	pip install vega
	```
- [Conda](https://anaconda.org/conda-forge/vega) (📥 470K · ⏱️ 10.02.2022):
	```
	conda install -c conda-forge vega
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/hiplot">HiPlot</a></b> (🥉24 ·  ⭐ 2.3K) - HiPlot makes understanding high dimensional data easy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/hiplot) (👨‍💻 7 · 🔀 110 · 📦 3 · 📋 73 - 16% open · ⏱️ 07.02.2022):

	```
	git clone https://github.com/facebookresearch/hiplot
	```
- [PyPi](https://pypi.org/project/hiplot) (📥 11K / month · 📦 9 · ⏱️ 05.11.2021):
	```
	pip install hiplot
	```
- [Conda](https://anaconda.org/conda-forge/hiplot) (📥 76K · ⏱️ 05.11.2021):
	```
	conda install -c conda-forge hiplot
	```
</details>
<details><summary><b><a href="https://github.com/pavlin-policar/openTSNE">openTSNE</a></b> (🥉24 ·  ⭐ 940 · 📉) - Extensible, parallel implementations of t-SNE. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pavlin-policar/openTSNE) (👨‍💻 10 · 🔀 100 · 📦 280 · 📋 100 - 5% open · ⏱️ 25.10.2021):

	```
	git clone https://github.com/pavlin-policar/openTSNE
	```
- [PyPi](https://pypi.org/project/opentsne) (📥 23K / month · 📦 8 · ⏱️ 25.10.2021):
	```
	pip install opentsne
	```
- [Conda](https://anaconda.org/conda-forge/opentsne) (📥 130K · ⏱️ 13.11.2021):
	```
	conda install -c conda-forge opentsne
	```
</details>
<details><summary><b><a href="https://github.com/AutoViML/AutoViz">AutoViz</a></b> (🥉24 ·  ⭐ 630) - Automatically Visualize any dataset, any size with a single line of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/AutoViML/AutoViz) (👨‍💻 11 · 🔀 92 · 📦 130 · 📋 47 - 12% open · ⏱️ 05.02.2022):

	```
	git clone https://github.com/AutoViML/AutoViz
	```
- [PyPi](https://pypi.org/project/autoviz) (📥 37K / month · 📦 3 · ⏱️ 25.12.2021):
	```
	pip install autoviz
	```
- [Conda](https://anaconda.org/conda-forge/autoviz) (📥 2.1K · ⏱️ 25.12.2021):
	```
	conda install -c conda-forge autoviz
	```
</details>
<details><summary><b><a href="https://github.com/PatrikHlobil/Pandas-Bokeh">Pandas-Bokeh</a></b> (🥉23 ·  ⭐ 760) - Bokeh Plotting Backend for Pandas and GeoPandas. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PatrikHlobil/Pandas-Bokeh) (👨‍💻 13 · 🔀 95 · 📦 280 · 📋 95 - 30% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/PatrikHlobil/Pandas-Bokeh
	```
- [PyPi](https://pypi.org/project/pandas-bokeh) (📥 16K / month · 📦 11 · ⏱️ 11.04.2021):
	```
	pip install pandas-bokeh
	```
</details>
<details><summary><b><a href="https://github.com/marcharper/python-ternary">python-ternary</a></b> (🥉23 ·  ⭐ 510) - Ternary plotting library for python with matplotlib. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/marcharper/python-ternary) (👨‍💻 27 · 🔀 130 · 📥 17 · 📦 84 · 📋 120 - 20% open · ⏱️ 21.10.2021):

	```
	git clone https://github.com/marcharper/python-ternary
	```
- [PyPi](https://pypi.org/project/python-ternary) (📥 16K / month · 📦 21 · ⏱️ 17.02.2021):
	```
	pip install python-ternary
	```
- [Conda](https://anaconda.org/conda-forge/python-ternary) (📥 61K · ⏱️ 17.02.2021):
	```
	conda install -c conda-forge python-ternary
	```
</details>
<details><summary><b><a href="https://github.com/leotac/joypy">joypy</a></b> (🥉23 ·  ⭐ 400) - Joyplots in Python with matplotlib & pandas. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/leotac/joypy) (👨‍💻 6 · 🔀 44 · 📦 120 · 📋 48 - 22% open · ⏱️ 19.12.2021):

	```
	git clone https://github.com/leotac/joypy
	```
- [PyPi](https://pypi.org/project/joypy) (📥 36K / month · 📦 5 · ⏱️ 19.12.2021):
	```
	pip install joypy
	```
- [Conda](https://anaconda.org/conda-forge/joypy) (📥 12K · ⏱️ 28.12.2020):
	```
	conda install -c conda-forge joypy
	```
</details>
<details><summary><b><a href="https://github.com/fbdesignpro/sweetviz">Sweetviz</a></b> (🥉22 ·  ⭐ 1.9K · 💤) - Visualize and compare datasets, target values and associations, with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/fbdesignpro/sweetviz) (👨‍💻 6 · 🔀 190 · 📋 97 - 27% open · ⏱️ 08.07.2021):

	```
	git clone https://github.com/fbdesignpro/sweetviz
	```
- [PyPi](https://pypi.org/project/sweetviz) (📥 66K / month · 📦 5 · ⏱️ 08.07.2021):
	```
	pip install sweetviz
	```
- [Conda](https://anaconda.org/conda-forge/sweetviz) (📥 8.6K · ⏱️ 09.07.2021):
	```
	conda install -c conda-forge sweetviz
	```
</details>
<details><summary><b><a href="https://github.com/SauceCat/PDPbox">PDPbox</a></b> (🥉22 ·  ⭐ 650 · 💤) - python partial dependence plot toolbox. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SauceCat/PDPbox) (👨‍💻 7 · 🔀 110 · 📦 470 · 📋 58 - 34% open · ⏱️ 14.03.2021):

	```
	git clone https://github.com/SauceCat/PDPbox
	```
- [PyPi](https://pypi.org/project/pdpbox) (📥 58K / month · 📦 25 · ⏱️ 14.03.2021):
	```
	pip install pdpbox
	```
- [Conda](https://anaconda.org/conda-forge/pdpbox) (📥 11K · ⏱️ 14.03.2021):
	```
	conda install -c conda-forge pdpbox
	```
</details>
<details><summary><b><a href="https://github.com/gyli/PyWaffle">PyWaffle</a></b> (🥉21 ·  ⭐ 470) - Make Waffle Charts in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gyli/PyWaffle) (👨‍💻 6 · 🔀 81 · 📦 110 · 📋 16 - 25% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/gyli/PyWaffle
	```
- [PyPi](https://pypi.org/project/pywaffle) (📥 2.9K / month · 📦 1 · ⏱️ 21.12.2021):
	```
	pip install pywaffle
	```
- [Conda](https://anaconda.org/conda-forge/pywaffle) (📥 4.2K · ⏱️ 22.12.2021):
	```
	conda install -c conda-forge pywaffle
	```
</details>
<details><summary>Show 11 hidden projects...</summary>

- <b><a href="https://github.com/SciTools/cartopy">cartopy</a></b> (🥈32 ·  ⭐ 990) - Cartopy - a cartographic python library with matplotlib support. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code>
- <b><a href="https://github.com/has2k1/plotnine">plotnine</a></b> (🥈30 ·  ⭐ 2.9K) - A grammar of graphics for Python. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code>
- <b><a href="https://github.com/DmitryUlyanov/Multicore-TSNE">Multicore-TSNE</a></b> (🥉24 ·  ⭐ 1.7K · 💀) - Parallel t-SNE implementation with Python and Torch.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/adamerose/PandasGUI">PandasGUI</a></b> (🥉23 ·  ⭐ 2.6K) - A GUI for Pandas DataFrames. <code><a href="https://tldrlegal.com/search?q=MIT-0">❗️MIT-0</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/nicolaskruchten/jupyter_pivottablejs">pivottablejs</a></b> (🥉23 ·  ⭐ 460 · 💀) - Dragndrop Pivot Tables and Charts for Jupyter/IPython.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/beringresearch/ivis">ivis</a></b> (🥉18 ·  ⭐ 260) - Dimensionality reduction in very large datasets using Siamese.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/t-makaro/animatplot">animatplot</a></b> (🥉17 ·  ⭐ 390 · 💀) - A python package for animating plots build on matplotlib. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Zsailer/nx_altair">nx-altair</a></b> (🥉17 ·  ⭐ 190 · 💀) - Draw interactive NetworkX graphs with Altair. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/altair-viz/pdvega">pdvega</a></b> (🥉16 ·  ⭐ 340 · 💀) - Interactive plotting for Pandas using Vega-Lite. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/data-describe/data-describe">data-describe</a></b> (🥉16 ·  ⭐ 290) - datadescribe: Pythonic EDA Accelerator for Data Science. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/biovault/nptsne">nptsne</a></b> (🥉15 ·  ⭐ 27 · 💤) - nptsne is a numpy compatible python binary package that offers a.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Text Data & NLP

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for processing, cleaning, manipulating, and analyzing text data as well as libraries for NLP tasks such as language detection, fuzzy matching, classification, seq2seq learning, conversational AI, keyword extraction, and translation._

<details><summary><b><a href="https://github.com/huggingface/transformers">transformers</a></b> (🥇48 ·  ⭐ 58K) - Transformers: State-of-the-art Machine Learning for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/huggingface/transformers) (👨‍💻 1.1K · 🔀 14K · 📥 1.4K · 📦 22K · 📋 8.8K - 5% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/huggingface/transformers
	```
- [PyPi](https://pypi.org/project/transformers) (📥 3.5M / month · 📦 760 · ⏱️ 31.01.2022):
	```
	pip install transformers
	```
- [Conda](https://anaconda.org/conda-forge/transformers) (📥 95K · ⏱️ 31.01.2022):
	```
	conda install -c conda-forge transformers
	```
</details>
<details><summary><b><a href="https://github.com/nltk/nltk">nltk</a></b> (🥇45 ·  ⭐ 10K) - Suite of libraries and programs for symbolic and statistical natural.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nltk/nltk) (👨‍💻 410 · 🔀 2.5K · 📦 130K · 📋 1.6K - 13% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/nltk/nltk
	```
- [PyPi](https://pypi.org/project/nltk) (📥 11M / month · 📦 12K · ⏱️ 09.02.2022):
	```
	pip install nltk
	```
- [Conda](https://anaconda.org/conda-forge/nltk) (📥 1.1M · ⏱️ 29.12.2021):
	```
	conda install -c conda-forge nltk
	```
</details>
<details><summary><b><a href="https://github.com/explosion/spaCy">spaCy</a></b> (🥇44 ·  ⭐ 22K) - Industrial-strength Natural Language Processing (NLP) in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/explosion/spaCy) (👨‍💻 650 · 🔀 3.7K · 📥 3.1K · 📦 35K · 📋 5K - 2% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/explosion/spaCy
	```
- [PyPi](https://pypi.org/project/spacy) (📥 3.9M / month · 📦 2.2K · ⏱️ 15.12.2021):
	```
	pip install spacy
	```
- [Conda](https://anaconda.org/conda-forge/spacy) (📥 2.5M · ⏱️ 14.01.2022):
	```
	conda install -c conda-forge spacy
	```
</details>
<details><summary><b><a href="https://github.com/RaRe-Technologies/gensim">gensim</a></b> (🥇41 ·  ⭐ 13K) - Topic Modelling for Humans. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code></summary>

- [GitHub](https://github.com/RaRe-Technologies/gensim) (👨‍💻 420 · 🔀 4.1K · 📥 3.5K · 📦 30K · 📋 1.7K - 21% open · ⏱️ 25.01.2022):

	```
	git clone https://github.com/RaRe-Technologies/gensim
	```
- [PyPi](https://pypi.org/project/gensim) (📥 9.6M / month · 📦 2.8K · ⏱️ 17.09.2021):
	```
	pip install gensim
	```
- [Conda](https://anaconda.org/conda-forge/gensim) (📥 770K · ⏱️ 09.11.2021):
	```
	conda install -c conda-forge gensim
	```
</details>
<details><summary><b><a href="https://github.com/RasaHQ/rasa">Rasa</a></b> (🥇39 ·  ⭐ 14K) - Open source machine learning framework to automate text- and voice-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/RasaHQ/rasa) (👨‍💻 530 · 🔀 3.9K · 📋 6.5K - 14% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/RasaHQ/rasa
	```
- [PyPi](https://pypi.org/project/rasa) (📥 230K / month · 📦 57 · ⏱️ 28.01.2022):
	```
	pip install rasa
	```
</details>
<details><summary><b><a href="https://github.com/flairNLP/flair">flair</a></b> (🥇39 ·  ⭐ 11K) - A very simple framework for state-of-the-art Natural Language Processing.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/flairNLP/flair) (👨‍💻 220 · 🔀 1.8K · 📦 1.2K · 📋 1.8K - 5% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/flairNLP/flair
	```
- [PyPi](https://pypi.org/project/flair) (📥 76K / month · 📦 66 · ⏱️ 18.11.2021):
	```
	pip install flair
	```
- [Conda](https://anaconda.org/conda-forge/python-flair) (📥 6.7K · ⏱️ 18.11.2021):
	```
	conda install -c conda-forge python-flair
	```
</details>
<details><summary><b><a href="https://github.com/allenai/allennlp">AllenNLP</a></b> (🥇38 ·  ⭐ 11K) - An open-source NLP research library, built on PyTorch. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/allenai/allennlp) (👨‍💻 260 · 🔀 2.2K · 📥 44 · 📦 2.2K · 📋 2.5K - 4% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/allenai/allennlp
	```
- [PyPi](https://pypi.org/project/allennlp) (📥 37K / month · 📦 180 · ⏱️ 27.01.2022):
	```
	pip install allennlp
	```
- [Conda](https://anaconda.org/conda-forge/allennlp) (📥 40K · ⏱️ 06.02.2022):
	```
	conda install -c conda-forge allennlp
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/fairseq">fairseq</a></b> (🥇36 ·  ⭐ 16K) - Facebook AI Research Sequence-to-Sequence Toolkit written in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/fairseq) (👨‍💻 370 · 🔀 4K · 📥 170 · 📦 650 · 📋 3.2K - 36% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/pytorch/fairseq
	```
- [PyPi](https://pypi.org/project/fairseq) (📥 35K / month · 📦 28 · ⏱️ 05.01.2021):
	```
	pip install fairseq
	```
- [Conda](https://anaconda.org/conda-forge/fairseq) (📥 13K · ⏱️ 28.04.2021):
	```
	conda install -c conda-forge fairseq
	```
</details>
<details><summary><b><a href="https://github.com/gunthercox/ChatterBot">ChatterBot</a></b> (🥇35 ·  ⭐ 12K · 💤) - ChatterBot is a machine learning, conversational dialog engine.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/gunthercox/ChatterBot) (👨‍💻 100 · 🔀 3.9K · 📦 4.1K · 📋 1.5K - 19% open · ⏱️ 01.06.2021):

	```
	git clone https://github.com/gunthercox/ChatterBot
	```
- [PyPi](https://pypi.org/project/chatterbot) (📥 31K / month · 📦 350 · ⏱️ 22.08.2020):
	```
	pip install chatterbot
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/ParlAI">ParlAI</a></b> (🥇35 ·  ⭐ 8.6K) - A framework for training and evaluating AI models on a variety of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/ParlAI) (👨‍💻 170 · 🔀 1.7K · 📦 59 · 📋 1.2K - 7% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/facebookresearch/ParlAI
	```
- [PyPi](https://pypi.org/project/parlai) (📥 6.8K / month · 📦 3 · ⏱️ 12.10.2021):
	```
	pip install parlai
	```
</details>
<details><summary><b><a href="https://github.com/sloria/TextBlob">TextBlob</a></b> (🥇35 ·  ⭐ 8K) - Simple, Pythonic, text processing--Sentiment analysis, part-of-speech.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sloria/TextBlob) (👨‍💻 35 · 🔀 1.1K · 📥 97 · 📦 17K · 📋 260 - 39% open · ⏱️ 22.10.2021):

	```
	git clone https://github.com/sloria/TextBlob
	```
- [PyPi](https://pypi.org/project/textblob) (📥 1.1M / month · 📦 1.4K · ⏱️ 15.12.2021):
	```
	pip install textblob
	```
- [Conda](https://anaconda.org/conda-forge/textblob) (📥 150K · ⏱️ 24.02.2019):
	```
	conda install -c conda-forge textblob
	```
</details>
<details><summary><b><a href="https://github.com/UKPLab/sentence-transformers">sentence-transformers</a></b> (🥈34 ·  ⭐ 7K) - Multilingual Sentence & Image Embeddings with BERT. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/UKPLab/sentence-transformers) (👨‍💻 73 · 🔀 1.4K · 📦 2.4K · 📋 1.3K - 50% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/UKPLab/sentence-transformers
	```
- [PyPi](https://pypi.org/project/sentence-transformers) (📥 780K / month · 📦 80 · ⏱️ 01.10.2021):
	```
	pip install sentence-transformers
	```
- [Conda](https://anaconda.org/conda-forge/sentence-transformers) (📥 14K · ⏱️ 30.11.2021):
	```
	conda install -c conda-forge sentence-transformers
	```
</details>
<details><summary><b><a href="https://github.com/JohnSnowLabs/spark-nlp">spark-nlp</a></b> (🥈34 ·  ⭐ 2.6K) - State of the Art Natural Language Processing. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/JohnSnowLabs/spark-nlp) (👨‍💻 110 · 🔀 530 · 📋 620 - 13% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/JohnSnowLabs/spark-nlp
	```
- [PyPi](https://pypi.org/project/spark-nlp) (📥 1.4M / month · 📦 9 · ⏱️ 08.02.2022):
	```
	pip install spark-nlp
	```
</details>
<details><summary><b><a href="https://github.com/google/sentencepiece">sentencepiece</a></b> (🥈33 ·  ⭐ 5.7K · 💤) - Unsupervised text tokenizer for Neural Network-based.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/sentencepiece) (👨‍💻 57 · 🔀 790 · 📥 20K · 📦 13K · 📋 500 - 11% open · ⏱️ 02.07.2021):

	```
	git clone https://github.com/google/sentencepiece
	```
- [PyPi](https://pypi.org/project/sentencepiece) (📥 4.3M / month · 📦 350 · ⏱️ 18.06.2021):
	```
	pip install sentencepiece
	```
- [Conda](https://anaconda.org/conda-forge/sentencepiece) (📥 150K · ⏱️ 07.02.2022):
	```
	conda install -c conda-forge sentencepiece
	```
</details>
<details><summary><b><a href="https://github.com/OpenNMT/OpenNMT-py">OpenNMT</a></b> (🥈33 ·  ⭐ 5.4K) - Open Source Neural Machine Translation in PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/OpenNMT/OpenNMT-py) (👨‍💻 170 · 🔀 2K · 📦 120 · 📋 1.3K - 9% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/OpenNMT/OpenNMT-py
	```
- [PyPi](https://pypi.org/project/OpenNMT-py) (📥 20K / month · 📦 8 · ⏱️ 14.09.2021):
	```
	pip install OpenNMT-py
	```
</details>
<details><summary><b><a href="https://github.com/huggingface/tokenizers">Tokenizers</a></b> (🥈33 ·  ⭐ 5.2K) - Fast State-of-the-Art Tokenizers optimized for Research and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/huggingface/tokenizers) (👨‍💻 50 · 🔀 430 · 📦 40 · 📋 560 - 27% open · ⏱️ 28.01.2022):

	```
	git clone https://github.com/huggingface/tokenizers
	```
- [PyPi](https://pypi.org/project/tokenizers) (📥 4.4M / month · 📦 93 · ⏱️ 17.01.2022):
	```
	pip install tokenizers
	```
- [Conda](https://anaconda.org/conda-forge/tokenizers) (📥 110K · ⏱️ 18.01.2022):
	```
	conda install -c conda-forge tokenizers
	```
</details>
<details><summary><b><a href="https://github.com/dedupeio/dedupe">Dedupe</a></b> (🥈33 ·  ⭐ 3.3K) - A python library for accurate and scalable fuzzy matching, record.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dedupeio/dedupe) (👨‍💻 63 · 🔀 460 · 📦 210 · 📋 680 - 4% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/dedupeio/dedupe
	```
- [PyPi](https://pypi.org/project/dedupe) (📥 280K / month · 📦 47 · ⏱️ 03.02.2022):
	```
	pip install dedupe
	```
- [Conda](https://anaconda.org/conda-forge/dedupe) (📥 1.2K · ⏱️ 04.02.2022):
	```
	conda install -c conda-forge dedupe
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/text">torchtext</a></b> (🥈33 ·  ⭐ 2.9K) - Data loaders and abstractions for text and NLP. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/text) (👨‍💻 120 · 🔀 680 · 📋 690 - 47% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/pytorch/text
	```
- [PyPi](https://pypi.org/project/torchtext) (📥 140K / month · 📦 430 · ⏱️ 27.01.2022):
	```
	pip install torchtext
	```
</details>
<details><summary><b><a href="https://github.com/stanfordnlp/stanza">stanza</a></b> (🥈32 ·  ⭐ 6K) - Official Stanford NLP Python Library for Many Human Languages. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/stanfordnlp/stanza) (👨‍💻 41 · 🔀 750 · 📦 840 · 📋 640 - 10% open · ⏱️ 26.01.2022):

	```
	git clone https://github.com/stanfordnlp/stanza
	```
- [PyPi](https://pypi.org/project/stanza) (📥 380K / month · 📦 49 · ⏱️ 05.10.2021):
	```
	pip install stanza
	```
- [Conda](https://anaconda.org/stanfordnlp/stanza) (📥 4.6K · ⏱️ 05.10.2021):
	```
	conda install -c stanfordnlp stanza
	```
</details>
<details><summary><b><a href="https://github.com/rspeer/python-ftfy">ftfy</a></b> (🥈31 ·  ⭐ 3.2K) - Fixes mojibake and other glitches in Unicode text, after the fact. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rspeer/python-ftfy) (👨‍💻 18 · 🔀 110 · 📦 4.8K · 📋 130 - 7% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/rspeer/python-ftfy
	```
- [PyPi](https://pypi.org/project/ftfy) (📥 1.5M / month · 📦 490 · ⏱️ 09.02.2022):
	```
	pip install ftfy
	```
- [Conda](https://anaconda.org/conda-forge/ftfy) (📥 140K · ⏱️ 25.05.2021):
	```
	conda install -c conda-forge ftfy
	```
</details>
<details><summary><b><a href="https://github.com/chartbeat-labs/textacy">textacy</a></b> (🥈31 ·  ⭐ 1.9K) - NLP, before and after spaCy. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/chartbeat-labs/textacy) (👨‍💻 31 · 🔀 230 · 📋 250 - 10% open · ⏱️ 06.12.2021):

	```
	git clone https://github.com/chartbeat-labs/textacy
	```
- [PyPi](https://pypi.org/project/textacy) (📥 45K / month · 📦 100 · ⏱️ 06.12.2021):
	```
	pip install textacy
	```
- [Conda](https://anaconda.org/conda-forge/textacy) (📥 100K · ⏱️ 06.02.2022):
	```
	conda install -c conda-forge textacy
	```
</details>
<details><summary><b><a href="https://github.com/jamesturk/jellyfish">jellyfish</a></b> (🥈31 ·  ⭐ 1.6K) - a python library for doing approximate and phonetic matching of.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/jamesturk/jellyfish) (👨‍💻 25 · 🔀 150 · 📦 3.2K · 📋 110 - 8% open · ⏱️ 07.01.2022):

	```
	git clone https://github.com/jamesturk/jellyfish
	```
- [PyPi](https://pypi.org/project/jellyfish) (📥 1.8M / month · 📦 400 · ⏱️ 07.01.2022):
	```
	pip install jellyfish
	```
- [Conda](https://anaconda.org/conda-forge/jellyfish) (📥 170K · ⏱️ 09.01.2022):
	```
	conda install -c conda-forge jellyfish
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/text">TensorFlow Text</a></b> (🥈31 ·  ⭐ 890) - Making text a first-class citizen in TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/text) (👨‍💻 73 · 🔀 180 · 📦 1.4K · 📋 190 - 35% open · ⏱️ 06.02.2022):

	```
	git clone https://github.com/tensorflow/text
	```
- [PyPi](https://pypi.org/project/tensorflow-text) (📥 2M / month · 📦 69 · ⏱️ 04.02.2022):
	```
	pip install tensorflow-text
	```
</details>
<details><summary><b><a href="https://github.com/deepmipt/DeepPavlov">DeepPavlov</a></b> (🥈30 ·  ⭐ 5.6K) - An open source library for deep learning end-to-end dialog.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmipt/DeepPavlov) (👨‍💻 67 · 🔀 990 · 📦 240 · 📋 620 - 18% open · ⏱️ 16.12.2021):

	```
	git clone https://github.com/deepmipt/DeepPavlov
	```
- [PyPi](https://pypi.org/project/deeppavlov) (📥 9.5K / month · 📦 6 · ⏱️ 16.12.2021):
	```
	pip install deeppavlov
	```
</details>
<details><summary><b><a href="https://github.com/NVIDIA/NeMo">NeMo</a></b> (🥈30 ·  ⭐ 3.9K) - NeMo: a toolkit for conversational AI. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NVIDIA/NeMo) (👨‍💻 130 · 🔀 850 · 📥 4K · 📋 970 - 7% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/NVIDIA/NeMo
	```
- [PyPi](https://pypi.org/project/nemo-toolkit) (📥 12K / month · 📦 7 · ⏱️ 05.02.2022):
	```
	pip install nemo-toolkit
	```
</details>
<details><summary><b><a href="https://github.com/makcedward/nlpaug">nlpaug</a></b> (🥈30 ·  ⭐ 2.9K) - Data augmentation for NLP. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/makcedward/nlpaug) (👨‍💻 26 · 🔀 330 · 📦 250 · 📋 170 - 16% open · ⏱️ 04.01.2022):

	```
	git clone https://github.com/makcedward/nlpaug
	```
- [PyPi](https://pypi.org/project/nlpaug) (📥 41K / month · 📦 14 · ⏱️ 23.12.2021):
	```
	pip install nlpaug
	```
- [Conda](https://anaconda.org/conda-forge/nlpaug) (📥 1.2K · ⏱️ 25.12.2021):
	```
	conda install -c conda-forge nlpaug
	```
</details>
<details><summary><b><a href="https://github.com/snowballstem/snowball">snowballstemmer</a></b> (🥈30 ·  ⭐ 540 · 📉) - Snowball compiler and stemming algorithms. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/snowballstem/snowball) (👨‍💻 28 · 🔀 150 · 📦 4 · 📋 69 - 36% open · ⏱️ 17.12.2021):

	```
	git clone https://github.com/snowballstem/snowball
	```
- [PyPi](https://pypi.org/project/snowballstemmer) (📥 6.2M / month · 📦 6.7K · ⏱️ 16.11.2021):
	```
	pip install snowballstemmer
	```
- [Conda](https://anaconda.org/conda-forge/snowballstemmer) (📥 3.8M · ⏱️ 17.11.2021):
	```
	conda install -c conda-forge snowballstemmer
	```
</details>
<details><summary><b><a href="https://github.com/dmlc/gluon-nlp">GluonNLP</a></b> (🥈29 ·  ⭐ 2.4K) - Toolkit that enables easy text preprocessing, datasets loading.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/dmlc/gluon-nlp) (👨‍💻 82 · 🔀 520 · 📦 710 · 📋 560 - 46% open · ⏱️ 24.08.2021):

	```
	git clone https://github.com/dmlc/gluon-nlp
	```
- [PyPi](https://pypi.org/project/gluonnlp) (📥 99K / month · 📦 22 · ⏱️ 13.08.2020):
	```
	pip install gluonnlp
	```
</details>
<details><summary><b><a href="https://github.com/cltk/cltk">CLTK</a></b> (🥈29 ·  ⭐ 710) - The Classical Language Toolkit. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cltk/cltk) (👨‍💻 110 · 🔀 310 · 📥 25 · 📦 190 · 📋 510 - 4% open · ⏱️ 06.02.2022):

	```
	git clone https://github.com/cltk/cltk
	```
- [PyPi](https://pypi.org/project/cltk) (📥 2.5K / month · 📦 42 · ⏱️ 04.02.2022):
	```
	pip install cltk
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/pytext">PyText</a></b> (🥈28 ·  ⭐ 6.3K) - A natural language modeling framework based on PyTorch. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/pytext) (👨‍💻 220 · 🔀 800 · 📥 290 · 📦 100 · 📋 220 - 66% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/facebookresearch/pytext
	```
- [PyPi](https://pypi.org/project/pytext-nlp) (📥 280 / month · 📦 1 · ⏱️ 08.06.2020):
	```
	pip install pytext-nlp
	```
</details>
<details><summary><b><a href="https://github.com/deepset-ai/haystack">haystack</a></b> (🥈28 ·  ⭐ 4.1K) - Haystack is an open source NLP framework that leverages Transformer.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/deepset-ai/haystack) (👨‍💻 97 · 🔀 670 · 📥 3 · 📋 1.2K - 14% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/deepset-ai/haystack
	```
- [PyPi](https://pypi.org/project/haystack) (📥 840 / month · 📦 85 · ⏱️ 15.12.2021):
	```
	pip install haystack
	```
</details>
<details><summary><b><a href="https://github.com/google-research/text-to-text-transfer-transformer">T5</a></b> (🥈28 ·  ⭐ 3.9K) - Code for the paper Exploring the Limits of Transfer Learning with a.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google-research/text-to-text-transfer-transformer) (👨‍💻 44 · 🔀 540 · 📦 82 · 📋 400 - 16% open · ⏱️ 04.02.2022):

	```
	git clone https://github.com/google-research/text-to-text-transfer-transformer
	```
- [PyPi](https://pypi.org/project/t5) (📥 6.1K / month · 📦 2 · ⏱️ 18.10.2021):
	```
	pip install t5
	```
</details>
<details><summary><b><a href="https://github.com/miso-belica/sumy">Sumy</a></b> (🥈28 ·  ⭐ 2.7K) - Module for automatic summarization of text documents and HTML pages. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/miso-belica/sumy) (👨‍💻 21 · 🔀 460 · 📦 1.1K · 📋 98 - 15% open · ⏱️ 23.11.2021):

	```
	git clone https://github.com/miso-belica/sumy
	```
- [PyPi](https://pypi.org/project/sumy) (📥 26K / month · 📦 100 · ⏱️ 21.10.2021):
	```
	pip install sumy
	```
- [Conda](https://anaconda.org/conda-forge/sumy) (📥 620 · ⏱️ 22.10.2021):
	```
	conda install -c conda-forge sumy
	```
</details>
<details><summary><b><a href="https://github.com/life4/textdistance">TextDistance</a></b> (🥈28 ·  ⭐ 2.6K) - Compute distance between sequences. 30+ algorithms, pure python.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/life4/textdistance) (👨‍💻 11 · 🔀 200 · 📥 460 · 📦 1.7K · ⏱️ 29.11.2021):

	```
	git clone https://github.com/life4/textdistance
	```
- [PyPi](https://pypi.org/project/textdistance) (📥 290K / month · 📦 39 · ⏱️ 27.10.2021):
	```
	pip install textdistance
	```
- [Conda](https://anaconda.org/conda-forge/textdistance) (📥 73K · ⏱️ 27.10.2021):
	```
	conda install -c conda-forge textdistance
	```
</details>
<details><summary><b><a href="https://github.com/DerwenAI/pytextrank">PyTextRank</a></b> (🥈28 ·  ⭐ 1.7K) - Python implementation of TextRank for phrase extraction and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/DerwenAI/pytextrank) (👨‍💻 18 · 🔀 320 · 📦 230 · 📋 83 - 27% open · ⏱️ 04.02.2022):

	```
	git clone https://github.com/DerwenAI/pytextrank
	```
- [PyPi](https://pypi.org/project/pytextrank) (📥 21K / month · 📦 12 · ⏱️ 10.10.2021):
	```
	pip install pytextrank
	```
</details>
<details><summary><b><a href="https://github.com/Ciphey/Ciphey">Ciphey</a></b> (🥈27 ·  ⭐ 9.4K) - Automatically decrypt encryptions without knowing the key or cipher,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Ciphey/Ciphey) (👨‍💻 46 · 🔀 580 · 📋 290 - 17% open · ⏱️ 03.11.2021):

	```
	git clone https://github.com/Ciphey/Ciphey
	```
- [PyPi](https://pypi.org/project/ciphey) (📥 11K / month · ⏱️ 06.06.2021):
	```
	pip install ciphey
	```
- [Docker Hub](https://hub.docker.com/r/remnux/ciphey) (📥 15K · ⭐ 5 · ⏱️ 05.02.2022):
	```
	docker pull remnux/ciphey
	```
</details>
<details><summary><b><a href="https://github.com/cjhutto/vaderSentiment">vaderSentiment</a></b> (🥈27 ·  ⭐ 3.4K · 💤) - VADER Sentiment Analysis. VADER (Valence Aware Dictionary.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cjhutto/vaderSentiment) (👨‍💻 10 · 🔀 830 · 📦 3.5K · 📋 110 - 30% open · ⏱️ 15.03.2021):

	```
	git clone https://github.com/cjhutto/vaderSentiment
	```
- [PyPi](https://pypi.org/project/vadersentiment) (📥 440K / month · 📦 170 · ⏱️ 22.05.2020):
	```
	pip install vadersentiment
	```
- [Conda](https://anaconda.org/conda-forge/vadersentiment) (📥 8K · ⏱️ 22.03.2021):
	```
	conda install -c conda-forge vadersentiment
	```
</details>
<details><summary><b><a href="https://github.com/huggingface/neuralcoref">neuralcoref</a></b> (🥈27 ·  ⭐ 2.5K · 💤) - Fast Coreference Resolution in spaCy with Neural Networks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/huggingface/neuralcoref) (👨‍💻 21 · 🔀 430 · 📥 310 · 📦 440 · 📋 290 - 16% open · ⏱️ 22.06.2021):

	```
	git clone https://github.com/huggingface/neuralcoref
	```
- [PyPi](https://pypi.org/project/neuralcoref) (📥 55K / month · 📦 14 · ⏱️ 08.04.2019):
	```
	pip install neuralcoref
	```
- [Conda](https://anaconda.org/conda-forge/neuralcoref) (📥 11K · ⏱️ 21.02.2020):
	```
	conda install -c conda-forge neuralcoref
	```
</details>
<details><summary><b><a href="https://github.com/dwyl/english-words">english-words</a></b> (🥉26 ·  ⭐ 6.5K) - A text file containing 479k English words for all your.. <code><a href="http://bit.ly/3rvuUlR">Unlicense</a></code></summary>

- [GitHub](https://github.com/dwyl/english-words) (👨‍💻 26 · 🔀 1.3K · 📋 73 - 61% open · ⏱️ 20.10.2021):

	```
	git clone https://github.com/dwyl/english-words
	```
- [PyPi](https://pypi.org/project/english-words) (📥 17K / month · 📦 6 · ⏱️ 29.01.2022):
	```
	pip install english-words
	```
</details>
<details><summary><b><a href="https://github.com/explosion/spacy-transformers">spacy-transformers</a></b> (🥉26 ·  ⭐ 1.1K) - Use pretrained transformers like BERT, XLNet and GPT-2.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>spacy</code></summary>

- [GitHub](https://github.com/explosion/spacy-transformers) (👨‍💻 18 · 🔀 140 · 📦 390 · ⏱️ 13.01.2022):

	```
	git clone https://github.com/explosion/spacy-transformers
	```
- [PyPi](https://pypi.org/project/spacy-transformers) (📥 87K / month · 📦 13 · ⏱️ 14.01.2022):
	```
	pip install spacy-transformers
	```
- [Conda](https://anaconda.org/conda-forge/spacy-transformers) (📥 380 · ⏱️ 14.01.2022):
	```
	conda install -c conda-forge spacy-transformers
	```
</details>
<details><summary><b><a href="https://github.com/snipsco/snips-nlu">Snips NLU</a></b> (🥉25 ·  ⭐ 3.6K · 💤) - Snips Python library to extract meaning from text. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/snipsco/snips-nlu) (👨‍💻 22 · 🔀 500 · 📋 260 - 23% open · ⏱️ 03.05.2021):

	```
	git clone https://github.com/snipsco/snips-nlu
	```
- [PyPi](https://pypi.org/project/snips-nlu) (📥 4.2K / month · 📦 11 · ⏱️ 15.01.2020):
	```
	pip install snips-nlu
	```
</details>
<details><summary><b><a href="https://github.com/fastnlp/fastNLP">fastNLP</a></b> (🥉25 ·  ⭐ 2.5K · 📉) - fastNLP: A Modularized and Extensible NLP Framework. Currently.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/fastnlp/fastNLP) (👨‍💻 54 · 🔀 400 · 📥 65 · 📦 55 · 📋 180 - 19% open · ⏱️ 06.12.2021):

	```
	git clone https://github.com/fastnlp/fastNLP
	```
- [PyPi](https://pypi.org/project/fastnlp) (📥 1.1K / month · 📦 3 · ⏱️ 04.02.2019):
	```
	pip install fastnlp
	```
</details>
<details><summary><b><a href="https://github.com/PetrochukM/PyTorch-NLP">pytorch-nlp</a></b> (🥉25 ·  ⭐ 2K · 💤) - Basic Utilities for PyTorch Natural Language Processing.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PetrochukM/PyTorch-NLP) (👨‍💻 18 · 🔀 240 · 📦 330 · 📋 67 - 26% open · ⏱️ 10.07.2021):

	```
	git clone https://github.com/PetrochukM/PyTorch-NLP
	```
- [PyPi](https://pypi.org/project/pytorch-nlp) (📥 7.1K / month · 📦 17 · ⏱️ 04.11.2019):
	```
	pip install pytorch-nlp
	```
</details>
<details><summary><b><a href="https://github.com/JasonKessler/scattertext">scattertext</a></b> (🥉25 ·  ⭐ 1.7K) - Beautiful visualizations of how language differs among document.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/JasonKessler/scattertext) (👨‍💻 12 · 🔀 240 · 📦 260 · 📋 85 - 20% open · ⏱️ 15.11.2021):

	```
	git clone https://github.com/JasonKessler/scattertext
	```
- [PyPi](https://pypi.org/project/scattertext) (📥 3.9K / month · 📦 10 · ⏱️ 15.11.2021):
	```
	pip install scattertext
	```
- [Conda](https://anaconda.org/conda-forge/scattertext) (📥 60K · ⏱️ 15.11.2021):
	```
	conda install -c conda-forge scattertext
	```
</details>
<details><summary><b><a href="https://github.com/allenai/scispacy">SciSpacy</a></b> (🥉25 ·  ⭐ 1.1K) - A full spaCy pipeline and models for scientific/biomedical documents. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/allenai/scispacy) (👨‍💻 22 · 🔀 150 · 📦 400 · 📋 240 - 14% open · ⏱️ 03.02.2022):

	```
	git clone https://github.com/allenai/scispacy
	```
- [PyPi](https://pypi.org/project/scispacy) (📥 26K / month · 📦 11 · ⏱️ 12.02.2021):
	```
	pip install scispacy
	```
</details>
<details><summary><b><a href="https://github.com/NTMC-Community/MatchZoo">MatchZoo</a></b> (🥉24 ·  ⭐ 3.6K · 💤) - Facilitating the design, comparison and sharing of deep.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NTMC-Community/MatchZoo) (👨‍💻 36 · 🔀 910 · 📦 10 · 📋 460 - 6% open · ⏱️ 02.06.2021):

	```
	git clone https://github.com/NTMC-Community/MatchZoo
	```
- [PyPi](https://pypi.org/project/matchzoo) (📥 91 / month · ⏱️ 24.10.2019):
	```
	pip install matchzoo
	```
</details>
<details><summary><b><a href="https://github.com/explosion/sense2vec">sense2vec</a></b> (🥉24 ·  ⭐ 1.3K) - Contextually-keyed word vectors. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/explosion/sense2vec) (👨‍💻 17 · 🔀 220 · 📥 25K · 📦 120 · 📋 110 - 17% open · ⏱️ 16.08.2021):

	```
	git clone https://github.com/explosion/sense2vec
	```
- [PyPi](https://pypi.org/project/sense2vec) (📥 9.3K / month · 📦 8 · ⏱️ 19.04.2021):
	```
	pip install sense2vec
	```
- [Conda](https://anaconda.org/conda-forge/sense2vec) (📥 24K · ⏱️ 14.07.2021):
	```
	conda install -c conda-forge sense2vec
	```
</details>
<details><summary><b><a href="https://github.com/awslabs/sockeye">Sockeye</a></b> (🥉24 ·  ⭐ 1K) - Sequence-to-sequence framework with a focus on Neural Machine.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/awslabs/sockeye) (👨‍💻 55 · 🔀 300 · 📥 14 · 📋 270 - 3% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/awslabs/sockeye
	```
- [PyPi](https://pypi.org/project/sockeye) (📥 1.3K / month · 📦 2 · ⏱️ 09.02.2022):
	```
	pip install sockeye
	```
</details>
<details><summary><b><a href="https://github.com/BrikerMan/Kashgari">Kashgari</a></b> (🥉23 ·  ⭐ 2.3K · 💤) - Kashgari is a production-level NLP Transfer learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/BrikerMan/Kashgari) (👨‍💻 21 · 🔀 430 · 📦 50 · 📋 360 - 10% open · ⏱️ 09.07.2021):

	```
	git clone https://github.com/BrikerMan/Kashgari
	```
- [PyPi](https://pypi.org/project/kashgari-tf) (📥 100 / month · 📦 2 · ⏱️ 18.10.2019):
	```
	pip install kashgari-tf
	```
</details>
<details><summary><b><a href="https://github.com/bytedance/lightseq">lightseq</a></b> (🥉23 ·  ⭐ 2K) - LightSeq: A High Performance Library for Sequence Processing and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bytedance/lightseq) (👨‍💻 8 · 🔀 210 · 📥 560 · 📋 150 - 53% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/bytedance/lightseq
	```
- [PyPi](https://pypi.org/project/lightseq) (📥 1.7K / month · ⏱️ 26.01.2022):
	```
	pip install lightseq
	```
</details>
<details><summary><b><a href="https://github.com/recognai/rubrix">rubrix</a></b> (🥉23 ·  ⭐ 840 · ➕) - Python framework for data-centric NLP. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/recognai/rubrix) (👨‍💻 18 · 🔀 72 · 📋 420 - 17% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/recognai/rubrix
	```
- [PyPi](https://pypi.org/project/rubrix) (📥 1.4K / month · ⏱️ 02.02.2022):
	```
	pip install rubrix
	```
- [Conda](https://anaconda.org/conda-forge/rubrix) (📥 170 · ⏱️ 03.02.2022):
	```
	conda install -c conda-forge rubrix
	```
</details>
<details><summary><b><a href="https://github.com/nipunsadvilkar/pySBD">pySBD</a></b> (🥉23 ·  ⭐ 410 · 💤) - pySBD (Python Sentence Boundary Disambiguation) is a rule-based sentence.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nipunsadvilkar/pySBD) (👨‍💻 6 · 🔀 48 · 📦 280 · 📋 60 - 20% open · ⏱️ 11.02.2021):

	```
	git clone https://github.com/nipunsadvilkar/pySBD
	```
- [PyPi](https://pypi.org/project/pysbd) (📥 45K / month · 📦 3 · ⏱️ 11.02.2021):
	```
	pip install pysbd
	```
- [Conda](https://anaconda.org/conda-forge/pysbd) (📥 210 · ⏱️ 11.10.2021):
	```
	conda install -c conda-forge pysbd
	```
</details>
<details><summary><b><a href="https://github.com/minimaxir/gpt-2-simple">gpt-2-simple</a></b> (🥉22 ·  ⭐ 2.9K) - Python package to easily retrain OpenAIs GPT-2 text-.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/minimaxir/gpt-2-simple) (👨‍💻 18 · 🔀 590 · 📥 290 · 📋 240 - 61% open · ⏱️ 18.10.2021):

	```
	git clone https://github.com/minimaxir/gpt-2-simple
	```
- [PyPi](https://pypi.org/project/gpt-2-simple) (📥 5.5K / month · 📦 5 · ⏱️ 18.10.2021):
	```
	pip install gpt-2-simple
	```
</details>
<details><summary><b><a href="https://github.com/IntelLabs/nlp-architect">NLP Architect</a></b> (🥉22 ·  ⭐ 2.8K) - A model library for exploring state-of-the-art deep learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/IntelLabs/nlp-architect) (👨‍💻 37 · 🔀 440 · 📦 8 · 📋 130 - 15% open · ⏱️ 12.09.2021):

	```
	git clone https://github.com/IntelLabs/nlp-architect
	```
- [PyPi](https://pypi.org/project/nlp-architect) (📥 290 / month · ⏱️ 12.04.2020):
	```
	pip install nlp-architect
	```
</details>
<details><summary><b><a href="https://github.com/jbesomi/texthero">Texthero</a></b> (🥉22 ·  ⭐ 2.4K · 💤) - Text preprocessing, representation and visualization from zero to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jbesomi/texthero) (👨‍💻 18 · 🔀 210 · 📥 87 · 📋 140 - 56% open · ⏱️ 19.07.2021):

	```
	git clone https://github.com/jbesomi/texthero
	```
- [PyPi](https://pypi.org/project/texthero) (📥 24K / month · 📦 4 · ⏱️ 01.07.2021):
	```
	pip install texthero
	```
</details>
<details><summary><b><a href="https://github.com/utterworks/fast-bert">fast-bert</a></b> (🥉22 ·  ⭐ 1.7K) - Super easy library for BERT based NLP models. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/utterworks/fast-bert) (👨‍💻 35 · 🔀 330 · 📋 250 - 61% open · ⏱️ 10.01.2022):

	```
	git clone https://github.com/utterworks/fast-bert
	```
- [PyPi](https://pypi.org/project/fast-bert) (📥 1.5K / month · 📦 2 · ⏱️ 10.01.2022):
	```
	pip install fast-bert
	```
</details>
<details><summary><b><a href="https://github.com/deepset-ai/FARM">FARM</a></b> (🥉22 ·  ⭐ 1.5K) - Fast & easy transfer learning for NLP. Harvesting language models.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepset-ai/FARM) (👨‍💻 37 · 🔀 210 · 📋 430 - 8% open · ⏱️ 23.11.2021):

	```
	git clone https://github.com/deepset-ai/FARM
	```
- [PyPi](https://pypi.org/project/farm) (📥 8.1K / month · 📦 2 · ⏱️ 10.06.2021):
	```
	pip install farm
	```
- [Conda](https://anaconda.org/conda-forge/farm) (📥 890 · ⏱️ 14.06.2021):
	```
	conda install -c conda-forge farm
	```
</details>
<details><summary><b><a href="https://github.com/Hironsan/anago">anaGo</a></b> (🥉22 ·  ⭐ 1.4K · 💤) - Bidirectional LSTM-CRF and ELMo for Named-Entity Recognition,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Hironsan/anago) (👨‍💻 11 · 🔀 360 · 📦 27 · 📋 110 - 33% open · ⏱️ 01.04.2021):

	```
	git clone https://github.com/Hironsan/anago
	```
- [PyPi](https://pypi.org/project/anago) (📥 510 / month · 📦 5 · ⏱️ 17.07.2018):
	```
	pip install anago
	```
</details>
<details><summary><b><a href="https://github.com/anhaidgroup/deepmatcher">DeepMatcher</a></b> (🥉21 ·  ⭐ 4K · 💤) - Python package for performing Entity and Text Matching using.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/anhaidgroup/deepmatcher) (👨‍💻 7 · 🔀 1.5K · 📦 14 · 📋 76 - 71% open · ⏱️ 13.06.2021):

	```
	git clone https://github.com/anhaidgroup/deepmatcher
	```
- [PyPi](https://pypi.org/project/deepmatcher) (📥 530 / month · ⏱️ 13.06.2021):
	```
	pip install deepmatcher
	```
</details>
<details><summary><b><a href="https://github.com/nyu-mll/jiant">jiant</a></b> (🥉21 ·  ⭐ 1.4K) - jiant is an nlp toolkit. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nyu-mll/jiant) (👨‍💻 56 · 🔀 260 · 📦 2 · 📋 550 - 11% open · ⏱️ 03.02.2022):

	```
	git clone https://github.com/nyu-mll/jiant
	```
- [PyPi](https://pypi.org/project/jiant) (📥 110 / month · ⏱️ 10.05.2021):
	```
	pip install jiant
	```
</details>
<details><summary><b><a href="https://github.com/thunlp/OpenPrompt">OpenPrompt</a></b> (🥉21 ·  ⭐ 1.1K · 🐣) - An Open-Source Framework for Prompt-Learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/thunlp/OpenPrompt) (👨‍💻 10 · 🔀 110 · 📦 6 · 📋 91 - 20% open · ⏱️ 24.01.2022):

	```
	git clone https://github.com/thunlp/OpenPrompt
	```
- [PyPi](https://pypi.org/project/openprompt) (📥 330 / month · ⏱️ 09.12.2021):
	```
	pip install openprompt
	```
</details>
<details><summary><b><a href="https://github.com/unitaryai/detoxify">detoxify</a></b> (🥉21 ·  ⭐ 380 · ➕) - Trained models & code to predict toxic comments on all 3 Jigsaw.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/unitaryai/detoxify) (👨‍💻 4 · 🔀 41 · 📥 32K · 📦 33 · 📋 23 - 43% open · ⏱️ 14.01.2022):

	```
	git clone https://github.com/unitaryai/detoxify
	```
- [PyPi](https://pypi.org/project/detoxify) (📥 5.8K / month · 📦 1 · ⏱️ 27.10.2021):
	```
	pip install detoxify
	```
</details>
<details><summary><b><a href="https://github.com/qdrant/qdrant">qdrant</a></b> (🥉20 ·  ⭐ 1.1K · ➕) - Qdrant - vector similarity search engine with extended filtering.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/qdrant/qdrant) (👨‍💻 22 · 🔀 71 · 📋 89 - 26% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/qdrant/qdrant
	```
</details>
<details><summary><b><a href="https://github.com/IndicoDataSolutions/finetune">finetune</a></b> (🥉20 ·  ⭐ 660) - Scikit-learn style model finetuning for NLP. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/IndicoDataSolutions/finetune) (👨‍💻 19 · 🔀 71 · 📦 9 · 📋 140 - 15% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/IndicoDataSolutions/finetune
	```
- [PyPi](https://pypi.org/project/finetune) (📥 86 / month · 📦 2 · ⏱️ 20.12.2021):
	```
	pip install finetune
	```
</details>
<details><summary><b><a href="https://github.com/RUCAIBox/TextBox">TextBox</a></b> (🥉18 ·  ⭐ 340) - TextBox is an open-source library for building text generation system. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/RUCAIBox/TextBox) (👨‍💻 13 · 🔀 58 · 📦 5 · 📋 18 - 16% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/RUCAIBox/TextBox
	```
- [PyPi](https://pypi.org/project/textbox) (📥 46 / month · ⏱️ 15.04.2021):
	```
	pip install textbox
	```
</details>
<details><summary><b><a href="https://github.com/thunlp/OpenNRE">OpenNRE</a></b> (🥉17 ·  ⭐ 3.5K) - An Open-Source Package for Neural Relation Extraction (NRE). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/thunlp/OpenNRE) (👨‍💻 10 · 🔀 920 · 📋 340 - 6% open · ⏱️ 09.12.2021):

	```
	git clone https://github.com/thunlp/OpenNRE
	```
</details>
<details><summary><b><a href="https://github.com/PKSHATechnology-Research/camphr">Camphr</a></b> (🥉16 ·  ⭐ 340) - Camphr - NLP libary for creating pipeline components. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>spacy</code></summary>

- [GitHub](https://github.com/PKSHATechnology-Research/camphr) (👨‍💻 7 · 🔀 17 · 📋 28 - 7% open · ⏱️ 18.08.2021):

	```
	git clone https://github.com/PKSHATechnology-Research/camphr
	```
- [PyPi](https://pypi.org/project/camphr) (📥 230 / month · 📦 2 · ⏱️ 28.07.2021):
	```
	pip install camphr
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/translate">Translate</a></b> (🥉15 ·  ⭐ 720) - Translate - a PyTorch Language Library. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/translate) (👨‍💻 87 · 🔀 170 · 📋 93 - 70% open · ⏱️ 06.10.2021):

	```
	git clone https://github.com/pytorch/translate
	```
- [PyPi](https://pypi.org/project/pytorch-translate) (📥 3 / month · ⏱️ 01.05.2018):
	```
	pip install pytorch-translate
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/vizseq">VizSeq</a></b> (🥉14 ·  ⭐ 380) - An Analysis Toolkit for Natural Language Generation (Translation,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/vizseq) (👨‍💻 3 · 🔀 45 · 📦 3 · 📋 16 - 43% open · ⏱️ 15.01.2022):

	```
	git clone https://github.com/facebookresearch/vizseq
	```
- [PyPi](https://pypi.org/project/vizseq) (📥 91 / month · ⏱️ 07.08.2020):
	```
	pip install vizseq
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/BLINK">BLINK</a></b> (🥉13 ·  ⭐ 810 · 💤) - Entity Linker solution. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/BLINK) (👨‍💻 16 · 🔀 140 · 📋 79 - 60% open · ⏱️ 02.04.2021):

	```
	git clone https://github.com/facebookresearch/BLINK
	```
</details>
<details><summary>Show 26 hidden projects...</summary>

- <b><a href="https://github.com/facebookresearch/fastText">fastText</a></b> (🥈34 ·  ⭐ 23K · 💀) - Library for fast text representation and classification. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/seatgeek/fuzzywuzzy">fuzzywuzzy</a></b> (🥈32 ·  ⭐ 8.6K) - Fuzzy String Matching in Python. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code>
- <b><a href="https://github.com/saffsd/langid.py">langid</a></b> (🥈27 ·  ⭐ 1.9K · 💀) - Stand-alone language identification system. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/aboSamoor/polyglot">polyglot</a></b> (🥉26 ·  ⭐ 2K · 💀) - Multilingual text (NLP) processing toolkit. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/vi3k6i5/flashtext">flashtext</a></b> (🥉25 ·  ⭐ 5K · 💀) - Extract Keywords from sentence or Replace keywords in sentences. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/minimaxir/textgenrnn">textgenrnn</a></b> (🥉25 ·  ⭐ 4.6K · 💀) - Easily train your own text-generating neural network of any.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/mchaput/whoosh">whoosh</a></b> (🥉23 ·  ⭐ 190 · ➕) - Pure-Python full-text search library. <code><a href="https://tldrlegal.com/search?q=BSD-1-Clause">❗️BSD-1-Clause</a></code>
- <b><a href="https://github.com/asyml/texar">Texar</a></b> (🥉22 ·  ⭐ 2.2K · 💀) - Toolkit for Machine Learning, Natural Language Processing, and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/VKCOM/YouTokenToMe">YouTokenToMe</a></b> (🥉22 ·  ⭐ 790 · 💀) - Unsupervised text tokenizer focused on computational efficiency. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/EricFillion/happy-transformer">happy-transformer</a></b> (🥉22 ·  ⭐ 260 · ➕) - A package built on top of Hugging Faces transformers.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>huggingface</code>
- <b><a href="https://github.com/Alir3z4/python-stop-words">stop-words</a></b> (🥉22 ·  ⭐ 140 · 💀) - Get list of common stop words in various languages in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/Delta-ML/delta">DELTA</a></b> (🥉21 ·  ⭐ 1.5K · 💀) - DELTA is a deep learning based natural language and speech.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/vrasneur/pyfasttext">pyfasttext</a></b> (🥉20 ·  ⭐ 230 · 💀) - Yet another Python binding for fastText. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/textpipe/textpipe">textpipe</a></b> (🥉19 ·  ⭐ 290 · 💤) - Textpipe: clean and extract metadata from text. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Ki6an/fastT5">fastT5</a></b> (🥉19 ·  ⭐ 250) - boost inference speed of T5 models by 5x & reduce the model size by 3x. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/Franck-Dernoncourt/NeuroNER">NeuroNER</a></b> (🥉18 ·  ⭐ 1.6K · 💀) - Named-entity recognition using neural networks. Easy-to-use and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/shaypal5/skift">skift</a></b> (🥉18 ·  ⭐ 230) - scikit-learn wrappers for Python fastText. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/koursaros-ai/nboost">nboost</a></b> (🥉17 ·  ⭐ 610 · 💀) - NBoost is a scalable, search-api-boosting platform for deploying.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/dsfsi/textaugment">textaugment</a></b> (🥉17 ·  ⭐ 210) - TextAugment: Text Augmentation Library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/victordibia/neuralqa">NeuralQA</a></b> (🥉15 ·  ⭐ 220 · 💀) - NeuralQA: A Usable Library for Question Answering on Large Datasets.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/feedly/transfer-nlp">TransferNLP</a></b> (🥉14 ·  ⭐ 290 · 💀) - NLP library designed for reproducible experimentation.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/as-ideas/headliner">Headliner</a></b> (🥉14 ·  ⭐ 230 · 💀) - Easy training and deployment of seq2seq models. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/jaidevd/numerizer">numerizer</a></b> (🥉14 ·  ⭐ 140) - A Python module to convert natural language numerics into ints and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/abelriboulot/onnxt5">ONNX-T5</a></b> (🥉13 ·  ⭐ 190 · 💀) - Summarization, translation, sentiment-analysis, text-generation.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/textvec/textvec">textvec</a></b> (🥉13 ·  ⭐ 180 · 💀) - Text vectorization tool to outperform TFIDF for classification.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/MartinoMensio/spacy-dbpedia-spotlight">spacy-dbpedia-spotlight</a></b> (🥉9 ·  ⭐ 50) - A spaCy wrapper for DBpedia Spotlight. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>spacy</code>
</details>
<br>

## Image Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for image & video processing, manipulation, and augmentation as well as libraries for computer vision tasks such as facial recognition, object detection, and classification._

<details><summary><b><a href="https://github.com/python-pillow/Pillow">Pillow</a></b> (🥇45 ·  ⭐ 9.4K) - The friendly PIL fork (Python Imaging Library). <code><a href="https://tldrlegal.com/search?q=PIL">❗️PIL</a></code></summary>

- [GitHub](https://github.com/python-pillow/Pillow) (👨‍💻 380 · 🔀 1.8K · 📋 2.4K - 6% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/python-pillow/Pillow
	```
- [PyPi](https://pypi.org/project/Pillow) (📥 37M / month · 📦 62K · ⏱️ 03.02.2022):
	```
	pip install Pillow
	```
- [Conda](https://anaconda.org/conda-forge/pillow) (📥 13M · ⏱️ 10.02.2022):
	```
	conda install -c conda-forge pillow
	```
</details>
<details><summary><b><a href="https://github.com/scikit-image/scikit-image">scikit-image</a></b> (🥇44 ·  ⭐ 4.8K) - Image processing in Python. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/scikit-image/scikit-image) (👨‍💻 540 · 🔀 1.9K · 📦 93K · 📋 2.4K - 13% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/scikit-image/scikit-image
	```
- [PyPi](https://pypi.org/project/scikit-image) (📥 5M / month · 📦 9K · ⏱️ 15.12.2021):
	```
	pip install scikit-image
	```
- [Conda](https://anaconda.org/conda-forge/scikit-image) (📥 3.2M · ⏱️ 17.12.2021):
	```
	conda install -c conda-forge scikit-image
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/vision">torchvision</a></b> (🥇41 ·  ⭐ 11K) - Datasets, Transforms and Models specific to Computer Vision. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/vision) (👨‍💻 460 · 🔀 5.6K · 📋 2.3K - 28% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/pytorch/vision
	```
- [PyPi](https://pypi.org/project/torchvision) (📥 2.9M / month · 📦 3.5K · ⏱️ 27.01.2022):
	```
	pip install torchvision
	```
- [Conda](https://anaconda.org/conda-forge/torchvision) (📥 170K · ⏱️ 06.02.2022):
	```
	conda install -c conda-forge torchvision
	```
</details>
<details><summary><b><a href="https://github.com/open-mmlab/mmdetection">MMDetection</a></b> (🥇37 ·  ⭐ 18K · 📈) - OpenMMLab Detection Toolbox and Benchmark. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/open-mmlab/mmdetection) (👨‍💻 300 · 🔀 6.6K · 📦 250 · 📋 5.2K - 9% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/open-mmlab/mmdetection
	```
- [PyPi](https://pypi.org/project/mmdet) (📥 33K / month · 📦 6 · ⏱️ 08.02.2022):
	```
	pip install mmdet
	```
</details>
<details><summary><b><a href="https://github.com/rwightman/pytorch-image-models">PyTorch Image Models</a></b> (🥇37 ·  ⭐ 16K) - PyTorch image models, scripts, pretrained weights --.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rwightman/pytorch-image-models) (👨‍💻 65 · 🔀 2.6K · 📥 900K · 📦 1.9K · 📋 460 - 14% open · ⏱️ 02.02.2022):

	```
	git clone https://github.com/rwightman/pytorch-image-models
	```
- [PyPi](https://pypi.org/project/timm) (📥 530K / month · 📦 67 · ⏱️ 17.01.2022):
	```
	pip install timm
	```
- [Conda](https://anaconda.org/conda-forge/timm) (📥 12K · ⏱️ 30.06.2021):
	```
	conda install -c conda-forge timm
	```
</details>
<details><summary><b><a href="https://github.com/imageio/imageio">imageio</a></b> (🥇37 ·  ⭐ 980) - Python library for reading and writing image data. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/imageio/imageio) (👨‍💻 85 · 🔀 200 · 📥 140 · 📦 56K · 📋 430 - 17% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/imageio/imageio
	```
- [PyPi](https://pypi.org/project/imageio) (📥 13M / month · 📦 2.6K · ⏱️ 07.02.2022):
	```
	pip install imageio
	```
- [Conda](https://anaconda.org/conda-forge/imageio) (📥 2.5M · ⏱️ 26.01.2022):
	```
	conda install -c conda-forge imageio
	```
</details>
<details><summary><b><a href="https://github.com/albumentations-team/albumentations">Albumentations</a></b> (🥈35 ·  ⭐ 9.6K) - Fast image augmentation library and an easy-to-use wrapper.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/albumentations-team/albumentations) (👨‍💻 100 · 🔀 1.2K · 📦 6.5K · 📋 580 - 41% open · ⏱️ 24.12.2021):

	```
	git clone https://github.com/albumentations-team/albumentations
	```
- [PyPi](https://pypi.org/project/albumentations) (📥 290K / month · 📦 180 · ⏱️ 04.10.2021):
	```
	pip install albumentations
	```
- [Conda](https://anaconda.org/conda-forge/albumentations) (📥 31K · ⏱️ 15.07.2021):
	```
	conda install -c conda-forge albumentations
	```
</details>
<details><summary><b><a href="https://github.com/Zulko/moviepy">MoviePy</a></b> (🥈35 ·  ⭐ 8.9K) - Video editing with Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Zulko/moviepy) (👨‍💻 140 · 🔀 1.2K · 📦 13K · 📋 1.2K - 28% open · ⏱️ 12.11.2021):

	```
	git clone https://github.com/Zulko/moviepy
	```
- [PyPi](https://pypi.org/project/moviepy) (📥 2.5M / month · 📦 720 · ⏱️ 15.12.2021):
	```
	pip install moviepy
	```
- [Conda](https://anaconda.org/conda-forge/moviepy) (📥 100K · ⏱️ 23.02.2020):
	```
	conda install -c conda-forge moviepy
	```
</details>
<details><summary><b><a href="https://github.com/kornia/kornia">Kornia</a></b> (🥈35 ·  ⭐ 5.9K) - Open Source Differentiable Computer Vision Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/kornia/kornia) (👨‍💻 150 · 🔀 570 · 📥 190 · 📦 970 · 📋 540 - 25% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/kornia/kornia
	```
- [PyPi](https://pypi.org/project/kornia) (📥 290K / month · 📦 44 · ⏱️ 31.01.2022):
	```
	pip install kornia
	```
- [Conda](https://anaconda.org/conda-forge/kornia) (📥 11K · ⏱️ 01.02.2022):
	```
	conda install -c conda-forge kornia
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/detectron2">detectron2</a></b> (🥈34 ·  ⭐ 20K) - Detectron2 is a platform for object detection, segmentation.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/detectron2) (👨‍💻 200 · 🔀 5.1K · 📦 490 · 📋 2.8K - 5% open · ⏱️ 07.02.2022):

	```
	git clone https://github.com/facebookresearch/detectron2
	```
- [PyPi](https://pypi.org/project/detectron2) (📦 2 · ⏱️ 06.02.2020):
	```
	pip install detectron2
	```
- [Conda](https://anaconda.org/conda-forge/detectron2) (📥 39K · ⏱️ 11.01.2022):
	```
	conda install -c conda-forge detectron2
	```
</details>
<details><summary><b><a href="https://github.com/deepinsight/insightface">InsightFace</a></b> (🥈34 ·  ⭐ 11K) - State-of-the-art 2D and 3D Face Analysis Project. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepinsight/insightface) (👨‍💻 37 · 🔀 3.6K · 📦 130 · 📋 1.8K - 54% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/deepinsight/insightface
	```
- [PyPi](https://pypi.org/project/insightface) (📥 22K / month · 📦 5 · ⏱️ 29.01.2022):
	```
	pip install insightface
	```
</details>
<details><summary><b><a href="https://github.com/opencv/opencv-python">opencv-python</a></b> (🥈34 ·  ⭐ 2.5K) - Automated CI toolchain to produce precompiled opencv-python,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/opencv/opencv-python) (👨‍💻 36 · 🔀 490 · 📋 510 - 6% open · ⏱️ 25.01.2022):

	```
	git clone https://github.com/opencv/opencv-python
	```
- [PyPi](https://pypi.org/project/opencv-python) (📥 4.9M / month · 📦 8.7K · ⏱️ 29.12.2021):
	```
	pip install opencv-python
	```
</details>
<details><summary><b><a href="https://github.com/ageitgey/face_recognition">Face Recognition</a></b> (🥈33 ·  ⭐ 43K · 💤) - The worlds simplest facial recognition api for Python.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ageitgey/face_recognition) (👨‍💻 47 · 🔀 12K · 📥 450 · 📋 1.2K - 54% open · ⏱️ 14.06.2021):

	```
	git clone https://github.com/ageitgey/face_recognition
	```
- [PyPi](https://pypi.org/project/face_recognition) (📥 44K / month · 📦 210 · ⏱️ 21.08.2018):
	```
	pip install face_recognition
	```
- [Conda](https://anaconda.org/conda-forge/face_recognition) (📥 4.2K · ⏱️ 30.04.2021):
	```
	conda install -c conda-forge face_recognition
	```
</details>
<details><summary><b><a href="https://github.com/dmlc/gluon-cv">GluonCV</a></b> (🥈32 ·  ⭐ 5.1K) - Gluon CV Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/dmlc/gluon-cv) (👨‍💻 120 · 🔀 1.1K · 📦 660 · 📋 810 - 7% open · ⏱️ 02.02.2022):

	```
	git clone https://github.com/dmlc/gluon-cv
	```
- [PyPi](https://pypi.org/project/gluoncv) (📥 560K / month · 📦 59 · ⏱️ 10.02.2022):
	```
	pip install gluoncv
	```
</details>
<details><summary><b><a href="https://github.com/emcconville/wand">Wand</a></b> (🥈32 ·  ⭐ 1.1K) - The ctypes-based simple ImageMagick binding for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/emcconville/wand) (👨‍💻 97 · 🔀 190 · 📥 6K · 📦 9K · 📋 360 - 4% open · ⏱️ 31.01.2022):

	```
	git clone https://github.com/emcconville/wand
	```
- [PyPi](https://pypi.org/project/wand) (📥 420K / month · 📦 680 · ⏱️ 17.08.2021):
	```
	pip install wand
	```
- [Conda](https://anaconda.org/conda-forge/wand) (📥 8.6K · ⏱️ 30.11.2020):
	```
	conda install -c conda-forge wand
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PaddleSeg">PaddleSeg</a></b> (🥈31 ·  ⭐ 3.7K) - Easy-to-use image segmentation library with awesome pre-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PaddleSeg) (👨‍💻 74 · 🔀 820 · 📦 490 · 📋 880 - 49% open · ⏱️ 01.02.2022):

	```
	git clone https://github.com/PaddlePaddle/PaddleSeg
	```
- [PyPi](https://pypi.org/project/paddleseg) (📥 1.2K / month · 📦 2 · ⏱️ 20.01.2022):
	```
	pip install paddleseg
	```
</details>
<details><summary><b><a href="https://github.com/serengil/deepface">deepface</a></b> (🥈31 ·  ⭐ 3.2K) - A Lightweight Face Recognition and Facial Attribute Analysis (Age,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/serengil/deepface) (👨‍💻 21 · 🔀 710 · 📦 410 · 📋 400 - 0% open · ⏱️ 02.02.2022):

	```
	git clone https://github.com/serengil/deepface
	```
- [PyPi](https://pypi.org/project/deepface) (📥 37K / month · 📦 3 · ⏱️ 12.01.2022):
	```
	pip install deepface
	```
</details>
<details><summary><b><a href="https://github.com/OlafenwaMoses/ImageAI">imageai</a></b> (🥈30 ·  ⭐ 6.8K · 💤) - A python library built to empower developers to build applications.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/OlafenwaMoses/ImageAI) (👨‍💻 15 · 🔀 1.9K · 📥 710K · 📦 1K · 📋 680 - 36% open · ⏱️ 08.05.2021):

	```
	git clone https://github.com/OlafenwaMoses/ImageAI
	```
- [PyPi](https://pypi.org/project/imageai) (📥 7.9K / month · 📦 16 · ⏱️ 05.01.2021):
	```
	pip install imageai
	```
- [Conda](https://anaconda.org/conda-forge/imageai) (📥 2.4K · ⏱️ 30.04.2021):
	```
	conda install -c conda-forge imageai
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PaddleDetection">PaddleDetection</a></b> (🥈30 ·  ⭐ 6.3K) - Object Detection toolkit based on PaddlePaddle. It.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PaddleDetection) (👨‍💻 80 · 🔀 1.6K · 📦 8 · 📋 3K - 30% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/PaddlePaddle/PaddleDetection
	```
- [PyPi](https://pypi.org/project/paddledet) (📥 310 / month · ⏱️ 26.11.2021):
	```
	pip install paddledet
	```
</details>
<details><summary><b><a href="https://github.com/PyImageSearch/imutils">imutils</a></b> (🥈30 ·  ⭐ 4K) - A series of convenience functions to make basic image processing operations.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/PyImageSearch/imutils) (👨‍💻 21 · 🔀 940 · 📦 23K · 📋 220 - 65% open · ⏱️ 27.01.2022):

	```
	git clone https://github.com/PyImageSearch/imutils
	```
- [PyPi](https://pypi.org/project/imutils) (📥 310K / month · 📦 760 · ⏱️ 15.01.2021):
	```
	pip install imutils
	```
- [Conda](https://anaconda.org/conda-forge/imutils) (📥 76K · ⏱️ 09.12.2021):
	```
	conda install -c conda-forge imutils
	```
</details>
<details><summary><b><a href="https://github.com/JohannesBuchner/imagehash">ImageHash</a></b> (🥈30 ·  ⭐ 2.3K) - A Python Perceptual Image Hashing Module. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/JohannesBuchner/imagehash) (👨‍💻 20 · 🔀 280 · 📦 4.2K · 📋 110 - 12% open · ⏱️ 07.09.2021):

	```
	git clone https://github.com/JohannesBuchner/imagehash
	```
- [PyPi](https://pypi.org/project/ImageHash) (📥 1.4M / month · 📦 320 · ⏱️ 15.07.2021):
	```
	pip install ImageHash
	```
- [Conda](https://anaconda.org/conda-forge/imagehash) (📥 170K · ⏱️ 15.07.2021):
	```
	conda install -c conda-forge imagehash
	```
</details>
<details><summary><b><a href="https://github.com/lucidrains/vit-pytorch">vit-pytorch</a></b> (🥉29 ·  ⭐ 8.5K) - Implementation of Vision Transformer, a simple way to achieve.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lucidrains/vit-pytorch) (👨‍💻 14 · 🔀 1.4K · 📦 69 · 📋 170 - 48% open · ⏱️ 31.01.2022):

	```
	git clone https://github.com/lucidrains/vit-pytorch
	```
- [PyPi](https://pypi.org/project/vit-pytorch) (📥 15K / month · 📦 1 · ⏱️ 31.01.2022):
	```
	pip install vit-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/1adrianb/face-alignment">Face Alignment</a></b> (🥉27 ·  ⭐ 5.5K) - 2D and 3D Face alignment library build using pytorch. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/1adrianb/face-alignment) (👨‍💻 23 · 🔀 1.1K · 📋 270 - 19% open · ⏱️ 04.08.2021):

	```
	git clone https://github.com/1adrianb/face-alignment
	```
- [PyPi](https://pypi.org/project/face-alignment) (📥 7K / month · 📦 8 · ⏱️ 14.09.2021):
	```
	pip install face-alignment
	```
</details>
<details><summary><b><a href="https://github.com/mdbloice/Augmentor">Augmentor</a></b> (🥉27 ·  ⭐ 4.6K) - Image augmentation library in Python for machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mdbloice/Augmentor) (👨‍💻 22 · 🔀 830 · 📦 400 · 📋 190 - 63% open · ⏱️ 15.10.2021):

	```
	git clone https://github.com/mdbloice/Augmentor
	```
- [PyPi](https://pypi.org/project/Augmentor) (📥 9.8K / month · 📦 29 · ⏱️ 14.10.2021):
	```
	pip install Augmentor
	```
</details>
<details><summary><b><a href="https://github.com/abhiTronix/vidgear">vidgear</a></b> (🥉27 ·  ⭐ 2.1K) - A High-performance cross-platform Video Processing Python framework.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/abhiTronix/vidgear) (👨‍💻 9 · 🔀 160 · 📥 520 · 📦 170 · 📋 200 - 2% open · ⏱️ 05.12.2021):

	```
	git clone https://github.com/abhiTronix/vidgear
	```
- [PyPi](https://pypi.org/project/vidgear) (📥 4.4K / month · 📦 3 · ⏱️ 05.12.2021):
	```
	pip install vidgear
	```
</details>
<details><summary><b><a href="https://github.com/luispedro/mahotas">mahotas</a></b> (🥉27 ·  ⭐ 730) - Computer Vision in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/luispedro/mahotas) (👨‍💻 32 · 🔀 140 · 📦 750 · 📋 77 - 20% open · ⏱️ 07.12.2021):

	```
	git clone https://github.com/luispedro/mahotas
	```
- [PyPi](https://pypi.org/project/mahotas) (📥 11K / month · 📦 110 · ⏱️ 14.10.2021):
	```
	pip install mahotas
	```
- [Conda](https://anaconda.org/conda-forge/mahotas) (📥 310K · ⏱️ 17.11.2021):
	```
	conda install -c conda-forge mahotas
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/mmf">MMF</a></b> (🥉26 ·  ⭐ 4.8K) - A modular framework for vision & language multimodal research from.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/mmf) (👨‍💻 90 · 🔀 790 · 📦 10 · 📋 610 - 31% open · ⏱️ 02.02.2022):

	```
	git clone https://github.com/facebookresearch/mmf
	```
- [PyPi](https://pypi.org/project/mmf) (📥 580 / month · 📦 1 · ⏱️ 12.06.2020):
	```
	pip install mmf
	```
</details>
<details><summary><b><a href="https://github.com/lightly-ai/lightly">lightly</a></b> (🥉26 ·  ⭐ 1.5K) - A python library for self-supervised learning on images. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lightly-ai/lightly) (👨‍💻 14 · 🔀 97 · 📦 28 · 📋 300 - 21% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/lightly-ai/lightly
	```
- [PyPi](https://pypi.org/project/lightly) (📥 2.8K / month · 📦 1 · ⏱️ 08.02.2022):
	```
	pip install lightly
	```
</details>
<details><summary><b><a href="https://github.com/CellProfiler/CellProfiler">CellProfiler</a></b> (🥉26 ·  ⭐ 650) - An open-source application for biological image analysis. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/CellProfiler/CellProfiler) (👨‍💻 120 · 🔀 300 · 📥 2.2K · 📦 7 · 📋 3K - 6% open · ⏱️ 01.02.2022):

	```
	git clone https://github.com/CellProfiler/CellProfiler
	```
- [PyPi](https://pypi.org/project/cellprofiler) (📥 760 / month · ⏱️ 04.09.2017):
	```
	pip install cellprofiler
	```
</details>
<details><summary><b><a href="https://github.com/Layout-Parser/layout-parser">layout-parser</a></b> (🥉25 ·  ⭐ 2.8K) - A Unified Toolkit for Deep Learning Based Document Image.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Layout-Parser/layout-parser) (👨‍💻 8 · 🔀 270 · 📦 43 · 📋 76 - 50% open · ⏱️ 02.02.2022):

	```
	git clone https://github.com/Layout-Parser/layout-parser
	```
- [PyPi](https://pypi.org/project/layoutparser) (📥 4.8K / month · 📦 1 · ⏱️ 23.09.2021):
	```
	pip install layoutparser
	```
</details>
<details><summary><b><a href="https://github.com/timesler/facenet-pytorch">facenet-pytorch</a></b> (🥉25 ·  ⭐ 2.7K) - Pretrained Pytorch face detection (MTCNN) and facial.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/timesler/facenet-pytorch) (👨‍💻 14 · 🔀 570 · 📥 200K · 📦 630 · 📋 140 - 38% open · ⏱️ 13.12.2021):

	```
	git clone https://github.com/timesler/facenet-pytorch
	```
- [PyPi](https://pypi.org/project/facenet-pytorch) (📥 13K / month · 📦 7 · ⏱️ 10.03.2021):
	```
	pip install facenet-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/graphics">tensorflow-graphics</a></b> (🥉25 ·  ⭐ 2.6K) - TensorFlow Graphics: Differentiable Graphics Layers.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/graphics) (👨‍💻 34 · 🔀 340 · 📋 220 - 59% open · ⏱️ 02.02.2022):

	```
	git clone https://github.com/tensorflow/graphics
	```
- [PyPi](https://pypi.org/project/tensorflow-graphics) (📥 2.5K / month · 📦 4 · ⏱️ 03.12.2021):
	```
	pip install tensorflow-graphics
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/vissl">vissl</a></b> (🥉25 ·  ⭐ 2.3K) - VISSL is FAIRs library of extensible, modular and scalable components.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/vissl) (👨‍💻 30 · 🔀 230 · 📦 5 · 📋 130 - 33% open · ⏱️ 01.02.2022):

	```
	git clone https://github.com/facebookresearch/vissl
	```
- [PyPi](https://pypi.org/project/vissl) (📥 190 / month · 📦 1 · ⏱️ 02.11.2021):
	```
	pip install vissl
	```
</details>
<details><summary><b><a href="https://github.com/ipazc/mtcnn">mtcnn</a></b> (🥉25 ·  ⭐ 1.7K · 💤) - MTCNN face detection implementation for TensorFlow, as a PIP.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ipazc/mtcnn) (👨‍💻 15 · 🔀 440 · 📦 1.9K · 📋 100 - 62% open · ⏱️ 09.07.2021):

	```
	git clone https://github.com/ipazc/mtcnn
	```
- [PyPi](https://pypi.org/project/mtcnn) (📥 27K / month · 📦 43 · ⏱️ 09.07.2021):
	```
	pip install mtcnn
	```
- [Conda](https://anaconda.org/conda-forge/mtcnn) (📥 4.2K · ⏱️ 17.08.2021):
	```
	conda install -c conda-forge mtcnn
	```
</details>
<details><summary><b><a href="https://github.com/airctic/icevision">icevision</a></b> (🥉25 ·  ⭐ 580 · ➕) - An Agnostic Computer Vision Framework - Pluggable to any.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/airctic/icevision) (👨‍💻 36 · 🔀 86 · 📋 620 - 21% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/airctic/icevision
	```
- [PyPi](https://pypi.org/project/icevision) (📥 1.9K / month · 📦 5 · ⏱️ 19.11.2021):
	```
	pip install icevision
	```
</details>
<details><summary><b><a href="https://github.com/libvips/pyvips">pyvips</a></b> (🥉25 ·  ⭐ 390) - python binding for libvips using cffi. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/libvips/pyvips) (👨‍💻 12 · 🔀 37 · 📦 270 · 📋 270 - 38% open · ⏱️ 15.12.2021):

	```
	git clone https://github.com/libvips/pyvips
	```
- [PyPi](https://pypi.org/project/pyvips) (📥 17K / month · 📦 28 · ⏱️ 20.11.2021):
	```
	pip install pyvips
	```
- [Conda](https://anaconda.org/conda-forge/pyvips) (📥 15K · ⏱️ 30.12.2021):
	```
	conda install -c conda-forge pyvips
	```
</details>
<details><summary><b><a href="https://github.com/lucidrains/deep-daze">deep-daze</a></b> (🥉24 ·  ⭐ 4.1K) - Simple command line tool for text to image generation using OpenAIs.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lucidrains/deep-daze) (👨‍💻 13 · 🔀 290 · 📦 33 · 📋 160 - 54% open · ⏱️ 26.01.2022):

	```
	git clone https://github.com/lucidrains/deep-daze
	```
- [PyPi](https://pypi.org/project/deep-daze) (📥 13K / month · ⏱️ 26.01.2022):
	```
	pip install deep-daze
	```
</details>
<details><summary><b><a href="https://github.com/idealo/image-super-resolution">Image Super-Resolution</a></b> (🥉24 ·  ⭐ 3.4K · 💤) - Super-scale your images and run experiments with.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/idealo/image-super-resolution) (👨‍💻 10 · 🔀 600 · 📦 71 · 📋 190 - 43% open · ⏱️ 02.06.2021):

	```
	git clone https://github.com/idealo/image-super-resolution
	```
- [PyPi](https://pypi.org/project/ISR) (📥 4.9K / month · 📦 5 · ⏱️ 08.01.2020):
	```
	pip install ISR
	```
- [Docker Hub](https://hub.docker.com/r/idealo/image-super-resolution-gpu) (📥 200 · ⏱️ 01.04.2019):
	```
	docker pull idealo/image-super-resolution-gpu
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/pytorchvideo">pytorchvideo</a></b> (🥉24 ·  ⭐ 2.3K) - A deep learning library for video understanding research. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/pytorchvideo) (👨‍💻 25 · 🔀 220 · 📋 130 - 41% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/facebookresearch/pytorchvideo
	```
- [PyPi](https://pypi.org/project/pytorchvideo) (📥 14K / month · 📦 5 · ⏱️ 20.01.2022):
	```
	pip install pytorchvideo
	```
</details>
<details><summary><b><a href="https://github.com/obss/sahi">sahi</a></b> (🥉24 ·  ⭐ 540 · ➕) - A lightweight vision library for performing large scale object detection/.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/obss/sahi) (👨‍💻 8 · 🔀 83 · 📦 19 · 📋 91 - 8% open · ⏱️ 07.02.2022):

	```
	git clone https://github.com/obss/sahi
	```
- [PyPi](https://pypi.org/project/sahi) (📥 12K / month · 📦 4 · ⏱️ 13.01.2022):
	```
	pip install sahi
	```
- [Conda](https://anaconda.org/conda-forge/sahi) (📥 1.3K · ⏱️ 13.01.2022):
	```
	conda install -c conda-forge sahi
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/ClassyVision">Classy Vision</a></b> (🥉22 ·  ⭐ 1.4K) - An end-to-end PyTorch framework for image and video.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/ClassyVision) (👨‍💻 67 · 🔀 240 · 📋 110 - 46% open · ⏱️ 28.12.2021):

	```
	git clone https://github.com/facebookresearch/ClassyVision
	```
- [PyPi](https://pypi.org/project/classy_vision) (📥 820 / month · 📦 2 · ⏱️ 09.07.2021):
	```
	pip install classy_vision
	```
- [Conda](https://anaconda.org/conda-forge/classy_vision) (📥 11K · ⏱️ 11.12.2020):
	```
	conda install -c conda-forge classy_vision
	```
</details>
<details><summary><b><a href="https://github.com/ProvenanceLabs/image-match">image-match</a></b> (🥉20 ·  ⭐ 2.7K) - Quickly search over billions of images. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ProvenanceLabs/image-match) (👨‍💻 19 · 🔀 380 · 📋 100 - 53% open · ⏱️ 21.09.2021):

	```
	git clone https://github.com/ProvenanceLabs/image-match
	```
- [PyPi](https://pypi.org/project/image_match) (📥 580 / month · 📦 4 · ⏱️ 13.02.2017):
	```
	pip install image_match
	```
</details>
<details><summary><b><a href="https://github.com/tryolabs/norfair">Norfair</a></b> (🥉20 ·  ⭐ 1.3K) - Lightweight Python library for adding real-time object tracking to any.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/tryolabs/norfair) (👨‍💻 10 · 🔀 110 · 📋 41 - 24% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/tryolabs/norfair
	```
- [PyPi](https://pypi.org/project/norfair) (📥 3.4K / month · 📦 1 · ⏱️ 29.07.2021):
	```
	pip install norfair
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/SlowFast">PySlowFast</a></b> (🥉19 ·  ⭐ 4.6K) - PySlowFast: video understanding codebase from FAIR for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/SlowFast) (👨‍💻 25 · 🔀 860 · 📦 6 · 📋 490 - 50% open · ⏱️ 28.10.2021):

	```
	git clone https://github.com/facebookresearch/SlowFast
	```
- [PyPi](https://pypi.org/project/pyslowfast) (📥 15 / month · ⏱️ 15.01.2020):
	```
	pip install pyslowfast
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/pycls">pycls</a></b> (🥉19 ·  ⭐ 1.8K) - Codebase for Image Classification Research, written in PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/pycls) (👨‍💻 13 · 🔀 210 · 📦 5 · 📋 77 - 27% open · ⏱️ 19.08.2021):

	```
	git clone https://github.com/facebookresearch/pycls
	```
- [PyPi](https://pypi.org/project/pycls) (📥 460 / month · ⏱️ 05.09.2020):
	```
	pip install pycls
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/detr">DE⫶TR</a></b> (🥉18 ·  ⭐ 8.3K) - End-to-End Object Detection with Transformers. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/detr) (👨‍💻 24 · 🔀 1.4K · 📋 400 - 33% open · ⏱️ 18.10.2021):

	```
	git clone https://github.com/facebookresearch/detr
	```
</details>
<details><summary><b><a href="https://github.com/jasmcaus/caer">Caer</a></b> (🥉18 ·  ⭐ 590) - A lightweight Computer Vision library. Scale your models, not boilerplate. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jasmcaus/caer) (👨‍💻 8 · 🔀 100 · 📥 19 · 📋 15 - 13% open · ⏱️ 13.10.2021):

	```
	git clone https://github.com/jasmcaus/caer
	```
- [PyPi](https://pypi.org/project/caer) (📥 4K / month · 📦 1 · ⏱️ 13.10.2021):
	```
	pip install caer
	```
</details>
<details><summary><b><a href="https://github.com/google-research/scenic">scenic</a></b> (🥉17 ·  ⭐ 720 · ➕) - Scenic: A Jax Library for Computer Vision Research and Beyond. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google-research/scenic) (👨‍💻 24 · 🔀 74 · 📦 9 · 📋 19 - 21% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/google-research/scenic
	```
</details>
<details><summary>Show 12 hidden projects...</summary>

- <b><a href="https://github.com/aleju/imgaug">imgaug</a></b> (🥈35 ·  ⭐ 12K · 💀) - Image augmentation for machine learning experiments. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/glfw/glfw">glfw</a></b> (🥈35 ·  ⭐ 8.6K) - A multi-platform library for OpenGL, OpenGL ES, Vulkan, window and input. <code><a href="https://tldrlegal.com/search?q=Zlib">❗️Zlib</a></code>
- <b><a href="https://github.com/uploadcare/pillow-simd">Pillow-SIMD</a></b> (🥈31 ·  ⭐ 1.7K) - The friendly PIL fork. <code><a href="https://tldrlegal.com/search?q=PIL">❗️PIL</a></code>
- <b><a href="https://github.com/facebookresearch/pytorch3d">PyTorch3D</a></b> (🥉28 ·  ⭐ 5.6K) - PyTorch3D is FAIRs library of reusable components for.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/chainer/chainercv">chainercv</a></b> (🥉27 ·  ⭐ 1.5K · 💀) - ChainerCV: a Library for Deep Learning in Computer Vision. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/qubvel/segmentation_models">segmentation_models</a></b> (🥉25 ·  ⭐ 3.7K · 💀) - Segmentation models with pretrained backbones. Keras.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/idealo/imagededup">Image Deduplicator</a></b> (🥉23 ·  ⭐ 4K · 💀) - Finding duplicate images made easy!. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/tryolabs/luminoth">Luminoth</a></b> (🥉22 ·  ⭐ 2.4K · 💀) - Deep Learning toolkit for Computer Vision. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/hhatto/nude.py">nude.py</a></b> (🥉22 ·  ⭐ 830 · 💀) - Nudity detection with Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Oulu-IMEDS/solt">solt</a></b> (🥉17 ·  ⭐ 250 · 💀) - Streaming over lightweight data transformations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/nicolas-chaulet/torch-points3d">Torch Points 3D</a></b> (🥉15 ·  ⭐ 12 · 🐣) - Pytorch framework for doing deep learning on point.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/qanastek/HugsVision">HugsVision</a></b> (🥉14 ·  ⭐ 140 · 🐣) - HugsVision is a easy to use huggingface wrapper for state-of-.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>huggingface</code>
</details>
<br>

## Graph Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for graph processing, clustering, embedding, and machine learning tasks._

<details><summary><b><a href="https://github.com/networkx/networkx">networkx</a></b> (🥇44 ·  ⭐ 10K) - Network Analysis in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/networkx/networkx) (👨‍💻 570 · 🔀 2.5K · 📥 57 · 📦 98K · 📋 2.8K - 12% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/networkx/networkx
	```
- [PyPi](https://pypi.org/project/networkx) (📥 16M / month · 📦 13K · ⏱️ 15.12.2021):
	```
	pip install networkx
	```
- [Conda](https://anaconda.org/conda-forge/networkx) (📥 5.5M · ⏱️ 26.10.2021):
	```
	conda install -c conda-forge networkx
	```
</details>
<details><summary><b><a href="https://github.com/pyg-team/pytorch_geometric">PyTorch Geometric</a></b> (🥇35 ·  ⭐ 14K) - Graph Neural Network Library for PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pyg-team/pytorch_geometric) (👨‍💻 240 · 🔀 2.4K · 📋 2.4K - 37% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/pyg-team/pytorch_geometric
	```
- [PyPi](https://pypi.org/project/torch-geometric) (📥 45K / month · 📦 33 · ⏱️ 22.12.2021):
	```
	pip install torch-geometric
	```
- [Conda](https://anaconda.org/conda-forge/pytorch_geometric) (📥 5.6K · ⏱️ 19.01.2022):
	```
	conda install -c conda-forge pytorch_geometric
	```
</details>
<details><summary><b><a href="https://github.com/dmlc/dgl">dgl</a></b> (🥇35 ·  ⭐ 8.9K) - Python package built to ease deep learning on graph, on top of existing.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dmlc/dgl) (👨‍💻 190 · 🔀 2K · 📋 1.4K - 24% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/dmlc/dgl
	```
- [PyPi](https://pypi.org/project/dgl) (📥 64K / month · 📦 39 · ⏱️ 27.05.2021):
	```
	pip install dgl
	```
</details>
<details><summary><b><a href="https://github.com/stellargraph/stellargraph">StellarGraph</a></b> (🥈28 ·  ⭐ 2.3K) - StellarGraph - Machine Learning on Graphs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/stellargraph/stellargraph) (👨‍💻 36 · 🔀 340 · 📦 120 · 📋 990 - 25% open · ⏱️ 29.10.2021):

	```
	git clone https://github.com/stellargraph/stellargraph
	```
- [PyPi](https://pypi.org/project/stellargraph) (📥 40K / month · 📦 3 · ⏱️ 30.06.2020):
	```
	pip install stellargraph
	```
</details>
<details><summary><b><a href="https://github.com/snap-stanford/ogb">ogb</a></b> (🥈28 ·  ⭐ 1.2K) - Benchmark datasets, data loaders, and evaluators for graph machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/snap-stanford/ogb) (👨‍💻 18 · 🔀 250 · 📦 220 · 📋 180 - 0% open · ⏱️ 14.01.2022):

	```
	git clone https://github.com/snap-stanford/ogb
	```
- [PyPi](https://pypi.org/project/ogb) (📥 25K / month · 📦 13 · ⏱️ 29.09.2021):
	```
	pip install ogb
	```
- [Conda](https://anaconda.org/conda-forge/ogb) (📥 6.5K · ⏱️ 29.09.2021):
	```
	conda install -c conda-forge ogb
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PGL">Paddle Graph Learning</a></b> (🥈26 ·  ⭐ 1.2K) - Paddle Graph Learning (PGL) is an efficient and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PGL) (👨‍💻 21 · 🔀 200 · 📦 24 · 📋 100 - 36% open · ⏱️ 29.12.2021):

	```
	git clone https://github.com/PaddlePaddle/PGL
	```
- [PyPi](https://pypi.org/project/pgl) (📥 980 / month · 📦 2 · ⏱️ 20.12.2021):
	```
	pip install pgl
	```
</details>
<details><summary><b><a href="https://github.com/pykeen/pykeen">PyKEEN</a></b> (🥈26 ·  ⭐ 700) - A Python library for learning and evaluating knowledge graph embeddings. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pykeen/pykeen) (👨‍💻 24 · 🔀 99 · 📥 92 · 📋 350 - 32% open · ⏱️ 06.02.2022):

	```
	git clone https://github.com/pykeen/pykeen
	```
- [PyPi](https://pypi.org/project/pykeen) (📥 1.2K / month · 📦 3 · ⏱️ 11.01.2022):
	```
	pip install pykeen
	```
</details>
<details><summary><b><a href="https://github.com/danielegrattarola/spektral">Spektral</a></b> (🥈25 ·  ⭐ 2K) - Graph Neural Networks with Keras and Tensorflow 2. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/danielegrattarola/spektral) (👨‍💻 19 · 🔀 270 · 📦 100 · 📋 200 - 17% open · ⏱️ 26.10.2021):

	```
	git clone https://github.com/danielegrattarola/spektral
	```
- [PyPi](https://pypi.org/project/spektral) (📥 4.4K / month · 📦 2 · ⏱️ 23.08.2021):
	```
	pip install spektral
	```
</details>
<details><summary><b><a href="https://github.com/graphistry/pygraphistry">pygraphistry</a></b> (🥈25 ·  ⭐ 1.5K) - PyGraphistry is a Python library to quickly load, shape,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/graphistry/pygraphistry) (👨‍💻 19 · 🔀 150 · 📦 57 · 📋 190 - 40% open · ⏱️ 22.12.2021):

	```
	git clone https://github.com/graphistry/pygraphistry
	```
- [PyPi](https://pypi.org/project/graphistry) (📥 2.2K / month · 📦 4 · ⏱️ 07.12.2021):
	```
	pip install graphistry
	```
</details>
<details><summary><b><a href="https://github.com/benedekrozemberczki/pytorch_geometric_temporal">pytorch_geometric_temporal</a></b> (🥈25 ·  ⭐ 1.3K) - PyTorch Geometric Temporal: Spatiotemporal Signal.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/benedekrozemberczki/pytorch_geometric_temporal) (👨‍💻 18 · 🔀 190 · 📋 81 - 1% open · ⏱️ 03.02.2022):

	```
	git clone https://github.com/benedekrozemberczki/pytorch_geometric_temporal
	```
- [PyPi](https://pypi.org/project/torch-geometric-temporal) (📥 1.3K / month · 📦 1 · ⏱️ 19.01.2022):
	```
	pip install torch-geometric-temporal
	```
</details>
<details><summary><b><a href="https://github.com/graph4ai/graph4nlp">graph4nlp</a></b> (🥈24 ·  ⭐ 1.2K) - Graph4nlp is the library for the easy use of Graph Neural.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/graph4ai/graph4nlp) (👨‍💻 23 · 🔀 140 · 📋 100 - 7% open · ⏱️ 20.01.2022):

	```
	git clone https://github.com/graph4ai/graph4nlp
	```
- [PyPi](https://pypi.org/project/graph4nlp) (📥 150 / month · ⏱️ 20.01.2022):
	```
	pip install graph4nlp
	```
</details>
<details><summary><b><a href="https://github.com/eliorc/node2vec">Node2Vec</a></b> (🥈24 ·  ⭐ 850) - Implementation of the node2vec algorithm. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/eliorc/node2vec) (👨‍💻 9 · 🔀 190 · ⏱️ 09.10.2021):

	```
	git clone https://github.com/eliorc/node2vec
	```
- [PyPi](https://pypi.org/project/node2vec) (📥 540K / month · 📦 14 · ⏱️ 09.10.2021):
	```
	pip install node2vec
	```
- [Conda](https://anaconda.org/conda-forge/node2vec) (📥 20K · ⏱️ 25.04.2020):
	```
	conda install -c conda-forge node2vec
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/PyTorch-BigGraph">PyTorch-BigGraph</a></b> (🥉23 ·  ⭐ 3K) - Generate embeddings from large-scale graph-structured.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/PyTorch-BigGraph) (👨‍💻 25 · 🔀 400 · 📥 120 · 📋 180 - 32% open · ⏱️ 07.02.2022):

	```
	git clone https://github.com/facebookresearch/PyTorch-BigGraph
	```
- [PyPi](https://pypi.org/project/torchbiggraph) (📥 13K / month · 📦 3 · ⏱️ 01.05.2019):
	```
	pip install torchbiggraph
	```
</details>
<details><summary><b><a href="https://github.com/Accenture/AmpliGraph">AmpliGraph</a></b> (🥉22 ·  ⭐ 1.7K · 💤) - Python library for Representation Learning on Knowledge.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Accenture/AmpliGraph) (👨‍💻 19 · 🔀 190 · 📦 17 · 📋 200 - 9% open · ⏱️ 25.05.2021):

	```
	git clone https://github.com/Accenture/AmpliGraph
	```
- [PyPi](https://pypi.org/project/ampligraph) (📥 760 / month · ⏱️ 25.05.2021):
	```
	pip install ampligraph
	```
</details>
<details><summary><b><a href="https://github.com/rusty1s/pytorch_cluster">torch-cluster</a></b> (🥉21 ·  ⭐ 470) - PyTorch Extension Library of Optimized Graph Cluster.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rusty1s/pytorch_cluster) (👨‍💻 20 · 🔀 89 · 📋 95 - 9% open · ⏱️ 03.02.2022):

	```
	git clone https://github.com/rusty1s/pytorch_cluster
	```
- [PyPi](https://pypi.org/project/torch-cluster) (📥 10K / month · 📦 26 · ⏱️ 01.03.2021):
	```
	pip install torch-cluster
	```
- [Conda](https://anaconda.org/conda-forge/pytorch_cluster) (📥 28K · ⏱️ 13.01.2022):
	```
	conda install -c conda-forge pytorch_cluster
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/jraph">jraph</a></b> (🥉20 ·  ⭐ 820 · ➕) - A Graph Neural Network Library in Jax. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmind/jraph) (👨‍💻 13 · 🔀 45 · 📦 11 · 📋 18 - 50% open · ⏱️ 07.02.2022):

	```
	git clone https://github.com/deepmind/jraph
	```
- [PyPi](https://pypi.org/project/jraph) (📥 1.2K / month · 📦 2 · ⏱️ 19.11.2021):
	```
	pip install jraph
	```
- [Conda](https://anaconda.org/conda-forge/jraph) (📥 280 · ⏱️ 31.10.2021):
	```
	conda install -c conda-forge jraph
	```
</details>
<details><summary><b><a href="https://github.com/snap-stanford/deepsnap">deepsnap</a></b> (🥉20 ·  ⭐ 390 · ➕) - Python library assists deep learning on graphs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/snap-stanford/deepsnap) (👨‍💻 15 · 🔀 43 · 📥 8 · 📦 15 · 📋 36 - 36% open · ⏱️ 19.09.2021):

	```
	git clone https://github.com/snap-stanford/deepsnap
	```
- [PyPi](https://pypi.org/project/deepsnap) (📥 370 / month · 📦 1 · ⏱️ 05.09.2021):
	```
	pip install deepsnap
	```
</details>
<details><summary><b><a href="https://github.com/THUMNLab/AutoGL">AutoGL</a></b> (🥉18 ·  ⭐ 760) - An autoML framework & toolkit for machine learning on graphs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/THUMNLab/AutoGL) (👨‍💻 13 · 🔀 80 · 📋 18 - 27% open · ⏱️ 31.12.2021):

	```
	git clone https://github.com/THUMNLab/AutoGL
	```
- [PyPi](https://pypi.org/project/auto-graph-learning) (📥 15 / month · ⏱️ 23.12.2020):
	```
	pip install auto-graph-learning
	```
</details>
<details><summary><b><a href="https://github.com/vaticle/kglib">kglib</a></b> (🥉16 ·  ⭐ 490) - Grakn Knowledge Graph Library (ML R&D). <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/vaticle/kglib) (👨‍💻 7 · 🔀 86 · 📥 210 · 📋 61 - 19% open · ⏱️ 22.10.2021):

	```
	git clone https://github.com/vaticle/kglib
	```
- [PyPi](https://pypi.org/project/grakn-kglib) (📥 90 / month · ⏱️ 19.08.2020):
	```
	pip install grakn-kglib
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/ptgnn">ptgnn</a></b> (🥉16 ·  ⭐ 300 · ➕) - A PyTorch Graph Neural Network Library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/microsoft/ptgnn) (👨‍💻 7 · 🔀 36 · 📦 1 · 📋 7 - 28% open · ⏱️ 01.02.2022):

	```
	git clone https://github.com/microsoft/ptgnn
	```
- [PyPi](https://pypi.org/project/ptgnn) (📥 150 / month · ⏱️ 21.10.2021):
	```
	pip install ptgnn
	```
</details>
<details><summary><b><a href="https://github.com/thunlp/OpenKE">OpenKE</a></b> (🥉15 ·  ⭐ 2.9K · 💤) - An Open-Source Package for Knowledge Embedding (KE). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/thunlp/OpenKE) (👨‍💻 10 · 🔀 850 · 📋 380 - 17% open · ⏱️ 06.04.2021):

	```
	git clone https://github.com/thunlp/OpenKE
	```
</details>
<details><summary><b><a href="https://github.com/snap-stanford/GraphGym">GraphGym</a></b> (🥉14 ·  ⭐ 880 · ➕) - Platform for designing and evaluating Graph Neural Networks (GNN). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/snap-stanford/GraphGym) (👨‍💻 5 · 🔀 100 · 📥 8 · 📦 2 · 📋 25 - 12% open · ⏱️ 11.12.2021):

	```
	git clone https://github.com/snap-stanford/GraphGym
	```
- [PyPi](https://pypi.org/project/graphgym) (📥 60 / month · ⏱️ 29.06.2021):
	```
	pip install graphgym
	```
</details>
<details><summary>Show 14 hidden projects...</summary>

- <b><a href="https://github.com/igraph/python-igraph">igraph</a></b> (🥇30 ·  ⭐ 930) - Python interface for igraph. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code>
- <b><a href="https://github.com/Kozea/pygal">pygal</a></b> (🥈28 ·  ⭐ 2.4K) - PYthon svg GrAph plotting Library. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code>
- <b><a href="https://github.com/benedekrozemberczki/karateclub">Karate Club</a></b> (🥈24 ·  ⭐ 1.5K) - Karate Club: An API Oriented Open-source Python Framework for.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/phanein/deepwalk">DeepWalk</a></b> (🥉21 ·  ⭐ 2.4K · 💀) - DeepWalk - Deep Learning for Graphs. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/deepmind/graph_nets">graph-nets</a></b> (🥉20 ·  ⭐ 5.1K · 💀) - Build Graph Nets in Tensorflow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/divelab/DIG">DIG</a></b> (🥉20 ·  ⭐ 1K) - A library for graph deep learning research. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/gsi-upm/sematch">Sematch</a></b> (🥉17 ·  ⭐ 380 · 💀) - semantic similarity framework for knowledge graph. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/alibaba/euler">Euler</a></b> (🥉16 ·  ⭐ 2.7K · 💀) - A distributed graph deep learning framework. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/shenweichen/GraphEmbedding">GraphEmbedding</a></b> (🥉16 ·  ⭐ 2.6K · 💀) - Implementation and experiments of graph embedding.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/deepgraph/deepgraph">DeepGraph</a></b> (🥉16 ·  ⭐ 250 · 💤) - Analyze Data with Pandas-based Networks. Documentation:. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/IBCNServices/pyRDF2Vec">pyRDF2Vec</a></b> (🥉16 ·  ⭐ 140) - Python Implementation and Extension of RDF2Vec. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/williamleif/GraphSAGE">GraphSAGE</a></b> (🥉15 ·  ⭐ 2.6K · 💀) - Representation learning on large graphs using stochastic.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/thunlp/OpenNE">OpenNE</a></b> (🥉15 ·  ⭐ 1.5K · 💀) - An Open-Source Package for Network Embedding (NE). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/DeepGraphLearning/graphvite">GraphVite</a></b> (🥉12 ·  ⭐ 1K · 💀) - GraphVite: A General and High-performance Graph Embedding System. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Audio Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for audio analysis, manipulation, transformation, and extraction, as well as speech recognition and music generation tasks._

<details><summary><b><a href="https://github.com/espnet/espnet">espnet</a></b> (🥇35 ·  ⭐ 4.7K) - End-to-End Speech Processing Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/espnet/espnet) (👨‍💻 230 · 🔀 1.5K · 📥 74 · 📦 32 · 📋 1.7K - 18% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/espnet/espnet
	```
- [PyPi](https://pypi.org/project/espnet) (📥 5.3K / month · 📦 1 · ⏱️ 08.02.2022):
	```
	pip install espnet
	```
</details>
<details><summary><b><a href="https://github.com/librosa/librosa">librosa</a></b> (🥇34 ·  ⭐ 5K) - Python library for audio and music analysis. <code><a href="http://bit.ly/3hkKRql">ISC</a></code></summary>

- [GitHub](https://github.com/librosa/librosa) (👨‍💻 93 · 🔀 790 · 📋 940 - 3% open · ⏱️ 07.02.2022):

	```
	git clone https://github.com/librosa/librosa
	```
- [PyPi](https://pypi.org/project/librosa) (📥 540K / month · 📦 1.2K · ⏱️ 07.02.2022):
	```
	pip install librosa
	```
- [Conda](https://anaconda.org/conda-forge/librosa) (📥 430K · ⏱️ 07.02.2022):
	```
	conda install -c conda-forge librosa
	```
</details>
<details><summary><b><a href="https://github.com/mozilla/DeepSpeech">DeepSpeech</a></b> (🥇33 ·  ⭐ 19K · 📈) - DeepSpeech is an open source embedded (offline, on-.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mozilla/DeepSpeech) (👨‍💻 160 · 🔀 3.3K · 📥 790K · 📦 660 · 📋 2.1K - 5% open · ⏱️ 17.11.2021):

	```
	git clone https://github.com/mozilla/DeepSpeech
	```
- [PyPi](https://pypi.org/project/deepspeech) (📥 8.4K / month · 📦 35 · ⏱️ 19.12.2020):
	```
	pip install deepspeech
	```
- [Conda](https://anaconda.org/conda-forge/deepspeech) (📥 340 · ⏱️ 29.07.2021):
	```
	conda install -c conda-forge deepspeech
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/audio">torchaudio</a></b> (🥇33 ·  ⭐ 1.6K) - Data manipulation and transformation for audio signal.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/audio) (👨‍💻 150 · 🔀 380 · 📋 600 - 25% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/pytorch/audio
	```
- [PyPi](https://pypi.org/project/torchaudio) (📥 310K / month · 📦 120 · ⏱️ 27.01.2022):
	```
	pip install torchaudio
	```
</details>
<details><summary><b><a href="https://github.com/magenta/magenta">Magenta</a></b> (🥈32 ·  ⭐ 17K · 💤) - Magenta: Music and Art Generation with Machine Intelligence. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/magenta/magenta) (👨‍💻 150 · 🔀 3.5K · 📦 330 · 📋 890 - 36% open · ⏱️ 30.06.2021):

	```
	git clone https://github.com/magenta/magenta
	```
- [PyPi](https://pypi.org/project/magenta) (📥 6.3K / month · 📦 36 · ⏱️ 12.11.2020):
	```
	pip install magenta
	```
</details>
<details><summary><b><a href="https://github.com/jiaaro/pydub">Pydub</a></b> (🥈32 ·  ⭐ 5.9K · 💤) - Manipulate audio with a simple and easy high level interface. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jiaaro/pydub) (👨‍💻 90 · 🔀 780 · 📦 11K · 📋 460 - 44% open · ⏱️ 08.06.2021):

	```
	git clone https://github.com/jiaaro/pydub
	```
- [PyPi](https://pypi.org/project/pydub) (📥 1.7M / month · 📦 900 · ⏱️ 10.03.2021):
	```
	pip install pydub
	```
- [Conda](https://anaconda.org/conda-forge/pydub) (📥 21K · ⏱️ 13.03.2021):
	```
	conda install -c conda-forge pydub
	```
</details>
<details><summary><b><a href="https://github.com/speechbrain/speechbrain">speechbrain</a></b> (🥈32 ·  ⭐ 3.7K) - A PyTorch-based Speech Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/speechbrain/speechbrain) (👨‍💻 150 · 🔀 670 · 📦 120 · 📋 590 - 20% open · ⏱️ 24.01.2022):

	```
	git clone https://github.com/speechbrain/speechbrain
	```
- [PyPi](https://pypi.org/project/speechbrain) (📥 6.4K / month · 📦 2 · ⏱️ 20.12.2021):
	```
	pip install speechbrain
	```
</details>
<details><summary><b><a href="https://github.com/Uberi/speech_recognition">SpeechRecognition</a></b> (🥈31 ·  ⭐ 6.1K) - Speech recognition module for Python, supporting several.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Uberi/speech_recognition) (👨‍💻 42 · 🔀 2K · 📋 510 - 45% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/Uberi/speech_recognition
	```
- [PyPi](https://pypi.org/project/SpeechRecognition) (📥 270K / month · 📦 670 · ⏱️ 05.12.2017):
	```
	pip install SpeechRecognition
	```
- [Conda](https://anaconda.org/conda-forge/speechrecognition) (📥 130K · ⏱️ 13.12.2021):
	```
	conda install -c conda-forge speechrecognition
	```
</details>
<details><summary><b><a href="https://github.com/tyiannak/pyAudioAnalysis">pyAudioAnalysis</a></b> (🥈30 ·  ⭐ 4.6K) - Python Audio Analysis Library: Feature Extraction,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tyiannak/pyAudioAnalysis) (👨‍💻 26 · 🔀 1.1K · 📦 250 · 📋 290 - 60% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/tyiannak/pyAudioAnalysis
	```
- [PyPi](https://pypi.org/project/pyAudioAnalysis) (📥 11K / month · 📦 19 · ⏱️ 07.02.2022):
	```
	pip install pyAudioAnalysis
	```
</details>
<details><summary><b><a href="https://github.com/coqui-ai/TTS">Coqui TTS</a></b> (🥈29 ·  ⭐ 3.9K) - - a deep learning toolkit for Text-to-Speech, battle-.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/coqui-ai/TTS) (👨‍💻 82 · 🔀 340 · 📥 69K · 📋 220 - 13% open · ⏱️ 03.01.2022):

	```
	git clone https://github.com/coqui-ai/TTS
	```
- [PyPi](https://pypi.org/project/tts) (📥 4.6K / month · ⏱️ 14.07.2017):
	```
	pip install tts
	```
- [Conda](https://anaconda.org/conda-forge/tts) (📥 1.1K · ⏱️ 15.12.2021):
	```
	conda install -c conda-forge tts
	```
</details>
<details><summary><b><a href="https://github.com/beetbox/audioread">audioread</a></b> (🥈29 ·  ⭐ 390) - cross-library (GStreamer + Core Audio + MAD + FFmpeg) audio decoding.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/beetbox/audioread) (👨‍💻 21 · 🔀 89 · 📦 7.3K · 📋 77 - 40% open · ⏱️ 03.12.2021):

	```
	git clone https://github.com/beetbox/audioread
	```
- [PyPi](https://pypi.org/project/audioread) (📥 510K / month · 📦 320 · ⏱️ 20.10.2020):
	```
	pip install audioread
	```
- [Conda](https://anaconda.org/conda-forge/audioread) (📥 380K · ⏱️ 08.01.2022):
	```
	conda install -c conda-forge audioread
	```
</details>
<details><summary><b><a href="https://github.com/deezer/spleeter">spleeter</a></b> (🥉28 ·  ⭐ 19K) - Deezer source separation library including pretrained models. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deezer/spleeter) (👨‍💻 18 · 🔀 2K · 📥 1.4M · 📋 640 - 17% open · ⏱️ 08.12.2021):

	```
	git clone https://github.com/deezer/spleeter
	```
- [PyPi](https://pypi.org/project/spleeter) (📥 10K / month · 📦 3 · ⏱️ 03.09.2021):
	```
	pip install spleeter
	```
- [Conda](https://anaconda.org/conda-forge/spleeter) (📥 62K · ⏱️ 30.06.2020):
	```
	conda install -c conda-forge spleeter
	```
</details>
<details><summary><b><a href="https://github.com/Picovoice/porcupine">Porcupine</a></b> (🥉28 ·  ⭐ 2.6K) - On-device wake word detection powered by deep learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Picovoice/porcupine) (👨‍💻 31 · 🔀 390 · 📦 8 · 📋 360 - 1% open · ⏱️ 06.02.2022):

	```
	git clone https://github.com/Picovoice/Porcupine
	```
- [PyPi](https://pypi.org/project/pvporcupine) (📥 2.2K / month · 📦 8 · ⏱️ 04.02.2022):
	```
	pip install pvporcupine
	```
</details>
<details><summary><b><a href="https://github.com/CPJKU/madmom">Madmom</a></b> (🥉27 ·  ⭐ 860) - Python audio and music signal processing library. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/CPJKU/madmom) (👨‍💻 20 · 🔀 150 · 📦 180 · 📋 260 - 21% open · ⏱️ 06.01.2022):

	```
	git clone https://github.com/CPJKU/madmom
	```
- [PyPi](https://pypi.org/project/madmom) (📥 7.6K / month · 📦 27 · ⏱️ 14.11.2018):
	```
	pip install madmom
	```
</details>
<details><summary><b><a href="https://github.com/devsnd/tinytag">tinytag</a></b> (🥉27 ·  ⭐ 500) - Read audio and music meta data and duration of MP3, OGG, OPUS, MP4, M4A,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/devsnd/tinytag) (👨‍💻 21 · 🔀 87 · 📦 480 · 📋 87 - 13% open · ⏱️ 17.12.2021):

	```
	git clone https://github.com/devsnd/tinytag
	```
- [PyPi](https://pypi.org/project/tinytag) (📥 26K / month · 📦 67 · ⏱️ 14.12.2021):
	```
	pip install tinytag
	```
</details>
<details><summary><b><a href="https://github.com/magenta/ddsp">DDSP</a></b> (🥉26 ·  ⭐ 2.1K) - DDSP: Differentiable Digital Signal Processing. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/magenta/ddsp) (👨‍💻 29 · 🔀 220 · 📦 19 · 📋 130 - 17% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/magenta/ddsp
	```
- [PyPi](https://pypi.org/project/ddsp) (📥 2K / month · 📦 1 · ⏱️ 24.12.2021):
	```
	pip install ddsp
	```
- [Conda](https://anaconda.org/conda-forge/ddsp) (📥 10K · ⏱️ 08.06.2020):
	```
	conda install -c conda-forge ddsp
	```
</details>
<details><summary><b><a href="https://github.com/iver56/audiomentations">audiomentations</a></b> (🥉25 ·  ⭐ 860) - A Python library for audio data augmentation. Inspired by.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/iver56/audiomentations) (👨‍💻 21 · 🔀 110 · 📦 110 · 📋 98 - 27% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/iver56/audiomentations
	```
- [PyPi](https://pypi.org/project/audiomentations) (📥 2.8K / month · ⏱️ 10.02.2022):
	```
	pip install audiomentations
	```
</details>
<details><summary><b><a href="https://github.com/keunwoochoi/kapre">kapre</a></b> (🥉24 ·  ⭐ 800) - kapre: Keras Audio Preprocessors. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/keunwoochoi/kapre) (👨‍💻 13 · 🔀 140 · 📥 19 · 📦 1.4K · 📋 94 - 12% open · ⏱️ 21.01.2022):

	```
	git clone https://github.com/keunwoochoi/kapre
	```
- [PyPi](https://pypi.org/project/kapre) (📥 2.2K / month · 📦 14 · ⏱️ 21.01.2022):
	```
	pip install kapre
	```
</details>
<details><summary><b><a href="https://github.com/bastibe/python-soundfile">python-soundfile</a></b> (🥉24 ·  ⭐ 430) - SoundFile is an audio library based on libsndfile, CFFI, and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bastibe/python-soundfile) (👨‍💻 23 · 🔀 59 · 📥 2.9K · 📋 160 - 38% open · ⏱️ 28.01.2022):

	```
	git clone https://github.com/bastibe/python-soundfile
	```
- [PyPi](https://pypi.org/project/soundfile) (📥 880K / month · 📦 540 · ⏱️ 27.11.2019):
	```
	pip install soundfile
	```
- [Conda](https://anaconda.org/anaconda/pysoundfile):
	```
	conda install -c anaconda pysoundfile
	```
</details>
<details><summary><b><a href="https://github.com/mozilla/TTS">TTS</a></b> (🥉22 ·  ⭐ 5.6K · 💤) - Deep learning for Text to Speech (Discussion forum:.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/mozilla/TTS) (👨‍💻 56 · 🔀 870 · 📥 1.8K · 📋 530 - 3% open · ⏱️ 12.02.2021):

	```
	git clone https://github.com/mozilla/TTS
	```
</details>
<details><summary><b><a href="https://github.com/KinWaiCheuk/nnAudio">nnAudio</a></b> (🥉21 ·  ⭐ 650) - Audio processing by using pytorch 1D convolution network. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/KinWaiCheuk/nnAudio) (👨‍💻 13 · 🔀 62 · 📦 41 · 📋 49 - 24% open · ⏱️ 24.12.2021):

	```
	git clone https://github.com/KinWaiCheuk/nnAudio
	```
- [PyPi](https://pypi.org/project/nnAudio) (📥 1.5K / month · 📦 1 · ⏱️ 24.12.2021):
	```
	pip install nnAudio
	```
</details>
<details><summary>Show 7 hidden projects...</summary>

- <b><a href="https://github.com/aubio/aubio">aubio</a></b> (🥈29 ·  ⭐ 2.6K) - a library for audio and music analysis. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/MTG/essentia">Essentia</a></b> (🥉28 ·  ⭐ 2K) - C++ library for audio and music analysis, description and.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/jameslyons/python_speech_features">python_speech_features</a></b> (🥉24 ·  ⭐ 2K · 💀) - This library provides common speech features for ASR.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/worldveil/dejavu">Dejavu</a></b> (🥉22 ·  ⭐ 5.6K · 💀) - Audio fingerprinting and recognition in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Parisson/TimeSide">TimeSide</a></b> (🥉21 ·  ⭐ 310 · 💤) - Scalable audio processing framework written in Python with a.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/bmcfee/muda">Muda</a></b> (🥉19 ·  ⭐ 200 · 💤) - A library for augmenting annotated audio data. <code><a href="http://bit.ly/3hkKRql">ISC</a></code>
- <b><a href="https://github.com/adefossez/julius">Julius</a></b> (🥉18 ·  ⭐ 250) - Fast PyTorch based DSP for audio and 1D signals. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Geospatial Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries to load, process, analyze, and write geographic data as well as libraries for spatial analysis, map visualization, and geocoding._

<details><summary><b><a href="https://github.com/visgl/deck.gl">pydeck</a></b> (🥇42 ·  ⭐ 9.4K) - WebGL2 powered visualization framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/visgl/deck.gl) (👨‍💻 190 · 🔀 1.7K · 📦 3.6K · 📋 2.4K - 5% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/visgl/deck.gl
	```
- [PyPi](https://pypi.org/project/pydeck) (📥 830K / month · 📦 16 · ⏱️ 25.10.2021):
	```
	pip install pydeck
	```
- [Conda](https://anaconda.org/conda-forge/pydeck) (📥 68K · ⏱️ 26.10.2021):
	```
	conda install -c conda-forge pydeck
	```
- [npm](https://www.npmjs.com/package/deck.gl) (📥 290K / month · 📦 380 · ⏱️ 10.02.2022):
	```
	npm install deck.gl
	```
</details>
<details><summary><b><a href="https://github.com/shapely/shapely">Shapely</a></b> (🥇37 ·  ⭐ 2.6K) - Manipulation and analysis of geometric objects. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/shapely/shapely) (👨‍💻 130 · 🔀 440 · 📦 26K · 📋 820 - 18% open · ⏱️ 07.02.2022):

	```
	git clone https://github.com/shapely/shapely
	```
- [PyPi](https://pypi.org/project/shapely) (📥 6.6M / month · 📦 3.6K · ⏱️ 25.10.2021):
	```
	pip install shapely
	```
- [Conda](https://anaconda.org/conda-forge/shapely) (📥 3.2M · ⏱️ 19.01.2022):
	```
	conda install -c conda-forge shapely
	```
</details>
<details><summary><b><a href="https://github.com/python-visualization/folium">folium</a></b> (🥇36 ·  ⭐ 5.6K) - Python Data. Leaflet.js Maps. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/python-visualization/folium) (👨‍💻 130 · 🔀 2K · 📦 14K · 📋 920 - 22% open · ⏱️ 08.01.2022):

	```
	git clone https://github.com/python-visualization/folium
	```
- [PyPi](https://pypi.org/project/folium) (📥 720K / month · 📦 630 · ⏱️ 19.11.2021):
	```
	pip install folium
	```
- [Conda](https://anaconda.org/conda-forge/folium) (📥 550K · ⏱️ 03.12.2021):
	```
	conda install -c conda-forge folium
	```
</details>
<details><summary><b><a href="https://github.com/geopandas/geopandas">GeoPandas</a></b> (🥇36 ·  ⭐ 3K) - Python tools for geographic data. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/geopandas/geopandas) (👨‍💻 160 · 🔀 670 · 📥 1.4K · 📦 12K · 📋 1.3K - 32% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/geopandas/geopandas
	```
- [PyPi](https://pypi.org/project/geopandas) (📥 2.3M / month · 📦 1.1K · ⏱️ 16.10.2021):
	```
	pip install geopandas
	```
- [Conda](https://anaconda.org/conda-forge/geopandas) (📥 1.3M · ⏱️ 01.12.2021):
	```
	conda install -c conda-forge geopandas
	```
</details>
<details><summary><b><a href="https://github.com/rasterio/rasterio">Rasterio</a></b> (🥇36 ·  ⭐ 1.7K) - Rasterio reads and writes geospatial raster datasets. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/rasterio/rasterio) (👨‍💻 120 · 🔀 460 · 📥 740 · 📦 4.3K · 📋 1.5K - 10% open · ⏱️ 04.02.2022):

	```
	git clone https://github.com/rasterio/rasterio
	```
- [PyPi](https://pypi.org/project/rasterio) (📥 790K / month · 📦 740 · ⏱️ 04.02.2022):
	```
	pip install rasterio
	```
- [Conda](https://anaconda.org/conda-forge/rasterio) (📥 1.4M · ⏱️ 04.01.2022):
	```
	conda install -c conda-forge rasterio
	```
</details>
<details><summary><b><a href="https://github.com/pyproj4/pyproj">pyproj</a></b> (🥈35 ·  ⭐ 710) - Python interface to PROJ (cartographic projections and coordinate.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyproj4/pyproj) (👨‍💻 46 · 🔀 170 · 📦 13K · 📋 460 - 1% open · ⏱️ 28.01.2022):

	```
	git clone https://github.com/pyproj4/pyproj
	```
- [PyPi](https://pypi.org/project/pyproj) (📥 4.2M / month · 📦 1.6K · ⏱️ 18.11.2021):
	```
	pip install pyproj
	```
- [Conda](https://anaconda.org/conda-forge/pyproj) (📥 2.9M · ⏱️ 03.01.2022):
	```
	conda install -c conda-forge pyproj
	```
</details>
<details><summary><b><a href="https://github.com/Toblerity/Fiona">Fiona</a></b> (🥈34 ·  ⭐ 880) - Fiona reads and writes geographic data files. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Toblerity/Fiona) (👨‍💻 66 · 🔀 180 · 📦 7.7K · 📋 660 - 11% open · ⏱️ 07.02.2022):

	```
	git clone https://github.com/Toblerity/Fiona
	```
- [PyPi](https://pypi.org/project/fiona) (📥 2.6M / month · 📦 770 · ⏱️ 07.02.2022):
	```
	pip install fiona
	```
- [Conda](https://anaconda.org/conda-forge/fiona) (📥 2.5M · ⏱️ 08.02.2022):
	```
	conda install -c conda-forge fiona
	```
</details>
<details><summary><b><a href="https://github.com/geopy/geopy">geopy</a></b> (🥈33 ·  ⭐ 3.6K) - Geocoding library for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/geopy/geopy) (👨‍💻 120 · 🔀 560 · 📦 33K · 📋 250 - 9% open · ⏱️ 26.09.2021):

	```
	git clone https://github.com/geopy/geopy
	```
- [PyPi](https://pypi.org/project/geopy) (📥 3.1M / month · 📦 3.9K · ⏱️ 11.07.2021):
	```
	pip install geopy
	```
- [Conda](https://anaconda.org/conda-forge/geopy) (📥 650K · ⏱️ 12.07.2021):
	```
	conda install -c conda-forge geopy
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/ipyleaflet">ipyleaflet</a></b> (🥉32 ·  ⭐ 1.2K) - A Jupyter - Leaflet.js bridge. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jupyter-widgets/ipyleaflet) (👨‍💻 74 · 🔀 320 · 📦 1.4K · 📋 470 - 38% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/jupyter-widgets/ipyleaflet
	```
- [PyPi](https://pypi.org/project/ipyleaflet) (📥 56K / month · 📦 100 · ⏱️ 06.12.2021):
	```
	pip install ipyleaflet
	```
- [Conda](https://anaconda.org/conda-forge/ipyleaflet) (📥 790K · ⏱️ 09.12.2021):
	```
	conda install -c conda-forge ipyleaflet
	```
- [npm](https://www.npmjs.com/package/jupyter-leaflet) (📥 45K / month · 📦 2 · ⏱️ 06.12.2021):
	```
	npm install jupyter-leaflet
	```
</details>
<details><summary><b><a href="https://github.com/Esri/arcgis-python-api">ArcGIS API</a></b> (🥉30 ·  ⭐ 1.2K) - Documentation and samples for ArcGIS API for Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Esri/arcgis-python-api) (👨‍💻 77 · 🔀 870 · 📥 1.7K · 📋 420 - 29% open · ⏱️ 01.02.2022):

	```
	git clone https://github.com/Esri/arcgis-python-api
	```
- [PyPi](https://pypi.org/project/arcgis) (📥 48K / month · 📦 22 · ⏱️ 03.02.2022):
	```
	pip install arcgis
	```
- [Docker Hub](https://hub.docker.com/r/esridocker/arcgis-api-python-notebook) (📥 5.9K · ⭐ 33 · ⏱️ 04.02.2022):
	```
	docker pull esridocker/arcgis-api-python-notebook
	```
</details>
<details><summary><b><a href="https://github.com/pysal/pysal">PySAL</a></b> (🥉28 ·  ⭐ 970) - PySAL: Python Spatial Analysis Library Meta-Package. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pysal/pysal) (👨‍💻 75 · 🔀 270 · 📋 610 - 1% open · ⏱️ 30.01.2022):

	```
	git clone https://github.com/pysal/pysal
	```
- [PyPi](https://pypi.org/project/pysal) (📥 17K / month · 📦 30 · ⏱️ 30.01.2022):
	```
	pip install pysal
	```
- [Conda](https://anaconda.org/conda-forge/pysal) (📥 430K · ⏱️ 31.01.2022):
	```
	conda install -c conda-forge pysal
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/geojson">geojson</a></b> (🥉28 ·  ⭐ 690) - Python bindings and utilities for GeoJSON. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/geojson) (👨‍💻 46 · 🔀 90 · 📦 8.5K · 📋 80 - 27% open · ⏱️ 03.01.2022):

	```
	git clone https://github.com/jazzband/geojson
	```
- [PyPi](https://pypi.org/project/geojson) (📥 760K / month · 📦 1.1K · ⏱️ 09.08.2019):
	```
	pip install geojson
	```
- [Conda](https://anaconda.org/conda-forge/geojson) (📥 470K · ⏱️ 11.08.2019):
	```
	conda install -c conda-forge geojson
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/geoviews">GeoViews</a></b> (🥉26 ·  ⭐ 390) - Simple, concise geographical visualization in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/holoviz/geoviews) (👨‍💻 25 · 🔀 69 · 📋 300 - 35% open · ⏱️ 25.12.2021):

	```
	git clone https://github.com/holoviz/geoviews
	```
- [PyPi](https://pypi.org/project/geoviews) (📥 13K / month · 📦 25 · ⏱️ 25.12.2021):
	```
	pip install geoviews
	```
- [Conda](https://anaconda.org/conda-forge/geoviews) (📥 93K · ⏱️ 13.01.2022):
	```
	conda install -c conda-forge geoviews
	```
</details>
<details><summary><b><a href="https://github.com/earthlab/earthpy">EarthPy</a></b> (🥉26 ·  ⭐ 330) - A package built to support working with spatial data using open source.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/earthlab/earthpy) (👨‍💻 40 · 🔀 120 · 📦 130 · 📋 220 - 8% open · ⏱️ 20.12.2021):

	```
	git clone https://github.com/earthlab/earthpy
	```
- [PyPi](https://pypi.org/project/earthpy) (📥 4.8K / month · 📦 7 · ⏱️ 01.10.2021):
	```
	pip install earthpy
	```
- [Conda](https://anaconda.org/conda-forge/earthpy) (📥 41K · ⏱️ 04.10.2021):
	```
	conda install -c conda-forge earthpy
	```
</details>
<details><summary><b><a href="https://github.com/mapbox/mapboxgl-jupyter">Mapbox GL</a></b> (🥉24 ·  ⭐ 600 · 💤) - Use Mapbox GL JS to visualize data in a Python Jupyter notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mapbox/mapboxgl-jupyter) (👨‍💻 21 · 🔀 130 · 📦 120 · 📋 100 - 34% open · ⏱️ 19.04.2021):

	```
	git clone https://github.com/mapbox/mapboxgl-jupyter
	```
- [PyPi](https://pypi.org/project/mapboxgl) (📥 17K / month · 📦 14 · ⏱️ 02.06.2019):
	```
	pip install mapboxgl
	```
</details>
<details><summary>Show 7 hidden projects...</summary>

- <b><a href="https://github.com/DenisCarriere/geocoder">Geocoder</a></b> (🥈33 ·  ⭐ 1.4K · 💀) - Python Geocoder. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/pytroll/satpy">Satpy</a></b> (🥉30 ·  ⭐ 800) - Python package for earth-observing satellite data processing. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/sentinelsat/sentinelsat">Sentinelsat</a></b> (🥉29 ·  ⭐ 710) - Search and download Copernicus Sentinel satellite images. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/pbugnion/gmaps">gmaps</a></b> (🥉24 ·  ⭐ 730 · 💀) - Google maps for Jupyter notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/andrea-cuttone/geoplotlib">geoplotlib</a></b> (🥉21 ·  ⭐ 950 · 💀) - python toolbox for visualizing geographical data and making maps. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/geospace-code/pymap3d">pymap3d</a></b> (🥉21 ·  ⭐ 230) - pure-Python (Numpy optional) 3D coordinate conversions for geospace ecef.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/marceloprates/prettymaps">prettymaps</a></b> (🥉18 ·  ⭐ 7.7K · ➕) - A small set of Python functions to draw pretty maps from.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
</details>
<br>

## Financial Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for algorithmic stock/crypto trading, risk analytics, backtesting, technical analysis, and other tasks on financial data._

<details><summary><b><a href="https://github.com/ranaroussi/yfinance">yfinance</a></b> (🥇35 ·  ⭐ 6.6K) - Download market data from Yahoo! Finances API. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ranaroussi/yfinance) (👨‍💻 53 · 🔀 1.5K · 📦 9.4K · 📋 740 - 55% open · ⏱️ 30.01.2022):

	```
	git clone https://github.com/ranaroussi/yfinance
	```
- [PyPi](https://pypi.org/project/yfinance) (📥 290K / month · 📦 120 · ⏱️ 30.01.2022):
	```
	pip install yfinance
	```
- [Conda](https://anaconda.org/ranaroussi/yfinance) (📥 29K · ⏱️ 10.07.2021):
	```
	conda install -c ranaroussi yfinance
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/qlib">Qlib</a></b> (🥇31 ·  ⭐ 8K) - Qlib is an AI-oriented quantitative investment platform, which aims to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/microsoft/qlib) (👨‍💻 81 · 🔀 1.3K · 📥 270 · 📦 11 · 📋 460 - 33% open · ⏱️ 07.02.2022):

	```
	git clone https://github.com/microsoft/qlib
	```
- [PyPi](https://pypi.org/project/pyqlib) (📥 4.4K / month · ⏱️ 19.01.2022):
	```
	pip install pyqlib
	```
</details>
<details><summary><b><a href="https://github.com/bukosabino/ta">ta</a></b> (🥇31 ·  ⭐ 2.8K) - Technical Analysis Library using Pandas and Numpy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bukosabino/ta) (👨‍💻 26 · 🔀 650 · 📦 980 · 📋 200 - 53% open · ⏱️ 27.01.2022):

	```
	git clone https://github.com/bukosabino/ta
	```
- [PyPi](https://pypi.org/project/ta) (📥 89K / month · 📦 27 · ⏱️ 09.01.2022):
	```
	pip install ta
	```
- [Conda](https://anaconda.org/conda-forge/ta) (📥 2.2K · ⏱️ 12.01.2022):
	```
	conda install -c conda-forge ta
	```
</details>
<details><summary><b><a href="https://github.com/erdewit/ib_insync">IB-insync</a></b> (🥈29 ·  ⭐ 1.7K) - Python sync/async framework for Interactive Brokers API. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/erdewit/ib_insync) (👨‍💻 29 · 🔀 470 · 📋 370 - 1% open · ⏱️ 06.02.2022):

	```
	git clone https://github.com/erdewit/ib_insync
	```
- [PyPi](https://pypi.org/project/ib_insync) (📥 9.8K / month · 📦 19 · ⏱️ 28.11.2021):
	```
	pip install ib_insync
	```
- [Conda](https://anaconda.org/conda-forge/ib-insync) (📥 14K · ⏱️ 29.11.2021):
	```
	conda install -c conda-forge ib-insync
	```
</details>
<details><summary><b><a href="https://github.com/RomelTorres/alpha_vantage">Alpha Vantage</a></b> (🥈28 ·  ⭐ 3.6K · 💤) - A python wrapper for Alpha Vantage API for financial data. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/RomelTorres/alpha_vantage) (👨‍💻 39 · 🔀 630 · 📋 260 - 5% open · ⏱️ 14.06.2021):

	```
	git clone https://github.com/RomelTorres/alpha_vantage
	```
- [PyPi](https://pypi.org/project/alpha_vantage) (📥 22K / month · 📦 100 · ⏱️ 26.08.2018):
	```
	pip install alpha_vantage
	```
- [Conda](https://anaconda.org/conda-forge/alpha_vantage) (📥 910 · ⏱️ 14.01.2021):
	```
	conda install -c conda-forge alpha_vantage
	```
</details>
<details><summary><b><a href="https://github.com/tensortrade-org/tensortrade">TensorTrade</a></b> (🥈27 ·  ⭐ 3.7K) - An open source reinforcement learning framework for training,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tensortrade-org/tensortrade) (👨‍💻 60 · 🔀 840 · 📦 30 · 📋 210 - 11% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/tensortrade-org/tensortrade
	```
- [PyPi](https://pypi.org/project/tensortrade) (📥 990 / month · 📦 1 · ⏱️ 10.05.2021):
	```
	pip install tensortrade
	```
- [Conda](https://anaconda.org/conda-forge/tensortrade) (📥 940 · ⏱️ 10.05.2021):
	```
	conda install -c conda-forge tensortrade
	```
</details>
<details><summary><b><a href="https://github.com/pmorissette/bt">bt</a></b> (🥈27 ·  ⭐ 1.3K) - bt - flexible backtesting for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pmorissette/bt) (👨‍💻 25 · 🔀 300 · 📦 93 · 📋 280 - 18% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/pmorissette/bt
	```
- [PyPi](https://pypi.org/project/bt) (📥 5.8K / month · 📦 21 · ⏱️ 21.04.2021):
	```
	pip install bt
	```
- [Conda](https://anaconda.org/conda-forge/bt) (📥 2.9K · ⏱️ 18.01.2022):
	```
	conda install -c conda-forge bt
	```
</details>
<details><summary><b><a href="https://github.com/jealous/stockstats">stockstats</a></b> (🥉26 ·  ⭐ 950) - Supply a wrapper ``StockDataFrame`` based on the.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jealous/stockstats) (👨‍💻 8 · 🔀 250 · 📦 400 · 📋 79 - 3% open · ⏱️ 07.01.2022):

	```
	git clone https://github.com/jealous/stockstats
	```
- [PyPi](https://pypi.org/project/stockstats) (📥 9.2K / month · 📦 29 · ⏱️ 07.01.2022):
	```
	pip install stockstats
	```
</details>
<details><summary><b><a href="https://github.com/scrtlabs/catalyst">Enigma Catalyst</a></b> (🥉25 ·  ⭐ 2.3K) - An Algorithmic Trading Library for Crypto-Assets in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/scrtlabs/catalyst) (👨‍💻 150 · 🔀 680 · 📦 23 · 📋 490 - 27% open · ⏱️ 22.09.2021):

	```
	git clone https://github.com/scrtlabs/catalyst
	```
- [PyPi](https://pypi.org/project/enigma-catalyst) (📥 460 / month · 📦 2 · ⏱️ 11.11.2018):
	```
	pip install enigma-catalyst
	```
</details>
<details><summary><b><a href="https://github.com/pmorissette/ffn">ffn</a></b> (🥉25 ·  ⭐ 1.1K) - ffn - a financial function library for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pmorissette/ffn) (👨‍💻 26 · 🔀 200 · 📦 160 · 📋 96 - 16% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/pmorissette/ffn
	```
- [PyPi](https://pypi.org/project/ffn) (📥 28K / month · 📦 25 · ⏱️ 21.04.2021):
	```
	pip install ffn
	```
- [Conda](https://anaconda.org/conda-forge/ffn) (📥 640 · ⏱️ 22.04.2021):
	```
	conda install -c conda-forge ffn
	```
</details>
<details><summary><b><a href="https://github.com/CryptoSignal/Crypto-Signal">Crypto Signals</a></b> (🥉21 ·  ⭐ 3.8K · 💤) - Github.com/CryptoSignal - #1 Quant Trading & Technical.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/CryptoSignal/Crypto-Signal) (👨‍💻 28 · 🔀 990 · 📋 250 - 21% open · ⏱️ 28.06.2021):

	```
	git clone https://github.com/CryptoSignal/crypto-signal
	```
- [Docker Hub](https://hub.docker.com/r/shadowreaver/crypto-signal) (📥 140K · ⭐ 7 · ⏱️ 03.09.2020):
	```
	docker pull shadowreaver/crypto-signal
	```
</details>
<details><summary><b><a href="https://github.com/google/tf-quant-finance">tf-quant-finance</a></b> (🥉21 ·  ⭐ 3K) - High-performance TensorFlow library for quantitative.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google/tf-quant-finance) (👨‍💻 36 · 🔀 400 · 📋 38 - 50% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/google/tf-quant-finance
	```
- [PyPi](https://pypi.org/project/tf-quant-finance) (📥 1K / month · 📦 2 · ⏱️ 07.01.2022):
	```
	pip install tf-quant-finance
	```
</details>
<details><summary><b><a href="https://github.com/cuemacro/finmarketpy">finmarketpy</a></b> (🥉20 ·  ⭐ 2.9K) - Python library for backtesting trading strategies & analyzing.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/cuemacro/finmarketpy) (👨‍💻 14 · 🔀 450 · 📥 40 · 📦 4 · 📋 26 - 88% open · ⏱️ 07.10.2021):

	```
	git clone https://github.com/cuemacro/finmarketpy
	```
- [PyPi](https://pypi.org/project/finmarketpy) (📥 110 / month · ⏱️ 07.10.2021):
	```
	pip install finmarketpy
	```
</details>
<details><summary>Show 12 hidden projects...</summary>

- <b><a href="https://github.com/quantopian/zipline">zipline</a></b> (🥇33 ·  ⭐ 15K · 💀) - Zipline, a Pythonic Algorithmic Trading Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/quantopian/pyfolio">pyfolio</a></b> (🥈30 ·  ⭐ 4.3K · 💀) - Portfolio and risk analytics in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/mementum/backtrader">backtrader</a></b> (🥈29 ·  ⭐ 8.2K · 💤) - Python Backtesting library for trading strategies. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/bashtage/arch">arch</a></b> (🥈29 ·  ⭐ 860) - ARCH models in Python. <code><a href="https://tldrlegal.com/search?q=NCSA">❗️NCSA</a></code>
- <b><a href="https://github.com/quantopian/alphalens">Alphalens</a></b> (🥈27 ·  ⭐ 2.2K · 💀) - Performance analysis of predictive (alpha) stock factors. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/quantopian/empyrical">empyrical</a></b> (🥉26 ·  ⭐ 890 · 💀) - Common financial risk and performance metrics. Used by zipline.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/gbeced/pyalgotrade">PyAlgoTrade</a></b> (🥉25 ·  ⭐ 3.6K · 💀) - Python Algorithmic Trading Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/peerchemist/finta">FinTA</a></b> (🥉22 ·  ⭐ 1.4K) - Common financial technical indicators implemented in Pandas. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code>
- <b><a href="https://github.com/kernc/backtesting.py">Backtesting.py</a></b> (🥉20 ·  ⭐ 2.1K) - Backtest trading strategies in Python. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/fmilthaler/FinQuant">FinQuant</a></b> (🥉18 ·  ⭐ 720 · 💀) - A program for financial portfolio management, analysis and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/tradytics/surpriver">surpriver</a></b> (🥉12 ·  ⭐ 1.4K · 💀) - Find big moving stocks before they move using machine.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/alvarobartt/pyrtfolio">pyrtfolio</a></b> (🥉7 ·  ⭐ 100 · 💀) - Python package to generate stock portfolios. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
</details>
<br>

## Time Series Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for forecasting, anomaly detection, feature extraction, and machine learning on time-series and sequential data._

<details><summary><b><a href="https://github.com/alan-turing-institute/sktime">sktime</a></b> (🥇33 ·  ⭐ 4.9K) - A unified framework for machine learning with time series. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/alan-turing-institute/sktime) (👨‍💻 140 · 🔀 740 · 📥 64 · 📦 350 · 📋 910 - 33% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/alan-turing-institute/sktime
	```
- [PyPi](https://pypi.org/project/sktime) (📥 140K / month · 📦 19 · ⏱️ 08.12.2021):
	```
	pip install sktime
	```
- [Conda](https://anaconda.org/conda-forge/sktime-all-extras) (📥 1.8K · ⏱️ 03.02.2022):
	```
	conda install -c conda-forge sktime-all-extras
	```
</details>
<details><summary><b><a href="https://github.com/facebook/prophet">Prophet</a></b> (🥇32 ·  ⭐ 14K) - Tool for producing high quality forecasts for time series data that has.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebook/prophet) (👨‍💻 140 · 🔀 4K · 📥 640 · 📋 1.8K - 10% open · ⏱️ 31.01.2022):

	```
	git clone https://github.com/facebook/prophet
	```
- [PyPi](https://pypi.org/project/fbprophet) (📥 1.3M / month · 📦 120 · ⏱️ 05.09.2020):
	```
	pip install fbprophet
	```
- [Conda](https://anaconda.org/conda-forge/prophet) (📥 28K · ⏱️ 23.08.2021):
	```
	conda install -c conda-forge prophet
	```
</details>
<details><summary><b><a href="https://github.com/blue-yonder/tsfresh">tsfresh</a></b> (🥇31 ·  ⭐ 6.2K) - Automatic extraction of relevant features from time series:. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/blue-yonder/tsfresh) (👨‍💻 82 · 🔀 960 · 📋 480 - 8% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/blue-yonder/tsfresh
	```
- [PyPi](https://pypi.org/project/tsfresh) (📥 400K / month · 📦 55 · ⏱️ 21.12.2021):
	```
	pip install tsfresh
	```
- [Conda](https://anaconda.org/conda-forge/tsfresh) (📥 94K · ⏱️ 21.12.2021):
	```
	conda install -c conda-forge tsfresh
	```
</details>
<details><summary><b><a href="https://github.com/alkaline-ml/pmdarima">pmdarima</a></b> (🥇31 ·  ⭐ 1.1K) - A statistical library designed to fill the void in Pythons time series.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/alkaline-ml/pmdarima) (👨‍💻 19 · 🔀 190 · 📦 1.7K · 📋 270 - 9% open · ⏱️ 04.01.2022):

	```
	git clone https://github.com/alkaline-ml/pmdarima
	```
- [PyPi](https://pypi.org/project/pmdarima) (📥 1M / month · 📦 44 · ⏱️ 05.11.2021):
	```
	pip install pmdarima
	```
- [Conda](https://anaconda.org/conda-forge/pmdarima) (📥 29K · ⏱️ 15.11.2021):
	```
	conda install -c conda-forge pmdarima
	```
</details>
<details><summary><b><a href="https://github.com/tslearn-team/tslearn">tslearn</a></b> (🥈30 ·  ⭐ 2K) - A machine learning toolkit dedicated to time-series data. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tslearn-team/tslearn) (👨‍💻 36 · 🔀 260 · 📦 400 · 📋 250 - 29% open · ⏱️ 06.12.2021):

	```
	git clone https://github.com/tslearn-team/tslearn
	```
- [PyPi](https://pypi.org/project/tslearn) (📥 100K / month · 📦 19 · ⏱️ 16.08.2021):
	```
	pip install tslearn
	```
- [Conda](https://anaconda.org/conda-forge/tslearn) (📥 250K · ⏱️ 15.01.2022):
	```
	conda install -c conda-forge tslearn
	```
</details>
<details><summary><b><a href="https://github.com/TDAmeritrade/stumpy">STUMPY</a></b> (🥈29 ·  ⭐ 2.1K) - STUMPY is a powerful and scalable Python library for modern time series.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/TDAmeritrade/stumpy) (👨‍💻 28 · 🔀 200 · 📋 290 - 10% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/TDAmeritrade/stumpy
	```
- [PyPi](https://pypi.org/project/stumpy) (📥 300K / month · 📦 4 · ⏱️ 24.12.2021):
	```
	pip install stumpy
	```
- [Conda](https://anaconda.org/conda-forge/stumpy) (📥 35K · ⏱️ 24.12.2021):
	```
	conda install -c conda-forge stumpy
	```
</details>
<details><summary><b><a href="https://github.com/jdb78/pytorch-forecasting">pytorch-forecasting</a></b> (🥈29 ·  ⭐ 1.7K) - Time series forecasting with PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jdb78/pytorch-forecasting) (👨‍💻 28 · 🔀 260 · 📋 390 - 39% open · ⏱️ 21.01.2022):

	```
	git clone https://github.com/jdb78/pytorch-forecasting
	```
- [PyPi](https://pypi.org/project/pytorch-forecasting) (📥 25K / month · 📦 4 · ⏱️ 29.11.2021):
	```
	pip install pytorch-forecasting
	```
- [Conda](https://anaconda.org/conda-forge/pytorch-forecasting) (📥 16K · ⏱️ 29.11.2021):
	```
	conda install -c conda-forge pytorch-forecasting
	```
</details>
<details><summary><b><a href="https://github.com/unit8co/darts">Darts</a></b> (🥈28 ·  ⭐ 3.7K) - A python library for easy manipulation and forecasting of time series. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/unit8co/darts) (👨‍💻 43 · 🔀 340 · 📦 28 · 📋 330 - 35% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/unit8co/darts
	```
- [PyPi](https://pypi.org/project/u8darts) (📥 5.1K / month · 📦 2 · ⏱️ 24.01.2022):
	```
	pip install u8darts
	```
- [Conda](https://anaconda.org/conda-forge/u8darts-all) (📥 2K · ⏱️ 25.01.2022):
	```
	conda install -c conda-forge u8darts-all
	```
- [Docker Hub](https://hub.docker.com/r/unit8/darts) (📥 260 · ⏱️ 24.01.2022):
	```
	docker pull unit8/darts
	```
</details>
<details><summary><b><a href="https://github.com/awslabs/gluon-ts">GluonTS</a></b> (🥈28 ·  ⭐ 2.5K) - Probabilistic time series modeling in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/awslabs/gluon-ts) (👨‍💻 84 · 🔀 500 · 📋 700 - 39% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/awslabs/gluon-ts
	```
- [PyPi](https://pypi.org/project/gluonts) (📥 77K / month · 📦 3 · ⏱️ 11.11.2021):
	```
	pip install gluonts
	```
- [Conda](https://anaconda.org/anaconda/gluonts) (📥 2 · ⏱️ 14.10.2021):
	```
	conda install -c anaconda gluonts
	```
</details>
<details><summary><b><a href="https://github.com/python-streamz/streamz">Streamz</a></b> (🥉26 ·  ⭐ 1K) - Real-time stream processing for python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/python-streamz/streamz) (👨‍💻 45 · 🔀 130 · 📦 260 · 📋 250 - 41% open · ⏱️ 24.12.2021):

	```
	git clone https://github.com/python-streamz/streamz
	```
- [PyPi](https://pypi.org/project/streamz) (📥 11K / month · 📦 29 · ⏱️ 04.10.2021):
	```
	pip install streamz
	```
- [Conda](https://anaconda.org/conda-forge/streamz) (📥 240K · ⏱️ 04.10.2021):
	```
	conda install -c conda-forge streamz
	```
</details>
<details><summary><b><a href="https://github.com/johannfaouzi/pyts">pyts</a></b> (🥉25 ·  ⭐ 1.2K) - A Python package for time series classification. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/johannfaouzi/pyts) (👨‍💻 10 · 🔀 120 · 📦 170 · 📋 57 - 57% open · ⏱️ 09.12.2021):

	```
	git clone https://github.com/johannfaouzi/pyts
	```
- [PyPi](https://pypi.org/project/pyts) (📥 110K / month · 📦 11 · ⏱️ 31.10.2021):
	```
	pip install pyts
	```
- [Conda](https://anaconda.org/conda-forge/pyts) (📥 10K · ⏱️ 31.10.2021):
	```
	conda install -c conda-forge pyts
	```
</details>
<details><summary><b><a href="https://github.com/linkedin/greykite">greykite</a></b> (🥉21 ·  ⭐ 1.5K) - A flexible, intuitive and fast forecasting library. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/linkedin/greykite) (👨‍💻 7 · 🔀 64 · 📦 8 · 📋 58 - 12% open · ⏱️ 15.12.2021):

	```
	git clone https://github.com/linkedin/greykite
	```
- [PyPi](https://pypi.org/project/greykite) (📥 20K / month · ⏱️ 15.12.2021):
	```
	pip install greykite
	```
</details>
<details><summary><b><a href="https://github.com/dmbee/seglearn">seglearn</a></b> (🥉20 ·  ⭐ 490 · 💤) - Python module for machine learning time series:. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dmbee/seglearn) (👨‍💻 13 · 🔀 52 · 📦 11 · 📋 28 - 17% open · ⏱️ 12.03.2021):

	```
	git clone https://github.com/dmbee/seglearn
	```
- [PyPi](https://pypi.org/project/seglearn) (📥 1.1K / month · 📦 1 · ⏱️ 13.03.2021):
	```
	pip install seglearn
	```
</details>
<details><summary><b><a href="https://github.com/AutoViML/Auto_TS">Auto TS</a></b> (🥉20 ·  ⭐ 390) - Automatically build ARIMA, SARIMAX, VAR, FB Prophet and XGBoost.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/AutoViML/Auto_TS) (👨‍💻 6 · 🔀 69 · 📋 62 - 9% open · ⏱️ 31.01.2022):

	```
	git clone https://github.com/AutoViML/Auto_TS
	```
- [PyPi](https://pypi.org/project/auto-ts) (📥 2.5K / month · ⏱️ 31.01.2022):
	```
	pip install auto-ts
	```
</details>
<details><summary><b><a href="https://github.com/fraunhoferportugal/tsfel">TSFEL</a></b> (🥉20 ·  ⭐ 380) - An intuitive library to extract features from time series. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/fraunhoferportugal/tsfel) (👨‍💻 13 · 🔀 56 · 📦 25 · 📋 48 - 10% open · ⏱️ 23.12.2021):

	```
	git clone https://github.com/fraunhoferportugal/tsfel
	```
- [PyPi](https://pypi.org/project/tsfel) (📥 5.7K / month · ⏱️ 14.02.2021):
	```
	pip install tsfel
	```
</details>
<details><summary><b><a href="https://github.com/firmai/atspy">atspy</a></b> (🥉14 ·  ⭐ 410) - AtsPy: Automated Time Series Models in Python (by @firmai). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/firmai/atspy) (👨‍💻 5 · 🔀 80 · 📦 5 · 📋 20 - 90% open · ⏱️ 18.12.2021):

	```
	git clone https://github.com/firmai/atspy
	```
- [PyPi](https://pypi.org/project/atspy) (📥 690 / month · ⏱️ 24.04.2020):
	```
	pip install atspy
	```
</details>
<details><summary>Show 7 hidden projects...</summary>

- <b><a href="https://github.com/RJT1990/pyflux">PyFlux</a></b> (🥉24 ·  ⭐ 1.9K · 💀) - Open source time series library for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/linkedin/luminol">luminol</a></b> (🥉21 ·  ⭐ 1K · 💀) - Anomaly Detection and Correlation library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/X-DataInitiative/tick">tick</a></b> (🥉21 ·  ⭐ 370 · 💀) - Module for statistical learning, with a particular emphasis on time-.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/wwrechard/pydlm">pydlm</a></b> (🥉20 ·  ⭐ 410 · 💀) - A python library for Bayesian time series modeling. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/arundo/adtk">ADTK</a></b> (🥉19 ·  ⭐ 770 · 💀) - A Python toolkit for rule-based/unsupervised anomaly detection in time.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code>
- <b><a href="https://github.com/target/matrixprofile-ts">matrixprofile-ts</a></b> (🥉19 ·  ⭐ 670 · 💀) - A Python library for detecting patterns and anomalies.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/arundo/tsaug">tsaug</a></b> (🥉14 ·  ⭐ 220 · 💀) - A Python package for time series augmentation. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Medical Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for processing and analyzing medical data such as MRIs, EEGs, genomic data, and other medical imaging formats._

<details><summary><b><a href="https://github.com/mne-tools/mne-python">MNE</a></b> (🥇37 ·  ⭐ 1.8K) - MNE: Magnetoencephalography (MEG) and Electroencephalography (EEG) in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mne-tools/mne-python) (👨‍💻 280 · 🔀 970 · 📦 1.4K · 📋 3.9K - 9% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/mne-tools/mne-python
	```
- [PyPi](https://pypi.org/project/mne) (📥 30K / month · 📦 190 · ⏱️ 01.12.2021):
	```
	pip install mne
	```
- [Conda](https://anaconda.org/conda-forge/mne) (📥 180K · ⏱️ 18.12.2021):
	```
	conda install -c conda-forge mne
	```
</details>
<details><summary><b><a href="https://github.com/nilearn/nilearn">Nilearn</a></b> (🥇35 ·  ⭐ 810) - Machine learning for NeuroImaging in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/nilearn/nilearn) (👨‍💻 180 · 🔀 440 · 📥 19 · 📦 1.4K · 📋 1.6K - 17% open · ⏱️ 07.02.2022):

	```
	git clone https://github.com/nilearn/nilearn
	```
- [PyPi](https://pypi.org/project/nilearn) (📥 19K / month · 📦 230 · ⏱️ 28.01.2022):
	```
	pip install nilearn
	```
- [Conda](https://anaconda.org/conda-forge/nilearn) (📥 140K · ⏱️ 31.01.2022):
	```
	conda install -c conda-forge nilearn
	```
</details>
<details><summary><b><a href="https://github.com/hail-is/hail">Hail</a></b> (🥈34 ·  ⭐ 780) - Scalable genomic data analysis. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/hail-is/hail) (👨‍💻 77 · 🔀 200 · 📦 47 · 📋 2K - 2% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/hail-is/hail
	```
- [PyPi](https://pypi.org/project/hail) (📥 180K / month · 📦 6 · ⏱️ 01.02.2022):
	```
	pip install hail
	```
</details>
<details><summary><b><a href="https://github.com/Project-MONAI/MONAI">MONAI</a></b> (🥈33 ·  ⭐ 2.7K) - AI Toolkit for Healthcare Imaging. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Project-MONAI/MONAI) (👨‍💻 85 · 🔀 520 · 📦 200 · 📋 1.5K - 10% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/Project-MONAI/MONAI
	```
- [PyPi](https://pypi.org/project/monai) (📥 44K / month · 📦 11 · ⏱️ 09.02.2022):
	```
	pip install monai
	```
- [Conda](https://anaconda.org/conda-forge/monai) (📥 90 · ⏱️ 09.01.2022):
	```
	conda install -c conda-forge monai
	```
</details>
<details><summary><b><a href="https://github.com/nipy/nipype">NIPYPE</a></b> (🥈33 ·  ⭐ 620) - Workflows and interfaces for neuroimaging packages. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nipy/nipype) (👨‍💻 230 · 🔀 480 · 📦 840 · 📋 1.3K - 28% open · ⏱️ 15.12.2021):

	```
	git clone https://github.com/nipy/nipype
	```
- [PyPi](https://pypi.org/project/nipype) (📥 43K / month · 📦 150 · ⏱️ 20.10.2021):
	```
	pip install nipype
	```
- [Conda](https://anaconda.org/conda-forge/nipype) (📥 460K · ⏱️ 20.10.2021):
	```
	conda install -c conda-forge nipype
	```
</details>
<details><summary><b><a href="https://github.com/nipy/nibabel">NiBabel</a></b> (🥈33 ·  ⭐ 460) - Python package to access a cacophony of neuro-imaging file formats. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nipy/nibabel) (👨‍💻 93 · 🔀 230 · 📦 6.3K · 📋 450 - 30% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/nipy/nibabel
	```
- [PyPi](https://pypi.org/project/nibabel) (📥 200K / month · 📦 970 · ⏱️ 07.02.2022):
	```
	pip install nibabel
	```
- [Conda](https://anaconda.org/conda-forge/nibabel) (📥 410K · ⏱️ 07.02.2022):
	```
	conda install -c conda-forge nibabel
	```
</details>
<details><summary><b><a href="https://github.com/CamDavidsonPilon/lifelines">Lifelines</a></b> (🥈32 ·  ⭐ 1.8K) - Survival analysis in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/CamDavidsonPilon/lifelines) (👨‍💻 99 · 🔀 460 · 📦 770 · 📋 850 - 26% open · ⏱️ 19.01.2022):

	```
	git clone https://github.com/CamDavidsonPilon/lifelines
	```
- [PyPi](https://pypi.org/project/lifelines) (📥 360K / month · 📦 100 · ⏱️ 30.11.2021):
	```
	pip install lifelines
	```
- [Conda](https://anaconda.org/conda-forge/lifelines) (📥 180K · ⏱️ 04.02.2022):
	```
	conda install -c conda-forge lifelines
	```
</details>
<details><summary><b><a href="https://github.com/dipy/dipy">DIPY</a></b> (🥈30 ·  ⭐ 490) - DIPY is the paragon 3D/4D+ imaging library in Python. Contains generic.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dipy/dipy) (👨‍💻 130 · 🔀 330 · 📦 490 · 📋 760 - 16% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/dipy/dipy
	```
- [PyPi](https://pypi.org/project/dipy) (📥 11K / month · 📦 80 · ⏱️ 06.05.2021):
	```
	pip install dipy
	```
- [Conda](https://anaconda.org/conda-forge/dipy) (📥 280K · ⏱️ 06.05.2021):
	```
	conda install -c conda-forge dipy
	```
</details>
<details><summary><b><a href="https://github.com/google/deepvariant">DeepVariant</a></b> (🥉26 ·  ⭐ 2.4K) - DeepVariant is an analysis pipeline that uses a deep neural.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google/deepvariant) (👨‍💻 21 · 🔀 580 · 📥 3.8K · 📋 460 - 1% open · ⏱️ 28.01.2022):

	```
	git clone https://github.com/google/deepvariant
	```
- [Conda](https://anaconda.org/bioconda/deepvariant) (📥 37K · ⏱️ 16.12.2021):
	```
	conda install -c bioconda deepvariant
	```
</details>
<details><summary><b><a href="https://github.com/nipy/nipy">NIPY</a></b> (🥉24 ·  ⭐ 320 · 💤) - Neuroimaging in Python FMRI analysis package. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nipy/nipy) (👨‍💻 63 · 🔀 130 · 📋 160 - 28% open · ⏱️ 29.03.2021):

	```
	git clone https://github.com/nipy/nipy
	```
- [PyPi](https://pypi.org/project/nipy) (📥 2.9K / month · 📦 47 · ⏱️ 19.02.2018):
	```
	pip install nipy
	```
- [Conda](https://anaconda.org/conda-forge/nipy) (📥 90K · ⏱️ 04.05.2020):
	```
	conda install -c conda-forge nipy
	```
</details>
<details><summary><b><a href="https://github.com/perone/medicaltorch">MedicalTorch</a></b> (🥉16 ·  ⭐ 760 · 💤) - A medical imaging framework for Pytorch. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/perone/medicaltorch) (👨‍💻 8 · 🔀 110 · 📦 11 · 📋 23 - 60% open · ⏱️ 16.04.2021):

	```
	git clone https://github.com/perone/medicaltorch
	```
- [PyPi](https://pypi.org/project/medicaltorch) (📥 120 / month · ⏱️ 24.11.2018):
	```
	pip install medicaltorch
	```
</details>
<details><summary><b><a href="https://github.com/MIC-DKFZ/medicaldetectiontoolkit">Medical Detection Toolkit</a></b> (🥉14 ·  ⭐ 1.1K) - The Medical Detection Toolkit contains 2D + 3D.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/MIC-DKFZ/medicaldetectiontoolkit) (👨‍💻 3 · 🔀 280 · 📋 120 - 32% open · ⏱️ 09.09.2021):

	```
	git clone https://github.com/MIC-DKFZ/medicaldetectiontoolkit
	```
</details>
<details><summary>Show 7 hidden projects...</summary>

- <b><a href="https://github.com/NifTK/NiftyNet">NiftyNet</a></b> (🥉23 ·  ⭐ 1.3K · 💀) - [unmaintained] An open-source convolutional neural.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/DLTK/DLTK">DLTK</a></b> (🥉22 ·  ⭐ 1.3K · 💀) - Deep Learning Toolkit for Medical Image Analysis. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/loli/medpy">MedPy</a></b> (🥉21 ·  ⭐ 390 · 💀) - Medical image processing in Python. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/brainiak/brainiak">Brainiak</a></b> (🥉21 ·  ⭐ 260 · 💤) - Brain Imaging Analysis Kit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/projectglow/glow">Glow</a></b> (🥉21 ·  ⭐ 190) - An open-source toolkit for large-scale genomic analysis. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/QTIM-Lab/DeepNeuro">DeepNeuro</a></b> (🥉13 ·  ⭐ 110 · 💀) - A deep learning python package for neuroimaging data. Made by:. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Tencent/MedicalNet">MedicalNet</a></b> (🥉12 ·  ⭐ 1.3K · 💀) - Many studies have shown that the performance on deep learning is.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Tabular Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for processing tabular and structured data._

<details><summary><b><a href="https://github.com/manujosephv/pytorch_tabular">pytorch_tabular</a></b> (🥇21 ·  ⭐ 530) - A standard framework for modelling Deep Learning Models.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/manujosephv/pytorch_tabular) (👨‍💻 8 · 🔀 52 · 📋 51 - 31% open · ⏱️ 05.02.2022):

	```
	git clone https://github.com/manujosephv/pytorch_tabular
	```
- [PyPi](https://pypi.org/project/pytorch_tabular) (📥 1.3K / month · ⏱️ 01.09.2021):
	```
	pip install pytorch_tabular
	```
</details>
<details><summary><b><a href="https://github.com/carefree0910/carefree-learn">carefree-learn</a></b> (🥈19 ·  ⭐ 360) - Deep Learning PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/carefree0910/carefree-learn) (👨‍💻 1 · 🔀 30 · 📦 2 · ⏱️ 03.02.2022):

	```
	git clone https://github.com/carefree0910/carefree-learn
	```
- [PyPi](https://pypi.org/project/carefree-learn) (📥 160 / month · ⏱️ 29.10.2021):
	```
	pip install carefree-learn
	```
</details>
<details><summary><b><a href="https://github.com/firmai/deltapy">deltapy</a></b> (🥉11 ·  ⭐ 400) - DeltaPy - Tabular Data Augmentation (by @firmai). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/firmai/deltapy) (👨‍💻 4 · 🔀 40 · 📦 2 · 📋 3 - 66% open · ⏱️ 18.12.2021):

	```
	git clone https://github.com/firmai/deltapy
	```
- [PyPi](https://pypi.org/project/deltapy) (📥 47 / month · ⏱️ 09.04.2020):
	```
	pip install deltapy
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/upgini/upgini">upgini</a></b> (🥉15 ·  ⭐ 21 · 🐣) - Automated feature discovery & enrichment library automatically find.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## Optical Character Recognition

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for optical character recognition (OCR) and text extraction from images or videos._

<details><summary><b><a href="https://github.com/PaddlePaddle/PaddleOCR">PaddleOCR</a></b> (🥇36 ·  ⭐ 19K) - Awesome multilingual OCR toolkits based on PaddlePaddle.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PaddleOCR) (👨‍💻 85 · 🔀 3.9K · 📦 540 · 📋 3.9K - 25% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/PaddlePaddle/PaddleOCR
	```
- [PyPi](https://pypi.org/project/paddleocr) (📥 39K / month · 📦 4 · ⏱️ 10.01.2022):
	```
	pip install paddleocr
	```
</details>
<details><summary><b><a href="https://github.com/JaidedAI/EasyOCR">EasyOCR</a></b> (🥇33 ·  ⭐ 14K) - Ready-to-use OCR with 80+ supported languages and all popular writing.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/JaidedAI/EasyOCR) (👨‍💻 91 · 🔀 1.8K · 📥 1.1M · 📦 870 · 📋 500 - 32% open · ⏱️ 14.01.2022):

	```
	git clone https://github.com/JaidedAI/EasyOCR
	```
- [PyPi](https://pypi.org/project/easyocr) (📥 120K / month · 📦 21 · ⏱️ 11.09.2021):
	```
	pip install easyocr
	```
</details>
<details><summary><b><a href="https://github.com/madmaze/pytesseract">Tesseract</a></b> (🥇33 ·  ⭐ 4K) - Python-tesseract is an optical character recognition (OCR) tool for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/madmaze/pytesseract) (👨‍💻 40 · 🔀 570 · 📋 290 - 4% open · ⏱️ 02.02.2022):

	```
	git clone https://github.com/madmaze/pytesseract
	```
- [PyPi](https://pypi.org/project/pytesseract) (📥 520K / month · 📦 920 · ⏱️ 28.06.2021):
	```
	pip install pytesseract
	```
- [Conda](https://anaconda.org/conda-forge/pytesseract) (📥 490K · ⏱️ 26.01.2022):
	```
	conda install -c conda-forge pytesseract
	```
</details>
<details><summary><b><a href="https://github.com/ocrmypdf/OCRmyPDF">OCRmyPDF</a></b> (🥈30 ·  ⭐ 5.9K) - OCRmyPDF adds an OCR text layer to scanned PDF files, allowing them.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/ocrmypdf/OCRmyPDF) (👨‍💻 61 · 🔀 540 · 📋 810 - 10% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/ocrmypdf/OCRmyPDF
	```
- [PyPi](https://pypi.org/project/ocrmypdf) (📥 23K / month · 📦 12 · ⏱️ 26.01.2022):
	```
	pip install ocrmypdf
	```
- [Conda](https://anaconda.org/conda-forge/ocrmypdf) (📥 8.3K · ⏱️ 26.01.2022):
	```
	conda install -c conda-forge ocrmypdf
	```
</details>
<details><summary><b><a href="https://github.com/sirfz/tesserocr">tesserocr</a></b> (🥈27 ·  ⭐ 1.6K) - A Python wrapper for the tesseract-ocr API. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sirfz/tesserocr) (👨‍💻 26 · 🔀 210 · 📦 610 · 📋 240 - 32% open · ⏱️ 09.11.2021):

	```
	git clone https://github.com/sirfz/tesserocr
	```
- [PyPi](https://pypi.org/project/tesserocr) (📥 52K / month · 📦 61 · ⏱️ 19.06.2021):
	```
	pip install tesserocr
	```
- [Conda](https://anaconda.org/conda-forge/tesserocr) (📥 64K · ⏱️ 13.01.2021):
	```
	conda install -c conda-forge tesserocr
	```
</details>
<details><summary><b><a href="https://github.com/Calamari-OCR/calamari">calamari</a></b> (🥉22 ·  ⭐ 900) - Line based ATR Engine based on OCRopy. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Calamari-OCR/calamari) (👨‍💻 19 · 🔀 190 · 📋 230 - 16% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/Calamari-OCR/calamari
	```
- [PyPi](https://pypi.org/project/calamari_ocr) (📥 650 / month · 📦 2 · ⏱️ 13.11.2018):
	```
	pip install calamari_ocr
	```
</details>
<details><summary><b><a href="https://github.com/faustomorales/keras-ocr">keras-ocr</a></b> (🥉21 ·  ⭐ 970) - A packaged and flexible version of the CRAFT text detector and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/faustomorales/keras-ocr) (👨‍💻 12 · 🔀 240 · 📥 220K · 📋 160 - 33% open · ⏱️ 24.11.2021):

	```
	git clone https://github.com/faustomorales/keras-ocr
	```
- [PyPi](https://pypi.org/project/keras-ocr) (📥 6K / month · 📦 2 · ⏱️ 24.11.2021):
	```
	pip install keras-ocr
	```
- [Conda](https://anaconda.org/anaconda/keras-ocr) (📥 19 · ⏱️ 14.01.2022):
	```
	conda install -c anaconda keras-ocr
	```
</details>
<details><summary><b><a href="https://github.com/emedvedev/attention-ocr">attention-ocr</a></b> (🥉21 ·  ⭐ 890) - A Tensorflow model for text recognition (CNN + seq2seq with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/emedvedev/attention-ocr) (👨‍💻 27 · 🔀 240 · 📦 18 · 📋 150 - 15% open · ⏱️ 29.10.2021):

	```
	git clone https://github.com/emedvedev/attention-ocr
	```
- [PyPi](https://pypi.org/project/aocr) (📥 250 / month · ⏱️ 19.04.2019):
	```
	pip install aocr
	```
</details>
<details><summary><b><a href="https://github.com/aashrafh/Mozart">Mozart</a></b> (🥉10 ·  ⭐ 350 · 💤) - An optical music recognition (OMR) system. Converts sheet.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/aashrafh/Mozart) (👨‍💻 5 · 🔀 52 · 📋 10 - 30% open · ⏱️ 05.05.2021):

	```
	git clone https://github.com/aashrafh/Mozart
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/WZBSocialScienceCenter/pdftabextract">pdftabextract</a></b> (🥉19 ·  ⭐ 2K · 💀) - A set of tools for extracting tables from PDF files.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/jlsutherland/doc2text">doc2text</a></b> (🥉19 ·  ⭐ 1.2K · 💀) - Detect text blocks and OCR poorly scanned PDFs in bulk. Python.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Data Containers & Structures

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_General-purpose data containers & structures as well as utilities & extensions for pandas._

<details><summary><b><a href="https://github.com/pandas-dev/pandas">pandas</a></b> (🥇52 ·  ⭐ 33K) - Flexible and powerful data analysis / manipulation library for.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pandas-dev/pandas) (👨‍💻 2.9K · 🔀 14K · 📥 140K · 📦 630K · 📋 22K - 15% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/pandas-dev/pandas
	```
- [PyPi](https://pypi.org/project/pandas) (📥 76M / month · 📦 57K · ⏱️ 22.01.2022):
	```
	pip install pandas
	```
- [Conda](https://anaconda.org/conda-forge/pandas) (📥 23M · ⏱️ 22.01.2022):
	```
	conda install -c conda-forge pandas
	```
</details>
<details><summary><b><a href="https://github.com/numpy/numpy">numpy</a></b> (🥇50 ·  ⭐ 20K) - The fundamental package for scientific computing with Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/numpy/numpy) (👨‍💻 1.4K · 🔀 6.5K · 📥 460K · 📦 960K · 📋 11K - 22% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/numpy/numpy
	```
- [PyPi](https://pypi.org/project/numpy) (📥 96M / month · 📦 120K · ⏱️ 04.02.2022):
	```
	pip install numpy
	```
- [Conda](https://anaconda.org/conda-forge/numpy) (📥 28M · ⏱️ 04.02.2022):
	```
	conda install -c conda-forge numpy
	```
</details>
<details><summary><b><a href="https://github.com/apache/arrow">Arrow</a></b> (🥇43 ·  ⭐ 9.1K) - Apache Arrow is a multi-language toolbox for accelerated data.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/arrow) (👨‍💻 800 · 🔀 2.2K · 📦 64 · 📋 900 - 22% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/apache/arrow
	```
- [PyPi](https://pypi.org/project/pyarrow) (📥 51M / month · 📦 1.4K · ⏱️ 03.02.2022):
	```
	pip install pyarrow
	```
- [Conda](https://anaconda.org/conda-forge/arrow) (📥 870K · ⏱️ 27.01.2022):
	```
	conda install -c conda-forge arrow
	```
</details>
<details><summary><b><a href="https://github.com/h5py/h5py">h5py</a></b> (🥇40 ·  ⭐ 1.7K) - HDF5 for Python -- The h5py package is a Pythonic interface to the HDF5.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/h5py/h5py) (👨‍💻 180 · 🔀 430 · 📥 1.7K · 📦 150K · 📋 1.3K - 17% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/h5py/h5py
	```
- [PyPi](https://pypi.org/project/h5py) (📥 12M / month · 📦 14K · ⏱️ 16.11.2021):
	```
	pip install h5py
	```
- [Conda](https://anaconda.org/conda-forge/h5py) (📥 7M · ⏱️ 26.11.2021):
	```
	conda install -c conda-forge h5py
	```
</details>
<details><summary><b><a href="https://github.com/pydata/xarray">xarray</a></b> (🥈38 ·  ⭐ 2.4K) - N-D labeled arrays and datasets in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pydata/xarray) (👨‍💻 360 · 🔀 760 · 📦 9K · 📋 3.2K - 29% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/pydata/xarray
	```
- [PyPi](https://pypi.org/project/xarray) (📥 1M / month · 📦 1.3K · ⏱️ 01.02.2022):
	```
	pip install xarray
	```
- [Conda](https://anaconda.org/conda-forge/xarray) (📥 4.6M · ⏱️ 01.02.2022):
	```
	conda install -c conda-forge xarray
	```
</details>
<details><summary><b><a href="https://github.com/PyTables/PyTables">PyTables</a></b> (🥈35 ·  ⭐ 1.1K) - A Python package to manage extremely large amounts of data. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/PyTables/PyTables) (👨‍💻 100 · 🔀 220 · 📥 160 · 📋 680 - 26% open · ⏱️ 28.01.2022):

	```
	git clone https://github.com/PyTables/PyTables
	```
- [PyPi](https://pypi.org/project/tables) (📥 800K / month · 📦 2.3K · ⏱️ 28.12.2021):
	```
	pip install tables
	```
- [Conda](https://anaconda.org/conda-forge/pytables) (📥 3.8M · ⏱️ 25.01.2022):
	```
	conda install -c conda-forge pytables
	```
</details>
<details><summary><b><a href="https://github.com/modin-project/modin">Modin</a></b> (🥈34 ·  ⭐ 6.8K) - Modin: Speed up your Pandas workflows by changing a single line of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/modin-project/modin) (👨‍💻 88 · 🔀 480 · 📥 200K · 📦 560 · 📋 2.5K - 33% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/modin-project/modin
	```
- [PyPi](https://pypi.org/project/modin) (📥 190K / month · 📦 21 · ⏱️ 04.02.2022):
	```
	pip install modin
	```
- [Conda](https://anaconda.org/conda-forge/modin-core) (📥 17K · ⏱️ 06.02.2022):
	```
	conda install -c conda-forge modin-core
	```
</details>
<details><summary><b><a href="https://github.com/pydata/numexpr">numexpr</a></b> (🥈33 ·  ⭐ 1.7K) - Fast numerical array expression evaluator for Python, NumPy, PyTables,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pydata/numexpr) (👨‍💻 59 · 🔀 170 · 📋 320 - 18% open · ⏱️ 06.02.2022):

	```
	git clone https://github.com/pydata/numexpr
	```
- [PyPi](https://pypi.org/project/numexpr) (📥 2.1M / month · 📦 3K · ⏱️ 15.12.2021):
	```
	pip install numexpr
	```
- [Conda](https://anaconda.org/conda-forge/numexpr) (📥 3.6M · ⏱️ 26.01.2022):
	```
	conda install -c conda-forge numexpr
	```
</details>
<details><summary><b><a href="https://github.com/zarr-developers/zarr-python">zarr</a></b> (🥈32 ·  ⭐ 840) - An implementation of chunked, compressed, N-dimensional arrays for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/zarr-developers/zarr-python) (👨‍💻 55 · 🔀 140 · 📦 1K · 📋 490 - 42% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/zarr-developers/zarr-python
	```
- [PyPi](https://pypi.org/project/zarr) (📥 83K / month · 📦 190 · ⏱️ 07.02.2022):
	```
	pip install zarr
	```
- [Conda](https://anaconda.org/conda-forge/zarr) (📥 1.2M · ⏱️ 07.02.2022):
	```
	conda install -c conda-forge zarr
	```
</details>
<details><summary><b><a href="https://github.com/msiemens/tinydb">TinyDB</a></b> (🥈31 ·  ⭐ 4.8K) - TinyDB is a lightweight document oriented database optimized for your.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/msiemens/tinydb) (👨‍💻 73 · 🔀 420 · 📋 280 - 2% open · ⏱️ 18.01.2022):

	```
	git clone https://github.com/msiemens/tinydb
	```
- [PyPi](https://pypi.org/project/tinydb) (📥 320K / month · 📦 790 · ⏱️ 18.01.2022):
	```
	pip install tinydb
	```
- [Conda](https://anaconda.org/conda-forge/tinydb) (📥 160K · ⏱️ 18.01.2022):
	```
	conda install -c conda-forge tinydb
	```
</details>
<details><summary><b><a href="https://github.com/pola-rs/polars">polars</a></b> (🥈31 ·  ⭐ 4.5K) - Fast multi-threaded DataFrame library in Rust | Python | Node.js. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pola-rs/polars) (👨‍💻 69 · 🔀 250 · 📦 2 · 📋 960 - 8% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/pola-rs/polars
	```
- [PyPi](https://pypi.org/project/polars) (📥 33K / month · 📦 11 · ⏱️ 09.02.2022):
	```
	pip install polars
	```
</details>
<details><summary><b><a href="https://github.com/databricks/koalas">Koalas</a></b> (🥈31 ·  ⭐ 3.1K) - Koalas: pandas API on Apache Spark. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/databricks/koalas) (👨‍💻 51 · 🔀 320 · 📥 1K · 📦 170 · 📋 580 - 16% open · ⏱️ 21.10.2021):

	```
	git clone https://github.com/databricks/koalas
	```
- [PyPi](https://pypi.org/project/koalas) (📥 2.2M / month · 📦 7 · ⏱️ 19.10.2021):
	```
	pip install koalas
	```
- [Conda](https://anaconda.org/conda-forge/koalas) (📥 110K · ⏱️ 20.10.2021):
	```
	conda install -c conda-forge koalas
	```
</details>
<details><summary><b><a href="https://github.com/vaexio/vaex">Vaex</a></b> (🥉30 ·  ⭐ 6.9K) - Out-of-Core hybrid Apache Arrow/NumPy DataFrame for Python, ML, visualization.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/vaexio/vaex) (👨‍💻 63 · 🔀 530 · 📥 230 · 📋 1K - 36% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/vaexio/vaex
	```
- [PyPi](https://pypi.org/project/vaex) (📥 26K / month · 📦 16 · ⏱️ 07.02.2022):
	```
	pip install vaex
	```
- [Conda](https://anaconda.org/conda-forge/vaex) (📥 120K · ⏱️ 30.12.2021):
	```
	conda install -c conda-forge vaex
	```
</details>
<details><summary><b><a href="https://github.com/man-group/arctic">Arctic</a></b> (🥉30 ·  ⭐ 2.6K) - Arctic is a high performance datastore for numeric data. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code></summary>

- [GitHub](https://github.com/man-group/arctic) (👨‍💻 75 · 🔀 520 · 📥 180 · 📦 150 · 📋 540 - 17% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/man-group/arctic
	```
- [PyPi](https://pypi.org/project/arctic) (📥 9.2K / month · 📦 34 · ⏱️ 24.01.2022):
	```
	pip install arctic
	```
- [Conda](https://anaconda.org/conda-forge/arctic) (📥 17K · ⏱️ 16.12.2019):
	```
	conda install -c conda-forge arctic
	```
</details>
<details><summary><b><a href="https://github.com/ekzhu/datasketch">datasketch</a></b> (🥉30 ·  ⭐ 1.7K) - MinHash, LSH, LSH Forest, Weighted MinHash, HyperLogLog,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ekzhu/datasketch) (👨‍💻 21 · 🔀 230 · 📥 19 · 📦 350 · 📋 130 - 22% open · ⏱️ 04.02.2022):

	```
	git clone https://github.com/ekzhu/datasketch
	```
- [PyPi](https://pypi.org/project/datasketch) (📥 420K / month · 📦 54 · ⏱️ 04.02.2022):
	```
	pip install datasketch
	```
</details>
<details><summary><b><a href="https://github.com/pydata/bottleneck">Bottleneck</a></b> (🥉30 ·  ⭐ 700) - Fast NumPy array functions written in C. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/pydata/bottleneck) (👨‍💻 22 · 🔀 74 · 📦 30K · 📋 220 - 17% open · ⏱️ 07.02.2022):

	```
	git clone https://github.com/pydata/bottleneck
	```
- [PyPi](https://pypi.org/project/Bottleneck) (📥 410K / month · 📦 1.6K · ⏱️ 21.02.2020):
	```
	pip install Bottleneck
	```
- [Conda](https://anaconda.org/conda-forge/bottleneck) (📥 1.9M · ⏱️ 04.11.2021):
	```
	conda install -c conda-forge bottleneck
	```
</details>
<details><summary><b><a href="https://github.com/h2oai/datatable">datatable</a></b> (🥉29 ·  ⭐ 1.4K) - A Python package for manipulating 2-dimensional tabular data.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/h2oai/datatable) (👨‍💻 33 · 🔀 130 · 📥 1.2K · 📋 1.4K - 9% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/h2oai/datatable
	```
- [PyPi](https://pypi.org/project/datatable) (📥 79K / month · 📦 12 · ⏱️ 01.07.2021):
	```
	pip install datatable
	```
- [Conda](https://anaconda.org/conda-forge/datatable) (📥 12K · ⏱️ 23.12.2020):
	```
	conda install -c conda-forge datatable
	```
</details>
<details><summary><b><a href="https://github.com/jmcarpenter2/swifter">swifter</a></b> (🥉28 ·  ⭐ 1.9K) - A package which efficiently applies any function to a pandas.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jmcarpenter2/swifter) (👨‍💻 15 · 🔀 87 · 📦 480 · 📋 110 - 21% open · ⏱️ 07.02.2022):

	```
	git clone https://github.com/jmcarpenter2/swifter
	```
- [PyPi](https://pypi.org/project/swifter) (📥 140K / month · 📦 28 · ⏱️ 07.02.2022):
	```
	pip install swifter
	```
- [Conda](https://anaconda.org/conda-forge/swifter) (📥 130K · ⏱️ 26.06.2021):
	```
	conda install -c conda-forge swifter
	```
</details>
<details><summary><b><a href="https://github.com/pandera-dev/pandera">pandera</a></b> (🥉27 ·  ⭐ 1K · ➕) - A light-weight, flexible, and expressive data validation library.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pandera-dev/pandera) (👨‍💻 48 · 🔀 82 · 📦 150 · 📋 360 - 22% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/pandera-dev/pandera
	```
- [PyPi](https://pypi.org/project/pandera) (📥 160K / month · 📦 18 · ⏱️ 09.02.2022):
	```
	pip install pandera
	```
- [Conda](https://anaconda.org/conda-forge/pandera-core) (📥 5.8K · ⏱️ 31.12.2021):
	```
	conda install -c conda-forge pandera-core
	```
</details>
<details><summary><b><a href="https://github.com/nalepae/pandarallel">Pandaral·lel</a></b> (🥉26 ·  ⭐ 2K) - A simple and efficient tool to parallelize Pandas.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/nalepae/pandarallel) (👨‍💻 19 · 🔀 130 · 📦 400 · 📋 150 - 54% open · ⏱️ 06.02.2022):

	```
	git clone https://github.com/nalepae/pandarallel
	```
- [PyPi](https://pypi.org/project/pandarallel) (📥 220K / month · 📦 19 · ⏱️ 06.02.2022):
	```
	pip install pandarallel
	```
- [Conda](https://anaconda.org/conda-forge/pandarallel) (📥 1.5K · ⏱️ 06.02.2022):
	```
	conda install -c conda-forge pandarallel
	```
</details>
<details><summary><b><a href="https://github.com/jina-ai/docarray">docarray</a></b> (🥉23 ·  ⭐ 520 · 🐣) - The data structure for unstructured data. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jina-ai/docarray) (👨‍💻 14 · 🔀 30 · 📦 7 · 📋 27 - 29% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/jina-ai/docarray
	```
- [PyPi](https://pypi.org/project/docarray) (📥 52K / month · ⏱️ 10.02.2022):
	```
	pip install docarray
	```
- [Conda](https://anaconda.org/conda-forge/docarray) (📥 41 · ⏱️ 10.01.2022):
	```
	conda install -c conda-forge docarray
	```
</details>
<details><summary><b><a href="https://github.com/polyaxon/datatile">Pandas Summary</a></b> (🥉21 ·  ⭐ 380) - A library for managing, validating, summarizing, and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/polyaxon/datatile) (👨‍💻 8 · 🔀 37 · 📋 15 - 53% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/polyaxon/datatile
	```
- [PyPi](https://pypi.org/project/pandas-summary) (📥 43K / month · 📦 57 · ⏱️ 25.11.2021):
	```
	pip install pandas-summary
	```
</details>
<details><summary><b><a href="https://github.com/RaRe-Technologies/bounter">Bounter</a></b> (🥉17 ·  ⭐ 930 · 💤) - Efficient Counter that uses a limited (bounded) amount of memory.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/RaRe-Technologies/bounter) (👨‍💻 8 · 🔀 48 · 📦 25 · 📋 24 - 62% open · ⏱️ 24.05.2021):

	```
	git clone https://github.com/RaRe-Technologies/bounter
	```
- [PyPi](https://pypi.org/project/bounter) (📥 110 / month · 📦 8 · ⏱️ 17.08.2020):
	```
	pip install bounter
	```
</details>
<details><summary><b><a href="https://github.com/firmai/pandapy">PandaPy</a></b> (🥉11 ·  ⭐ 490) - PandaPy has the speed of NumPy and the usability of Pandas 10x to 50x.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/firmai/pandapy) (👨‍💻 3 · 🔀 56 · 📦 1 · 📋 3 - 66% open · ⏱️ 20.10.2021):

	```
	git clone https://github.com/firmai/pandapy
	```
- [PyPi](https://pypi.org/project/pandapy) (📥 96 / month · ⏱️ 25.01.2020):
	```
	pip install pandapy
	```
</details>
<details><summary>Show 7 hidden projects...</summary>

- <b><a href="https://github.com/blaze/blaze">Blaze</a></b> (🥈31 ·  ⭐ 3K · 💀) - NumPy and Pandas interface to Big Data. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/scikit-learn-contrib/sklearn-pandas">sklearn-pandas</a></b> (🥉27 ·  ⭐ 2.6K · 💤) - Pandas integration with sklearn. <code><a href="https://tldrlegal.com/search?q=Zlib">❗️Zlib</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/Blosc/bcolz">bcolz</a></b> (🥉26 ·  ⭐ 940 · 💀) - A columnar data container that can be compressed. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/InvestmentSystems/static-frame">StaticFrame</a></b> (🥉26 ·  ⭐ 260) - Immutable and grow-only Pandas-like DataFrames with a more explicit.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/yhat/pandasql">pandasql</a></b> (🥉25 ·  ⭐ 1.1K · 💀) - sqldf for pandas. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/patx/pickledb">pickleDB</a></b> (🥉23 ·  ⭐ 640 · 💀) - pickleDB is an open source key-value store using Pythons json module. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/xhochy/fletcher">fletcher</a></b> (🥉19 ·  ⭐ 220 · 💤) - Pandas ExtensionDType/Array backed by Apache Arrow. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Data Loading & Extraction

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for loading, collecting, and extracting data from a variety of data sources and formats._

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-python#data-loading--extraction">best-of-python - Data Extraction</a></b> ( ⭐ 2K)  - Collection of data-loading and -extraction libraries.

<br>

## Web Scraping & Crawling

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for web scraping, crawling, downloading, and mining as well as libraries._

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-web-python#web-scraping--crawling">best-of-web-python - Web Scraping</a></b> ( ⭐ 1.4K)  - Collection of web-scraping and crawling libraries.

<br>

## Data Pipelines & Streaming

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for data batch- and stream-processing, workflow automation, job scheduling, and other data pipeline tasks._

<details><summary><b><a href="https://github.com/celery/celery">Celery</a></b> (🥇46 ·  ⭐ 19K) - Asynchronous task queue/job queue based on distributed message passing. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/celery/celery) (👨‍💻 1.2K · 🔀 4.2K · 📦 64K · 📋 4.7K - 11% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/celery/celery
	```
- [PyPi](https://pypi.org/project/celery) (📥 5.2M / month · 📦 15K · ⏱️ 29.12.2021):
	```
	pip install celery
	```
- [Conda](https://anaconda.org/conda-forge/celery) (📥 780K · ⏱️ 07.02.2022):
	```
	conda install -c conda-forge celery
	```
</details>
<details><summary><b><a href="https://github.com/apache/airflow">Airflow</a></b> (🥇44 ·  ⭐ 25K) - Platform to programmatically author, schedule, and monitor workflows. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/airflow) (👨‍💻 2.3K · 🔀 10K · 📥 250K · 📋 5.1K - 18% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/apache/airflow
	```
- [PyPi](https://pypi.org/project/apache-airflow) (📥 4.2M / month · 📦 440 · ⏱️ 21.12.2021):
	```
	pip install apache-airflow
	```
- [Conda](https://anaconda.org/conda-forge/airflow) (📥 540K · ⏱️ 22.12.2021):
	```
	conda install -c conda-forge airflow
	```
- [Docker Hub](https://hub.docker.com/r/apache/airflow) (📥 63M · ⭐ 320 · ⏱️ 25.01.2022):
	```
	docker pull apache/airflow
	```
</details>
<details><summary><b><a href="https://github.com/apache/beam">Beam</a></b> (🥇39 ·  ⭐ 5.3K) - Unified programming model to define and execute data processing.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/beam) (👨‍💻 1.2K · 🔀 3.4K · ⏱️ 10.02.2022):

	```
	git clone https://github.com/apache/beam
	```
- [PyPi](https://pypi.org/project/apache-beam) (📥 15M / month · 📦 150 · ⏱️ 07.02.2022):
	```
	pip install apache-beam
	```
- [Conda](https://anaconda.org/conda-forge/apache-beam-with-aws) (📥 3.9K · ⏱️ 08.02.2022):
	```
	conda install -c conda-forge apache-beam-with-aws
	```
</details>
<details><summary><b><a href="https://github.com/joblib/joblib">joblib</a></b> (🥇39 ·  ⭐ 2.7K) - Computing with Python functions. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/joblib/joblib) (👨‍💻 110 · 🔀 320 · 📦 160K · 📋 720 - 46% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/joblib/joblib
	```
- [PyPi](https://pypi.org/project/joblib) (📥 27M / month · 📦 4.9K · ⏱️ 07.10.2021):
	```
	pip install joblib
	```
- [Conda](https://anaconda.org/conda-forge/joblib) (📥 7.1M · ⏱️ 07.10.2021):
	```
	conda install -c conda-forge joblib
	```
</details>
<details><summary><b><a href="https://github.com/spotify/luigi">luigi</a></b> (🥇38 ·  ⭐ 15K) - Luigi is a Python module that helps you build complex pipelines of batch.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/spotify/luigi) (👨‍💻 580 · 🔀 2.3K · 📦 1.6K · 📋 970 - 10% open · ⏱️ 16.01.2022):

	```
	git clone https://github.com/spotify/luigi
	```
- [PyPi](https://pypi.org/project/luigi) (📥 620K / month · 📦 400 · ⏱️ 23.09.2020):
	```
	pip install luigi
	```
- [Conda](https://anaconda.org/anaconda/luigi) (📥 8.9K · 📦 2 · ⏱️ 20.01.2022):
	```
	conda install -c anaconda luigi
	```
</details>
<details><summary><b><a href="https://github.com/rq/rq">rq</a></b> (🥇38 ·  ⭐ 8.1K) - Simple job queues for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/rq/rq) (👨‍💻 250 · 🔀 1.3K · 📦 9.6K · 📋 940 - 17% open · ⏱️ 07.02.2022):

	```
	git clone https://github.com/rq/rq
	```
- [PyPi](https://pypi.org/project/rq) (📥 540K / month · 📦 1.7K · ⏱️ 07.12.2021):
	```
	pip install rq
	```
- [Conda](https://anaconda.org/conda-forge/rq) (📥 68K · ⏱️ 30.06.2021):
	```
	conda install -c conda-forge rq
	```
</details>
<details><summary><b><a href="https://github.com/PrefectHQ/prefect">Prefect</a></b> (🥈37 ·  ⭐ 8.3K) - The easiest way to automate your data. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PrefectHQ/prefect) (👨‍💻 290 · 🔀 800 · 📦 590 · 📋 2.1K - 20% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/PrefectHQ/prefect
	```
- [PyPi](https://pypi.org/project/prefect) (📥 170K / month · 📦 40 · ⏱️ 09.02.2022):
	```
	pip install prefect
	```
- [Conda](https://anaconda.org/conda-forge/prefect) (📥 240K · ⏱️ 25.01.2022):
	```
	conda install -c conda-forge prefect
	```
</details>
<details><summary><b><a href="https://github.com/dagster-io/dagster">Dagster</a></b> (🥈37 ·  ⭐ 4.3K) - An orchestration platform for the development, production, and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dagster-io/dagster) (👨‍💻 190 · 🔀 530 · 📦 300 · 📋 3.7K - 24% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/dagster-io/dagster
	```
- [PyPi](https://pypi.org/project/dagster) (📥 180K / month · 📦 84 · ⏱️ 03.02.2022):
	```
	pip install dagster
	```
- [Conda](https://anaconda.org/conda-forge/dagster) (📥 450K · ⏱️ 04.02.2022):
	```
	conda install -c conda-forge dagster
	```
</details>
<details><summary><b><a href="https://github.com/dbt-labs/dbt-core">dbt</a></b> (🥈36 ·  ⭐ 4.2K) - dbt enables data analysts and engineers to transform their data using the.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dbt-labs/dbt-core) (👨‍💻 200 · 🔀 760 · 📥 160 · 📦 300 · 📋 2.5K - 11% open · ⏱️ 07.02.2022):

	```
	git clone https://github.com/dbt-labs/dbt-core
	```
- [PyPi](https://pypi.org/project/dbt) (📥 680K / month · 📦 29 · ⏱️ 06.12.2021):
	```
	pip install dbt
	```
- [Conda](https://anaconda.org/conda-forge/dbt) (📥 190K · ⏱️ 09.12.2021):
	```
	conda install -c conda-forge dbt
	```
</details>
<details><summary><b><a href="https://github.com/great-expectations/great_expectations">Great Expectations</a></b> (🥈35 ·  ⭐ 6.1K) - Always know what to expect from your data. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/great-expectations/great_expectations) (👨‍💻 260 · 🔀 830 · 📋 1.2K - 15% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/great-expectations/great_expectations
	```
- [PyPi](https://pypi.org/project/great_expectations) (📥 2.9M / month · 📦 27 · ⏱️ 03.02.2022):
	```
	pip install great_expectations
	```
- [Conda](https://anaconda.org/conda-forge/great-expectations) (📥 350K · ⏱️ 04.02.2022):
	```
	conda install -c conda-forge great-expectations
	```
</details>
<details><summary><b><a href="https://github.com/kedro-org/kedro">Kedro</a></b> (🥈33 ·  ⭐ 6.5K) - A Python framework for creating reproducible, maintainable and modular.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/kedro-org/kedro) (👨‍💻 140 · 🔀 600 · 📦 730 · 📋 600 - 6% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/kedro-org/kedro
	```
- [PyPi](https://pypi.org/project/kedro) (📥 300K / month · 📦 35 · ⏱️ 09.12.2021):
	```
	pip install kedro
	```
</details>
<details><summary><b><a href="https://github.com/combust/mleap">mleap</a></b> (🥈31 ·  ⭐ 1.4K) - MLeap: Deploy ML Pipelines to Production. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/combust/mleap) (👨‍💻 71 · 🔀 290 · 📦 180 · 📋 440 - 20% open · ⏱️ 27.01.2022):

	```
	git clone https://github.com/combust/mleap
	```
- [PyPi](https://pypi.org/project/mleap) (📥 200K / month · 📦 25 · ⏱️ 12.01.2022):
	```
	pip install mleap
	```
- [Conda](https://anaconda.org/conda-forge/mleap) (📥 43K · ⏱️ 12.01.2022):
	```
	conda install -c conda-forge mleap
	```
</details>
<details><summary><b><a href="https://github.com/petl-developers/petl">petl</a></b> (🥈31 ·  ⭐ 970) - Python Extract Transform and Load Tables of Data. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/petl-developers/petl) (👨‍💻 54 · 🔀 170 · 📦 620 · 📋 440 - 16% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/petl-developers/petl
	```
- [PyPi](https://pypi.org/project/petl) (📥 56K / month · 📦 74 · ⏱️ 08.02.2022):
	```
	pip install petl
	```
- [Conda](https://anaconda.org/conda-forge/petl) (📥 70K · ⏱️ 05.02.2022):
	```
	conda install -c conda-forge petl
	```
</details>
<details><summary><b><a href="https://github.com/activeloopai/Hub">Activeloop</a></b> (🥈30 ·  ⭐ 4.3K) - Dataset format for AI. Build, manage, & visualize datasets for.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/activeloopai/Hub) (👨‍💻 91 · 🔀 350 · 📋 340 - 19% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/activeloopai/Hub
	```
- [PyPi](https://pypi.org/project/hub) (📥 3.2K / month · 📦 52 · ⏱️ 01.02.2022):
	```
	pip install hub
	```
</details>
<details><summary><b><a href="https://github.com/coleifer/huey">huey</a></b> (🥈30 ·  ⭐ 3.8K) - a little task queue for python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/coleifer/huey) (👨‍💻 66 · 🔀 330 · 📦 860 · ⏱️ 10.01.2022):

	```
	git clone https://github.com/coleifer/huey
	```
- [PyPi](https://pypi.org/project/huey) (📥 59K / month · 📦 160 · ⏱️ 28.12.2021):
	```
	pip install huey
	```
- [Conda](https://anaconda.org/conda-forge/huey) (📥 23K · ⏱️ 16.10.2019):
	```
	conda install -c conda-forge huey
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/tfx">TFX</a></b> (🥈30 ·  ⭐ 1.7K) - TFX is an end-to-end platform for deploying production ML pipelines. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tfx) (👨‍💻 130 · 🔀 520 · 📋 740 - 33% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/tensorflow/tfx
	```
- [PyPi](https://pypi.org/project/tfx) (📥 310K / month · 📦 7 · ⏱️ 08.02.2022):
	```
	pip install tfx
	```
</details>
<details><summary><b><a href="https://github.com/ploomber/ploomber">ploomber</a></b> (🥉29 ·  ⭐ 1.2K) - The fastest way to build data pipelines. Develop iteratively,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ploomber/ploomber) (👨‍💻 34 · 🔀 92 · 📦 28 · 📋 510 - 26% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/ploomber/ploomber
	```
- [PyPi](https://pypi.org/project/ploomber) (📥 7.7K / month · 📦 4 · ⏱️ 09.02.2022):
	```
	pip install ploomber
	```
- [Conda](https://anaconda.org/conda-forge/ploomber) (📥 3.9K · ⏱️ 03.02.2022):
	```
	conda install -c conda-forge ploomber
	```
</details>
<details><summary><b><a href="https://github.com/Parsely/streamparse">streamparse</a></b> (🥉28 ·  ⭐ 1.5K) - Run Python in Apache Storm topologies. Pythonic API, CLI.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Parsely/streamparse) (👨‍💻 42 · 🔀 220 · 📦 53 · 📋 330 - 21% open · ⏱️ 10.01.2022):

	```
	git clone https://github.com/Parsely/streamparse
	```
- [PyPi](https://pypi.org/project/streamparse) (📥 2.4K / month · 📦 27 · ⏱️ 10.01.2022):
	```
	pip install streamparse
	```
</details>
<details><summary><b><a href="https://github.com/zenml-io/zenml">zenml</a></b> (🥉27 ·  ⭐ 1.6K) - ZenML : MLOps framework to create reproducible pipelines. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/zenml-io/zenml) (👨‍💻 24 · 🔀 100 · 📋 58 - 17% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/zenml-io/zenml
	```
- [PyPi](https://pypi.org/project/zenml) (📥 1.3K / month · ⏱️ 07.02.2022):
	```
	pip install zenml
	```
</details>
<details><summary><b><a href="https://github.com/hi-primus/optimus">Optimus</a></b> (🥉27 ·  ⭐ 1.2K) - Agile Data Preparation Workflows madeeasy with Pandas, Dask,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/hi-primus/optimus) (👨‍💻 25 · 🔀 200 · 📋 230 - 14% open · ⏱️ 07.02.2022):

	```
	git clone https://github.com/hi-primus/optimus
	```
- [PyPi](https://pypi.org/project/optimuspyspark) (📥 21K / month · ⏱️ 30.05.2019):
	```
	pip install optimuspyspark
	```
</details>
<details><summary><b><a href="https://github.com/EntilZha/PyFunctional">PyFunctional</a></b> (🥉26 ·  ⭐ 2K) - Python library for creating data pipelines with chain functional.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/EntilZha/PyFunctional) (👨‍💻 25 · 🔀 110 · 📦 390 · 📋 130 - 5% open · ⏱️ 05.11.2021):

	```
	git clone https://github.com/EntilZha/PyFunctional
	```
- [PyPi](https://pypi.org/project/pyfunctional) (📥 86K / month · 📦 12 · ⏱️ 12.01.2021):
	```
	pip install pyfunctional
	```
</details>
<details><summary><b><a href="https://github.com/python-bonobo/bonobo">bonobo</a></b> (🥉25 ·  ⭐ 1.5K · 💤) - Extract Transform Load for Python 3.5+. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/python-bonobo/bonobo) (👨‍💻 37 · 🔀 120 · 📦 130 · 📋 200 - 46% open · ⏱️ 10.03.2021):

	```
	git clone https://github.com/python-bonobo/bonobo
	```
- [PyPi](https://pypi.org/project/bonobo) (📥 8.6K / month · 📦 33 · ⏱️ 20.07.2019):
	```
	pip install bonobo
	```
</details>
<details><summary><b><a href="https://github.com/samuelcolvin/arq">arq</a></b> (🥉25 ·  ⭐ 1.1K) - Fast job queuing and RPC in python with asyncio and redis. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/samuelcolvin/arq) (👨‍💻 35 · 🔀 86 · 📦 180 · 📋 130 - 26% open · ⏱️ 26.01.2022):

	```
	git clone https://github.com/samuelcolvin/arq
	```
- [PyPi](https://pypi.org/project/arq) (📥 18K / month · 📦 10 · ⏱️ 02.09.2021):
	```
	pip install arq
	```
- [Conda](https://anaconda.org/conda-forge/arq) (📥 1.7K · ⏱️ 03.09.2021):
	```
	conda install -c conda-forge arq
	```
</details>
<details><summary><b><a href="https://github.com/cgarciae/pypeln">Pypeline</a></b> (🥉23 ·  ⭐ 1.3K) - Concurrent data pipelines in Python . <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cgarciae/pypeln) (👨‍💻 12 · 🔀 77 · 📋 57 - 26% open · ⏱️ 06.01.2022):

	```
	git clone https://github.com/cgarciae/pypeln
	```
- [PyPi](https://pypi.org/project/pypeln) (📥 10K / month · 📦 9 · ⏱️ 06.01.2022):
	```
	pip install pypeln
	```
- [Conda](https://anaconda.org/conda-forge/pypeln) (📥 4.6K · ⏱️ 06.01.2022):
	```
	conda install -c conda-forge pypeln
	```
</details>
<details><summary><b><a href="https://github.com/closeio/tasktiger">TaskTiger</a></b> (🥉23 ·  ⭐ 1.1K) - Python task queue using Redis. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/closeio/tasktiger) (👨‍💻 25 · 🔀 62 · 📦 22 · 📋 68 - 48% open · ⏱️ 07.02.2022):

	```
	git clone https://github.com/closeio/tasktiger
	```
- [PyPi](https://pypi.org/project/tasktiger) (📥 2.2K / month · 📦 10 · ⏱️ 02.12.2021):
	```
	pip install tasktiger
	```
</details>
<details><summary><b><a href="https://github.com/whylabs/whylogs">whylogs</a></b> (🥉23 ·  ⭐ 750) - Open standard for end-to-end data and ML monitoring for any scale in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/whylabs/whylogs) (👨‍💻 26 · 🔀 39 · 📥 49 · 📋 110 - 43% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/whylabs/whylogs
	```
- [PyPi](https://pypi.org/project/whylogs) (📥 8K / month · 📦 2 · ⏱️ 08.02.2022):
	```
	pip install whylogs
	```
</details>
<details><summary><b><a href="https://github.com/pdpipe/pdpipe">pdpipe</a></b> (🥉23 ·  ⭐ 650) - Easy pipelines for pandas DataFrames. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pdpipe/pdpipe) (👨‍💻 9 · 🔀 32 · 📦 40 · 📋 41 - 34% open · ⏱️ 30.01.2022):

	```
	git clone https://github.com/pdpipe/pdpipe
	```
- [PyPi](https://pypi.org/project/pdpipe) (📥 2.9K / month · 📦 5 · ⏱️ 30.01.2022):
	```
	pip install pdpipe
	```
- [Conda](https://anaconda.org/conda-forge/pdpipe) (📥 3K · ⏱️ 26.12.2021):
	```
	conda install -c conda-forge pdpipe
	```
</details>
<details><summary><b><a href="https://github.com/nerevu/riko">riko</a></b> (🥉20 ·  ⭐ 1.6K) - A Python stream processing engine modeled after Yahoo! Pipes. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nerevu/riko) (👨‍💻 18 · 🔀 75 · 📋 30 - 73% open · ⏱️ 28.12.2021):

	```
	git clone https://github.com/nerevu/riko
	```
- [PyPi](https://pypi.org/project/riko) (📥 290 / month · 📦 1 · ⏱️ 28.12.2021):
	```
	pip install riko
	```
</details>
<details><summary><b><a href="https://github.com/databricks/spark-deep-learning">spark-deep-learning</a></b> (🥉19 ·  ⭐ 1.9K) - Deep Learning Pipelines for Apache Spark. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/databricks/spark-deep-learning) (👨‍💻 16 · 🔀 460 · 📦 19 · 📋 100 - 73% open · ⏱️ 19.08.2021):

	```
	git clone https://github.com/databricks/spark-deep-learning
	```
</details>
<details><summary><b><a href="https://github.com/d6t/d6tflow">Databolt Flow</a></b> (🥉19 ·  ⭐ 940) - Python library for building highly effective data science workflows. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/d6t/d6tflow) (👨‍💻 12 · 🔀 69 · 📦 19 · 📋 23 - 43% open · ⏱️ 28.09.2021):

	```
	git clone https://github.com/d6t/d6tflow
	```
- [PyPi](https://pypi.org/project/d6tflow) (📥 210 / month · ⏱️ 06.10.2021):
	```
	pip install d6tflow
	```
</details>
<details><summary><b><a href="https://github.com/kubeflow-kale/kale">kale</a></b> (🥉18 ·  ⭐ 480) - Kubeflows superfood for Data Scientists. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/kubeflow-kale/kale) (👨‍💻 10 · 🔀 94 · 📋 160 - 53% open · ⏱️ 20.10.2021):

	```
	git clone https://github.com/kubeflow-kale/kale
	```
- [PyPi](https://pypi.org/project/kubeflow-kale) (📥 1.1K / month · ⏱️ 19.05.2021):
	```
	pip install kubeflow-kale
	```
</details>
<details><summary><b><a href="https://github.com/mara/mara-pipelines">Mara Pipelines</a></b> (🥉17 ·  ⭐ 1.9K) - A lightweight opinionated ETL framework, halfway between plain.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mara/mara-pipelines) (👨‍💻 16 · 🔀 86 · 📦 8 · 📋 24 - 45% open · ⏱️ 18.09.2021):

	```
	git clone https://github.com/mara/mara-pipelines
	```
- [PyPi](https://pypi.org/project/mara-pipelines) (📥 250 / month · ⏱️ 23.01.2021):
	```
	pip install mara-pipelines
	```
</details>
<details><summary>Show 11 hidden projects...</summary>

- <b><a href="https://github.com/Yelp/mrjob">mrjob</a></b> (🥈32 ·  ⭐ 2.6K · 💀) - Run MapReduce jobs on Hadoop or Amazon Web Services. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/robinhood/faust">faust</a></b> (🥈31 ·  ⭐ 6K · 💀) - Python Stream Processing. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/databand-ai/dbnd">dbnd</a></b> (🥉26 ·  ⭐ 220) - DBND is an agile pipeline framework that helps data engineering teams.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/douban/dpark">dpark</a></b> (🥉22 ·  ⭐ 2.7K · 💀) - Python clone of Spark, a MapReduce alike framework in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/svenkreiss/pysparkling">pysparkling</a></b> (🥉22 ·  ⭐ 240 · 💤) - A pure Python implementation of Apache Sparks RDD and DStream.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/pricingassistant/mrq">mrq</a></b> (🥉21 ·  ⭐ 860 · 💀) - Mr. Queue - A distributed worker task queue in Python using Redis & gevent. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/analysiscenter/batchflow">BatchFlow</a></b> (🥉20 ·  ⭐ 170) - BatchFlow helps you conveniently work with random or sequential.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/bodywork-ml/bodywork-core">bodywork-core</a></b> (🥉17 ·  ⭐ 320) - ML pipeline orchestration and model deployments on.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/olirice/flupy">flupy</a></b> (🥉17 ·  ⭐ 170) - Fluent data pipelines for python and your shell. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/kkyon/botflow">Botflow</a></b> (🥉15 ·  ⭐ 1.2K · 💀) - Python Fast Dataflow programming framework for Data pipeline work(.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/vincentclaes/datajob">datajob</a></b> (🥉14 ·  ⭐ 83 · ➕) - Build and deploy a serverless data pipeline on AWS with no effort. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Distributed Machine Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that provide capabilities to distribute and parallelize machine learning tasks across large-scale compute infrastructure._

<details><summary><b><a href="https://github.com/ray-project/ray">Ray</a></b> (🥇43 ·  ⭐ 19K) - An open source framework that provides a simple, universal API for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ray-project/ray) (👨‍💻 630 · 🔀 3.2K · 📦 3.9K · 📋 9.5K - 24% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/ray-project/ray
	```
- [PyPi](https://pypi.org/project/ray) (📥 850K / month · 📦 230 · ⏱️ 04.02.2022):
	```
	pip install ray
	```
- [Conda](https://anaconda.org/conda-forge/ray-tune) (📥 22K · ⏱️ 07.02.2022):
	```
	conda install -c conda-forge ray-tune
	```
</details>
<details><summary><b><a href="https://github.com/dask/dask">dask</a></b> (🥇43 ·  ⭐ 9.5K) - Parallel computing with task scheduling. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dask/dask) (👨‍💻 510 · 🔀 1.4K · 📦 34K · 📋 4.2K - 18% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/dask/dask
	```
- [PyPi](https://pypi.org/project/dask) (📥 7.6M / month · 📦 2.6K · ⏱️ 28.01.2022):
	```
	pip install dask
	```
- [Conda](https://anaconda.org/conda-forge/dask) (📥 5M · ⏱️ 29.01.2022):
	```
	conda install -c conda-forge dask
	```
</details>
<details><summary><b><a href="https://github.com/dask/distributed">dask.distributed</a></b> (🥇40 ·  ⭐ 1.3K) - A distributed task scheduler for Dask. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dask/distributed) (👨‍💻 260 · 🔀 590 · 📦 22K · 📋 2.6K - 35% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/dask/distributed
	```
- [PyPi](https://pypi.org/project/distributed) (📥 6.6M / month · 📦 1.2K · ⏱️ 28.01.2022):
	```
	pip install distributed
	```
- [Conda](https://anaconda.org/conda-forge/distributed) (📥 6.2M · ⏱️ 29.01.2022):
	```
	conda install -c conda-forge distributed
	```
</details>
<details><summary><b><a href="https://github.com/horovod/horovod">horovod</a></b> (🥇36 ·  ⭐ 12K) - Distributed training framework for TensorFlow, Keras, PyTorch, and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/horovod/horovod) (👨‍💻 140 · 🔀 2K · 📦 500 · 📋 1.9K - 14% open · ⏱️ 04.02.2022):

	```
	git clone https://github.com/horovod/horovod
	```
- [PyPi](https://pypi.org/project/horovod) (📥 48K / month · 📦 29 · ⏱️ 06.10.2021):
	```
	pip install horovod
	```
</details>
<details><summary><b><a href="https://github.com/ipython/ipyparallel">ipyparallel</a></b> (🥈34 ·  ⭐ 2.2K) - IPython Parallel: Interactive Parallel Computing in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ipython/ipyparallel) (👨‍💻 100 · 🔀 860 · 📦 1.8K · 📋 320 - 15% open · ⏱️ 07.02.2022):

	```
	git clone https://github.com/ipython/ipyparallel
	```
- [PyPi](https://pypi.org/project/ipyparallel) (📥 54K / month · 📦 280 · ⏱️ 07.02.2022):
	```
	pip install ipyparallel
	```
- [Conda](https://anaconda.org/conda-forge/ipyparallel) (📥 560K · ⏱️ 07.02.2022):
	```
	conda install -c conda-forge ipyparallel
	```
</details>
<details><summary><b><a href="https://github.com/intel-analytics/BigDL">BigDL</a></b> (🥈32 ·  ⭐ 3.8K) - Building Large-Scale AI Applications for Distributed Big Data. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/intel-analytics/BigDL) (👨‍💻 130 · 🔀 970 · 📦 33 · 📋 1.2K - 31% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/intel-analytics/BigDL
	```
- [PyPi](https://pypi.org/project/bigdl) (📥 14K / month · 📦 1 · ⏱️ 10.02.2022):
	```
	pip install bigdl
	```
- [Maven](https://search.maven.org/artifact/com.intel.analytics.bigdl/bigdl-SPARK_2.4) (📦 4 · ⏱️ 20.04.2021):
	```
	<dependency>
		<groupId>com.intel.analytics.bigdl</groupId>
		<artifactId>bigdl-SPARK_2.4</artifactId>
		<version>[VERSION]</version>
	</dependency>
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/DeepSpeed">DeepSpeed</a></b> (🥈31 ·  ⭐ 6.3K) - DeepSpeed is a deep learning optimization library that makes.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/microsoft/DeepSpeed) (👨‍💻 89 · 🔀 680 · 📦 160 · 📋 770 - 48% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/microsoft/DeepSpeed
	```
- [PyPi](https://pypi.org/project/deepspeed) (📥 72K / month · 📦 9 · ⏱️ 19.01.2022):
	```
	pip install deepspeed
	```
- [Docker Hub](https://hub.docker.com/r/deepspeed/deepspeed) (📥 13K · ⭐ 3 · ⏱️ 05.05.2021):
	```
	docker pull deepspeed/deepspeed
	```
</details>
<details><summary><b><a href="https://github.com/PyTorchLightning/metrics">metrics</a></b> (🥈31 ·  ⭐ 670) - Machine learning metrics for distributed, scalable PyTorch.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyTorchLightning/metrics) (👨‍💻 120 · 🔀 150 · 📥 430 · 📦 1.8K · 📋 300 - 21% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/PyTorchLightning/metrics
	```
- [PyPi](https://pypi.org/project/metrics) (📥 2.7K / month · 📦 14 · ⏱️ 28.04.2018):
	```
	pip install metrics
	```
- [Conda](https://anaconda.org/conda-forge/torchmetrics) (📥 280K · ⏱️ 04.02.2022):
	```
	conda install -c conda-forge torchmetrics
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/fairscale">FairScale</a></b> (🥈30 ·  ⭐ 1.6K) - PyTorch extensions for high performance and large scale training. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/fairscale) (👨‍💻 54 · 🔀 150 · 📦 160 · 📋 270 - 22% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/facebookresearch/fairscale
	```
- [PyPi](https://pypi.org/project/fairscale) (📥 59K / month · 📦 13 · ⏱️ 14.01.2022):
	```
	pip install fairscale
	```
- [Conda](https://anaconda.org/conda-forge/fairscale) (📥 4.8K · ⏱️ 05.02.2022):
	```
	conda install -c conda-forge fairscale
	```
</details>
<details><summary><b><a href="https://github.com/dask/dask-ml">dask-ml</a></b> (🥈29 ·  ⭐ 780) - Scalable Machine Learning with Dask. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dask/dask-ml) (👨‍💻 71 · 🔀 220 · 📦 550 · 📋 470 - 49% open · ⏱️ 20.01.2022):

	```
	git clone https://github.com/dask/dask-ml
	```
- [PyPi](https://pypi.org/project/dask-ml) (📥 62K / month · 📦 55 · ⏱️ 22.01.2022):
	```
	pip install dask-ml
	```
- [Conda](https://anaconda.org/conda-forge/dask-ml) (📥 260K · ⏱️ 22.01.2022):
	```
	conda install -c conda-forge dask-ml
	```
</details>
<details><summary><b><a href="https://github.com/intel-analytics/analytics-zoo">analytics-zoo</a></b> (🥈28 ·  ⭐ 2.5K) - Distributed Tensorflow, Keras and PyTorch on Apache.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/intel-analytics/analytics-zoo) (👨‍💻 100 · 🔀 710 · 📦 3 · 📋 1.4K - 40% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/intel-analytics/analytics-zoo
	```
- [PyPi](https://pypi.org/project/analytics-zoo) (📥 9.5K / month · 📦 1 · ⏱️ 09.02.2022):
	```
	pip install analytics-zoo
	```
</details>
<details><summary><b><a href="https://github.com/uber/petastorm">petastorm</a></b> (🥈28 ·  ⭐ 1.4K) - Petastorm library enables single machine or distributed training.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/uber/petastorm) (👨‍💻 43 · 🔀 230 · 📥 310 · 📦 54 · 📋 270 - 49% open · ⏱️ 10.01.2022):

	```
	git clone https://github.com/uber/petastorm
	```
- [PyPi](https://pypi.org/project/petastorm) (📥 84K / month · 📦 4 · ⏱️ 04.09.2021):
	```
	pip install petastorm
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/SynapseML">MMLSpark</a></b> (🥉27 ·  ⭐ 3.1K) - Simple and Distributed Machine Learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/microsoft/SynapseML) (👨‍💻 84 · 🔀 640 · 📋 540 - 43% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/microsoft/SynapseML
	```
- [PyPi](https://pypi.org/project/mmlspark) (📥 46K / month · ⏱️ 18.03.2020):
	```
	pip install mmlspark
	```
</details>
<details><summary><b><a href="https://github.com/mpi4py/mpi4py">mpi4py</a></b> (🥉27 ·  ⭐ 500) - Python bindings for MPI. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/mpi4py/mpi4py) (👨‍💻 20 · 🔀 74 · 📥 3.3K · 📋 64 - 20% open · ⏱️ 26.01.2022):

	```
	git clone https://github.com/mpi4py/mpi4py
	```
- [PyPi](https://pypi.org/project/mpi4py) (📥 160K / month · 📦 580 · ⏱️ 15.12.2021):
	```
	pip install mpi4py
	```
- [Conda](https://anaconda.org/conda-forge/mpi4py) (📥 920K · ⏱️ 25.11.2021):
	```
	conda install -c conda-forge mpi4py
	```
</details>
<details><summary><b><a href="https://github.com/yahoo/TensorFlowOnSpark">TensorFlowOnSpark</a></b> (🥉26 ·  ⭐ 3.8K) - TensorFlowOnSpark brings TensorFlow programs to.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/yahoo/TensorFlowOnSpark) (👨‍💻 34 · 🔀 960 · 📋 360 - 1% open · ⏱️ 10.01.2022):

	```
	git clone https://github.com/yahoo/TensorFlowOnSpark
	```
- [PyPi](https://pypi.org/project/tensorflowonspark) (📥 440K / month · 📦 5 · ⏱️ 25.05.2021):
	```
	pip install tensorflowonspark
	```
- [Conda](https://anaconda.org/conda-forge/tensorflowonspark) (📥 9.7K · ⏱️ 19.12.2020):
	```
	conda install -c conda-forge tensorflowonspark
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/SynapseML">SynapseML</a></b> (🥉26 ·  ⭐ 3.1K · ➕) - Simple and Distributed Machine Learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/SynapseML) (👨‍💻 84 · 🔀 640 · 📋 540 - 43% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/microsoft/SynapseML
	```
- [PyPi](https://pypi.org/project/synapseml) (📥 5.1K / month · ⏱️ 12.01.2022):
	```
	pip install synapseml
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/mesh">Mesh</a></b> (🥉26 ·  ⭐ 1.2K) - Mesh TensorFlow: Model Parallelism Made Easier. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/mesh) (👨‍💻 45 · 🔀 200 · 📦 630 · 📋 100 - 86% open · ⏱️ 26.01.2022):

	```
	git clone https://github.com/tensorflow/mesh
	```
- [PyPi](https://pypi.org/project/mesh-tensorflow) (📥 53K / month · 📦 32 · ⏱️ 24.03.2021):
	```
	pip install mesh-tensorflow
	```
</details>
<details><summary><b><a href="https://github.com/maxpumperla/elephas">Elephas</a></b> (🥉25 ·  ⭐ 1.5K · 📉) - Distributed Deep learning with Keras & Spark. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>keras</code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/maxpumperla/elephas) (👨‍💻 27 · 🔀 290 · 📦 52 · 📋 160 - 15% open · ⏱️ 17.08.2021):

	```
	git clone https://github.com/maxpumperla/elephas
	```
- [PyPi](https://pypi.org/project/elephas) (📥 28K / month · 📦 3 · ⏱️ 17.08.2021):
	```
	pip install elephas
	```
- [Conda](https://anaconda.org/conda-forge/elephas) (📥 7.7K · ⏱️ 02.06.2021):
	```
	conda install -c conda-forge elephas
	```
</details>
<details><summary><b><a href="https://github.com/learning-at-home/hivemind">Hivemind</a></b> (🥉21 ·  ⭐ 910) - Decentralized deep learning in PyTorch. Built to train models on.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/learning-at-home/hivemind) (👨‍💻 20 · 🔀 59 · 📦 4 · 📋 120 - 36% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/learning-at-home/hivemind
	```
- [PyPi](https://pypi.org/project/hivemind) (📥 240 / month · 📦 1 · ⏱️ 20.12.2021):
	```
	pip install hivemind
	```
</details>
<details><summary><b><a href="https://github.com/facebookincubator/submitit">Submit it</a></b> (🥉21 ·  ⭐ 550) - Python 3.6+ toolbox for submitting jobs to Slurm. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookincubator/submitit) (👨‍💻 17 · 🔀 52 · 📋 58 - 43% open · ⏱️ 09.12.2021):

	```
	git clone https://github.com/facebookincubator/submitit
	```
- [PyPi](https://pypi.org/project/submitit) (📥 14K / month · 📦 6 · ⏱️ 30.11.2021):
	```
	pip install submitit
	```
- [Conda](https://anaconda.org/conda-forge/submitit) (📥 5.2K · ⏱️ 10.02.2021):
	```
	conda install -c conda-forge submitit
	```
</details>
<details><summary><b><a href="https://github.com/bytedance/byteps">BytePS</a></b> (🥉20 ·  ⭐ 3.1K) - A high performance and generic framework for distributed DNN training. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bytedance/byteps) (👨‍💻 19 · 🔀 430 · 📋 260 - 38% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/bytedance/byteps
	```
- [PyPi](https://pypi.org/project/byteps) (📥 84 / month · ⏱️ 02.08.2021):
	```
	pip install byteps
	```
- [Docker Hub](https://hub.docker.com/r/bytepsimage/tensorflow) (📥 1.2K · ⏱️ 03.03.2020):
	```
	docker pull bytepsimage/tensorflow
	```
</details>
<details><summary><b><a href="https://github.com/apache/singa">Apache Singa</a></b> (🥉20 ·  ⭐ 2.5K) - a distributed deep learning platform. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/singa) (👨‍💻 76 · 🔀 760 · 📦 1 · 📋 89 - 44% open · ⏱️ 10.08.2021):

	```
	git clone https://github.com/apache/singa
	```
- [Conda](https://anaconda.org/nusdbsystem/singa) (📥 410 · ⏱️ 09.08.2021):
	```
	conda install -c nusdbsystem singa
	```
- [Docker Hub](https://hub.docker.com/r/apache/singa) (📥 220 · ⭐ 4 · ⏱️ 04.06.2019):
	```
	docker pull apache/singa
	```
</details>
<details><summary><b><a href="https://github.com/uber/fiber">Fiber</a></b> (🥉18 ·  ⭐ 960 · 💤) - Distributed Computing for AI Made Simple. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/uber/fiber) (👨‍💻 5 · 🔀 100 · 📦 31 · 📋 28 - 71% open · ⏱️ 15.03.2021):

	```
	git clone https://github.com/uber/fiber
	```
- [PyPi](https://pypi.org/project/fiber) (📥 2K / month · 📦 1 · ⏱️ 09.07.2020):
	```
	pip install fiber
	```
</details>
<details><summary><b><a href="https://github.com/tunib-ai/parallelformers">parallelformers</a></b> (🥉18 ·  ⭐ 440 · ➕) - Parallelformers: An Efficient Model Parallelization.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tunib-ai/parallelformers) (👨‍💻 3 · 🔀 23 · 📦 3 · 📋 12 - 25% open · ⏱️ 29.12.2021):

	```
	git clone https://github.com/tunib-ai/parallelformers
	```
- [PyPi](https://pypi.org/project/parallelformers) (📥 220 / month · ⏱️ 29.12.2021):
	```
	pip install parallelformers
	```
</details>
<details><summary><b><a href="https://github.com/kingoflolz/mesh-transformer-jax">mesh-transformer-jax</a></b> (🥉16 ·  ⭐ 3.8K · ➕) - Model parallel transformers in JAX and Haiku. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/kingoflolz/mesh-transformer-jax) (👨‍💻 23 · 🔀 460 · 📋 140 - 7% open · ⏱️ 28.01.2022):

	```
	git clone https://github.com/kingoflolz/mesh-transformer-jax
	```
</details>
<details><summary>Show 7 hidden projects...</summary>

- <b><a href="https://github.com/DEAP/deap">DEAP</a></b> (🥈32 ·  ⭐ 4.6K) - Distributed Evolutionary Algorithms in Python. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code>
- <b><a href="https://github.com/databricks/tensorframes">TensorFrames</a></b> (🥉21 ·  ⭐ 760 · 💀) - [DEPRECATED] Tensorflow wrapper for DataFrames on.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/deepmind/launchpad">launchpad</a></b> (🥉20 ·  ⭐ 250) - Launchpad is a library that simplifies writing distributed.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/peterwittek/somoclu">somoclu</a></b> (🥉20 ·  ⭐ 230) - Massively parallel self-organizing maps: accelerate training on multicore.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Ibotta/sk-dist">sk-dist</a></b> (🥉19 ·  ⭐ 280 · 💤) - Distributed scikit-learn meta-estimators in PySpark. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/ml-tooling/lazycluster">LazyCluster</a></b> (🥉12 ·  ⭐ 43) - Distributed machine learning made simple. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/petuum/autodist">autodist</a></b> (🥉11 ·  ⭐ 120 · 💀) - Simple Distributed Deep Learning on TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Hyperparameter Optimization & AutoML

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for hyperparameter optimization, automl and neural architecture search._

<details><summary><b><a href="https://github.com/optuna/optuna">Optuna</a></b> (🥇38 ·  ⭐ 5.9K) - A hyperparameter optimization framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/optuna/optuna) (👨‍💻 180 · 🔀 650 · 📦 2.6K · 📋 1.1K - 13% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/optuna/optuna
	```
- [PyPi](https://pypi.org/project/optuna) (📥 830K / month · 📦 180 · ⏱️ 07.02.2022):
	```
	pip install optuna
	```
- [Conda](https://anaconda.org/conda-forge/optuna) (📥 96K · ⏱️ 04.10.2021):
	```
	conda install -c conda-forge optuna
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/nni">NNI</a></b> (🥇36 ·  ⭐ 11K) - An open source AutoML toolkit for automate machine learning lifecycle,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/nni) (👨‍💻 160 · 🔀 1.5K · 📦 180 · 📋 1.5K - 17% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/microsoft/nni
	```
- [PyPi](https://pypi.org/project/nni) (📥 8.6K / month · 📦 28 · ⏱️ 19.01.2022):
	```
	pip install nni
	```
</details>
<details><summary><b><a href="https://github.com/alteryx/featuretools">featuretools</a></b> (🥇35 ·  ⭐ 6K) - An open source python library for automated feature engineering. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/alteryx/featuretools) (👨‍💻 59 · 🔀 780 · 📦 920 · 📋 730 - 22% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/alteryx/featuretools
	```
- [PyPi](https://pypi.org/project/featuretools) (📥 590K / month · 📦 62 · ⏱️ 28.01.2022):
	```
	pip install featuretools
	```
- [Conda](https://anaconda.org/conda-forge/featuretools) (📥 78K · ⏱️ 01.02.2022):
	```
	conda install -c conda-forge featuretools
	```
</details>
<details><summary><b><a href="https://github.com/keras-team/autokeras">AutoKeras</a></b> (🥇34 ·  ⭐ 8.3K) - AutoML library for deep learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/keras-team/autokeras) (👨‍💻 130 · 🔀 1.3K · 📥 2.6K · 📦 270 · 📋 800 - 8% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/keras-team/autokeras
	```
- [PyPi](https://pypi.org/project/autokeras) (📥 40K / month · 📦 10 · ⏱️ 03.02.2022):
	```
	pip install autokeras
	```
</details>
<details><summary><b><a href="https://github.com/hyperopt/hyperopt">Hyperopt</a></b> (🥇34 ·  ⭐ 6.1K) - Distributed Asynchronous Hyperparameter Optimization in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/hyperopt/hyperopt) (👨‍💻 93 · 🔀 920 · 📦 5.7K · 📋 590 - 60% open · ⏱️ 29.11.2021):

	```
	git clone https://github.com/hyperopt/hyperopt
	```
- [PyPi](https://pypi.org/project/hyperopt) (📥 2M / month · 📦 400 · ⏱️ 17.11.2021):
	```
	pip install hyperopt
	```
- [Conda](https://anaconda.org/conda-forge/hyperopt) (📥 340K · ⏱️ 14.10.2020):
	```
	conda install -c conda-forge hyperopt
	```
</details>
<details><summary><b><a href="https://github.com/automl/auto-sklearn">auto-sklearn</a></b> (🥈33 ·  ⭐ 6K) - Automated Machine Learning with scikit-learn. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/automl/auto-sklearn) (👨‍💻 79 · 🔀 1.1K · 📥 14 · 📦 260 · 📋 850 - 13% open · ⏱️ 25.01.2022):

	```
	git clone https://github.com/automl/auto-sklearn
	```
- [PyPi](https://pypi.org/project/auto-sklearn) (📥 28K / month · 📦 30 · ⏱️ 25.01.2022):
	```
	pip install auto-sklearn
	```
- [Conda](https://anaconda.org/conda-forge/auto-sklearn) (📥 2.9K · ⏱️ 28.01.2022):
	```
	conda install -c conda-forge auto-sklearn
	```
</details>
<details><summary><b><a href="https://github.com/keras-team/keras-tuner">Keras Tuner</a></b> (🥈33 ·  ⭐ 2.5K) - Hyperparameter tuning for humans. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/keras-team/keras-tuner) (👨‍💻 42 · 🔀 320 · 📦 1.1K · 📋 360 - 44% open · ⏱️ 20.01.2022):

	```
	git clone https://github.com/keras-team/keras-tuner
	```
- [PyPi](https://pypi.org/project/keras-tuner) (📥 530K / month · 📦 34 · ⏱️ 05.11.2021):
	```
	pip install keras-tuner
	```
- [Conda](https://anaconda.org/conda-forge/keras-tuner) (📥 4.9K · ⏱️ 12.01.2022):
	```
	conda install -c conda-forge keras-tuner
	```
</details>
<details><summary><b><a href="https://github.com/scikit-optimize/scikit-optimize">scikit-optimize</a></b> (🥈33 ·  ⭐ 2.3K) - Sequential model-based optimization with a `scipy.optimize`.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/scikit-optimize/scikit-optimize) (👨‍💻 75 · 🔀 420 · 📦 2.4K · 📋 620 - 37% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/scikit-optimize/scikit-optimize
	```
- [PyPi](https://pypi.org/project/scikit-optimize) (📥 780K / month · 📦 170 · ⏱️ 12.10.2021):
	```
	pip install scikit-optimize
	```
- [Conda](https://anaconda.org/conda-forge/scikit-optimize) (📥 530K · ⏱️ 15.12.2021):
	```
	conda install -c conda-forge scikit-optimize
	```
</details>
<details><summary><b><a href="https://github.com/facebook/Ax">Ax</a></b> (🥈33 ·  ⭐ 1.7K) - Adaptive Experimentation Platform. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebook/Ax) (👨‍💻 110 · 🔀 180 · 📦 240 · 📋 360 - 10% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/facebook/Ax
	```
- [PyPi](https://pypi.org/project/ax-platform) (📥 110K / month · 📦 14 · ⏱️ 16.12.2021):
	```
	pip install ax-platform
	```
- [Conda](https://anaconda.org/conda-forge/ax-platform) (📥 690 · ⏱️ 22.06.2021):
	```
	conda install -c conda-forge ax-platform
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/botorch">BoTorch</a></b> (🥈32 ·  ⭐ 2.2K) - Bayesian optimization in PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/botorch) (👨‍💻 68 · 🔀 240 · 📦 210 · 📋 240 - 23% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/pytorch/botorch
	```
- [PyPi](https://pypi.org/project/botorch) (📥 130K / month · 📦 12 · ⏱️ 09.12.2021):
	```
	pip install botorch
	```
- [Conda](https://anaconda.org/conda-forge/botorch) (📥 17K · ⏱️ 09.12.2021):
	```
	conda install -c conda-forge botorch
	```
</details>
<details><summary><b><a href="https://github.com/awslabs/autogluon">AutoGluon</a></b> (🥈29 ·  ⭐ 4.1K) - AutoGluon: AutoML for Image, Text, and Tabular Data. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/awslabs/autogluon) (👨‍💻 65 · 🔀 550 · 📦 97 · 📋 620 - 21% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/awslabs/autogluon
	```
- [PyPi](https://pypi.org/project/autogluon) (📥 45K / month · 📦 4 · ⏱️ 10.02.2022):
	```
	pip install autogluon
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/nevergrad">nevergrad</a></b> (🥈29 ·  ⭐ 3.2K) - A Python toolbox for performing gradient-free optimization. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/nevergrad) (👨‍💻 47 · 🔀 300 · 📦 280 · 📋 250 - 38% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/facebookresearch/nevergrad
	```
- [PyPi](https://pypi.org/project/nevergrad) (📥 20K / month · 📦 17 · ⏱️ 10.11.2021):
	```
	pip install nevergrad
	```
- [Conda](https://anaconda.org/conda-forge/nevergrad) (📥 22K · ⏱️ 14.06.2021):
	```
	conda install -c conda-forge nevergrad
	```
</details>
<details><summary><b><a href="https://github.com/mljar/mljar-supervised">mljar-supervised</a></b> (🥈27 ·  ⭐ 1.8K) - Python package for AutoML on Tabular Data with Feature.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mljar/mljar-supervised) (👨‍💻 14 · 🔀 250 · 📦 36 · 📋 460 - 17% open · ⏱️ 06.12.2021):

	```
	git clone https://github.com/mljar/mljar-supervised
	```
- [PyPi](https://pypi.org/project/mljar-supervised) (📥 25K / month · ⏱️ 01.10.2021):
	```
	pip install mljar-supervised
	```
- [Conda](https://anaconda.org/conda-forge/mljar-supervised) (📥 1K · ⏱️ 03.12.2021):
	```
	conda install -c conda-forge mljar-supervised
	```
</details>
<details><summary><b><a href="https://github.com/automl/SMAC3">SMAC3</a></b> (🥈27 ·  ⭐ 660) - Sequential Model-based Algorithm Configuration. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/automl/SMAC3) (👨‍💻 38 · 🔀 170 · 📋 360 - 18% open · ⏱️ 05.11.2021):

	```
	git clone https://github.com/automl/SMAC3
	```
- [PyPi](https://pypi.org/project/smac) (📥 23K / month · 📦 32 · ⏱️ 05.11.2021):
	```
	pip install smac
	```
- [Conda](https://anaconda.org/conda-forge/smac) (📥 2.2K · ⏱️ 21.10.2021):
	```
	conda install -c conda-forge smac
	```
</details>
<details><summary><b><a href="https://github.com/maxpumperla/hyperas">Hyperas</a></b> (🥈26 ·  ⭐ 2.1K) - Keras + Hyperopt: A very simple wrapper for convenient.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/maxpumperla/hyperas) (👨‍💻 21 · 🔀 300 · 📦 220 · 📋 250 - 36% open · ⏱️ 19.11.2021):

	```
	git clone https://github.com/maxpumperla/hyperas
	```
- [PyPi](https://pypi.org/project/hyperas) (📥 12K / month · 📦 24 · ⏱️ 28.02.2019):
	```
	pip install hyperas
	```
</details>
<details><summary><b><a href="https://github.com/autonomio/talos">Talos</a></b> (🥈26 ·  ⭐ 1.5K · 📈) - Hyperparameter Optimization for TensorFlow, Keras and PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/autonomio/talos) (👨‍💻 21 · 🔀 250 · 📦 140 · 📋 400 - 8% open · ⏱️ 28.01.2022):

	```
	git clone https://github.com/autonomio/talos
	```
- [PyPi](https://pypi.org/project/talos) (📥 1.1K / month · 📦 6 · ⏱️ 28.01.2022):
	```
	pip install talos
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/adanet">AdaNet</a></b> (🥉25 ·  ⭐ 3.4K) - Fast and flexible AutoML with learning guarantees. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/adanet) (👨‍💻 27 · 🔀 520 · 📦 42 · 📋 110 - 57% open · ⏱️ 30.08.2021):

	```
	git clone https://github.com/tensorflow/adanet
	```
- [PyPi](https://pypi.org/project/adanet) (📥 1.1K / month · 📦 2 · ⏱️ 09.07.2020):
	```
	pip install adanet
	```
</details>
<details><summary><b><a href="https://github.com/SimonBlanke/Hyperactive">Hyperactive</a></b> (🥉23 ·  ⭐ 360) - An optimization and data collection toolbox for convenient and fast.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SimonBlanke/Hyperactive) (👨‍💻 4 · 🔀 32 · 📥 98 · 📦 11 · 📋 43 - 16% open · ⏱️ 18.01.2022):

	```
	git clone https://github.com/SimonBlanke/Hyperactive
	```
- [PyPi](https://pypi.org/project/hyperactive) (📥 530 / month · 📦 3 · ⏱️ 05.12.2021):
	```
	pip install hyperactive
	```
</details>
<details><summary><b><a href="https://github.com/Neuraxio/Neuraxle">Neuraxle</a></b> (🥉22 ·  ⭐ 500) - A Sklearn-like Framework for Hyperparameter Tuning and AutoML in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Neuraxio/Neuraxle) (👨‍💻 7 · 🔀 53 · 📦 26 · 📋 350 - 41% open · ⏱️ 01.11.2021):

	```
	git clone https://github.com/Neuraxio/Neuraxle
	```
- [PyPi](https://pypi.org/project/neuraxle) (📥 320 / month · 📦 1 · ⏱️ 17.10.2021):
	```
	pip install neuraxle
	```
</details>
<details><summary><b><a href="https://github.com/AutoViML/Auto_ViML">Auto ViML</a></b> (🥉20 ·  ⭐ 330) - Automatically Build Multiple ML Models with a Single Line of Code... <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/AutoViML/Auto_ViML) (👨‍💻 6 · 🔀 70 · 📦 15 · 📋 18 - 22% open · ⏱️ 06.12.2021):

	```
	git clone https://github.com/AutoViML/Auto_ViML
	```
- [PyPi](https://pypi.org/project/autoviml) (📥 1.1K / month · 📦 2 · ⏱️ 06.12.2021):
	```
	pip install autoviml
	```
</details>
<details><summary><b><a href="https://github.com/ScottfreeLLC/AlphaPy">AlphaPy</a></b> (🥉19 ·  ⭐ 710) - Automated Machine Learning [AutoML] with Python, scikit-learn, Keras,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ScottfreeLLC/AlphaPy) (👨‍💻 3 · 🔀 150 · 📦 3 · 📋 41 - 29% open · ⏱️ 23.10.2021):

	```
	git clone https://github.com/ScottfreeLLC/AlphaPy
	```
- [PyPi](https://pypi.org/project/alphapy) (📥 87 / month · ⏱️ 29.08.2020):
	```
	pip install alphapy
	```
</details>
<details><summary><b><a href="https://github.com/rsteca/sklearn-deap">sklearn-deap</a></b> (🥉19 ·  ⭐ 680 · 💤) - Use evolutionary algorithms instead of gridsearch in.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rsteca/sklearn-deap) (👨‍💻 22 · 🔀 110 · 📦 31 · 📋 55 - 38% open · ⏱️ 30.07.2021):

	```
	git clone https://github.com/rsteca/sklearn-deap
	```
- [PyPi](https://pypi.org/project/sklearn-deap) (📥 730 / month · 📦 2 · ⏱️ 30.07.2021):
	```
	pip install sklearn-deap
	```
</details>
<details><summary><b><a href="https://github.com/google/model_search">model_search</a></b> (🥉11 ·  ⭐ 3.2K) - AutoML algorithms for model architecture search at scale. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/model_search) (👨‍💻 1 · 🔀 310 · 📋 50 - 70% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/google/model_search
	```
</details>
<details><summary>Show 24 hidden projects...</summary>

- <b><a href="https://github.com/EpistasisLab/tpot">TPOT</a></b> (🥈32 ·  ⭐ 8.4K · 💀) - A Python Automated Machine Learning tool that optimizes.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/fmfn/BayesianOptimization">Bayesian Optimization</a></b> (🥈32 ·  ⭐ 5.7K · 💀) - A Python implementation of global optimization with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Epistimio/orion">Orion</a></b> (🥈27 ·  ⭐ 220) - Asynchronous Distributed Hyperparameter Optimization. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/SheffieldML/GPyOpt">GPyOpt</a></b> (🥈26 ·  ⭐ 790 · 💀) - Gaussian Process Optimization using GPy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/ClimbsRocks/auto_ml">auto_ml</a></b> (🥉23 ·  ⭐ 1.6K · 💀) - [UNMAINTAINED] Automated machine learning for analytics & production. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/AxeldeRomblay/MLBox">MLBox</a></b> (🥉23 ·  ⭐ 1.3K · 💀) - MLBox is a powerful Automated Machine Learning python library. <code><a href="https://tldrlegal.com/search?q=BSD-1-Clause">❗️BSD-1-Clause</a></code>
- <b><a href="https://github.com/automl/HpBandSter">HpBandSter</a></b> (🥉22 ·  ⭐ 520 · 💀) - a distributed Hyperband implementation on Steroids. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/claesenm/optunity">optunity</a></b> (🥉22 ·  ⭐ 380 · 💀) - optimization routines for hyperparameter tuning. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/shankarpandala/lazypredict">lazypredict</a></b> (🥉22 ·  ⭐ 290) - Lazy Predict help build a lot of basic models without much code.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/williamFalcon/test-tube">Test Tube</a></b> (🥉20 ·  ⭐ 710 · 💀) - Python library to easily log experiments and parallelize.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/dragonfly/dragonfly">Dragonfly</a></b> (🥉19 ·  ⭐ 620 · 💀) - An open source python library for scalable Bayesian optimisation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/HDI-Project/ATM">Auto Tune Models</a></b> (🥉18 ·  ⭐ 510 · 💀) - Auto Tune Models - A multi-tenant, multi-data system for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/sherpa-ai/sherpa">Sherpa</a></b> (🥉18 ·  ⭐ 310 · 💀) - Hyperparameter optimization that enables researchers to.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/AutoViML/featurewiz">featurewiz</a></b> (🥉18 ·  ⭐ 150) - Use advanced feature engineering strategies and select best.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/tobegit3hub/advisor">Advisor</a></b> (🥉17 ·  ⭐ 1.4K · 💀) - Open-source implementation of Google Vizier for hyper parameters.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/reiinakano/xcessiv">Xcessiv</a></b> (🥉16 ·  ⭐ 1.3K · 💀) - A web-based application for quick, scalable, and automated.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/HunterMcGushion/hyperparameter_hunter">HyperparameterHunter</a></b> (🥉16 ·  ⭐ 680 · 💀) - Easy hyperparameter optimization and automatic result.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/minimaxir/automl-gs">automl-gs</a></b> (🥉15 ·  ⭐ 1.8K · 💀) - Provide an input CSV and a target field to predict, generate a.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/jmcarpenter2/parfit">Parfit</a></b> (🥉15 ·  ⭐ 200 · 💀) - A package for parallelizing the fit and flexibly scoring of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/carpedm20/ENAS-pytorch">ENAS</a></b> (🥉13 ·  ⭐ 2.5K · 💀) - PyTorch implementation of Efficient Neural Architecture Search via.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/LGE-ARC-AdvancedAI/auptimizer">Auptimizer</a></b> (🥉13 ·  ⭐ 180 · 💤) - An automatic ML model optimization tool. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/electricbrainio/hypermax">Hypermax</a></b> (🥉12 ·  ⭐ 100 · 💀) - Better, faster hyper-parameter optimization. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/joeddav/devol">Devol</a></b> (🥉11 ·  ⭐ 940 · 💀) - Genetic neural architecture search with Keras. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/gdikov/hypertunity">Hypertunity</a></b> (🥉9 ·  ⭐ 120 · 💀) - A toolset for black-box hyperparameter optimisation. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Reinforcement Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for building and evaluating reinforcement learning & agent-based systems._

<details><summary><b><a href="https://github.com/openai/gym">OpenAI Gym</a></b> (🥇42 ·  ⭐ 26K) - A toolkit for developing and comparing reinforcement learning.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/openai/gym) (👨‍💻 340 · 🔀 7.3K · 📦 26K · 📋 1.5K - 7% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/openai/gym
	```
- [PyPi](https://pypi.org/project/gym) (📥 570K / month · 📦 2.3K · ⏱️ 06.10.2021):
	```
	pip install gym
	```
- [Conda](https://anaconda.org/conda-forge/gym) (📥 89K · ⏱️ 08.02.2022):
	```
	conda install -c conda-forge gym
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/agents">TF-Agents</a></b> (🥇33 ·  ⭐ 2.2K) - TF-Agents: A reliable, scalable and easy to use TensorFlow.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/agents) (👨‍💻 120 · 🔀 600 · 📦 700 · 📋 530 - 20% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/tensorflow/agents
	```
- [PyPi](https://pypi.org/project/tf-agents) (📥 140K / month · 📦 14 · ⏱️ 20.01.2022):
	```
	pip install tf-agents
	```
</details>
<details><summary><b><a href="https://github.com/google/dopamine">Dopamine</a></b> (🥇30 ·  ⭐ 9.7K) - Dopamine is a research framework for fast prototyping of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google/dopamine) (👨‍💻 14 · 🔀 1.3K · 📋 160 - 49% open · ⏱️ 14.12.2021):

	```
	git clone https://github.com/google/dopamine
	```
- [PyPi](https://pypi.org/project/dopamine-rl) (📥 600K / month · 📦 37 · ⏱️ 13.12.2021):
	```
	pip install dopamine-rl
	```
</details>
<details><summary><b><a href="https://github.com/AI4Finance-Foundation/FinRL">FinRL</a></b> (🥈29 ·  ⭐ 3.3K) - FinRL: Financial Reinforcement Learning Framework. Please star. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/AI4Finance-Foundation/FinRL) (👨‍💻 52 · 🔀 900 · 📦 10 · 📋 330 - 24% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/AI4Finance-Foundation/FinRL
	```
- [PyPi](https://pypi.org/project/finrl) (📥 400 / month · ⏱️ 08.01.2022):
	```
	pip install finrl
	```
</details>
<details><summary><b><a href="https://github.com/tensorlayer/TensorLayer">TensorLayer</a></b> (🥈28 ·  ⭐ 6.8K) - Deep Learning and Reinforcement Learning Library for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorlayer/TensorLayer) (👨‍💻 130 · 🔀 1.5K · 📥 1.4K · 📋 460 - 4% open · ⏱️ 29.10.2021):

	```
	git clone https://github.com/tensorlayer/tensorlayer
	```
- [PyPi](https://pypi.org/project/tensorlayer) (📥 2.5K / month · 📦 39 · ⏱️ 19.06.2020):
	```
	pip install tensorlayer
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/acme">Acme</a></b> (🥈28 ·  ⭐ 2.5K) - A library of reinforcement learning components and agents. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmind/acme) (👨‍💻 58 · 🔀 300 · 📦 56 · 📋 160 - 25% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/deepmind/acme
	```
- [PyPi](https://pypi.org/project/dm-acme) (📥 3.9K / month · 📦 2 · ⏱️ 10.02.2022):
	```
	pip install dm-acme
	```
- [Conda](https://anaconda.org/conda-forge/dm-acme) (📥 1.8K · ⏱️ 09.12.2021):
	```
	conda install -c conda-forge dm-acme
	```
</details>
<details><summary><b><a href="https://github.com/mwydmuch/ViZDoom">ViZDoom</a></b> (🥈28 ·  ⭐ 1.3K) - Doom-based AI Research Platform for Reinforcement Learning from Raw.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mwydmuch/ViZDoom) (👨‍💻 46 · 🔀 310 · 📥 11K · 📦 120 · 📋 430 - 20% open · ⏱️ 20.01.2022):

	```
	git clone https://github.com/mwydmuch/ViZDoom
	```
- [PyPi](https://pypi.org/project/vizdoom) (📥 900 / month · 📦 14 · ⏱️ 22.11.2021):
	```
	pip install vizdoom
	```
</details>
<details><summary><b><a href="https://github.com/tensorforce/tensorforce">TensorForce</a></b> (🥉27 ·  ⭐ 3.1K · 📉) - Tensorforce: a TensorFlow library for applied.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorforce/tensorforce) (👨‍💻 82 · 🔀 510 · 📋 630 - 1% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/tensorforce/tensorforce
	```
- [PyPi](https://pypi.org/project/tensorforce) (📥 1.9K / month · 📦 26 · ⏱️ 07.09.2019):
	```
	pip install tensorforce
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PARL">PARL</a></b> (🥉27 ·  ⭐ 2.4K) - A high-performance distributed training framework for Reinforcement.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PARL) (👨‍💻 29 · 🔀 620 · 📦 86 · 📋 310 - 23% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/PaddlePaddle/PARL
	```
- [PyPi](https://pypi.org/project/parl) (📥 530 / month · ⏱️ 30.12.2021):
	```
	pip install parl
	```
</details>
<details><summary><b><a href="https://github.com/hill-a/stable-baselines">Stable Baselines</a></b> (🥉25 ·  ⭐ 3.4K) - A fork of OpenAI Baselines, implementations of reinforcement.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/hill-a/stable-baselines) (👨‍💻 110 · 🔀 670 · 📋 930 - 13% open · ⏱️ 25.08.2021):

	```
	git clone https://github.com/hill-a/stable-baselines
	```
- [PyPi](https://pypi.org/project/stable-baselines) (📥 8.5K / month · 📦 34 · ⏱️ 06.04.2021):
	```
	pip install stable-baselines
	```
</details>
<details><summary><b><a href="https://github.com/rlworkgroup/garage">garage</a></b> (🥉25 ·  ⭐ 1.4K) - A toolkit for reproducible reinforcement learning research. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rlworkgroup/garage) (👨‍💻 78 · 🔀 240 · 📦 29 · 📋 1K - 20% open · ⏱️ 20.10.2021):

	```
	git clone https://github.com/rlworkgroup/garage
	```
- [PyPi](https://pypi.org/project/garage) (📥 460 / month · 📦 2 · ⏱️ 23.03.2021):
	```
	pip install garage
	```
</details>
<details><summary><b><a href="https://github.com/chainer/chainerrl">ChainerRL</a></b> (🥉23 ·  ⭐ 1K · 💤) - ChainerRL is a deep reinforcement learning library built on top of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/chainer/chainerrl) (👨‍💻 29 · 🔀 210 · 📦 110 · 📋 220 - 33% open · ⏱️ 17.04.2021):

	```
	git clone https://github.com/chainer/chainerrl
	```
- [PyPi](https://pypi.org/project/chainerrl) (📥 530 / month · 📦 8 · ⏱️ 14.02.2020):
	```
	pip install chainerrl
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/ReAgent">ReAgent</a></b> (🥉22 ·  ⭐ 3.1K) - A platform for Reasoning systems (Reinforcement Learning,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/ReAgent) (👨‍💻 120 · 🔀 430 · 📋 120 - 35% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/facebookresearch/ReAgent
	```
- [PyPi](https://pypi.org/project/reagent) (📥 17 / month · ⏱️ 27.05.2020):
	```
	pip install reagent
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/trfl">TRFL</a></b> (🥉22 ·  ⭐ 3.1K) - TensorFlow Reinforcement Learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmind/trfl) (👨‍💻 13 · 🔀 370 · 📦 71 · 📋 22 - 27% open · ⏱️ 16.08.2021):

	```
	git clone https://github.com/deepmind/trfl
	```
- [PyPi](https://pypi.org/project/trfl) (📥 4.2K / month · 📦 3 · ⏱️ 16.08.2021):
	```
	pip install trfl
	```
</details>
<details><summary><b><a href="https://github.com/IntelLabs/coach">Coach</a></b> (🥉22 ·  ⭐ 2.1K · 💤) - Reinforcement Learning Coach by Intel AI Lab enables easy.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/IntelLabs/coach) (👨‍💻 35 · 🔀 410 · 📋 270 - 32% open · ⏱️ 28.06.2021):

	```
	git clone https://github.com/IntelLabs/coach
	```
- [PyPi](https://pypi.org/project/rl_coach) (📥 150 / month · 📦 2 · ⏱️ 10.10.2019):
	```
	pip install rl_coach
	```
</details>
<details><summary><b><a href="https://github.com/deepmind/rlax">RLax</a></b> (🥉21 ·  ⭐ 740) - A library of reinforcement learning building blocks in JAX. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepmind/rlax) (👨‍💻 16 · 🔀 57 · 📦 37 · 📋 18 - 50% open · ⏱️ 04.02.2022):

	```
	git clone https://github.com/deepmind/rlax
	```
- [PyPi](https://pypi.org/project/rlax) (📥 3K / month · ⏱️ 19.11.2021):
	```
	pip install rlax
	```
</details>
<details><summary><b><a href="https://github.com/pfnet/pfrl">PFRL</a></b> (🥉20 ·  ⭐ 780) - PFRL: a PyTorch-based deep reinforcement learning library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pfnet/pfrl) (👨‍💻 15 · 🔀 110 · 📦 30 · 📋 60 - 45% open · ⏱️ 06.12.2021):

	```
	git clone https://github.com/pfnet/pfrl
	```
- [PyPi](https://pypi.org/project/pfrl) (📥 5.3K / month · 📦 1 · ⏱️ 07.07.2021):
	```
	pip install pfrl
	```
</details>
<details><summary><b><a href="https://github.com/google-research/rliable">rliable</a></b> (🥉11 ·  ⭐ 310 · 🐣) - Library for reliable evaluation on RL and ML benchmarks, as.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google-research/rliable) (👨‍💻 2 · 🔀 17 · 📦 6 · ⏱️ 06.02.2022):

	```
	git clone https://github.com/google-research/rliable
	```
- [PyPi](https://pypi.org/project/rliable`):
	```
	pip install rliable`
	```
</details>
<details><summary>Show 5 hidden projects...</summary>

- <b><a href="https://github.com/openai/baselines">baselines</a></b> (🥇30 ·  ⭐ 12K · 💀) - OpenAI Baselines: high-quality implementations of reinforcement.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/keras-rl/keras-rl">keras-rl</a></b> (🥈29 ·  ⭐ 5.2K · 💀) - Deep Reinforcement Learning for Keras. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/deepmind/lab">DeepMind Lab</a></b> (🥉19 ·  ⭐ 6.6K) - A customisable 3D platform for agent-based AI research. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code>
- <b><a href="https://github.com/SerpentAI/SerpentAI">SerpentAI</a></b> (🥉19 ·  ⭐ 6.2K · 💀) - Game Agent Framework. Helping you create AIs / Bots that learn to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/enlite-ai/maze">Maze</a></b> (🥉16 ·  ⭐ 200) - Maze Applied Reinforcement Learning Framework. <code><a href="https://tldrlegal.com/search?q=Custom">❗️Custom</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Recommender Systems

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for building and evaluating recommendation systems._

<details><summary><b><a href="https://github.com/microsoft/recommenders">Recommenders</a></b> (🥇32 ·  ⭐ 12K · 📈) - Best Practices on Recommendation Systems. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/recommenders) (👨‍💻 100 · 🔀 2.1K · 📥 120 · 📦 11 · 📋 650 - 18% open · ⏱️ 13.01.2022):

	```
	git clone https://github.com/microsoft/recommenders
	```
- [PyPi](https://pypi.org/project/recommenders) (📥 4.6K / month · 📦 2 · ⏱️ 14.03.2021):
	```
	pip install recommenders
	```
</details>
<details><summary><b><a href="https://github.com/benfred/implicit">implicit</a></b> (🥇32 ·  ⭐ 2.6K) - Fast Python Collaborative Filtering for Implicit Feedback Datasets. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/benfred/implicit) (👨‍💻 30 · 🔀 530 · 📦 540 · 📋 380 - 16% open · ⏱️ 29.01.2022):

	```
	git clone https://github.com/benfred/implicit
	```
- [PyPi](https://pypi.org/project/implicit) (📥 160K / month · 📦 31 · ⏱️ 29.01.2022):
	```
	pip install implicit
	```
- [Conda](https://anaconda.org/conda-forge/implicit) (📥 330K · ⏱️ 29.01.2022):
	```
	conda install -c conda-forge implicit
	```
</details>
<details><summary><b><a href="https://github.com/lyst/lightfm">lightfm</a></b> (🥈28 ·  ⭐ 3.9K) - A Python implementation of LightFM, a hybrid recommendation algorithm. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/lyst/lightfm) (👨‍💻 44 · 🔀 610 · 📦 640 · 📋 440 - 20% open · ⏱️ 31.12.2021):

	```
	git clone https://github.com/lyst/lightfm
	```
- [PyPi](https://pypi.org/project/lightfm) (📥 300K / month · 📦 45 · ⏱️ 27.11.2020):
	```
	pip install lightfm
	```
- [Conda](https://anaconda.org/conda-forge/lightfm) (📥 110K · ⏱️ 07.02.2021):
	```
	conda install -c conda-forge lightfm
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/recommenders">TF Recommenders</a></b> (🥈28 ·  ⭐ 1.2K) - TensorFlow Recommenders is a library for building.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/recommenders) (👨‍💻 30 · 🔀 160 · 📦 71 · 📋 230 - 54% open · ⏱️ 28.01.2022):

	```
	git clone https://github.com/tensorflow/recommenders
	```
- [PyPi](https://pypi.org/project/tensorflow-recommenders) (📥 270K / month · 📦 1 · ⏱️ 23.08.2021):
	```
	pip install tensorflow-recommenders
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/ranking">TF Ranking</a></b> (🥈27 ·  ⭐ 2.4K) - Learning to Rank in TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/ranking) (👨‍💻 25 · 🔀 410 · 📋 280 - 17% open · ⏱️ 22.11.2021):

	```
	git clone https://github.com/tensorflow/ranking
	```
- [PyPi](https://pypi.org/project/tensorflow_ranking) (📥 45K / month · 📦 11 · ⏱️ 16.11.2021):
	```
	pip install tensorflow_ranking
	```
</details>
<details><summary><b><a href="https://github.com/RUCAIBox/RecBole">RecBole</a></b> (🥉25 ·  ⭐ 1.6K) - A unified, comprehensive and efficient recommendation library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/RUCAIBox/RecBole) (👨‍💻 43 · 🔀 290 · 📋 300 - 21% open · ⏱️ 25.01.2022):

	```
	git clone https://github.com/RUCAIBox/RecBole
	```
- [PyPi](https://pypi.org/project/recbole) (📥 560 / month · ⏱️ 16.09.2021):
	```
	pip install recbole
	```
- [Conda](https://anaconda.org/aibox/recbole) (📥 1.1K · ⏱️ 16.09.2021):
	```
	conda install -c aibox recbole
	```
</details>
<details><summary><b><a href="https://github.com/PreferredAI/cornac">Cornac</a></b> (🥉25 ·  ⭐ 530) - A Comparative Framework for Multimodal Recommender Systems. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PreferredAI/cornac) (👨‍💻 13 · 🔀 86 · 📦 75 · 📋 85 - 9% open · ⏱️ 30.09.2021):

	```
	git clone https://github.com/PreferredAI/cornac
	```
- [PyPi](https://pypi.org/project/cornac) (📥 9.2K / month · 📦 14 · ⏱️ 26.09.2021):
	```
	pip install cornac
	```
- [Conda](https://anaconda.org/conda-forge/cornac) (📥 200K · ⏱️ 15.11.2021):
	```
	conda install -c conda-forge cornac
	```
</details>
<details><summary><b><a href="https://github.com/ibayer/fastFM">fastFM</a></b> (🥉22 ·  ⭐ 960 · 💤) - fastFM: A Library for Factorization Machines. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ibayer/fastFM) (👨‍💻 20 · 🔀 190 · 📥 430 · 📦 93 · 📋 110 - 43% open · ⏱️ 24.03.2021):

	```
	git clone https://github.com/ibayer/fastFM
	```
- [PyPi](https://pypi.org/project/fastfm) (📥 610 / month · 📦 8 · ⏱️ 23.11.2017):
	```
	pip install fastfm
	```
</details>
<details><summary><b><a href="https://github.com/statisticianinstilettos/recmetrics">recmetrics</a></b> (🥉18 ·  ⭐ 340) - A library of metrics for evaluating recommender systems. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/statisticianinstilettos/recmetrics) (👨‍💻 13 · 🔀 79 · 📦 22 · 📋 17 - 41% open · ⏱️ 27.10.2021):

	```
	git clone https://github.com/statisticianinstilettos/recmetrics
	```
- [PyPi](https://pypi.org/project/recmetrics) (📥 1K / month · ⏱️ 24.09.2021):
	```
	pip install recmetrics
	```
</details>
<details><summary><b><a href="https://github.com/caserec/CaseRecommender">Case Recommender</a></b> (🥉17 ·  ⭐ 380) - Case Recommender: A Flexible and Extensible Python.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/caserec/CaseRecommender) (👨‍💻 11 · 🔀 77 · 📦 9 · 📋 27 - 25% open · ⏱️ 25.11.2021):

	```
	git clone https://github.com/caserec/CaseRecommender
	```
- [PyPi](https://pypi.org/project/caserecommender) (📥 350 / month · ⏱️ 25.11.2021):
	```
	pip install caserecommender
	```
</details>
<details><summary>Show 5 hidden projects...</summary>

- <b><a href="https://github.com/NicolasHug/Surprise">scikit-surprise</a></b> (🥈28 ·  ⭐ 5.2K · 💀) - A Python scikit for building and analyzing recommender.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jfkirk/tensorrec">tensorrec</a></b> (🥉22 ·  ⭐ 1.2K · 💀) - A TensorFlow recommendation algorithm and framework in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/lenskit/lkpy">lkpy</a></b> (🥉21 ·  ⭐ 190) - Python recommendation toolkit. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/maciejkula/spotlight">Spotlight</a></b> (🥉18 ·  ⭐ 2.7K · 💀) - Deep recommender models using PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/ylongqi/openrec">OpenRec</a></b> (🥉16 ·  ⭐ 390 · 💀) - OpenRec is an open-source and modular library for neural network-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Privacy Machine Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for encrypted and privacy-preserving machine learning using methods like federated learning & differential privacy._

<details><summary><b><a href="https://github.com/OpenMined/PySyft">PySyft</a></b> (🥇34 ·  ⭐ 7.9K) - A library for answering questions using data you cannot see. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/OpenMined/PySyft) (👨‍💻 430 · 🔀 1.7K · 📋 3.1K - 9% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/OpenMined/PySyft
	```
- [PyPi](https://pypi.org/project/syft) (📥 3.6K / month · 📦 5 · ⏱️ 01.12.2021):
	```
	pip install syft
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/privacy">TensorFlow Privacy</a></b> (🥈27 ·  ⭐ 1.5K) - Library for training machine learning models with.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/privacy) (👨‍💻 44 · 🔀 330 · 📥 62 · 📋 150 - 41% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/tensorflow/privacy
	```
- [PyPi](https://pypi.org/project/tensorflow-privacy) (📥 31K / month · 📦 6 · ⏱️ 01.09.2021):
	```
	pip install tensorflow-privacy
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/opacus">Opacus</a></b> (🥈27 ·  ⭐ 1K) - Training PyTorch models with differential privacy. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/opacus) (👨‍💻 42 · 🔀 180 · 📥 42 · 📦 74 · 📋 140 - 18% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/pytorch/opacus
	```
- [PyPi](https://pypi.org/project/opacus) (📥 4.6K / month · 📦 11 · ⏱️ 09.02.2022):
	```
	pip install opacus
	```
- [Conda](https://anaconda.org/conda-forge/opacus) (📥 82 · ⏱️ 10.02.2022):
	```
	conda install -c conda-forge opacus
	```
</details>
<details><summary><b><a href="https://github.com/FederatedAI/FATE">FATE</a></b> (🥉25 ·  ⭐ 3.9K · 📉) - An Industrial Grade Federated Learning Framework. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/FederatedAI/FATE) (👨‍💻 69 · 🔀 1.1K · 📋 1.1K - 32% open · ⏱️ 27.01.2022):

	```
	git clone https://github.com/FederatedAI/FATE
	```
- [PyPi](https://pypi.org/project/ETAF) (📥 1 / month · ⏱️ 06.05.2020):
	```
	pip install ETAF
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/CrypTen">CrypTen</a></b> (🥉23 ·  ⭐ 990) - A framework for Privacy Preserving Machine Learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/CrypTen) (👨‍💻 25 · 🔀 160 · 📦 12 · 📋 140 - 23% open · ⏱️ 31.01.2022):

	```
	git clone https://github.com/facebookresearch/CrypTen
	```
- [PyPi](https://pypi.org/project/crypten) (📥 250 / month · ⏱️ 09.09.2021):
	```
	pip install crypten
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/tf-encrypted/tf-encrypted">TFEncrypted</a></b> (🥉24 ·  ⭐ 970 · 💀) - A Framework for Encrypted Machine Learning in TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Workflow & Experiment Tracking

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries to organize, track, and visualize machine learning experiments._

<details><summary><b><a href="https://github.com/tensorflow/tensorboard">Tensorboard</a></b> (🥇42 ·  ⭐ 5.8K) - TensorFlows Visualization Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tensorboard) (👨‍💻 280 · 🔀 1.5K · 📦 94K · 📋 1.6K - 33% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/tensorflow/tensorboard
	```
- [PyPi](https://pypi.org/project/tensorboard) (📥 13M / month · 📦 2.3K · ⏱️ 20.01.2022):
	```
	pip install tensorboard
	```
- [Conda](https://anaconda.org/conda-forge/tensorboard) (📥 2.7M · ⏱️ 04.02.2022):
	```
	conda install -c conda-forge tensorboard
	```
</details>
<details><summary><b><a href="https://github.com/mlflow/mlflow">mlflow</a></b> (🥇40 ·  ⭐ 11K) - Open source platform for the machine learning lifecycle. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/mlflow/mlflow) (👨‍💻 350 · 🔀 2.5K · 📋 2.2K - 45% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/mlflow/mlflow
	```
- [PyPi](https://pypi.org/project/mlflow) (📥 14M / month · 📦 280 · ⏱️ 27.01.2022):
	```
	pip install mlflow
	```
- [Conda](https://anaconda.org/conda-forge/mlflow) (📥 480K · ⏱️ 27.01.2022):
	```
	conda install -c conda-forge mlflow
	```
</details>
<details><summary><b><a href="https://github.com/pycaret/pycaret">PyCaret</a></b> (🥇37 ·  ⭐ 5.1K) - An open-source, low-code machine learning library in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pycaret/pycaret) (👨‍💻 72 · 🔀 1.1K · 📥 520 · 📦 1.8K · 📋 1.3K - 15% open · ⏱️ 03.02.2022):

	```
	git clone https://github.com/pycaret/pycaret
	```
- [PyPi](https://pypi.org/project/pycaret) (📥 320K / month · 📦 12 · ⏱️ 12.01.2022):
	```
	pip install pycaret
	```
- [Conda](https://anaconda.org/conda-forge/pycaret) (📥 7.2K · ⏱️ 12.01.2022):
	```
	conda install -c conda-forge pycaret
	```
</details>
<details><summary><b><a href="https://github.com/iterative/dvc">DVC</a></b> (🥇36 ·  ⭐ 9.2K) - Data Version Control | Git for Data & Models | ML Experiments Management. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/iterative/dvc) (👨‍💻 260 · 🔀 880 · 📥 60K · 📋 3.5K - 17% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/iterative/dvc
	```
- [PyPi](https://pypi.org/project/dvc) (📥 340K / month · 📦 46 · ⏱️ 22.12.2021):
	```
	pip install dvc
	```
- [Conda](https://anaconda.org/conda-forge/dvc) (📥 980K · ⏱️ 25.12.2021):
	```
	conda install -c conda-forge dvc
	```
</details>
<details><summary><b><a href="https://github.com/aws/sagemaker-python-sdk">SageMaker SDK</a></b> (🥇36 ·  ⭐ 1.6K) - A library for training and deploying machine learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/aws/sagemaker-python-sdk) (👨‍💻 240 · 🔀 740 · 📦 1.1K · 📋 970 - 33% open · ⏱️ 07.02.2022):

	```
	git clone https://github.com/aws/sagemaker-python-sdk
	```
- [PyPi](https://pypi.org/project/sagemaker) (📥 2.7M / month · 📦 44 · ⏱️ 08.02.2022):
	```
	pip install sagemaker
	```
- [Conda](https://anaconda.org/conda-forge/sagemaker-python-sdk) (📥 230K · ⏱️ 08.02.2022):
	```
	conda install -c conda-forge sagemaker-python-sdk
	```
</details>
<details><summary><b><a href="https://github.com/wandb/client">wandb client</a></b> (🥈35 ·  ⭐ 3.7K) - A tool for visualizing and tracking your machine learning.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wandb/client) (👨‍💻 100 · 🔀 290 · 📋 1.7K - 21% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/wandb/client
	```
- [PyPi](https://pypi.org/project/wandb) (📥 650K / month · 📦 200 · ⏱️ 01.02.2022):
	```
	pip install wandb
	```
- [Conda](https://anaconda.org/conda-forge/wandb) (📥 43K · ⏱️ 02.02.2022):
	```
	conda install -c conda-forge wandb
	```
</details>
<details><summary><b><a href="https://github.com/lanpa/tensorboardX">tensorboardX</a></b> (🥈34 ·  ⭐ 7.2K) - tensorboard for pytorch (and chainer, mxnet, numpy, ...). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lanpa/tensorboardX) (👨‍💻 70 · 🔀 840 · 📥 340 · 📦 17K · 📋 440 - 16% open · ⏱️ 06.02.2022):

	```
	git clone https://github.com/lanpa/tensorboardX
	```
- [PyPi](https://pypi.org/project/tensorboardX) (📥 660K / month · 📦 860 · ⏱️ 21.11.2021):
	```
	pip install tensorboardX
	```
- [Conda](https://anaconda.org/conda-forge/tensorboardx) (📥 640K · ⏱️ 10.08.2021):
	```
	conda install -c conda-forge tensorboardx
	```
</details>
<details><summary><b><a href="https://github.com/Azure/MachineLearningNotebooks">AzureML SDK</a></b> (🥈34 ·  ⭐ 2.8K) - Python notebooks with ML and deep learning examples with Azure.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Azure/MachineLearningNotebooks) (👨‍💻 59 · 🔀 2K · 📥 430 · 📋 1.2K - 16% open · ⏱️ 02.02.2022):

	```
	git clone https://github.com/Azure/MachineLearningNotebooks
	```
- [PyPi](https://pypi.org/project/azureml-sdk) (📥 1.5M / month · 📦 45 · ⏱️ 24.01.2022):
	```
	pip install azureml-sdk
	```
</details>
<details><summary><b><a href="https://github.com/snakemake/snakemake">snakemake</a></b> (🥈34 ·  ⭐ 1.2K) - This is the development home of the workflow management system.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/snakemake/snakemake) (👨‍💻 240 · 🔀 290 · 📦 1K · 📋 830 - 63% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/snakemake/snakemake
	```
- [PyPi](https://pypi.org/project/snakemake) (📥 70K / month · 📦 200 · ⏱️ 09.02.2022):
	```
	pip install snakemake
	```
- [Conda](https://anaconda.org/bioconda/snakemake) (📥 380K · ⏱️ 10.02.2022):
	```
	conda install -c bioconda snakemake
	```
</details>
<details><summary><b><a href="https://github.com/allegroai/clearml">ClearML</a></b> (🥈33 ·  ⭐ 3K) - ClearML - Auto-Magical CI/CD to streamline your ML workflow... <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/allegroai/clearml) (👨‍💻 46 · 🔀 410 · 📥 380 · 📦 190 · 📋 460 - 36% open · ⏱️ 07.02.2022):

	```
	git clone https://github.com/allegroai/clearml
	```
- [PyPi](https://pypi.org/project/clearml) (📥 62K / month · 📦 4 · ⏱️ 07.02.2022):
	```
	pip install clearml
	```
- [Docker Hub](https://hub.docker.com/r/allegroai/trains) (📥 30K · ⏱️ 05.10.2020):
	```
	docker pull allegroai/trains
	```
</details>
<details><summary><b><a href="https://github.com/Netflix/metaflow">Metaflow</a></b> (🥈32 ·  ⭐ 5.3K) - Build and manage real-life data science projects with ease!. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Netflix/metaflow) (👨‍💻 47 · 🔀 460 · 📦 240 · 📋 420 - 53% open · ⏱️ 03.02.2022):

	```
	git clone https://github.com/Netflix/metaflow
	```
- [PyPi](https://pypi.org/project/metaflow) (📥 45K / month · 📦 5 · ⏱️ 26.01.2022):
	```
	pip install metaflow
	```
- [Conda](https://anaconda.org/conda-forge/metaflow) (📥 31K · ⏱️ 26.01.2022):
	```
	conda install -c conda-forge metaflow
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/VisualDL">VisualDL</a></b> (🥈31 ·  ⭐ 4.3K) - Deep Learning Visualization Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/VisualDL) (👨‍💻 31 · 🔀 580 · 📥 160 · 📦 960 · 📋 390 - 15% open · ⏱️ 30.12.2021):

	```
	git clone https://github.com/PaddlePaddle/VisualDL
	```
- [PyPi](https://pypi.org/project/visualdl) (📥 54K / month · 📦 23 · ⏱️ 06.01.2022):
	```
	pip install visualdl
	```
</details>
<details><summary><b><a href="https://github.com/catalyst-team/catalyst">Catalyst</a></b> (🥈31 ·  ⭐ 2.8K) - Accelerated deep learning R&D. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/catalyst-team/catalyst) (👨‍💻 100 · 🔀 350 · 📦 470 · 📋 330 - 1% open · ⏱️ 07.02.2022):

	```
	git clone https://github.com/catalyst-team/catalyst
	```
- [PyPi](https://pypi.org/project/catalyst) (📥 11K / month · 📦 29 · ⏱️ 07.02.2022):
	```
	pip install catalyst
	```
</details>
<details><summary><b><a href="https://github.com/aimhubio/aim">aim</a></b> (🥈31 ·  ⭐ 2.1K) - Aim an easy-to-use and performant open-source experiment tracker. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/aimhubio/aim) (👨‍💻 27 · 🔀 120 · 📦 52 · 📋 330 - 33% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/aimhubio/aim
	```
- [PyPi](https://pypi.org/project/aim) (📥 12K / month · 📦 2 · ⏱️ 04.02.2022):
	```
	pip install aim
	```
- [Conda](https://anaconda.org/conda-forge/aim) (📥 7.1K · ⏱️ 15.10.2021):
	```
	conda install -c conda-forge aim
	```
</details>
<details><summary><b><a href="https://github.com/IDSIA/sacred">sacred</a></b> (🥈29 ·  ⭐ 3.7K) - Sacred is a tool to help you configure, organize, log and reproduce.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/IDSIA/sacred) (👨‍💻 96 · 🔀 340 · 📦 1.2K · 📋 520 - 18% open · ⏱️ 26.01.2022):

	```
	git clone https://github.com/IDSIA/sacred
	```
- [PyPi](https://pypi.org/project/sacred) (📥 25K / month · 📦 100 · ⏱️ 14.12.2020):
	```
	pip install sacred
	```
- [Conda](https://anaconda.org/conda-forge/sacred) (📥 130 · ⏱️ 14.11.2021):
	```
	conda install -c conda-forge sacred
	```
</details>
<details><summary><b><a href="https://github.com/Kaggle/kaggle-api">kaggle</a></b> (🥉28 ·  ⭐ 4.6K · 💤) - Official Kaggle API. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Kaggle/kaggle-api) (👨‍💻 36 · 🔀 880 · 📋 340 - 56% open · ⏱️ 15.03.2021):

	```
	git clone https://github.com/Kaggle/kaggle-api
	```
- [PyPi](https://pypi.org/project/kaggle) (📥 130K / month · 📦 320 · ⏱️ 13.03.2021):
	```
	pip install kaggle
	```
- [Conda](https://anaconda.org/conda-forge/kaggle) (📥 77K · ⏱️ 17.12.2021):
	```
	conda install -c conda-forge kaggle
	```
</details>
<details><summary><b><a href="https://github.com/google/ml-metadata">ml-metadata</a></b> (🥉28 ·  ⭐ 430) - For recording and retrieving metadata associated with ML.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/ml-metadata) (👨‍💻 13 · 🔀 87 · 📥 1.7K · 📦 180 · 📋 82 - 26% open · ⏱️ 25.01.2022):

	```
	git clone https://github.com/google/ml-metadata
	```
- [PyPi](https://pypi.org/project/ml-metadata) (📥 450K / month · 📦 18 · ⏱️ 21.01.2022):
	```
	pip install ml-metadata
	```
</details>
<details><summary><b><a href="https://github.com/stared/livelossplot">livelossplot</a></b> (🥉25 ·  ⭐ 1.2K) - Live training loss plot in Jupyter Notebook for Keras,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/stared/livelossplot) (👨‍💻 17 · 🔀 140 · 📦 720 · 📋 74 - 5% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/stared/livelossplot
	```
- [PyPi](https://pypi.org/project/livelossplot) (📥 64K / month · 📦 8 · ⏱️ 03.02.2021):
	```
	pip install livelossplot
	```
</details>
<details><summary><b><a href="https://github.com/labmlai/labml">Labml</a></b> (🥉25 ·  ⭐ 1K) - Monitor deep learning model training and hardware usage from your mobile phone. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/labmlai/labml) (👨‍💻 6 · 🔀 71 · 📦 42 · 📋 25 - 52% open · ⏱️ 05.02.2022):

	```
	git clone https://github.com/labmlai/labml
	```
- [PyPi](https://pypi.org/project/labml) (📥 7.6K / month · 📦 6 · ⏱️ 18.01.2022):
	```
	pip install labml
	```
</details>
<details><summary><b><a href="https://github.com/guildai/guildai">Guild AI</a></b> (🥉25 ·  ⭐ 660) - Experiment tracking, ML developer tools. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/guildai/guildai) (👨‍💻 18 · 🔀 59 · 📦 42 · 📋 300 - 38% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/guildai/guildai
	```
- [PyPi](https://pypi.org/project/guildai) (📥 3.8K / month · ⏱️ 07.02.2022):
	```
	pip install guildai
	```
</details>
<details><summary><b><a href="https://github.com/instacart/lore">lore</a></b> (🥉22 ·  ⭐ 1.5K) - Lore makes machine learning approachable for Software Engineers and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/instacart/lore) (👨‍💻 23 · 🔀 130 · 📦 17 · 📋 44 - 59% open · ⏱️ 02.02.2022):

	```
	git clone https://github.com/instacart/lore
	```
- [PyPi](https://pypi.org/project/lore) (📥 2.5K / month · 📦 1 · ⏱️ 02.02.2022):
	```
	pip install lore
	```
</details>
<details><summary><b><a href="https://github.com/studioml/studio">Studio.ml</a></b> (🥉22 ·  ⭐ 370) - Studio: Simplify and expedite model building process. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/studioml/studio) (👨‍💻 21 · 🔀 52 · 📦 5 · 📋 250 - 22% open · ⏱️ 14.09.2021):

	```
	git clone https://github.com/studioml/studio
	```
- [PyPi](https://pypi.org/project/studioml) (📥 710 / month · ⏱️ 14.09.2021):
	```
	pip install studioml
	```
</details>
<details><summary><b><a href="https://github.com/MrPowers/quinn">quinn</a></b> (🥉19 ·  ⭐ 310 · 💤) - pyspark methods to enhance developer productivity. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/MrPowers/quinn) (👨‍💻 6 · 🔀 40 · 📋 26 - 65% open · ⏱️ 09.02.2021):

	```
	git clone https://github.com/MrPowers/quinn
	```
- [PyPi](https://pypi.org/project/quinn) (📥 460K / month · 📦 4 · ⏱️ 06.02.2021):
	```
	pip install quinn
	```
</details>
<details><summary><b><a href="https://github.com/replicate/keepsake">keepsake</a></b> (🥉18 ·  ⭐ 1.5K · 💤) - Version control for machine learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/replicate/keepsake) (👨‍💻 16 · 🔀 60 · 📋 190 - 65% open · ⏱️ 07.05.2021):

	```
	git clone https://github.com/replicate/keepsake
	```
- [PyPi](https://pypi.org/project/keepsake) (📥 840 / month · ⏱️ 11.03.2021):
	```
	pip install keepsake
	```
</details>
<details><summary>Show 14 hidden projects...</summary>

- <b><a href="https://github.com/EducationalTestingService/skll">SKLL</a></b> (🥉25 ·  ⭐ 530) - SciKit-Learn Laboratory (SKLL) makes it easy to run machine.. <code><a href="https://tldrlegal.com/search?q=BSD-1-Clause">❗️BSD-1-Clause</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/huggingface/knockknock">knockknock</a></b> (🥉23 ·  ⭐ 2.4K · 💀) - Knock Knock: Get notified when your training ends with only two.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/pytorch/tnt">TNT</a></b> (🥉23 ·  ⭐ 1.4K · 💀) - Simple tools for logging and visualizing, loading and training. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/microsoft/tensorwatch">TensorWatch</a></b> (🥉21 ·  ⭐ 3.2K · 💀) - Debugging, monitoring and visualization for Python Machine.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/waleedka/hiddenlayer">hiddenlayer</a></b> (🥉21 ·  ⭐ 1.6K · 💀) - Neural network graphs and training metrics for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/TeamHG-Memex/tensorboard_logger">TensorBoard Logger</a></b> (🥉21 ·  ⭐ 620 · 💀) - Log TensorBoard events without touching TensorFlow. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/m3dev/gokart">gokart</a></b> (🥉21 ·  ⭐ 230) - Gokart solves reproducibility, task dependencies, constraints of good code,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/awslabs/mxboard">MXBoard</a></b> (🥉20 ·  ⭐ 330 · 💀) - Logging MXNet data for visualization in TensorBoard. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/gradsflow/chitra">chitra</a></b> (🥉19 ·  ⭐ 180 · ➕) - A multi-functional library for full-stack Deep Learning... <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/datmo/datmo">datmo</a></b> (🥉18 ·  ⭐ 340 · 💀) - Open source production model management tool for data scientists. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/minerva-ml/steppy">steppy</a></b> (🥉16 ·  ⭐ 130 · 💀) - Lightweight, Python library for fast and reproducible experimentation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/google/caliban">caliban</a></b> (🥉14 ·  ⭐ 410 · 💀) - Research workflows made easy, locally and in the Cloud. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/ModelChimp/modelchimp">ModelChimp</a></b> (🥉13 ·  ⭐ 120) - Experiment tracking for machine and deep learning projects. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/jrieke/traintool">traintool</a></b> (🥉9 ·  ⭐ 9 · 💤) - Train off-the-shelf machine learning models in one.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Model Serialization & Deployment

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries to serialize models to files, convert between a variety of model formats, and optimize models for deployment._

<details><summary><b><a href="https://github.com/onnx/onnx">onnx</a></b> (🥇41 ·  ⭐ 12K) - Open standard for machine learning interoperability. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/onnx/onnx) (👨‍💻 220 · 🔀 2.3K · 📥 17K · 📦 5.5K · 📋 1.8K - 26% open · ⏱️ 07.02.2022):

	```
	git clone https://github.com/onnx/onnx
	```
- [PyPi](https://pypi.org/project/onnx) (📥 1.4M / month · 📦 320 · ⏱️ 26.10.2021):
	```
	pip install onnx
	```
- [Conda](https://anaconda.org/conda-forge/onnx) (📥 350K · ⏱️ 14.12.2021):
	```
	conda install -c conda-forge onnx
	```
</details>
<details><summary><b><a href="https://github.com/apple/coremltools">Core ML Tools</a></b> (🥇31 ·  ⭐ 2.5K) - Core ML tools contain supporting tools for Core ML model.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/apple/coremltools) (👨‍💻 120 · 🔀 390 · 📥 4K · 📦 760 · 📋 870 - 36% open · ⏱️ 21.01.2022):

	```
	git clone https://github.com/apple/coremltools
	```
- [PyPi](https://pypi.org/project/coremltools) (📥 95K / month · 📦 140 · ⏱️ 09.11.2021):
	```
	pip install coremltools
	```
- [Conda](https://anaconda.org/conda-forge/coremltools) (📥 27K · ⏱️ 15.10.2021):
	```
	conda install -c conda-forge coremltools
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/serve">TorchServe</a></b> (🥈30 ·  ⭐ 2.4K) - Model Serving on PyTorch. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/serve) (👨‍💻 95 · 🔀 450 · 📥 950 · 📋 790 - 16% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/pytorch/serve
	```
- [PyPi](https://pypi.org/project/torchserve) (📥 11K / month · 📦 8 · ⏱️ 29.12.2021):
	```
	pip install torchserve
	```
- [Conda](https://anaconda.org/pytorch/torchserve) (📥 19K · ⏱️ 29.12.2021):
	```
	conda install -c pytorch torchserve
	```
- [Docker Hub](https://hub.docker.com/r/pytorch/torchserve) (📥 970K · ⭐ 11 · ⏱️ 29.12.2021):
	```
	docker pull pytorch/torchserve
	```
</details>
<details><summary><b><a href="https://github.com/huggingface/huggingface_hub">huggingface_hub</a></b> (🥈29 ·  ⭐ 330) - All the open source things related to the Hugging Face Hub. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/huggingface/huggingface_hub) (👨‍💻 55 · 🔀 71 · 📋 210 - 48% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/huggingface/huggingface_hub
	```
- [PyPi](https://pypi.org/project/huggingface_hub) (📥 2.5M / month · 📦 51 · ⏱️ 11.01.2022):
	```
	pip install huggingface_hub
	```
- [Conda](https://anaconda.org/conda-forge/huggingface_hub) (📥 27K · ⏱️ 12.01.2022):
	```
	conda install -c conda-forge huggingface_hub
	```
</details>
<details><summary><b><a href="https://github.com/openai/triton">triton</a></b> (🥈28 ·  ⭐ 3.5K · ➕) - Development repository for the Triton language and compiler. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/openai/triton) (👨‍💻 34 · 🔀 260 · 📦 66 · 📋 180 - 34% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/openai/triton
	```
- [PyPi](https://pypi.org/project/triton) (📥 52K / month · 📦 2 · ⏱️ 10.02.2022):
	```
	pip install triton
	```
</details>
<details><summary><b><a href="https://github.com/cortexlabs/cortex">cortex</a></b> (🥈27 ·  ⭐ 7.7K) - Production infrastructure for machine learning at scale. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/cortexlabs/cortex) (👨‍💻 24 · 🔀 590 · 📋 1.1K - 9% open · ⏱️ 06.02.2022):

	```
	git clone https://github.com/cortexlabs/cortex
	```
- [PyPi](https://pypi.org/project/cortex) (📥 1.2K / month · 📦 1 · ⏱️ 10.01.2022):
	```
	pip install cortex
	```
</details>
<details><summary><b><a href="https://github.com/bentoml/BentoML">BentoML</a></b> (🥈27 ·  ⭐ 3.2K · 📉) - The Unified Model Serving Framework. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bentoml/BentoML) (👨‍💻 98 · 🔀 370 · 📥 930 · 📋 530 - 8% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/bentoml/BentoML
	```
- [PyPi](https://pypi.org/project/bentoml) (📥 13K / month · 📦 2 · ⏱️ 28.01.2022):
	```
	pip install bentoml
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/hummingbird">Hummingbird</a></b> (🥈27 ·  ⭐ 2.7K) - Hummingbird compiles trained ML models into tensor computation for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/hummingbird) (👨‍💻 28 · 🔀 210 · 📥 160 · 📦 20 · 📋 240 - 22% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/microsoft/hummingbird
	```
- [PyPi](https://pypi.org/project/hummingbird-ml) (📥 2K / month · ⏱️ 14.12.2021):
	```
	pip install hummingbird-ml
	```
- [Conda](https://anaconda.org/conda-forge/hummingbird-ml) (📥 5.2K · ⏱️ 14.12.2021):
	```
	conda install -c conda-forge hummingbird-ml
	```
</details>
<details><summary><b><a href="https://github.com/BayesWitnesses/m2cgen">m2cgen</a></b> (🥉25 ·  ⭐ 2K) - Transform ML models into a native code (Java, C, Python, Go, JavaScript,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/BayesWitnesses/m2cgen) (👨‍💻 12 · 🔀 170 · 📦 15 · 📋 100 - 35% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/BayesWitnesses/m2cgen
	```
- [PyPi](https://pypi.org/project/m2cgen) (📥 58K / month · ⏱️ 18.09.2020):
	```
	pip install m2cgen
	```
</details>
<details><summary><b><a href="https://github.com/gmalivenko/pytorch2keras">pytorch2keras</a></b> (🥉18 ·  ⭐ 770) - PyTorch to Keras model convertor. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gmalivenko/pytorch2keras) (👨‍💻 13 · 🔀 130 · 📦 28 · 📋 120 - 44% open · ⏱️ 06.08.2021):

	```
	git clone https://github.com/gmalivenko/pytorch2keras
	```
- [PyPi](https://pypi.org/project/pytorch2keras) (📥 730 / month · 📦 1 · ⏱️ 14.05.2020):
	```
	pip install pytorch2keras
	```
</details>
<details><summary>Show 5 hidden projects...</summary>

- <b><a href="https://github.com/microsoft/MMdnn">mmdnn</a></b> (🥉25 ·  ⭐ 5.5K · 💀) - MMdnn is a set of tools to help users inter-operate among different deep.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/larq/compute-engine">Larq Compute Engine</a></b> (🥉21 ·  ⭐ 180) - Highly optimized inference engine for Binarized.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/nok/sklearn-porter">sklearn-porter</a></b> (🥉20 ·  ⭐ 1.1K · 💀) - Transpile trained scikit-learn estimators to C, Java,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/riga/tfdeploy">tfdeploy</a></b> (🥉16 ·  ⭐ 350 · 💀) - Deploy tensorflow graphs for fast evaluation and export to.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/backprop-ai/backprop">backprop</a></b> (🥉13 ·  ⭐ 220 · 💤) - Backprop makes it simple to use, finetune, and deploy state-of-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Model Interpretability

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries to visualize, explain, debug, evaluate, and interpret machine learning models._

<details><summary><b><a href="https://github.com/slundberg/shap">shap</a></b> (🥇39 ·  ⭐ 15K) - A game theoretic approach to explain the output of any machine learning model. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/slundberg/shap) (👨‍💻 160 · 🔀 2.3K · 📦 4.5K · 📋 1.8K - 68% open · ⏱️ 04.12.2021):

	```
	git clone https://github.com/slundberg/shap
	```
- [PyPi](https://pypi.org/project/shap) (📥 4.6M / month · 📦 220 · ⏱️ 20.10.2021):
	```
	pip install shap
	```
- [Conda](https://anaconda.org/conda-forge/shap) (📥 840K · ⏱️ 23.01.2022):
	```
	conda install -c conda-forge shap
	```
</details>
<details><summary><b><a href="https://github.com/marcotcr/lime">Lime</a></b> (🥇33 ·  ⭐ 9.6K · 💤) - Lime: Explaining the predictions of any machine learning classifier. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/marcotcr/lime) (👨‍💻 61 · 🔀 1.5K · 📦 1.9K · 📋 550 - 4% open · ⏱️ 29.07.2021):

	```
	git clone https://github.com/marcotcr/lime
	```
- [PyPi](https://pypi.org/project/lime) (📥 740K / month · 📦 110 · ⏱️ 26.06.2020):
	```
	pip install lime
	```
- [Conda](https://anaconda.org/conda-forge/lime) (📥 92K · ⏱️ 28.06.2020):
	```
	conda install -c conda-forge lime
	```
</details>
<details><summary><b><a href="https://github.com/arviz-devs/arviz">arviz</a></b> (🥇33 ·  ⭐ 1.2K) - Exploratory analysis of Bayesian models with Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/arviz-devs/arviz) (👨‍💻 110 · 🔀 260 · 📥 110 · 📦 1.9K · 📋 750 - 25% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/arviz-devs/arviz
	```
- [PyPi](https://pypi.org/project/arviz) (📥 320K / month · 📦 71 · ⏱️ 03.10.2021):
	```
	pip install arviz
	```
- [Conda](https://anaconda.org/conda-forge/arviz) (📥 620K · ⏱️ 03.10.2021):
	```
	conda install -c conda-forge arviz
	```
</details>
<details><summary><b><a href="https://github.com/interpretml/interpret">InterpretML</a></b> (🥇32 ·  ⭐ 4.5K) - Fit interpretable models. Explain blackbox machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/interpretml/interpret) (👨‍💻 28 · 🔀 560 · 📦 160 · 📋 270 - 32% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/interpretml/interpret
	```
- [PyPi](https://pypi.org/project/interpret) (📥 88K / month · 📦 8 · ⏱️ 23.09.2021):
	```
	pip install interpret
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/captum">Captum</a></b> (🥇31 ·  ⭐ 2.9K) - Model interpretability and understanding for PyTorch. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/captum) (👨‍💻 78 · 🔀 300 · 📦 390 · 📋 330 - 23% open · ⏱️ 27.01.2022):

	```
	git clone https://github.com/pytorch/captum
	```
- [PyPi](https://pypi.org/project/captum) (📥 33K / month · 📦 17 · ⏱️ 02.11.2021):
	```
	pip install captum
	```
- [Conda](https://anaconda.org/conda-forge/captum) (📥 180 · ⏱️ 27.01.2022):
	```
	conda install -c conda-forge captum
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/model-analysis">Model Analysis</a></b> (🥇31 ·  ⭐ 1.1K) - Model analysis tools for TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/model-analysis) (👨‍💻 37 · 🔀 240 · 📋 74 - 36% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/tensorflow/model-analysis
	```
- [PyPi](https://pypi.org/project/tensorflow-model-analysis) (📥 5.4M / month · 📦 21 · ⏱️ 24.01.2022):
	```
	pip install tensorflow-model-analysis
	```
</details>
<details><summary><b><a href="https://github.com/bmabey/pyLDAvis">pyLDAvis</a></b> (🥈30 ·  ⭐ 1.6K · 💤) - Python library for interactive topic model visualization... <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/bmabey/pyLDAvis) (👨‍💻 32 · 🔀 320 · 📦 3.1K · 📋 160 - 52% open · ⏱️ 24.03.2021):

	```
	git clone https://github.com/bmabey/pyLDAvis
	```
- [PyPi](https://pypi.org/project/pyldavis) (📥 610K / month · 📦 130 · ⏱️ 24.03.2021):
	```
	pip install pyldavis
	```
- [Conda](https://anaconda.org/conda-forge/pyldavis) (📥 34K · ⏱️ 24.03.2021):
	```
	conda install -c conda-forge pyldavis
	```
</details>
<details><summary><b><a href="https://github.com/MAIF/shapash">shapash</a></b> (🥈29 ·  ⭐ 1.6K) - Shapash makes Machine Learning models transparent and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/MAIF/shapash) (👨‍💻 31 · 🔀 210 · 📦 61 · 📋 98 - 12% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/MAIF/shapash
	```
- [PyPi](https://pypi.org/project/shapash) (📥 21K / month · ⏱️ 14.01.2022):
	```
	pip install shapash
	```
</details>
<details><summary><b><a href="https://github.com/SeldonIO/alibi">Alibi</a></b> (🥈29 ·  ⭐ 1.5K) - Algorithms for explaining machine learning models. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/SeldonIO/alibi) (👨‍💻 18 · 🔀 180 · 📦 140 · 📋 260 - 41% open · ⏱️ 04.02.2022):

	```
	git clone https://github.com/SeldonIO/alibi
	```
- [PyPi](https://pypi.org/project/alibi) (📥 45K / month · 📦 22 · ⏱️ 28.01.2022):
	```
	pip install alibi
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/dowhy">DoWhy</a></b> (🥈28 ·  ⭐ 3.6K) - DoWhy is a Python library for causal inference that supports explicit.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/dowhy) (👨‍💻 48 · 🔀 560 · 📥 24 · 📦 83 · 📋 180 - 29% open · ⏱️ 06.02.2022):

	```
	git clone https://github.com/Microsoft/dowhy
	```
- [PyPi](https://pypi.org/project/dowhy) (📥 99K / month · 📦 4 · ⏱️ 10.01.2022):
	```
	pip install dowhy
	```
- [Conda](https://anaconda.org/conda-forge/dowhy) (📥 4.3K · ⏱️ 22.01.2022):
	```
	conda install -c conda-forge dowhy
	```
</details>
<details><summary><b><a href="https://github.com/parrt/dtreeviz">dtreeviz</a></b> (🥈28 ·  ⭐ 2K) - A python library for decision tree visualization and model interpretation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/parrt/dtreeviz) (👨‍💻 17 · 🔀 250 · 📦 300 · 📋 120 - 17% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/parrt/dtreeviz
	```
- [PyPi](https://pypi.org/project/dtreeviz) (📥 75K / month · 📦 14 · ⏱️ 09.02.2022):
	```
	pip install dtreeviz
	```
- [Conda](https://anaconda.org/conda-forge/dtreeviz) (📥 7.2K · ⏱️ 03.12.2021):
	```
	conda install -c conda-forge dtreeviz
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/lucid">Lucid</a></b> (🥈26 ·  ⭐ 4.4K · 💤) - A collection of infrastructure and tools for research in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/lucid) (👨‍💻 40 · 🔀 590 · 📦 600 · 📋 170 - 41% open · ⏱️ 19.03.2021):

	```
	git clone https://github.com/tensorflow/lucid
	```
- [PyPi](https://pypi.org/project/lucid) (📥 1.5K / month · 📦 6 · ⏱️ 19.03.2021):
	```
	pip install lucid
	```
</details>
<details><summary><b><a href="https://github.com/DistrictDataLabs/yellowbrick">yellowbrick</a></b> (🥈26 ·  ⭐ 3.5K) - Visual analysis and diagnostic tools to facilitate machine.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/DistrictDataLabs/yellowbrick) (👨‍💻 100 · 🔀 500 · 📋 640 - 14% open · ⏱️ 05.01.2022):

	```
	git clone https://github.com/DistrictDataLabs/yellowbrick
	```
- [PyPi](https://pypi.org/project/yellowbrick) (📥 350K / month · 📦 47 · ⏱️ 13.02.2021):
	```
	pip install yellowbrick
	```
- [Conda](https://anaconda.org/conda-forge/yellowbrick) (📥 20K · ⏱️ 06.05.2021):
	```
	conda install -c conda-forge yellowbrick
	```
</details>
<details><summary><b><a href="https://github.com/fairlearn/fairlearn">fairlearn</a></b> (🥈26 ·  ⭐ 1.2K) - A Python package to assess and improve fairness of machine.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/fairlearn/fairlearn) (👨‍💻 63 · 🔀 280 · 📋 330 - 40% open · ⏱️ 31.01.2022):

	```
	git clone https://github.com/fairlearn/fairlearn
	```
- [PyPi](https://pypi.org/project/fairlearn) (📥 56K / month · 📦 9 · ⏱️ 07.07.2021):
	```
	pip install fairlearn
	```
- [Conda](https://anaconda.org/conda-forge/fairlearn) (📥 17K · ⏱️ 07.07.2021):
	```
	conda install -c conda-forge fairlearn
	```
</details>
<details><summary><b><a href="https://github.com/Trusted-AI/AIF360">Fairness 360</a></b> (🥈25 ·  ⭐ 1.6K) - A comprehensive set of fairness metrics for datasets and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Trusted-AI/AIF360) (👨‍💻 48 · 🔀 510 · 📦 140 · 📋 120 - 51% open · ⏱️ 21.01.2022):

	```
	git clone https://github.com/Trusted-AI/AIF360
	```
- [PyPi](https://pypi.org/project/aif360) (📥 7.9K / month · 📦 8 · ⏱️ 04.03.2021):
	```
	pip install aif360
	```
- [Conda](https://anaconda.org/conda-forge/aif360) (📥 1.5K · ⏱️ 29.09.2021):
	```
	conda install -c conda-forge aif360
	```
</details>
<details><summary><b><a href="https://github.com/marcotcr/checklist">checklist</a></b> (🥈25 ·  ⭐ 1.6K) - Beyond Accuracy: Behavioral Testing of NLP models with CheckList. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/marcotcr/checklist) (👨‍💻 12 · 🔀 150 · 📦 80 · 📋 92 - 13% open · ⏱️ 28.09.2021):

	```
	git clone https://github.com/marcotcr/checklist
	```
- [PyPi](https://pypi.org/project/checklist) (📥 18K / month · 📦 3 · ⏱️ 24.05.2021):
	```
	pip install checklist
	```
- [Conda](https://anaconda.org/conda-forge/checklist) (📥 2.3K · ⏱️ 15.07.2021):
	```
	conda install -c conda-forge checklist
	```
</details>
<details><summary><b><a href="https://github.com/quantumblacklabs/causalnex">CausalNex</a></b> (🥈25 ·  ⭐ 1.4K) - A Python library that helps data scientists to infer.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/quantumblacklabs/causalnex) (👨‍💻 22 · 🔀 160 · 📦 38 · 📋 100 - 14% open · ⏱️ 11.11.2021):

	```
	git clone https://github.com/quantumblacklabs/causalnex
	```
- [PyPi](https://pypi.org/project/causalnex) (📥 2.2K / month · 📦 2 · ⏱️ 11.11.2021):
	```
	pip install causalnex
	```
</details>
<details><summary><b><a href="https://github.com/oegedijk/explainerdashboard">explainerdashboard</a></b> (🥈25 ·  ⭐ 1.1K) - Quickly build Explainable AI dashboards that show the inner.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/oegedijk/explainerdashboard) (👨‍💻 12 · 🔀 130 · 📦 58 · 📋 140 - 8% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/oegedijk/explainerdashboard
	```
- [PyPi](https://pypi.org/project/explainerdashboard) (📥 16K / month · 📦 2 · ⏱️ 10.02.2022):
	```
	pip install explainerdashboard
	```
- [Conda](https://anaconda.org/conda-forge/explainerdashboard) (📥 14K · ⏱️ 04.08.2021):
	```
	conda install -c conda-forge explainerdashboard
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/responsible-ai-toolbox">responsible-ai-widgets</a></b> (🥈25 ·  ⭐ 420) - This project provides responsible AI user interfaces.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/microsoft/responsible-ai-toolbox) (👨‍💻 24 · 🔀 98 · 📦 20 · 📋 240 - 26% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/microsoft/responsible-ai-toolbox
	```
- [PyPi](https://pypi.org/project/raiwidgets) (📥 5.8K / month · 📦 2 · ⏱️ 05.01.2022):
	```
	pip install raiwidgets
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/lit">LIT</a></b> (🥉24 ·  ⭐ 2.8K) - The Language Interpretability Tool: Interactively analyze NLP models for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PAIR-code/lit) (👨‍💻 18 · 🔀 280 · 📦 7 · 📋 130 - 50% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/PAIR-code/lit
	```
- [PyPi](https://pypi.org/project/lit-nlp) (📥 1.1K / month · ⏱️ 21.12.2021):
	```
	pip install lit-nlp
	```
- [Conda](https://anaconda.org/conda-forge/lit-nlp) (📥 32K · ⏱️ 09.11.2021):
	```
	conda install -c conda-forge lit-nlp
	```
</details>
<details><summary><b><a href="https://github.com/Trusted-AI/AIX360">Explainability 360</a></b> (🥉23 ·  ⭐ 1.1K) - Interpretability and explainability of data and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Trusted-AI/AIX360) (👨‍💻 29 · 🔀 220 · 📦 37 · 📋 63 - 60% open · ⏱️ 12.10.2021):

	```
	git clone https://github.com/Trusted-AI/AIX360
	```
- [PyPi](https://pypi.org/project/aix360) (📥 1.5K / month · 📦 1 · ⏱️ 28.10.2020):
	```
	pip install aix360
	```
</details>
<details><summary><b><a href="https://github.com/philipperemy/keract">keract</a></b> (🥉23 ·  ⭐ 960) - Layers Outputs and Gradients in Keras. Made easy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/philipperemy/keract) (👨‍💻 16 · 🔀 180 · 📦 110 · 📋 84 - 3% open · ⏱️ 24.01.2022):

	```
	git clone https://github.com/philipperemy/keract
	```
- [PyPi](https://pypi.org/project/keract) (📥 1.2K / month · 📦 5 · ⏱️ 19.06.2021):
	```
	pip install keract
	```
</details>
<details><summary><b><a href="https://github.com/jalammar/ecco">ecco</a></b> (🥉22 ·  ⭐ 1.3K) - Explain, analyze, and visualize NLP language models. Ecco creates.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jalammar/ecco) (👨‍💻 10 · 🔀 82 · 📥 12 · 📦 3 · 📋 34 - 38% open · ⏱️ 18.01.2022):

	```
	git clone https://github.com/jalammar/ecco
	```
- [PyPi](https://pypi.org/project/ecco) (📥 440 / month · 📦 1 · ⏱️ 09.01.2022):
	```
	pip install ecco
	```
- [Conda](https://anaconda.org/conda-forge/ecco) (📥 130 · ⏱️ 10.01.2022):
	```
	conda install -c conda-forge ecco
	```
</details>
<details><summary><b><a href="https://github.com/sicara/tf-explain">tf-explain</a></b> (🥉22 ·  ⭐ 900) - Interpretability Methods for tf.keras models with Tensorflow 2.x. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/sicara/tf-explain) (👨‍💻 16 · 🔀 91 · 📦 98 · 📋 90 - 43% open · ⏱️ 30.11.2021):

	```
	git clone https://github.com/sicara/tf-explain
	```
- [PyPi](https://pypi.org/project/tf-explain) (📥 2.3K / month · 📦 6 · ⏱️ 18.11.2021):
	```
	pip install tf-explain
	```
</details>
<details><summary><b><a href="https://github.com/interpretml/DiCE">DiCE</a></b> (🥉22 ·  ⭐ 770) - Generate Diverse Counterfactual Explanations for any machine.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/interpretml/DiCE) (👨‍💻 12 · 🔀 100 · 📋 100 - 46% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/interpretml/DiCE
	```
- [PyPi](https://pypi.org/project/dice-ml) (📥 34K / month · 📦 3 · ⏱️ 27.09.2021):
	```
	pip install dice-ml
	```
</details>
<details><summary><b><a href="https://github.com/andosa/treeinterpreter">TreeInterpreter</a></b> (🥉22 ·  ⭐ 700 · 💤) - Package for interpreting scikit-learns decision tree.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/andosa/treeinterpreter) (👨‍💻 11 · 🔀 130 · 📦 200 · 📋 28 - 85% open · ⏱️ 28.02.2021):

	```
	git clone https://github.com/andosa/treeinterpreter
	```
- [PyPi](https://pypi.org/project/treeinterpreter) (📥 210K / month · 📦 10 · ⏱️ 10.01.2021):
	```
	pip install treeinterpreter
	```
- [Conda](https://anaconda.org/conda-forge/treeinterpreter) (📥 970 · ⏱️ 03.10.2020):
	```
	conda install -c conda-forge treeinterpreter
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/what-if-tool">What-If Tool</a></b> (🥉22 ·  ⭐ 640) - Source code/webpage/demos for the What-If Tool. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PAIR-code/what-if-tool) (👨‍💻 20 · 🔀 120 · 📋 100 - 54% open · ⏱️ 05.01.2022):

	```
	git clone https://github.com/PAIR-code/what-if-tool
	```
- [PyPi](https://pypi.org/project/witwidget) (📥 7.5K / month · 📦 3 · ⏱️ 12.10.2021):
	```
	pip install witwidget
	```
- [Conda](https://anaconda.org/conda-forge/tensorboard-plugin-wit) (📥 850K · ⏱️ 06.01.2022):
	```
	conda install -c conda-forge tensorboard-plugin-wit
	```
- [npm](https://www.npmjs.com/package/wit-widget) (📥 3.7K / month · ⏱️ 12.10.2021):
	```
	npm install wit-widget
	```
</details>
<details><summary><b><a href="https://github.com/csinva/imodels">imodels</a></b> (🥉22 ·  ⭐ 490) - Interpretable ML package for concise, transparent, and accurate predictive.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/csinva/imodels) (👨‍💻 8 · 🔀 49 · 📦 12 · 📋 26 - 23% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/csinva/imodels
	```
- [PyPi](https://pypi.org/project/imodels) (📥 1.3K / month · ⏱️ 29.01.2022):
	```
	pip install imodels
	```
</details>
<details><summary><b><a href="https://github.com/albermax/innvestigate">iNNvestigate</a></b> (🥉20 ·  ⭐ 950) - A toolbox to iNNvestigate neural networks predictions!. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/albermax/innvestigate) (👨‍💻 19 · 🔀 200 · 📋 230 - 30% open · ⏱️ 03.08.2021):

	```
	git clone https://github.com/albermax/innvestigate
	```
- [PyPi](https://pypi.org/project/innvestigate) (📥 470 / month · 📦 1 · ⏱️ 14.11.2020):
	```
	pip install innvestigate
	```
</details>
<details><summary><b><a href="https://github.com/kundajelab/deeplift">deeplift</a></b> (🥉20 ·  ⭐ 610) - Public facing deeplift repo. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/kundajelab/deeplift) (👨‍💻 11 · 🔀 140 · 📦 54 · 📋 82 - 41% open · ⏱️ 11.11.2021):

	```
	git clone https://github.com/kundajelab/deeplift
	```
- [PyPi](https://pypi.org/project/deeplift) (📥 530 / month · 📦 4 · ⏱️ 11.11.2020):
	```
	pip install deeplift
	```
</details>
<details><summary><b><a href="https://github.com/dssg/aequitas">aequitas</a></b> (🥉20 ·  ⭐ 460 · 💤) - Bias and Fairness Audit Toolkit. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dssg/aequitas) (👨‍💻 16 · 🔀 85 · 📦 89 · 📋 58 - 63% open · ⏱️ 27.05.2021):

	```
	git clone https://github.com/dssg/aequitas
	```
- [PyPi](https://pypi.org/project/aequitas) (📥 760 / month · 📦 6 · ⏱️ 16.12.2020):
	```
	pip install aequitas
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/tcav">tcav</a></b> (🥉19 ·  ⭐ 510) - Code for the TCAV ML interpretability project. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tcav) (👨‍💻 19 · 🔀 120 · 📦 11 · 📋 60 - 11% open · ⏱️ 16.09.2021):

	```
	git clone https://github.com/tensorflow/tcav
	```
- [PyPi](https://pypi.org/project/tcav) (📥 120 / month · 📦 3 · ⏱️ 23.02.2021):
	```
	pip install tcav
	```
</details>
<details><summary><b><a href="https://github.com/edublancas/sklearn-evaluation">sklearn-evaluation</a></b> (🥉19 ·  ⭐ 320) - Machine learning model evaluation made easy: plots,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/edublancas/sklearn-evaluation) (👨‍💻 6 · 🔀 28 · 📦 38 · 📋 37 - 21% open · ⏱️ 17.10.2021):

	```
	git clone https://github.com/edublancas/sklearn-evaluation
	```
- [PyPi](https://pypi.org/project/sklearn-evaluation) (📥 1K / month · 📦 2 · ⏱️ 17.10.2021):
	```
	pip install sklearn-evaluation
	```
</details>
<details><summary><b><a href="https://github.com/EthicalML/xai">XAI</a></b> (🥉18 ·  ⭐ 770) - XAI - An eXplainability toolbox for machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/EthicalML/xai) (👨‍💻 3 · 🔀 120 · 📦 12 · 📋 9 - 22% open · ⏱️ 30.10.2021):

	```
	git clone https://github.com/EthicalML/xai
	```
- [PyPi](https://pypi.org/project/xai) (📥 240 / month · 📦 6 · ⏱️ 30.10.2021):
	```
	pip install xai
	```
</details>
<details><summary><b><a href="https://github.com/aerdem4/lofo-importance">LOFO</a></b> (🥉16 ·  ⭐ 440) - Leave One Feature Out Importance. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/aerdem4/lofo-importance) (👨‍💻 3 · 🔀 52 · 📦 7 · 📋 18 - 27% open · ⏱️ 04.10.2021):

	```
	git clone https://github.com/aerdem4/lofo-importance
	```
- [PyPi](https://pypi.org/project/lofo-importance) (📥 240 / month · ⏱️ 04.10.2021):
	```
	pip install lofo-importance
	```
</details>
<details><summary><b><a href="https://github.com/marcotcr/anchor">Anchor</a></b> (🥉15 ·  ⭐ 680) - Code for High-Precision Model-Agnostic Explanations paper. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/marcotcr/anchor) (👨‍💻 10 · 🔀 95 · 📋 69 - 26% open · ⏱️ 17.11.2021):

	```
	git clone https://github.com/marcotcr/anchor
	```
- [PyPi](https://pypi.org/project/anchor_exp) (📥 1.8K / month · ⏱️ 26.06.2020):
	```
	pip install anchor_exp
	```
</details>
<details><summary><b><a href="https://github.com/MisaOgura/flashtorch">FlashTorch</a></b> (🥉15 ·  ⭐ 640 · 💤) - Visualization toolkit for neural networks in PyTorch! Demo --. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/MisaOgura/flashtorch) (👨‍💻 2 · 🔀 80 · 📦 9 · 📋 32 - 31% open · ⏱️ 27.04.2021):

	```
	git clone https://github.com/MisaOgura/flashtorch
	```
- [PyPi](https://pypi.org/project/flashtorch) (📥 480 / month · ⏱️ 29.05.2020):
	```
	pip install flashtorch
	```
</details>
<details><summary><b><a href="https://github.com/interpretml/interpret-text">interpret-text</a></b> (🥉15 ·  ⭐ 300) - A library that incorporates state-of-the-art explainers for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/interpretml/interpret-text) (👨‍💻 17 · 🔀 54 · 📋 74 - 78% open · ⏱️ 06.12.2021):

	```
	git clone https://github.com/interpretml/interpret-text
	```
- [PyPi](https://pypi.org/project/interpret-text) (📥 91 / month · ⏱️ 07.12.2021):
	```
	pip install interpret-text
	```
</details>
<details><summary>Show 12 hidden projects...</summary>

- <b><a href="https://github.com/TeamHG-Memex/eli5">eli5</a></b> (🥈27 ·  ⭐ 2.5K · 💀) - A library for debugging/inspecting machine learning classifiers and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/raghakot/keras-vis">keras-vis</a></b> (🥈26 ·  ⭐ 2.9K · 💀) - Neural network visualization toolkit for keras. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/reiinakano/scikit-plot">scikit-plot</a></b> (🥈26 ·  ⭐ 2.2K · 💀) - An intuitive library to add plotting functionality to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/ModelOriented/DALEX">DALEX</a></b> (🥉22 ·  ⭐ 1K) - moDel Agnostic Language for Exploration and eXplanation. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/parrt/random-forest-importances">random-forest-importances</a></b> (🥉22 ·  ⭐ 490 · 💀) - Code to compute permutation and drop-column.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/oracle/Skater">Skater</a></b> (🥉20 ·  ⭐ 1K · 💀) - Python Library for Model Interpretation/Explanations. <code><a href="https://tldrlegal.com/search?q=UPL-1.0">❗️UPL-1.0</a></code>
- <b><a href="https://github.com/tensorflow/model-card-toolkit">model-card-toolkit</a></b> (🥉18 ·  ⭐ 250) - a tool that leverages rich metadata and lineage.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/tensorflow/fairness-indicators">fairness-indicators</a></b> (🥉18 ·  ⭐ 240) - Tensorflows Fairness Evaluation and Visualization.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/explainX/explainx">ExplainX.ai</a></b> (🥉15 ·  ⭐ 290 · 💤) - Explainable AI framework for data scientists. Explain & debug any.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/suinleelab/attributionpriors">Attribution Priors</a></b> (🥉12 ·  ⭐ 93 · 💤) - Tools for training explainable models using.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/SAP/contextual-ai">contextual-ai</a></b> (🥉12 ·  ⭐ 78) - Contextual AI adds explainability to different stages of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/intuit/bias-detector">bias-detector</a></b> (🥉12 ·  ⭐ 37) - Bias Detector is a python package for detecting bias in machine.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Vector Similarity Search (ANN)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for Approximate Nearest Neighbor Search and Vector Indexing/Similarity Search._

🔗&nbsp;<b><a href="https://github.com/erikbern/ann-benchmarks">ANN Benchmarks</a></b> ( ⭐ 2.8K)  - Benchmarks of approximate nearest neighbor libraries in Python.

<details><summary><b><a href="https://github.com/milvus-io/milvus">Milvus</a></b> (🥇39 ·  ⭐ 9.4K) - An open-source vector database for scalable similarity search and AI.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/milvus-io/milvus) (👨‍💻 180 · 🔀 1.3K · 📥 6.8K · 📋 4.5K - 5% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/milvus-io/milvus
	```
- [PyPi](https://pypi.org/project/pymilvus) (📥 32K / month · 📦 15 · ⏱️ 25.01.2022):
	```
	pip install pymilvus
	```
- [Docker Hub](https://hub.docker.com/r/milvusdb/milvus) (📥 800K · ⭐ 18 · ⏱️ 25.01.2022):
	```
	docker pull milvusdb/milvus
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/faiss">Faiss</a></b> (🥇34 ·  ⭐ 16K) - A library for efficient similarity search and clustering of dense vectors. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/faiss) (👨‍💻 92 · 🔀 2.5K · 📦 550 · 📋 1.7K - 10% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/facebookresearch/faiss
	```
- [PyPi](https://pypi.org/project/pymilvus) (📥 32K / month · 📦 15 · ⏱️ 25.01.2022):
	```
	pip install pymilvus
	```
- [Conda](https://anaconda.org/conda-forge/faiss) (📥 240K · ⏱️ 09.02.2022):
	```
	conda install -c conda-forge faiss
	```
</details>
<details><summary><b><a href="https://github.com/spotify/annoy">Annoy</a></b> (🥈32 ·  ⭐ 9.4K) - Approximate Nearest Neighbors in C++/Python optimized for memory usage.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/spotify/annoy) (👨‍💻 80 · 🔀 960 · 📦 1.9K · 📋 340 - 11% open · ⏱️ 03.01.2022):

	```
	git clone https://github.com/spotify/annoy
	```
- [PyPi](https://pypi.org/project/annoy) (📥 850K / month · 📦 240 · ⏱️ 18.09.2020):
	```
	pip install annoy
	```
- [Conda](https://anaconda.org/conda-forge/python-annoy) (📥 210K · ⏱️ 28.01.2022):
	```
	conda install -c conda-forge python-annoy
	```
</details>
<details><summary><b><a href="https://github.com/nmslib/hnswlib">hnswlib</a></b> (🥈30 ·  ⭐ 1.9K) - Header-only C++/python library for fast approximate nearest neighbors. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nmslib/hnswlib) (👨‍💻 54 · 🔀 360 · 📦 190 · 📋 240 - 50% open · ⏱️ 06.02.2022):

	```
	git clone https://github.com/nmslib/hnswlib
	```
- [PyPi](https://pypi.org/project/hnswlib) (📥 67K / month · 📦 20 · ⏱️ 07.02.2022):
	```
	pip install hnswlib
	```
- [Conda](https://anaconda.org/conda-forge/hnswlib) (📥 35K · ⏱️ 04.02.2021):
	```
	conda install -c conda-forge hnswlib
	```
</details>
<details><summary><b><a href="https://github.com/nmslib/nmslib">NMSLIB</a></b> (🥈29 ·  ⭐ 2.7K) - Non-Metric Space Library (NMSLIB): An efficient similarity search.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nmslib/nmslib) (👨‍💻 45 · 🔀 380 · 📦 550 · 📋 390 - 15% open · ⏱️ 19.09.2021):

	```
	git clone https://github.com/nmslib/nmslib
	```
- [PyPi](https://pypi.org/project/nmslib) (📥 110K / month · 📦 47 · ⏱️ 03.02.2021):
	```
	pip install nmslib
	```
- [Conda](https://anaconda.org/conda-forge/nmslib) (📥 47K · ⏱️ 22.11.2021):
	```
	conda install -c conda-forge nmslib
	```
</details>
<details><summary><b><a href="https://github.com/lmcinnes/pynndescent">PyNNDescent</a></b> (🥉28 ·  ⭐ 580) - A Python nearest neighbor descent for approximate nearest neighbors. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/lmcinnes/pynndescent) (👨‍💻 18 · 🔀 76 · 📦 1.2K · 📋 97 - 46% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/lmcinnes/pynndescent
	```
- [PyPi](https://pypi.org/project/pynndescent) (📥 1.1M / month · 📦 25 · ⏱️ 21.01.2022):
	```
	pip install pynndescent
	```
- [Conda](https://anaconda.org/conda-forge/pynndescent) (📥 460K · ⏱️ 22.01.2022):
	```
	conda install -c conda-forge pynndescent
	```
</details>
<details><summary><b><a href="https://github.com/yahoojapan/NGT">NGT</a></b> (🥉20 ·  ⭐ 850) - Nearest Neighbor Search with Neighborhood Graph and Tree for High-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/yahoojapan/NGT) (👨‍💻 12 · 🔀 84 · 📋 88 - 12% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/yahoojapan/NGT
	```
- [PyPi](https://pypi.org/project/ngt) (📥 17K / month · 📦 8 · ⏱️ 10.02.2022):
	```
	pip install ngt
	```
</details>
<details><summary><b><a href="https://github.com/kakao/n2">N2</a></b> (🥉18 ·  ⭐ 510 · 💤) - TOROS N2 - lightweight approximate Nearest Neighbor library which runs.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/kakao/n2) (👨‍💻 18 · 🔀 61 · 📦 22 · 📋 37 - 45% open · ⏱️ 20.05.2021):

	```
	git clone https://github.com/kakao/n2
	```
- [PyPi](https://pypi.org/project/n2) (📥 710 / month · 📦 3 · ⏱️ 16.10.2020):
	```
	pip install n2
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/plasticityai/magnitude">Magnitude</a></b> (🥉23 ·  ⭐ 1.5K · 💀) - A fast, efficient universal vector embedding utility package. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/pixelogik/NearPy">NearPy</a></b> (🥉21 ·  ⭐ 700 · 💀) - Python framework for fast (approximated) nearest neighbour search in.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/facebookresearch/pysparnn">PySparNN</a></b> (🥉11 ·  ⭐ 900 · 💀) - Approximate Nearest Neighbor Search for Sparse Data in Python!. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## Probabilistics & Statistics

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries providing capabilities for probabilistic programming/reasoning, bayesian inference, gaussian processes, or statistics._

<details><summary><b><a href="https://github.com/pymc-devs/pymc">PyMC3</a></b> (🥇38 ·  ⭐ 6.3K) - Probabilistic Programming in Python: Bayesian Modeling and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pymc-devs/pymc) (👨‍💻 360 · 🔀 1.5K · 📥 1.7K · 📦 580 · 📋 2.6K - 8% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/pymc-devs/pymc
	```
- [PyPi](https://pypi.org/project/pymc3) (📥 320K / month · 📦 230 · ⏱️ 24.08.2021):
	```
	pip install pymc3
	```
- [Conda](https://anaconda.org/conda-forge/pymc3) (📥 380K · ⏱️ 12.10.2021):
	```
	conda install -c conda-forge pymc3
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/probability">tensorflow-probability</a></b> (🥇37 ·  ⭐ 3.6K) - Probabilistic reasoning and statistical analysis in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/probability) (👨‍💻 440 · 🔀 960 · 📋 1.2K - 45% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/tensorflow/probability
	```
- [PyPi](https://pypi.org/project/tensorflow-probability) (📥 710K / month · 📦 310 · ⏱️ 17.11.2021):
	```
	pip install tensorflow-probability
	```
- [Conda](https://anaconda.org/conda-forge/tensorflow-probability) (📥 49K · ⏱️ 26.01.2022):
	```
	conda install -c conda-forge tensorflow-probability
	```
</details>
<details><summary><b><a href="https://github.com/pyro-ppl/pyro">Pyro</a></b> (🥇33 ·  ⭐ 7.3K) - Deep universal probabilistic programming with Python and PyTorch. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pyro-ppl/pyro) (👨‍💻 120 · 🔀 880 · 📦 620 · 📋 920 - 19% open · ⏱️ 27.01.2022):

	```
	git clone https://github.com/pyro-ppl/pyro
	```
- [PyPi](https://pypi.org/project/pyro-ppl) (📥 74K / month · 📦 49 · ⏱️ 14.12.2021):
	```
	pip install pyro-ppl
	```
- [Conda](https://anaconda.org/conda-forge/pyro-ppl) (📥 4.1K · ⏱️ 14.12.2021):
	```
	conda install -c conda-forge pyro-ppl
	```
</details>
<details><summary><b><a href="https://github.com/cornellius-gp/gpytorch">GPyTorch</a></b> (🥇33 ·  ⭐ 2.7K) - A highly efficient and modular implementation of Gaussian Processes.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/cornellius-gp/gpytorch) (👨‍💻 91 · 🔀 390 · 📦 480 · 📋 1K - 23% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/cornellius-gp/gpytorch
	```
- [PyPi](https://pypi.org/project/gpytorch) (📥 140K / month · 📦 30 · ⏱️ 04.12.2021):
	```
	pip install gpytorch
	```
- [Conda](https://anaconda.org/conda-forge/gpytorch) (📥 25K · ⏱️ 14.12.2021):
	```
	conda install -c conda-forge gpytorch
	```
</details>
<details><summary><b><a href="https://github.com/hmmlearn/hmmlearn">hmmlearn</a></b> (🥈32 ·  ⭐ 2.4K) - Hidden Markov Models in Python, with scikit-learn like API. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/hmmlearn/hmmlearn) (👨‍💻 38 · 🔀 690 · 📦 1.2K · 📋 380 - 14% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/hmmlearn/hmmlearn
	```
- [PyPi](https://pypi.org/project/hmmlearn) (📥 330K / month · 📦 130 · ⏱️ 10.02.2022):
	```
	pip install hmmlearn
	```
- [Conda](https://anaconda.org/conda-forge/hmmlearn) (📥 110K · ⏱️ 13.11.2021):
	```
	conda install -c conda-forge hmmlearn
	```
</details>
<details><summary><b><a href="https://github.com/pgmpy/pgmpy">pgmpy</a></b> (🥈32 ·  ⭐ 2K) - Python Library for learning (Structure and Parameter), inference.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pgmpy/pgmpy) (👨‍💻 100 · 🔀 630 · 📥 130 · 📦 320 · 📋 770 - 28% open · ⏱️ 21.01.2022):

	```
	git clone https://github.com/pgmpy/pgmpy
	```
- [PyPi](https://pypi.org/project/pgmpy) (📥 62K / month · 📦 9 · ⏱️ 30.12.2021):
	```
	pip install pgmpy
	```
</details>
<details><summary><b><a href="https://github.com/rlabbe/filterpy">filterpy</a></b> (🥈31 ·  ⭐ 2.1K · 💤) - Python Kalman filtering and optimal estimation library. Implements.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rlabbe/filterpy) (👨‍💻 36 · 🔀 480 · 📦 1.2K · 📋 200 - 23% open · ⏱️ 04.05.2021):

	```
	git clone https://github.com/rlabbe/filterpy
	```
- [PyPi](https://pypi.org/project/filterpy) (📥 650K / month · 📦 130 · ⏱️ 10.10.2018):
	```
	pip install filterpy
	```
- [Conda](https://anaconda.org/conda-forge/filterpy) (📥 72K · ⏱️ 05.05.2020):
	```
	conda install -c conda-forge filterpy
	```
</details>
<details><summary><b><a href="https://github.com/GPflow/GPflow">GPflow</a></b> (🥈31 ·  ⭐ 1.6K) - Gaussian processes in TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/GPflow/GPflow) (👨‍💻 76 · 🔀 420 · 📦 320 · 📋 750 - 16% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/GPflow/GPflow
	```
- [PyPi](https://pypi.org/project/gpflow) (📥 8.5K / month · 📦 28 · ⏱️ 20.01.2022):
	```
	pip install gpflow
	```
- [Conda](https://anaconda.org/conda-forge/gpflow) (📥 10K · ⏱️ 06.02.2022):
	```
	conda install -c conda-forge gpflow
	```
</details>
<details><summary><b><a href="https://github.com/jmschrei/pomegranate">pomegranate</a></b> (🥈30 ·  ⭐ 2.8K) - Fast, flexible and easy to use probabilistic modelling in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jmschrei/pomegranate) (👨‍💻 65 · 🔀 510 · 📦 630 · 📋 670 - 8% open · ⏱️ 06.02.2022):

	```
	git clone https://github.com/jmschrei/pomegranate
	```
- [PyPi](https://pypi.org/project/pomegranate) (📥 40K / month · 📦 44 · ⏱️ 19.11.2021):
	```
	pip install pomegranate
	```
- [Conda](https://anaconda.org/conda-forge/pomegranate) (📥 79K · ⏱️ 16.11.2021):
	```
	conda install -c conda-forge pomegranate
	```
</details>
<details><summary><b><a href="https://github.com/pydata/patsy">patsy</a></b> (🥈30 ·  ⭐ 810) - Describing statistical models in Python using symbolic formulas. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/pydata/patsy) (👨‍💻 16 · 🔀 94 · 📦 47K · 📋 140 - 51% open · ⏱️ 26.09.2021):

	```
	git clone https://github.com/pydata/patsy
	```
- [PyPi](https://pypi.org/project/patsy) (📥 5.5M / month · 📦 2.6K · ⏱️ 26.09.2021):
	```
	pip install patsy
	```
- [Conda](https://anaconda.org/conda-forge/patsy) (📥 4.2M · ⏱️ 26.09.2021):
	```
	conda install -c conda-forge patsy
	```
</details>
<details><summary><b><a href="https://github.com/twopirllc/pandas-ta">pandas-ta</a></b> (🥉28 ·  ⭐ 2.1K) - Technical Analysis Indicators - Pandas TA is an easy to use.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/twopirllc/pandas-ta) (👨‍💻 44 · 🔀 490 · 📦 430 · 📋 360 - 15% open · ⏱️ 31.01.2022):

	```
	git clone https://github.com/twopirllc/pandas-ta
	```
- [PyPi](https://pypi.org/project/pandas-ta) (📥 83K / month · 📦 10 · ⏱️ 28.07.2021):
	```
	pip install pandas-ta
	```
- [Conda](https://anaconda.org/conda-forge/pandas-ta) (📥 310 · ⏱️ 05.10.2021):
	```
	conda install -c conda-forge pandas-ta
	```
</details>
<details><summary><b><a href="https://github.com/SALib/SALib">SALib</a></b> (🥉28 ·  ⭐ 560) - Sensitivity Analysis Library in Python. Contains Sobol, Morris, FAST, and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SALib/SALib) (👨‍💻 35 · 🔀 170 · 📋 270 - 17% open · ⏱️ 06.02.2022):

	```
	git clone https://github.com/SALib/SALib
	```
- [PyPi](https://pypi.org/project/salib) (📥 120K / month · 📦 54 · ⏱️ 06.02.2022):
	```
	pip install salib
	```
- [Conda](https://anaconda.org/conda-forge/salib) (📥 75K · ⏱️ 04.09.2021):
	```
	conda install -c conda-forge salib
	```
</details>
<details><summary><b><a href="https://github.com/bambinos/bambi">bambi</a></b> (🥉25 ·  ⭐ 740) - BAyesian Model-Building Interface (Bambi) in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bambinos/bambi) (👨‍💻 21 · 🔀 76 · 📦 21 · 📋 220 - 17% open · ⏱️ 21.01.2022):

	```
	git clone https://github.com/bambinos/bambi
	```
- [PyPi](https://pypi.org/project/bambi) (📥 2.5K / month · 📦 3 · ⏱️ 15.01.2022):
	```
	pip install bambi
	```
- [Conda](https://anaconda.org/conda-forge/bambi) (📥 6.3K · ⏱️ 18.01.2022):
	```
	conda install -c conda-forge bambi
	```
</details>
<details><summary><b><a href="https://github.com/uber/orbit">Orbit</a></b> (🥉24 ·  ⭐ 1.2K) - A Python package for Bayesian forecasting with object-oriented design.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/uber/orbit) (👨‍💻 16 · 🔀 83 · 📦 6 · 📋 330 - 15% open · ⏱️ 27.01.2022):

	```
	git clone https://github.com/uber/orbit
	```
- [PyPi](https://pypi.org/project/orbit-ml) (📥 6K / month · 📦 1 · ⏱️ 12.01.2022):
	```
	pip install orbit-ml
	```
</details>
<details><summary><b><a href="https://github.com/ElementAI/baal">Baal</a></b> (🥉20 ·  ⭐ 540) - Library to enable Bayesian active learning in your research or labeling.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ElementAI/baal) (👨‍💻 11 · 🔀 50 · 📋 63 - 28% open · ⏱️ 10.01.2022):

	```
	git clone https://github.com/ElementAI/baal
	```
- [PyPi](https://pypi.org/project/baal) (📥 740 / month · 📦 1 · ⏱️ 17.12.2021):
	```
	pip install baal
	```
- [Conda](https://anaconda.org/conda-forge/baal) (📥 1K · ⏱️ 06.08.2021):
	```
	conda install -c conda-forge baal
	```
</details>
<details><summary>Show 7 hidden projects...</summary>

- <b><a href="https://github.com/raphaelvallat/pingouin">pingouin</a></b> (🥉29 ·  ⭐ 900) - Statistical package in Python based on Pandas. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/blei-lab/edward">Edward</a></b> (🥉28 ·  ⭐ 4.7K · 💀) - A probabilistic programming language in TensorFlow. Deep.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/stan-dev/pystan">PyStan</a></b> (🥉27 ·  ⭐ 160) - PyStan, a Python interface to Stan, a platform for statistical modeling... <code><a href="http://bit.ly/3hkKRql">ISC</a></code>
- <b><a href="https://github.com/mattjj/pyhsmm">pyhsmm</a></b> (🥉21 ·  ⭐ 510 · 💀) - Bayesian inference in HSMMs and HMMs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/maximtrp/scikit-posthocs">scikit-posthocs</a></b> (🥉20 ·  ⭐ 230) - Multiple Pairwise Comparisons (Post Hoc) Tests in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/pyro-ppl/funsor">Funsor</a></b> (🥉19 ·  ⭐ 190) - Functional tensors for probabilistic programming. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/thu-ml/zhusuan">ZhuSuan</a></b> (🥉15 ·  ⭐ 2.1K · 💀) - A probabilistic programming library for Bayesian deep learning,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Adversarial Robustness

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for testing the robustness of machine learning models against attacks with adversarial/malicious examples._

<details><summary><b><a href="https://github.com/Trusted-AI/adversarial-robustness-toolbox">ART</a></b> (🥇32 ·  ⭐ 2.8K) - Adversarial Robustness Toolbox (ART) - Python Library for Machine Learning.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Trusted-AI/adversarial-robustness-toolbox) (👨‍💻 90 · 🔀 760 · 📦 180 · 📋 630 - 11% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/Trusted-AI/adversarial-robustness-toolbox
	```
- [PyPi](https://pypi.org/project/adversarial-robustness-toolbox) (📥 4.1K / month · 📦 6 · ⏱️ 07.01.2022):
	```
	pip install adversarial-robustness-toolbox
	```
- [Conda](https://anaconda.org/conda-forge/adversarial-robustness-toolbox) (📥 7.7K · ⏱️ 10.01.2022):
	```
	conda install -c conda-forge adversarial-robustness-toolbox
	```
</details>
<details><summary><b><a href="https://github.com/cleverhans-lab/cleverhans">CleverHans</a></b> (🥈30 ·  ⭐ 5.4K) - An adversarial example library for constructing attacks,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/cleverhans-lab/cleverhans) (👨‍💻 130 · 🔀 1.3K · 📦 290 · 📋 450 - 5% open · ⏱️ 23.09.2021):

	```
	git clone https://github.com/cleverhans-lab/cleverhans
	```
- [PyPi](https://pypi.org/project/cleverhans) (📥 1.1K / month · 📦 11 · ⏱️ 24.07.2021):
	```
	pip install cleverhans
	```
- [Conda](https://anaconda.org/conda-forge/cleverhans) (📥 2.5K · ⏱️ 29.07.2021):
	```
	conda install -c conda-forge cleverhans
	```
</details>
<details><summary><b><a href="https://github.com/QData/TextAttack">TextAttack</a></b> (🥈30 ·  ⭐ 1.8K) - TextAttack is a Python framework for adversarial attacks, data.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/QData/TextAttack) (👨‍💻 46 · 🔀 220 · 📦 62 · 📋 190 - 20% open · ⏱️ 16.12.2021):

	```
	git clone https://github.com/QData/TextAttack
	```
- [PyPi](https://pypi.org/project/textattack) (📥 11K / month · 📦 3 · ⏱️ 10.11.2021):
	```
	pip install textattack
	```
- [Conda](https://anaconda.org/conda-forge/textattack) (📥 2.5K · ⏱️ 29.06.2021):
	```
	conda install -c conda-forge textattack
	```
</details>
<details><summary><b><a href="https://github.com/bethgelab/foolbox">Foolbox</a></b> (🥈29 ·  ⭐ 2.1K) - A Python toolbox to create adversarial examples that fool neural networks.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bethgelab/foolbox) (👨‍💻 32 · 🔀 370 · 📦 260 · 📋 360 - 16% open · ⏱️ 04.02.2022):

	```
	git clone https://github.com/bethgelab/foolbox
	```
- [PyPi](https://pypi.org/project/foolbox) (📥 3K / month · 📦 13 · ⏱️ 23.02.2021):
	```
	pip install foolbox
	```
- [Conda](https://anaconda.org/conda-forge/foolbox) (📥 5.3K · ⏱️ 30.04.2021):
	```
	conda install -c conda-forge foolbox
	```
</details>
<details><summary><b><a href="https://github.com/advboxes/AdvBox">AdvBox</a></b> (🥉19 ·  ⭐ 1.2K · 💤) - Advbox is a toolbox to generate adversarial examples that fool.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/advboxes/AdvBox) (👨‍💻 19 · 🔀 240 · 📋 37 - 21% open · ⏱️ 03.05.2021):

	```
	git clone https://github.com/advboxes/AdvBox
	```
- [PyPi](https://pypi.org/project/advbox) (📥 26 / month · ⏱️ 05.12.2018):
	```
	pip install advbox
	```
</details>
<details><summary><b><a href="https://github.com/MadryLab/robustness">robustness</a></b> (🥉17 ·  ⭐ 660) - A library for experimenting with, training and evaluating neural.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/MadryLab/robustness) (👨‍💻 13 · 🔀 120 · 📦 69 · 📋 70 - 21% open · ⏱️ 30.11.2021):

	```
	git clone https://github.com/MadryLab/robustness
	```
- [PyPi](https://pypi.org/project/robustness) (📥 440 / month · 📦 2 · ⏱️ 01.12.2020):
	```
	pip install robustness
	```
- [Conda](https://anaconda.org/conda-forge/robustness) (📥 3.2K · ⏱️ 30.04.2021):
	```
	conda install -c conda-forge robustness
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/BorealisAI/advertorch">advertorch</a></b> (🥉21 ·  ⭐ 1K · 💤) - A Toolbox for Adversarial Robustness Research. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/airbnb/artificial-adversary">Adversary</a></b> (🥉16 ·  ⭐ 360 · 💀) - Tool to generate adversarial text examples and test machine.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/textflint/textflint">textflint</a></b> (🥉14 ·  ⭐ 540) - Unified Multilingual Robustness Evaluation Toolkit for Natural.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
</details>
<br>

## GPU Utilities

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that require and make use of CUDA/GPU system capabilities to optimize data handling and machine learning tasks._

<details><summary><b><a href="https://github.com/cupy/cupy">CuPy</a></b> (🥇38 ·  ⭐ 5.8K) - NumPy & SciPy for GPU. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cupy/cupy) (👨‍💻 290 · 🔀 560 · 📥 25K · 📦 920 · 📋 1.7K - 23% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/cupy/cupy
	```
- [PyPi](https://pypi.org/project/cupy) (📥 88K / month · 📦 150 · ⏱️ 20.01.2022):
	```
	pip install cupy
	```
- [Conda](https://anaconda.org/conda-forge/cupy) (📥 1.2M · ⏱️ 03.02.2022):
	```
	conda install -c conda-forge cupy
	```
- [Docker Hub](https://hub.docker.com/r/cupy/cupy) (📥 54K · ⭐ 7 · ⏱️ 20.01.2022):
	```
	docker pull cupy/cupy
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/cudf">cuDF</a></b> (🥇30 ·  ⭐ 4.5K) - cuDF - GPU DataFrame Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/rapidsai/cudf) (👨‍💻 230 · 🔀 590 · 📋 4.4K - 16% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/rapidsai/cudf
	```
- [PyPi](https://pypi.org/project/cudf) (📥 1K / month · 📦 3 · ⏱️ 01.06.2020):
	```
	pip install cudf
	```
</details>
<details><summary><b><a href="https://github.com/inducer/pycuda">PyCUDA</a></b> (🥇30 ·  ⭐ 1.3K) - CUDA integration for Python, plus shiny features. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/inducer/pycuda) (👨‍💻 74 · 🔀 250 · 📦 1.2K · 📋 220 - 29% open · ⏱️ 11.01.2022):

	```
	git clone https://github.com/inducer/pycuda
	```
- [PyPi](https://pypi.org/project/pycuda) (📥 32K / month · 📦 190 · ⏱️ 03.04.2021):
	```
	pip install pycuda
	```
- [Conda](https://anaconda.org/conda-forge/pycuda) (📥 55K · ⏱️ 06.11.2021):
	```
	conda install -c conda-forge pycuda
	```
</details>
<details><summary><b><a href="https://github.com/wookayin/gpustat">gpustat</a></b> (🥈29 ·  ⭐ 2.7K) - A simple command-line utility for querying and monitoring GPU status. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wookayin/gpustat) (👨‍💻 12 · 🔀 210 · 📦 1.6K · 📋 79 - 27% open · ⏱️ 13.08.2021):

	```
	git clone https://github.com/wookayin/gpustat
	```
- [PyPi](https://pypi.org/project/gpustat) (📥 480K / month · 📦 99 · ⏱️ 02.01.2021):
	```
	pip install gpustat
	```
- [Conda](https://anaconda.org/conda-forge/gpustat) (📥 120K · ⏱️ 24.11.2020):
	```
	conda install -c conda-forge gpustat
	```
</details>
<details><summary><b><a href="https://github.com/NVIDIA/apex">Apex</a></b> (🥈27 ·  ⭐ 6.1K) - A PyTorch Extension: Tools for easy mixed precision and distributed.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NVIDIA/apex) (👨‍💻 91 · 🔀 880 · 📦 870 · 📋 930 - 56% open · ⏱️ 07.02.2022):

	```
	git clone https://github.com/NVIDIA/apex
	```
- [Conda](https://anaconda.org/conda-forge/nvidia-apex) (📥 73K · ⏱️ 22.04.2021):
	```
	conda install -c conda-forge nvidia-apex
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/cuml">cuML</a></b> (🥈27 ·  ⭐ 2.6K) - cuML - RAPIDS Machine Learning Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/rapidsai/cuml) (👨‍💻 150 · 🔀 380 · 📋 2K - 33% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/rapidsai/cuml
	```
- [PyPi](https://pypi.org/project/cuml) (📥 570 / month · 📦 1 · ⏱️ 01.06.2020):
	```
	pip install cuml
	```
</details>
<details><summary><b><a href="https://github.com/arrayfire/arrayfire">ArrayFire</a></b> (🥈26 ·  ⭐ 3.7K) - ArrayFire: a general purpose GPU library. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/arrayfire/arrayfire) (👨‍💻 81 · 🔀 490 · 📥 2K · 📋 1.5K - 15% open · ⏱️ 07.02.2022):

	```
	git clone https://github.com/arrayfire/arrayfire
	```
- [PyPi](https://pypi.org/project/arrayfire) (📥 570 / month · 📦 5 · ⏱️ 05.03.2021):
	```
	pip install arrayfire
	```
</details>
<details><summary><b><a href="https://github.com/NVIDIA/DALI">DALI</a></b> (🥈24 ·  ⭐ 3.7K) - A GPU-accelerated library containing highly optimized building blocks.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/NVIDIA/DALI) (👨‍💻 69 · 🔀 460 · 📋 1.1K - 13% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/NVIDIA/DALI
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/cugraph">cuGraph</a></b> (🥈24 ·  ⭐ 920) - cuGraph - RAPIDS Graph Analytics Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/rapidsai/cugraph) (👨‍💻 75 · 🔀 170 · 📋 760 - 11% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/rapidsai/cugraph
	```
- [PyPi](https://pypi.org/project/cugraph) (📥 170 / month · 📦 1 · ⏱️ 01.06.2020):
	```
	pip install cugraph
	```
- [Conda](https://anaconda.org/conda-forge/libcugraph) (📥 6.2K · ⏱️ 29.04.2021):
	```
	conda install -c conda-forge libcugraph
	```
</details>
<details><summary><b><a href="https://github.com/lebedov/scikit-cuda">scikit-cuda</a></b> (🥈24 ·  ⭐ 880 · 💤) - Python interface to GPU-powered libraries. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lebedov/scikit-cuda) (👨‍💻 45 · 🔀 170 · 📦 160 · 📋 220 - 22% open · ⏱️ 13.07.2021):

	```
	git clone https://github.com/lebedov/scikit-cuda
	```
- [PyPi](https://pypi.org/project/scikit-cuda) (📥 870 / month · 📦 44 · ⏱️ 27.05.2019):
	```
	pip install scikit-cuda
	```
</details>
<details><summary><b><a href="https://github.com/BlazingDB/blazingsql">BlazingSQL</a></b> (🥉22 ·  ⭐ 1.7K) - BlazingSQL is a lightweight, GPU accelerated, SQL engine for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/BlazingDB/blazingsql) (👨‍💻 47 · 🔀 160 · 📋 720 - 18% open · ⏱️ 30.09.2021):

	```
	git clone https://github.com/BlazingDB/blazingsql
	```
- [Conda](https://anaconda.org/blazingsql/blazingsql-protocol) (📥 940 · ⏱️ 11.11.2019):
	```
	conda install -c blazingsql blazingsql-protocol
	```
</details>
<details><summary><b><a href="https://github.com/KomputeProject/kompute">Vulkan Kompute</a></b> (🥉20 ·  ⭐ 750) - General purpose GPU compute framework built on Vulkan to.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/KomputeProject/kompute) (👨‍💻 16 · 🔀 54 · 📥 130 · 📦 2 · 📋 170 - 33% open · ⏱️ 30.01.2022):

	```
	git clone https://github.com/KomputeProject/kompute
	```
- [PyPi](https://pypi.org/project/kp) (📥 150 / month · ⏱️ 15.09.2021):
	```
	pip install kp
	```
</details>
<details><summary><b><a href="https://github.com/KomputeProject/kompute">kompute</a></b> (🥉20 ·  ⭐ 750 · ➕) - General purpose GPU compute framework built on Vulkan to support.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/KomputeProject/kompute) (👨‍💻 16 · 🔀 54 · 📥 130 · 📦 2 · 📋 170 - 33% open · ⏱️ 30.01.2022):

	```
	git clone https://github.com/KomputeProject/kompute
	```
- [PyPi](https://pypi.org/project/kp) (📥 150 / month · ⏱️ 15.09.2021):
	```
	pip install kp
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/cusignal">cuSignal</a></b> (🥉19 ·  ⭐ 570) - GPU accelerated signal processing. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/rapidsai/cusignal) (👨‍💻 36 · 🔀 81 · 📋 130 - 11% open · ⏱️ 28.01.2022):

	```
	git clone https://github.com/rapidsai/cusignal
	```
</details>
<details><summary>Show 5 hidden projects...</summary>

- <b><a href="https://github.com/anderskm/gputil">GPUtil</a></b> (🥉23 ·  ⭐ 820 · 💀) - A Python module for getting the GPU status from NVIDA GPUs using.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/fbcotter/py3nvml">py3nvml</a></b> (🥉22 ·  ⭐ 200) - Python 3 Bindings for NVML library. Get NVIDIA GPU status inside your.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/nicolargo/nvidia-ml-py3">nvidia-ml-py3</a></b> (🥉20 ·  ⭐ 72 · 💀) - Python 3 Bindings for the NVIDIA Management Library. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/stas00/ipyexperiments">ipyexperiments</a></b> (🥉16 ·  ⭐ 140) - jupyter/ipython experiment containers for GPU and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/Santosh-Gupta/SpeedTorch">SpeedTorch</a></b> (🥉15 ·  ⭐ 650 · 💀) - Library for faster pinned CPU - GPU transfer in Pytorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Tensorflow Utilities

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that extend TensorFlow with additional capabilities._

<details><summary><b><a href="https://github.com/tensorflow/addons">TF Addons</a></b> (🥇37 ·  ⭐ 1.4K) - Useful extra functionality for TensorFlow 2.x maintained by.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/addons) (👨‍💻 180 · 🔀 490 · 📦 5.3K · 📋 920 - 23% open · ⏱️ 01.02.2022):

	```
	git clone https://github.com/tensorflow/addons
	```
- [PyPi](https://pypi.org/project/tensorflow-addons) (📥 6.4M / month · 📦 140 · ⏱️ 10.11.2021):
	```
	pip install tensorflow-addons
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/datasets">TensorFlow Datasets</a></b> (🥇36 ·  ⭐ 3.2K) - TFDS is a collection of datasets ready to use with.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/datasets) (👨‍💻 240 · 🔀 1.2K · 📋 1.1K - 46% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/tensorflow/datasets
	```
- [PyPi](https://pypi.org/project/tensorflow-datasets) (📥 1.3M / month · 📦 150 · ⏱️ 31.01.2022):
	```
	pip install tensorflow-datasets
	```
- [Conda](https://anaconda.org/conda-forge/tensorflow-datasets) (📥 3.1K · ⏱️ 17.08.2021):
	```
	conda install -c conda-forge tensorflow-datasets
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/hub">tensorflow-hub</a></b> (🥈34 ·  ⭐ 3K) - A library for transfer learning by reusing parts of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/hub) (👨‍💻 83 · 🔀 1.6K · 📦 10K · 📋 640 - 2% open · ⏱️ 06.02.2022):

	```
	git clone https://github.com/tensorflow/hub
	```
- [PyPi](https://pypi.org/project/tensorflow-hub) (📥 3.2M / month · 📦 280 · ⏱️ 14.04.2021):
	```
	pip install tensorflow-hub
	```
- [Conda](https://anaconda.org/conda-forge/tensorflow-hub) (📥 60K · ⏱️ 18.04.2021):
	```
	conda install -c conda-forge tensorflow-hub
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/tensor2tensor">tensor2tensor</a></b> (🥈33 ·  ⭐ 12K · 📉) - Library of deep learning models and datasets designed.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tensor2tensor) (👨‍💻 240 · 🔀 2.9K · 📦 1.1K · 📋 1.2K - 45% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/tensorflow/tensor2tensor
	```
- [PyPi](https://pypi.org/project/tensor2tensor) (📥 50K / month · 📦 93 · ⏱️ 17.06.2020):
	```
	pip install tensor2tensor
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/model-optimization">TF Model Optimization</a></b> (🥈32 ·  ⭐ 1.2K) - A toolkit to optimize ML models for deployment for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/model-optimization) (👨‍💻 65 · 🔀 270 · 📦 1.5K · 📋 300 - 50% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/tensorflow/model-optimization
	```
- [PyPi](https://pypi.org/project/tensorflow-model-optimization) (📥 180K / month · 📦 19 · ⏱️ 09.02.2022):
	```
	pip install tensorflow-model-optimization
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/transform">TensorFlow Transform</a></b> (🥈32 ·  ⭐ 900) - Input pipeline framework. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/transform) (👨‍💻 27 · 🔀 180 · 📦 690 · 📋 180 - 13% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/tensorflow/transform
	```
- [PyPi](https://pypi.org/project/tensorflow-transform) (📥 8.9M / month · 📦 55 · ⏱️ 21.01.2022):
	```
	pip install tensorflow-transform
	```
</details>
<details><summary><b><a href="https://github.com/keras-team/keras-preprocessing">Keras-Preprocessing</a></b> (🥉30 ·  ⭐ 1K · 💤) - Utilities for working with image data, text data, and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/keras-team/keras-preprocessing) (👨‍💻 50 · 🔀 440 · 📋 190 - 48% open · ⏱️ 04.02.2021):

	```
	git clone https://github.com/keras-team/keras-preprocessing
	```
- [PyPi](https://pypi.org/project/keras-preprocessing) (📥 8.8M / month · 📦 1.5K · ⏱️ 14.05.2020):
	```
	pip install keras-preprocessing
	```
- [Conda](https://anaconda.org/conda-forge/keras-preprocessing) (📥 1.2M · ⏱️ 15.01.2021):
	```
	conda install -c conda-forge keras-preprocessing
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/io">TensorFlow I/O</a></b> (🥉30 ·  ⭐ 530) - Dataset, streaming, and file system extensions.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/io) (👨‍💻 88 · 🔀 220 · 📋 490 - 33% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/tensorflow/io
	```
- [PyPi](https://pypi.org/project/tensorflow-io) (📥 170K / month · 📦 18 · ⏱️ 04.02.2022):
	```
	pip install tensorflow-io
	```
</details>
<details><summary><b><a href="https://github.com/qubvel/efficientnet">efficientnet</a></b> (🥉27 ·  ⭐ 1.9K · 💤) - Implementation of EfficientNet model. Keras and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/qubvel/efficientnet) (👨‍💻 10 · 🔀 440 · 📥 200K · 📦 880 · 📋 120 - 51% open · ⏱️ 16.07.2021):

	```
	git clone https://github.com/qubvel/efficientnet
	```
- [PyPi](https://pypi.org/project/efficientnet) (📥 79K / month · 📦 7 · ⏱️ 15.09.2020):
	```
	pip install efficientnet
	```
- [Conda](https://anaconda.org/anaconda/efficientnet) (📥 15 · ⏱️ 14.01.2022):
	```
	conda install -c anaconda efficientnet
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/neural-structured-learning">Neural Structured Learning</a></b> (🥉26 ·  ⭐ 900) - Training neural models with structured signals. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/neural-structured-learning) (👨‍💻 32 · 🔀 170 · 📦 170 · 📋 61 - 4% open · ⏱️ 01.02.2022):

	```
	git clone https://github.com/tensorflow/neural-structured-learning
	```
- [PyPi](https://pypi.org/project/neural-structured-learning) (📥 11K / month · 📦 2 · ⏱️ 18.08.2020):
	```
	pip install neural-structured-learning
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/cloud">TensorFlow Cloud</a></b> (🥉24 ·  ⭐ 320) - The TensorFlow Cloud repository provides APIs that.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/cloud) (👨‍💻 26 · 🔀 66 · 📦 120 · 📋 81 - 67% open · ⏱️ 04.01.2022):

	```
	git clone https://github.com/tensorflow/cloud
	```
- [PyPi](https://pypi.org/project/tensorflow-cloud) (📥 260K / month · 📦 1 · ⏱️ 17.06.2021):
	```
	pip install tensorflow-cloud
	```
</details>
<details><summary><b><a href="https://github.com/geffy/tffm">tffm</a></b> (🥉21 ·  ⭐ 780) - TensorFlow implementation of an arbitrary order Factorization Machine. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/geffy/tffm) (👨‍💻 10 · 🔀 190 · 📦 11 · 📋 40 - 45% open · ⏱️ 17.01.2022):

	```
	git clone https://github.com/geffy/tffm
	```
- [PyPi](https://pypi.org/project/tffm) (📥 2.1K / month · 📦 1 · ⏱️ 17.01.2022):
	```
	pip install tffm
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/compression">TF Compression</a></b> (🥉21 ·  ⭐ 580 · 📈) - Data compression in TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/compression) (👨‍💻 10 · 🔀 210 · 📋 79 - 2% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/tensorflow/compression
	```
- [PyPi](https://pypi.org/project/tensorflow-compression) (📥 990 / month · 📦 1 · ⏱️ 09.02.2022):
	```
	pip install tensorflow-compression
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/saliency">Saliency</a></b> (🥉20 ·  ⭐ 760 · 💤) - Framework-agnostic implementation for state-of-the-art.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PAIR-code/saliency) (👨‍💻 14 · 🔀 160 · 📦 21 · 📋 40 - 35% open · ⏱️ 28.07.2021):

	```
	git clone https://github.com/PAIR-code/saliency
	```
- [PyPi](https://pypi.org/project/saliency) (📥 740 / month · 📦 3 · ⏱️ 03.05.2021):
	```
	pip install saliency
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/taehoonlee/tensornets">TensorNets</a></b> (🥉21 ·  ⭐ 1K · 💀) - High level network definitions with pre-trained weights in.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Jax Utilities

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that extend Jax with additional capabilities._

<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/patrick-kidger/equinox">equinox</a></b> (🥇18 ·  ⭐ 260 · ➕) - Callable PyTrees and filtered JIT/grad transformations =.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/ucl-bug/jaxdf">jaxdf</a></b> (🥉8 ·  ⭐ 43 · 🐣) - A JAX-based research framework for writing differentiable.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Sklearn Utilities

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that extend scikit-learn with additional capabilities._

<details><summary><b><a href="https://github.com/scikit-learn-contrib/imbalanced-learn">imbalanced-learn</a></b> (🥇36 ·  ⭐ 5.7K) - A Python Package to Tackle the Curse of Imbalanced.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/imbalanced-learn) (👨‍💻 62 · 🔀 1.2K · 📦 9.2K · 📋 510 - 12% open · ⏱️ 25.01.2022):

	```
	git clone https://github.com/scikit-learn-contrib/imbalanced-learn
	```
- [PyPi](https://pypi.org/project/imbalanced-learn) (📥 2.9M / month · 📦 240 · ⏱️ 11.01.2022):
	```
	pip install imbalanced-learn
	```
- [Conda](https://anaconda.org/conda-forge/imbalanced-learn) (📥 180K · ⏱️ 11.01.2022):
	```
	conda install -c conda-forge imbalanced-learn
	```
</details>
<details><summary><b><a href="https://github.com/rasbt/mlxtend">MLxtend</a></b> (🥇35 ·  ⭐ 3.8K) - A library of extension and helper modules for Pythons data.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rasbt/mlxtend) (👨‍💻 86 · 🔀 730 · 📦 5.1K · 📋 400 - 24% open · ⏱️ 19.01.2022):

	```
	git clone https://github.com/rasbt/mlxtend
	```
- [PyPi](https://pypi.org/project/mlxtend) (📥 2M / month · 📦 140 · ⏱️ 03.09.2021):
	```
	pip install mlxtend
	```
- [Conda](https://anaconda.org/conda-forge/mlxtend) (📥 190K · ⏱️ 03.09.2021):
	```
	conda install -c conda-forge mlxtend
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/category_encoders">category_encoders</a></b> (🥈31 ·  ⭐ 1.8K · 📉) - A library of sklearn compatible categorical variable.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/category_encoders) (👨‍💻 48 · 🔀 340 · 📦 3K · 📋 240 - 32% open · ⏱️ 16.11.2021):

	```
	git clone https://github.com/scikit-learn-contrib/category_encoders
	```
- [PyPi](https://pypi.org/project/category_encoders) (📥 1.2M / month · 📦 23 · ⏱️ 14.10.2018):
	```
	pip install category_encoders
	```
- [Conda](https://anaconda.org/conda-forge/category_encoders) (📥 140K · ⏱️ 13.10.2021):
	```
	conda install -c conda-forge category_encoders
	```
</details>
<details><summary><b><a href="https://github.com/guofei9987/scikit-opt">scikit-opt</a></b> (🥈26 ·  ⭐ 2.9K) - Genetic Algorithm, Particle Swarm Optimization, Simulated.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/guofei9987/scikit-opt) (👨‍💻 14 · 🔀 700 · 📦 59 · 📋 130 - 22% open · ⏱️ 16.01.2022):

	```
	git clone https://github.com/guofei9987/scikit-opt
	```
- [PyPi](https://pypi.org/project/scikit-opt) (📥 1.2K / month · 📦 6 · ⏱️ 14.01.2022):
	```
	pip install scikit-opt
	```
</details>
<details><summary><b><a href="https://github.com/iskandr/fancyimpute">fancyimpute</a></b> (🥈26 ·  ⭐ 1K) - Multivariate imputation and matrix completion algorithms.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/iskandr/fancyimpute) (👨‍💻 12 · 🔀 170 · 📦 1.1K · 📋 110 - 0% open · ⏱️ 21.10.2021):

	```
	git clone https://github.com/iskandr/fancyimpute
	```
- [PyPi](https://pypi.org/project/fancyimpute) (📥 12K / month · 📦 29 · ⏱️ 21.10.2021):
	```
	pip install fancyimpute
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/lightning">sklearn-contrib-lightning</a></b> (🥈25 ·  ⭐ 1.5K) - Large-scale linear classification, regression and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/lightning) (👨‍💻 17 · 🔀 200 · 📥 120 · 📦 99 · 📋 92 - 55% open · ⏱️ 30.01.2022):

	```
	git clone https://github.com/scikit-learn-contrib/lightning
	```
- [PyPi](https://pypi.org/project/sklearn-contrib-lightning) (📥 3.9K / month · 📦 6 · ⏱️ 30.01.2022):
	```
	pip install sklearn-contrib-lightning
	```
- [Conda](https://anaconda.org/conda-forge/sklearn-contrib-lightning) (📥 160K · ⏱️ 13.11.2021):
	```
	conda install -c conda-forge sklearn-contrib-lightning
	```
</details>
<details><summary><b><a href="https://github.com/koaning/scikit-lego">scikit-lego</a></b> (🥈25 ·  ⭐ 700) - Extra blocks for scikit-learn pipelines. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/koaning/scikit-lego) (👨‍💻 48 · 🔀 77 · 📦 40 · 📋 240 - 13% open · ⏱️ 21.12.2021):

	```
	git clone https://github.com/koaning/scikit-lego
	```
- [PyPi](https://pypi.org/project/scikit-lego) (📥 17K / month · 📦 6 · ⏱️ 09.12.2021):
	```
	pip install scikit-lego
	```
- [Conda](https://anaconda.org/conda-forge/scikit-lego) (📥 17K · ⏱️ 09.12.2021):
	```
	conda install -c conda-forge scikit-lego
	```
</details>
<details><summary><b><a href="https://github.com/trent-b/iterative-stratification">iterative-stratification</a></b> (🥉22 ·  ⭐ 630) - scikit-learn cross validators for iterative.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/trent-b/iterative-stratification) (👨‍💻 6 · 🔀 57 · 📦 180 · 📋 19 - 21% open · ⏱️ 11.11.2021):

	```
	git clone https://github.com/trent-b/iterative-stratification
	```
- [PyPi](https://pypi.org/project/iterative-stratification) (📥 150K / month · 📦 8 · ⏱️ 03.10.2021):
	```
	pip install iterative-stratification
	```
</details>
<details><summary><b><a href="https://github.com/yzhao062/combo">combo</a></b> (🥉21 ·  ⭐ 570) - (AAAI 20) A Python Toolbox for Machine Learning Model Combination. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code> <code>xgboost</code></summary>

- [GitHub](https://github.com/yzhao062/combo) (👨‍💻 1 · 🔀 95 · 📦 440 · 📋 12 - 75% open · ⏱️ 02.10.2021):

	```
	git clone https://github.com/yzhao062/combo
	```
- [PyPi](https://pypi.org/project/combo) (📥 44K / month · 📦 1 · ⏱️ 23.12.2020):
	```
	pip install combo
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/DESlib">DESlib</a></b> (🥉20 ·  ⭐ 370) - A Python library for dynamic classifier and ensemble selection. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/DESlib) (👨‍💻 13 · 🔀 73 · 📦 22 · 📋 140 - 9% open · ⏱️ 10.10.2021):

	```
	git clone https://github.com/scikit-learn-contrib/DESlib
	```
- [PyPi](https://pypi.org/project/deslib) (📥 14K / month · 📦 2 · ⏱️ 08.02.2021):
	```
	pip install deslib
	```
</details>
<details><summary><b><a href="https://github.com/scikit-tda/scikit-tda">scikit-tda</a></b> (🥉17 ·  ⭐ 330) - Topological Data Analysis for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-tda/scikit-tda) (👨‍💻 3 · 🔀 40 · 📦 25 · 📋 17 - 76% open · ⏱️ 03.08.2021):

	```
	git clone https://github.com/scikit-tda/scikit-tda
	```
- [PyPi](https://pypi.org/project/scikit-tda) (📥 5K / month · ⏱️ 03.08.2021):
	```
	pip install scikit-tda
	```
</details>
<details><summary>Show 6 hidden projects...</summary>

- <b><a href="https://github.com/scikit-multilearn/scikit-multilearn">scikit-multilearn</a></b> (🥈25 ·  ⭐ 720 · 💀) - A scikit-learn based module for multi-label et. al... <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/TeamHG-Memex/sklearn-crfsuite">sklearn-crfsuite</a></b> (🥈25 ·  ⭐ 390 · 💀) - scikit-learn inspired API for CRFsuite. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/scikit-learn-contrib/skope-rules">skope-rules</a></b> (🥉21 ·  ⭐ 440 · 💀) - machine learning with logical rules in Python. <code><a href="https://tldrlegal.com/search?q=BSD-1-Clause">❗️BSD-1-Clause</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/mathurinm/celer">celer</a></b> (🥉18 ·  ⭐ 130) - Fast solver for L1-type problems: Lasso, sparse Logisitic regression,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/skggm/skggm">skggm</a></b> (🥉17 ·  ⭐ 190 · 💀) - Scikit-learn compatible estimation of general graphical models. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/amueller/dabl">dabl</a></b> (🥉15 ·  ⭐ 110 · 💤) - Data Analysis Baseline Library. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Pytorch Utilities

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that extend Pytorch with additional capabilities._

<details><summary><b><a href="https://github.com/KevinMusgrave/pytorch-metric-learning">PML</a></b> (🥇32 ·  ⭐ 4.1K) - The easiest way to use deep metric learning in your application. Modular,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/KevinMusgrave/pytorch-metric-learning) (👨‍💻 23 · 🔀 500 · 📦 200 · 📋 320 - 13% open · ⏱️ 12.01.2022):

	```
	git clone https://github.com/KevinMusgrave/pytorch-metric-learning
	```
- [PyPi](https://pypi.org/project/pytorch-metric-learning) (📥 160K / month · 📦 8 · ⏱️ 10.02.2022):
	```
	pip install pytorch-metric-learning
	```
- [Conda](https://anaconda.org/metric-learning/pytorch-metric-learning) (📥 5.8K · ⏱️ 28.12.2021):
	```
	conda install -c metric-learning pytorch-metric-learning
	```
</details>
<details><summary><b><a href="https://github.com/jettify/pytorch-optimizer">pytorch-optimizer</a></b> (🥇29 ·  ⭐ 2.3K) - torch-optimizer -- collection of optimizers for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jettify/pytorch-optimizer) (👨‍💻 25 · 🔀 220 · 📦 460 · 📋 44 - 36% open · ⏱️ 11.11.2021):

	```
	git clone https://github.com/jettify/pytorch-optimizer
	```
- [PyPi](https://pypi.org/project/torch_optimizer) (📥 79K / month · 📦 23 · ⏱️ 31.10.2021):
	```
	pip install torch_optimizer
	```
- [Conda](https://anaconda.org/conda-forge/torch-optimizer) (📥 790 · ⏱️ 31.10.2021):
	```
	conda install -c conda-forge torch-optimizer
	```
</details>
<details><summary><b><a href="https://github.com/PyTorchLightning/lightning-flash">lightning-flash</a></b> (🥇28 ·  ⭐ 1.4K) - Your PyTorch AI Factory - Flash enables you to easily.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PyTorchLightning/lightning-flash) (👨‍💻 61 · 🔀 140 · 📦 48 · 📋 420 - 10% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/PyTorchLightning/lightning-flash
	```
- [PyPi](https://pypi.org/project/lightning-flash) (📥 2.4K / month · 📦 2 · ⏱️ 04.02.2022):
	```
	pip install lightning-flash
	```
- [Conda](https://anaconda.org/conda-forge/lightning-flash) (📥 680 · ⏱️ 13.12.2021):
	```
	conda install -c conda-forge lightning-flash
	```
</details>
<details><summary><b><a href="https://github.com/lukemelas/EfficientNet-PyTorch">EfficientNet-PyTorch</a></b> (🥈27 ·  ⭐ 6.8K · 💤) - A PyTorch implementation of EfficientNet and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lukemelas/EfficientNet-PyTorch) (👨‍💻 24 · 🔀 1.3K · 📥 1.2M · 📋 270 - 49% open · ⏱️ 15.04.2021):

	```
	git clone https://github.com/lukemelas/EfficientNet-PyTorch
	```
- [PyPi](https://pypi.org/project/efficientnet-pytorch) (📥 790K / month · 📦 30 · ⏱️ 15.04.2021):
	```
	pip install efficientnet-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/sksq96/pytorch-summary">pytorch-summary</a></b> (🥈27 ·  ⭐ 3.4K · 💤) - Model summary in PyTorch similar to `model.summary()`.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/sksq96/pytorch-summary) (👨‍💻 11 · 🔀 380 · 📦 4.2K · 📋 160 - 75% open · ⏱️ 10.05.2021):

	```
	git clone https://github.com/sksq96/pytorch-summary
	```
- [PyPi](https://pypi.org/project/torchsummary) (📥 63K / month · 📦 71 · ⏱️ 26.09.2018):
	```
	pip install torchsummary
	```
</details>
<details><summary><b><a href="https://github.com/huggingface/accelerate">accelerate</a></b> (🥈27 ·  ⭐ 2.2K) - A simple way to train and use PyTorch models with multi-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/huggingface/accelerate) (👨‍💻 32 · 🔀 130 · 📦 310 · 📋 160 - 36% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/huggingface/accelerate
	```
- [PyPi](https://pypi.org/project/accelerate) (📥 48K / month · 📦 4 · ⏱️ 27.09.2021):
	```
	pip install accelerate
	```
- [Conda](https://anaconda.org/conda-forge/accelerate) (📥 800 · ⏱️ 11.10.2021):
	```
	conda install -c conda-forge accelerate
	```
</details>
<details><summary><b><a href="https://github.com/rtqichen/torchdiffeq">torchdiffeq</a></b> (🥈25 ·  ⭐ 3.9K) - Differentiable ODE solvers with full GPU support and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rtqichen/torchdiffeq) (👨‍💻 20 · 🔀 680 · 📦 190 · 📋 160 - 19% open · ⏱️ 17.01.2022):

	```
	git clone https://github.com/rtqichen/torchdiffeq
	```
- [PyPi](https://pypi.org/project/torchdiffeq) (📥 19K / month · 📦 6 · ⏱️ 02.06.2021):
	```
	pip install torchdiffeq
	```
- [Conda](https://anaconda.org/conda-forge/torchdiffeq) (📥 4.6K · ⏱️ 03.06.2021):
	```
	conda install -c conda-forge torchdiffeq
	```
</details>
<details><summary><b><a href="https://github.com/tristandeleu/pytorch-meta">Torchmeta</a></b> (🥈25 ·  ⭐ 1.5K) - A collection of extensions and data-loaders for few-shot learning.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tristandeleu/pytorch-meta) (👨‍💻 12 · 🔀 200 · 📦 81 · 📋 120 - 28% open · ⏱️ 20.09.2021):

	```
	git clone https://github.com/tristandeleu/pytorch-meta
	```
- [PyPi](https://pypi.org/project/torchmeta) (📥 1.9K / month · ⏱️ 20.09.2021):
	```
	pip install torchmeta
	```
</details>
<details><summary><b><a href="https://github.com/asappresearch/sru">SRU</a></b> (🥈24 ·  ⭐ 2K · 💤) - Training RNNs as Fast as CNNs (https://arxiv.org/abs/1709.02755). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/asappresearch/sru) (👨‍💻 21 · 🔀 300 · 📦 17 · 📋 120 - 44% open · ⏱️ 19.05.2021):

	```
	git clone https://github.com/asappresearch/sru
	```
- [PyPi](https://pypi.org/project/sru) (📥 4.2K / month · 📦 3 · ⏱️ 17.06.2021):
	```
	pip install sru
	```
</details>
<details><summary><b><a href="https://github.com/dreamquark-ai/tabnet">TabNet</a></b> (🥈24 ·  ⭐ 1.6K) - PyTorch implementation of TabNet paper :.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/dreamquark-ai/tabnet) (👨‍💻 19 · 🔀 320 · 📋 210 - 18% open · ⏱️ 27.12.2021):

	```
	git clone https://github.com/dreamquark-ai/tabnet
	```
- [PyPi](https://pypi.org/project/pytorch-tabnet) (📥 23K / month · 📦 7 · ⏱️ 02.02.2021):
	```
	pip install pytorch-tabnet
	```
- [Conda](https://anaconda.org/conda-forge/pytorch-tabnet) (📥 120 · ⏱️ 30.12.2021):
	```
	conda install -c conda-forge pytorch-tabnet
	```
</details>
<details><summary><b><a href="https://github.com/rwightman/gen-efficientnet-pytorch">EfficientNets</a></b> (🥈23 ·  ⭐ 1.4K · 💤) - Pretrained EfficientNet, EfficientNet-Lite, MixNet,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rwightman/gen-efficientnet-pytorch) (👨‍💻 5 · 🔀 190 · 📦 93 · 📋 51 - 1% open · ⏱️ 08.07.2021):

	```
	git clone https://github.com/rwightman/gen-efficientnet-pytorch
	```
- [PyPi](https://pypi.org/project/geffnet) (📥 9K / month · 📦 1 · ⏱️ 08.07.2021):
	```
	pip install geffnet
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/higher">Higher</a></b> (🥈23 ·  ⭐ 1.3K) - higher is a pytorch library allowing users to obtain higher.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/higher) (👨‍💻 9 · 🔀 94 · 📦 110 · 📋 98 - 48% open · ⏱️ 26.10.2021):

	```
	git clone https://github.com/facebookresearch/higher
	```
- [PyPi](https://pypi.org/project/higher) (📥 10K / month · 📦 2 · ⏱️ 14.07.2020):
	```
	pip install higher
	```
</details>
<details><summary><b><a href="https://github.com/rusty1s/pytorch_sparse">PyTorch Sparse</a></b> (🥈23 ·  ⭐ 560) - PyTorch Extension Library of Optimized Autograd Sparse.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rusty1s/pytorch_sparse) (👨‍💻 21 · 🔀 77 · 📋 200 - 30% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/rusty1s/pytorch_sparse
	```
- [PyPi](https://pypi.org/project/torch-sparse) (📥 20K / month · 📦 32 · ⏱️ 08.09.2021):
	```
	pip install torch-sparse
	```
- [Conda](https://anaconda.org/conda-forge/pytorch_sparse) (📥 79K · ⏱️ 29.06.2021):
	```
	conda install -c conda-forge pytorch_sparse
	```
</details>
<details><summary><b><a href="https://github.com/BloodAxe/pytorch-toolbelt">Pytorch Toolbelt</a></b> (🥉22 ·  ⭐ 1.2K) - PyTorch extensions for fast R&D prototyping and Kaggle.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/BloodAxe/pytorch-toolbelt) (👨‍💻 7 · 🔀 88 · 📋 23 - 21% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/BloodAxe/pytorch-toolbelt
	```
- [PyPi](https://pypi.org/project/pytorch_toolbelt) (📥 15K / month · 📦 6 · ⏱️ 12.08.2021):
	```
	pip install pytorch_toolbelt
	```
</details>
<details><summary><b><a href="https://github.com/rusty1s/pytorch_scatter">torch-scatter</a></b> (🥉22 ·  ⭐ 890) - PyTorch Extension Library of Optimized Scatter Operations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rusty1s/pytorch_scatter) (👨‍💻 19 · 🔀 97 · 📋 240 - 9% open · ⏱️ 03.02.2022):

	```
	git clone https://github.com/rusty1s/pytorch_scatter
	```
- [PyPi](https://pypi.org/project/torch-scatter) (📥 32K / month · 📦 40 · ⏱️ 22.10.2021):
	```
	pip install torch-scatter
	```
- [Conda](https://anaconda.org/conda-forge/pytorch_scatter) (📥 67K · ⏱️ 18.08.2021):
	```
	conda install -c conda-forge pytorch_scatter
	```
</details>
<details><summary><b><a href="https://github.com/lucidrains/reformer-pytorch">reformer-pytorch</a></b> (🥉21 ·  ⭐ 1.7K) - Reformer, the efficient Transformer, in Pytorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lucidrains/reformer-pytorch) (👨‍💻 10 · 🔀 220 · 📋 120 - 11% open · ⏱️ 06.11.2021):

	```
	git clone https://github.com/lucidrains/reformer-pytorch
	```
- [PyPi](https://pypi.org/project/reformer-pytorch) (📥 5.5K / month · ⏱️ 06.11.2021):
	```
	pip install reformer-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/google-research/torchsde">torchsde</a></b> (🥉21 ·  ⭐ 910 · 💤) - Differentiable SDE solvers with GPU support and efficient.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google-research/torchsde) (👨‍💻 5 · 🔀 100 · 📦 11 · 📋 44 - 15% open · ⏱️ 26.07.2021):

	```
	git clone https://github.com/google-research/torchsde
	```
- [PyPi](https://pypi.org/project/torchsde) (📥 14K / month · ⏱️ 20.07.2021):
	```
	pip install torchsde
	```
- [Conda](https://anaconda.org/conda-forge/torchsde) (📥 8.5K · ⏱️ 12.07.2021):
	```
	conda install -c conda-forge torchsde
	```
</details>
<details><summary><b><a href="https://github.com/geohot/tinygrad">tinygrad</a></b> (🥉19 ·  ⭐ 5.2K) - You like pytorch? You like micrograd? You love tinygrad!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/geohot/tinygrad) (👨‍💻 54 · 🔀 570 · 📦 2 · 📋 110 - 19% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/geohot/tinygrad
	```
</details>
<details><summary><b><a href="https://github.com/lucidrains/performer-pytorch">Performer Pytorch</a></b> (🥉19 ·  ⭐ 780) - An implementation of Performer, a linear attention-based.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lucidrains/performer-pytorch) (👨‍💻 6 · 🔀 100 · 📦 38 · 📋 72 - 43% open · ⏱️ 02.02.2022):

	```
	git clone https://github.com/lucidrains/performer-pytorch
	```
- [PyPi](https://pypi.org/project/performer-pytorch) (📥 1.5K / month · 📦 4 · ⏱️ 02.02.2022):
	```
	pip install performer-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/parrt/tensor-sensor">Tensor Sensor</a></b> (🥉19 ·  ⭐ 620) - The goal of this library is to generate more helpful.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/parrt/tensor-sensor) (👨‍💻 3 · 🔀 33 · 📦 7 · 📋 23 - 34% open · ⏱️ 13.12.2021):

	```
	git clone https://github.com/parrt/tensor-sensor
	```
- [PyPi](https://pypi.org/project/tensor-sensor) (📥 2.1K / month · ⏱️ 11.12.2021):
	```
	pip install tensor-sensor
	```
- [Conda](https://anaconda.org/conda-forge/tensor-sensor) (📥 160 · ⏱️ 11.12.2021):
	```
	conda install -c conda-forge tensor-sensor
	```
</details>
<details><summary><b><a href="https://github.com/szagoruyko/pytorchviz">pytorchviz</a></b> (🥉18 ·  ⭐ 2.1K · 💤) - A small package to create visualizations of PyTorch execution.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/szagoruyko/pytorchviz) (👨‍💻 6 · 🔀 220 · 📦 570 · 📋 52 - 36% open · ⏱️ 15.06.2021):

	```
	git clone https://github.com/szagoruyko/pytorchviz
	```
</details>
<details><summary><b><a href="https://github.com/harvardnlp/pytorch-struct">Torch-Struct</a></b> (🥉18 ·  ⭐ 1K · 📈) - Fast, general, and tested differentiable structured.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/harvardnlp/pytorch-struct) (👨‍💻 16 · 🔀 80 · 📋 54 - 44% open · ⏱️ 30.01.2022):

	```
	git clone https://github.com/harvardnlp/pytorch-struct
	```
- [PyPi](https://pypi.org/project/torch-struct) (📥 7.2K / month · ⏱️ 14.02.2021):
	```
	pip install torch-struct
	```
</details>
<details><summary><b><a href="https://github.com/abhishekkrthakur/tez">Tez</a></b> (🥉17 ·  ⭐ 770) - Tez is a super-simple and lightweight Trainer for PyTorch. It also.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/abhishekkrthakur/tez) (👨‍💻 1 · 🔀 110 · 📦 19 · 📋 28 - 64% open · ⏱️ 28.12.2021):

	```
	git clone https://github.com/abhishekkrthakur/tez
	```
- [PyPi](https://pypi.org/project/tez) (📥 2.4K / month · 📦 2 · ⏱️ 28.12.2021):
	```
	pip install tez
	```
</details>
<details><summary><b><a href="https://github.com/achaiah/pywick">Pywick</a></b> (🥉17 ·  ⭐ 370) - High-level batteries-included neural network training library for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/achaiah/pywick) (👨‍💻 4 · 🔀 38 · 📦 5 · 📋 14 - 14% open · ⏱️ 22.10.2021):

	```
	git clone https://github.com/achaiah/pywick
	```
- [PyPi](https://pypi.org/project/pywick) (📥 60 / month · ⏱️ 22.10.2021):
	```
	pip install pywick
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/madgrad">madgrad</a></b> (🥉14 ·  ⭐ 750) - MADGRAD Optimization Method. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/madgrad) (👨‍💻 1 · 🔀 52 · 📦 21 · 📋 9 - 22% open · ⏱️ 20.08.2021):

	```
	git clone https://github.com/facebookresearch/madgrad
	```
- [PyPi](https://pypi.org/project/madgrad) (📥 5.5K / month · ⏱️ 01.04.2021):
	```
	pip install madgrad
	```
</details>
<details><summary>Show 7 hidden projects...</summary>

- <b><a href="https://github.com/Cadene/pretrained-models.pytorch">pretrainedmodels</a></b> (🥇31 ·  ⭐ 8.4K · 💀) - Pretrained ConvNets for pytorch: NASNet, ResNeXt,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/GRAAL-Research/poutyne">Poutyne</a></b> (🥉21 ·  ⭐ 510) - A simplified framework and utilities for PyTorch. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/Luolc/AdaBound">AdaBound</a></b> (🥉20 ·  ⭐ 2.9K · 💀) - An optimizer that trains as fast as Adam and as good as SGD. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/adobe/antialiased-cnns">Antialiased CNNs</a></b> (🥉20 ·  ⭐ 1.5K) - pip install antialiased-cnns to improve stability and.. <code><a href="https://tldrlegal.com/search?q=CC%20BY-NC-SA%204.0">❗️CC BY-NC-SA 4.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/lucidrains/lambda-networks">Lambda Networks</a></b> (🥉18 ·  ⭐ 1.5K · 💀) - Implementation of LambdaNetworks, a new approach to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/karpathy/micrograd">micrograd</a></b> (🥉15 ·  ⭐ 1.9K · 💀) - A tiny scalar-valued autograd engine and a neural net library.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/TorchDrift/TorchDrift">TorchDrift</a></b> (🥉14 ·  ⭐ 200 · 💤) - Drift Detection for your PyTorch Models. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Database Clients

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for connecting to, operating, and querying databases._

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-python#database-clients">best-of-python - DB Clients</a></b> ( ⭐ 2K)  - Collection of database clients for python.

<br>

## Others

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/scipy/scipy">scipy</a></b> (🥇49 ·  ⭐ 9.2K) - Ecosystem of open-source software for mathematics, science, and engineering. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/scipy/scipy) (👨‍💻 1.2K · 🔀 4.1K · 📥 340K · 📦 460K · 📋 8.3K - 22% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/scipy/scipy
	```
- [PyPi](https://pypi.org/project/scipy) (📥 36M / month · 📦 56K · ⏱️ 05.02.2022):
	```
	pip install scipy
	```
- [Conda](https://anaconda.org/conda-forge/scipy) (📥 21M · ⏱️ 09.02.2022):
	```
	conda install -c conda-forge scipy
	```
</details>
<details><summary><b><a href="https://github.com/sympy/sympy">SymPy</a></b> (🥇44 ·  ⭐ 8.8K) - A computer algebra system written in pure Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/sympy/sympy) (👨‍💻 1.1K · 🔀 3.5K · 📥 440K · 📦 39K · 📋 12K - 35% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/sympy/sympy
	```
- [PyPi](https://pypi.org/project/sympy) (📥 2M / month · 📦 4K · ⏱️ 08.10.2021):
	```
	pip install sympy
	```
- [Conda](https://anaconda.org/conda-forge/sympy) (📥 1.9M · ⏱️ 06.11.2021):
	```
	conda install -c conda-forge sympy
	```
</details>
<details><summary><b><a href="https://github.com/streamlit/streamlit">Streamlit</a></b> (🥇38 ·  ⭐ 18K) - Streamlit The fastest way to build data apps in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/streamlit/streamlit) (👨‍💻 130 · 🔀 1.6K · 📦 220 · 📋 2.3K - 24% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/streamlit/streamlit
	```
- [PyPi](https://pypi.org/project/streamlit) (📥 860K / month · 📦 300 · ⏱️ 09.02.2022):
	```
	pip install streamlit
	```
</details>
<details><summary><b><a href="https://github.com/yzhao062/pyod">PyOD</a></b> (🥇34 ·  ⭐ 5.2K) - (JMLR 19) A Python Toolbox for Scalable Outlier Detection (Anomaly.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/yzhao062/pyod) (👨‍💻 33 · 🔀 1K · 📦 1.1K · 📋 240 - 50% open · ⏱️ 04.01.2022):

	```
	git clone https://github.com/yzhao062/pyod
	```
- [PyPi](https://pypi.org/project/pyod) (📥 470K / month · 📦 28 · ⏱️ 04.01.2022):
	```
	pip install pyod
	```
- [Conda](https://anaconda.org/conda-forge/pyod) (📥 16K · ⏱️ 04.01.2022):
	```
	conda install -c conda-forge pyod
	```
</details>
<details><summary><b><a href="https://github.com/gradio-app/gradio">Gradio</a></b> (🥇34 ·  ⭐ 5.1K) - Wrap UIs around any model, share with anyone. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/gradio-app/gradio) (👨‍💻 45 · 🔀 320 · 📦 520 · 📋 330 - 17% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/gradio-app/gradio
	```
- [PyPi](https://pypi.org/project/gradio) (📥 81K / month · 📦 16 · ⏱️ 08.02.2022):
	```
	pip install gradio
	```
</details>
<details><summary><b><a href="https://github.com/deepchem/deepchem">DeepChem</a></b> (🥇34 ·  ⭐ 3.4K) - Democratizing Deep-Learning for Drug Discovery, Quantum Chemistry,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepchem/deepchem) (👨‍💻 180 · 🔀 1.3K · 📦 70 · 📋 1.4K - 31% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/deepchem/deepchem
	```
- [PyPi](https://pypi.org/project/deepchem) (📥 9.2K / month · 📦 4 · ⏱️ 08.02.2022):
	```
	pip install deepchem
	```
- [Conda](https://anaconda.org/conda-forge/deepchem) (📥 8.1K · ⏱️ 19.01.2022):
	```
	conda install -c conda-forge deepchem
	```
</details>
<details><summary><b><a href="https://github.com/simonw/datasette">Datasette</a></b> (🥈33 ·  ⭐ 5.8K) - An open source multi-tool for exploring and publishing data. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/simonw/datasette) (👨‍💻 61 · 🔀 390 · 📥 34 · 📦 580 · 📋 1.3K - 27% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/simonw/datasette
	```
- [PyPi](https://pypi.org/project/datasette) (📥 260K / month · 📦 140 · ⏱️ 07.02.2022):
	```
	pip install datasette
	```
- [Conda](https://anaconda.org/conda-forge/datasette) (📥 2.7K · ⏱️ 08.02.2022):
	```
	conda install -c conda-forge datasette
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PaddleHub">PaddleHub</a></b> (🥈32 ·  ⭐ 7.5K) - Awesome pre-trained models toolkit based on.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PaddleHub) (👨‍💻 54 · 🔀 1.5K · 📥 560 · 📦 690 · 📋 1K - 37% open · ⏱️ 21.01.2022):

	```
	git clone https://github.com/PaddlePaddle/PaddleHub
	```
- [PyPi](https://pypi.org/project/paddlehub) (📥 9.6K / month · 📦 4 · ⏱️ 28.12.2021):
	```
	pip install paddlehub
	```
</details>
<details><summary><b><a href="https://github.com/HIPS/autograd">Autograd</a></b> (🥈32 ·  ⭐ 5.7K · 💤) - Efficiently computes derivatives of numpy code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/HIPS/autograd) (👨‍💻 51 · 🔀 780 · 📦 2.9K · 📋 390 - 42% open · ⏱️ 03.03.2021):

	```
	git clone https://github.com/HIPS/autograd
	```
- [PyPi](https://pypi.org/project/autograd) (📥 1.2M / month · 📦 270 · ⏱️ 25.07.2019):
	```
	pip install autograd
	```
- [Conda](https://anaconda.org/conda-forge/autograd) (📥 200K · ⏱️ 25.07.2019):
	```
	conda install -c conda-forge autograd
	```
</details>
<details><summary><b><a href="https://github.com/carla-simulator/carla">carla</a></b> (🥈31 ·  ⭐ 7.2K · 📉) - Open-source simulator for autonomous driving research. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/carla-simulator/carla) (👨‍💻 140 · 🔀 2.1K · 📦 120 · 📋 3.7K - 13% open · ⏱️ 19.11.2021):

	```
	git clone https://github.com/carla-simulator/carla
	```
- [PyPi](https://pypi.org/project/carla) (📥 2.5K / month · 📦 3 · ⏱️ 17.11.2021):
	```
	pip install carla
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/hdbscan">hdbscan</a></b> (🥈31 ·  ⭐ 2.1K) - A high performance implementation of HDBSCAN clustering. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/hdbscan) (👨‍💻 76 · 🔀 400 · 📦 1.2K · 📋 420 - 63% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/scikit-learn-contrib/hdbscan
	```
- [PyPi](https://pypi.org/project/hdbscan) (📥 360K / month · 📦 150 · ⏱️ 08.02.2022):
	```
	pip install hdbscan
	```
- [Conda](https://anaconda.org/conda-forge/hdbscan) (📥 1M · ⏱️ 10.02.2022):
	```
	conda install -c conda-forge hdbscan
	```
</details>
<details><summary><b><a href="https://github.com/serge-sans-paille/pythran">Pythran</a></b> (🥈31 ·  ⭐ 1.7K) - Ahead of Time compiler for numeric kernels. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/serge-sans-paille/pythran) (👨‍💻 64 · 🔀 170 · 📦 100 · 📋 740 - 15% open · ⏱️ 01.02.2022):

	```
	git clone https://github.com/serge-sans-paille/pythran
	```
- [PyPi](https://pypi.org/project/pythran) (📥 350K / month · 📦 14 · ⏱️ 14.12.2021):
	```
	pip install pythran
	```
- [Conda](https://anaconda.org/conda-forge/pythran) (📥 220K · ⏱️ 14.12.2021):
	```
	conda install -c conda-forge pythran
	```
</details>
<details><summary><b><a href="https://github.com/online-ml/river">River</a></b> (🥈30 ·  ⭐ 3.2K · 📈) - Online machine learning in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/online-ml/river) (👨‍💻 72 · 🔀 340 · 📦 73 · 📋 340 - 1% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/online-ml/river
	```
- [PyPi](https://pypi.org/project/river) (📥 5.8K / month · 📦 6 · ⏱️ 04.02.2022):
	```
	pip install river
	```
- [Conda](https://anaconda.org/conda-forge/river) (📥 6.6K · ⏱️ 09.12.2021):
	```
	conda install -c conda-forge river
	```
</details>
<details><summary><b><a href="https://github.com/tensorly/tensorly">tensorly</a></b> (🥈30 ·  ⭐ 1.2K) - TensorLy: Tensor Learning in Python. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/tensorly/tensorly) (👨‍💻 49 · 🔀 220 · 📦 220 · 📋 180 - 25% open · ⏱️ 24.01.2022):

	```
	git clone https://github.com/tensorly/tensorly
	```
- [PyPi](https://pypi.org/project/tensorly) (📥 5.6K / month · 📦 30 · ⏱️ 08.11.2021):
	```
	pip install tensorly
	```
- [Conda](https://anaconda.org/conda-forge/tensorly) (📥 200K · ⏱️ 09.12.2021):
	```
	conda install -c conda-forge tensorly
	```
</details>
<details><summary><b><a href="https://github.com/PennyLaneAI/pennylane">PennyLane</a></b> (🥈30 ·  ⭐ 1.2K) - PennyLane is a cross-platform Python library for differentiable.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PennyLaneAI/pennylane) (👨‍💻 89 · 🔀 340 · 📥 59 · 📋 620 - 24% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/PennyLaneAI/PennyLane
	```
- [PyPi](https://pypi.org/project/pennylane) (📥 11K / month · 📦 28 · ⏱️ 08.02.2022):
	```
	pip install pennylane
	```
- [Conda](https://anaconda.org/conda-forge/pennylane) (📥 340 · ⏱️ 14.12.2021):
	```
	conda install -c conda-forge pennylane
	```
</details>
<details><summary><b><a href="https://github.com/wireservice/agate">agate</a></b> (🥈30 ·  ⭐ 1.1K · 💤) - A Python data analysis library that is optimized for humans instead of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wireservice/agate) (👨‍💻 49 · 🔀 130 · 📦 760 · 📋 680 - 7% open · ⏱️ 15.07.2021):

	```
	git clone https://github.com/wireservice/agate
	```
- [PyPi](https://pypi.org/project/agate) (📥 1.1M / month · 📦 130 · ⏱️ 15.07.2021):
	```
	pip install agate
	```
- [Conda](https://anaconda.org/conda-forge/agate) (📥 76K · ⏱️ 16.07.2021):
	```
	conda install -c conda-forge agate
	```
</details>
<details><summary><b><a href="https://github.com/inducer/pyopencl">pyopencl</a></b> (🥈30 ·  ⭐ 870) - OpenCL integration for Python, plus shiny features. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/inducer/pyopencl) (👨‍💻 90 · 🔀 220 · 📦 630 · 📋 300 - 22% open · ⏱️ 17.01.2022):

	```
	git clone https://github.com/inducer/pyopencl
	```
- [PyPi](https://pypi.org/project/pyopencl) (📥 26K / month · 📦 180 · ⏱️ 17.01.2022):
	```
	pip install pyopencl
	```
- [Conda](https://anaconda.org/conda-forge/pyopencl) (📥 560K · ⏱️ 19.01.2022):
	```
	conda install -c conda-forge pyopencl
	```
</details>
<details><summary><b><a href="https://github.com/uber/causalml">causalml</a></b> (🥈29 ·  ⭐ 2.8K) - Uplift modeling and causal inference with machine learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/uber/causalml) (👨‍💻 35 · 🔀 420 · 📦 37 · 📋 240 - 18% open · ⏱️ 05.02.2022):

	```
	git clone https://github.com/uber/causalml
	```
- [PyPi](https://pypi.org/project/causalml) (📥 43K / month · 📦 1 · ⏱️ 05.02.2022):
	```
	pip install causalml
	```
</details>
<details><summary><b><a href="https://github.com/tableau/TabPy">TabPy</a></b> (🥈29 ·  ⭐ 1.2K) - Execute Python code on the fly and display results in Tableau visualizations:. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tableau/TabPy) (👨‍💻 46 · 🔀 450 · 📦 81 · 📋 290 - 3% open · ⏱️ 20.01.2022):

	```
	git clone https://github.com/tableau/TabPy
	```
- [PyPi](https://pypi.org/project/tabpy) (📥 17K / month · 📦 2 · ⏱️ 20.01.2022):
	```
	pip install tabpy
	```
- [Conda](https://anaconda.org/anaconda/tabpy-client) (📥 2.4K · ⏱️ 20.01.2022):
	```
	conda install -c anaconda tabpy-client
	```
</details>
<details><summary><b><a href="https://github.com/sepandhaghighi/pycm">pycm</a></b> (🥈28 ·  ⭐ 1.2K) - Multi-class confusion matrix library in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sepandhaghighi/pycm) (👨‍💻 17 · 🔀 100 · 📦 130 · 📋 180 - 6% open · ⏱️ 26.01.2022):

	```
	git clone https://github.com/sepandhaghighi/pycm
	```
- [PyPi](https://pypi.org/project/pycm) (📥 35K / month · 📦 12 · ⏱️ 26.01.2022):
	```
	pip install pycm
	```
</details>
<details><summary><b><a href="https://github.com/pyjanitor-devs/pyjanitor">pyjanitor</a></b> (🥈28 ·  ⭐ 820) - Clean APIs for data cleaning. Python implementation of R package Janitor. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyjanitor-devs/pyjanitor) (👨‍💻 96 · 🔀 140 · 📦 150 · 📋 440 - 21% open · ⏱️ 08.02.2022):

	```
	git clone https://github.com/pyjanitor-devs/pyjanitor
	```
- [PyPi](https://pypi.org/project/pyjanitor) (📥 18K / month · 📦 10 · ⏱️ 21.11.2021):
	```
	pip install pyjanitor
	```
- [Conda](https://anaconda.org/conda-forge/pyjanitor) (📥 110K · ⏱️ 22.11.2021):
	```
	conda install -c conda-forge pyjanitor
	```
</details>
<details><summary><b><a href="https://github.com/Adapter-Hub/adapter-transformers">adapter-transformers</a></b> (🥈28 ·  ⭐ 660 · ➕) - Huggingface Transformers + Adapters =. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>huggingface</code></summary>

- [GitHub](https://github.com/Adapter-Hub/adapter-transformers) (👨‍💻 1.1K · 🔀 110 · 📦 43 · 📋 140 - 24% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/Adapter-Hub/adapter-transformers
	```
- [PyPi](https://pypi.org/project/adapter-transformers) (📥 50K / month · 📦 4 · ⏱️ 09.02.2022):
	```
	pip install adapter-transformers
	```
</details>
<details><summary><b><a href="https://github.com/google/trax">Trax</a></b> (🥉27 ·  ⭐ 6.8K) - Trax Deep Learning with Clear Code and Speed. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/trax) (👨‍💻 75 · 🔀 680 · 📦 42 · 📋 200 - 41% open · ⏱️ 02.02.2022):

	```
	git clone https://github.com/google/trax
	```
- [PyPi](https://pypi.org/project/trax) (📥 3.8K / month · ⏱️ 26.10.2021):
	```
	pip install trax
	```
</details>
<details><summary><b><a href="https://github.com/nicodv/kmodes">kmodes</a></b> (🥉27 ·  ⭐ 970) - Python implementations of the k-modes and k-prototypes clustering.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nicodv/kmodes) (👨‍💻 20 · 🔀 360 · 📦 990 · 📋 140 - 11% open · ⏱️ 15.12.2021):

	```
	git clone https://github.com/nicodv/kmodes
	```
- [PyPi](https://pypi.org/project/kmodes) (📥 310K / month · 📦 26 · ⏱️ 08.10.2021):
	```
	pip install kmodes
	```
- [Conda](https://anaconda.org/conda-forge/kmodes) (📥 5.9K · ⏱️ 26.01.2022):
	```
	conda install -c conda-forge kmodes
	```
</details>
<details><summary><b><a href="https://github.com/annoviko/pyclustering">pyclustering</a></b> (🥉27 ·  ⭐ 920 · 💤) - pyclustring is a Python, C++ data mining library. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/annoviko/pyclustering) (👨‍💻 26 · 🔀 220 · 📥 390 · 📦 270 · 📋 650 - 8% open · ⏱️ 12.02.2021):

	```
	git clone https://github.com/annoviko/pyclustering
	```
- [PyPi](https://pypi.org/project/pyclustering) (📥 43K / month · 📦 28 · ⏱️ 25.11.2020):
	```
	pip install pyclustering
	```
- [Conda](https://anaconda.org/conda-forge/pyclustering) (📥 34K · ⏱️ 13.09.2021):
	```
	conda install -c conda-forge pyclustering
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/AugLy">AugLy</a></b> (🥉26 ·  ⭐ 4.3K) - A data augmentations library for audio, image, text, and video. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/AugLy) (👨‍💻 15 · 🔀 220 · 📦 25 · 📋 56 - 25% open · ⏱️ 01.02.2022):

	```
	git clone https://github.com/facebookresearch/AugLy
	```
- [PyPi](https://pypi.org/project/augly) (📥 1.9K / month · 📦 3 · ⏱️ 17.12.2021):
	```
	pip install augly
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/metric-learn">metric-learn</a></b> (🥉26 ·  ⭐ 1.2K) - Metric learning algorithms in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/metric-learn) (👨‍💻 21 · 🔀 220 · 📦 190 · 📋 170 - 30% open · ⏱️ 17.11.2021):

	```
	git clone https://github.com/scikit-learn-contrib/metric-learn
	```
- [PyPi](https://pypi.org/project/metric-learn) (📥 9.9K / month · 📦 11 · ⏱️ 02.07.2020):
	```
	pip install metric-learn
	```
- [Conda](https://anaconda.org/conda-forge/metric-learn) (📥 5.3K · ⏱️ 02.07.2020):
	```
	conda install -c conda-forge metric-learn
	```
</details>
<details><summary><b><a href="https://github.com/SeldonIO/alibi-detect">alibi-detect</a></b> (🥉26 ·  ⭐ 1.1K) - Algorithms for outlier, adversarial and drift detection. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/SeldonIO/alibi-detect) (👨‍💻 15 · 🔀 120 · 📦 58 · 📋 220 - 39% open · ⏱️ 04.02.2022):

	```
	git clone https://github.com/SeldonIO/alibi-detect
	```
- [PyPi](https://pypi.org/project/alibi-detect) (📥 11K / month · 📦 5 · ⏱️ 18.01.2022):
	```
	pip install alibi-detect
	```
</details>
<details><summary><b><a href="https://github.com/ljvmiranda921/pyswarms">PySwarms</a></b> (🥉26 ·  ⭐ 880 · 💤) - A research toolkit for particle swarm optimization in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ljvmiranda921/pyswarms) (👨‍💻 43 · 🔀 290 · 📦 150 · 📋 200 - 8% open · ⏱️ 23.06.2021):

	```
	git clone https://github.com/ljvmiranda921/pyswarms
	```
- [PyPi](https://pypi.org/project/pyswarms) (📥 32K / month · 📦 6 · ⏱️ 03.01.2021):
	```
	pip install pyswarms
	```
</details>
<details><summary><b><a href="https://github.com/mars-project/mars">Mars</a></b> (🥉25 ·  ⭐ 2.3K) - Mars is a tensor-based unified framework for large-scale data.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/mars-project/mars) (👨‍💻 41 · 🔀 300 · 📋 960 - 16% open · ⏱️ 10.02.2022):

	```
	git clone https://github.com/mars-project/mars
	```
- [PyPi](https://pypi.org/project/pymars) (📥 4.2K / month · 📦 1 · ⏱️ 03.02.2022):
	```
	pip install pymars
	```
</details>
<details><summary><b><a href="https://github.com/ContinualAI/avalanche">avalanche</a></b> (🥉24 ·  ⭐ 730) - Avalanche: an End-to-End Library for Continual Learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ContinualAI/avalanche) (👨‍💻 49 · 🔀 110 · 📋 460 - 15% open · ⏱️ 09.02.2022):

	```
	git clone https://github.com/ContinualAI/avalanche
	```
- [PyPi](https://pypi.org/project/avalanche-lib) (📥 240 / month · ⏱️ 16.12.2021):
	```
	pip install avalanche-lib
	```
</details>
<details><summary><b><a href="https://github.com/minrk/findspark">findspark</a></b> (🥉24 ·  ⭐ 430) - Find pyspark to make it importable. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/minrk/findspark) (👨‍💻 14 · 🔀 66 · 📦 2.2K · 📋 22 - 54% open · ⏱️ 17.01.2022):

	```
	git clone https://github.com/minrk/findspark
	```
- [PyPi](https://pypi.org/project/findspark) (📥 2.2M / month · 📦 140 · ⏱️ 17.01.2022):
	```
	pip install findspark
	```
- [Conda](https://anaconda.org/conda-forge/findspark) (📥 610K · ⏱️ 19.01.2022):
	```
	conda install -c conda-forge findspark
	```
</details>
<details><summary><b><a href="https://github.com/trevorstephens/gplearn">gplearn</a></b> (🥉23 ·  ⭐ 1.1K) - Genetic Programming in Python, with a scikit-learn inspired API. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/trevorstephens/gplearn) (👨‍💻 11 · 🔀 190 · 📦 220 · 📋 180 - 26% open · ⏱️ 18.10.2021):

	```
	git clone https://github.com/trevorstephens/gplearn
	```
- [PyPi](https://pypi.org/project/gplearn) (📥 2.7K / month · 📦 10 · ⏱️ 01.06.2019):
	```
	pip install gplearn
	```
- [Conda](https://anaconda.org/conda-forge/gplearn) (📥 1.8K · ⏱️ 18.06.2020):
	```
	conda install -c conda-forge gplearn
	```
</details>
<details><summary><b><a href="https://github.com/astroML/astroML">AstroML</a></b> (🥉23 ·  ⭐ 800) - Machine learning, statistics, and data mining for astronomy and.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/astroML/astroML) (👨‍💻 30 · 🔀 280 · 📋 140 - 40% open · ⏱️ 25.01.2022):

	```
	git clone https://github.com/astroML/astroML
	```
- [PyPi](https://pypi.org/project/astroML) (📥 2.7K / month · 📦 33 · ⏱️ 25.01.2022):
	```
	pip install astroML
	```
- [Conda](https://anaconda.org/conda-forge/astroml) (📥 27K · ⏱️ 26.01.2022):
	```
	conda install -c conda-forge astroml
	```
</details>
<details><summary><b><a href="https://github.com/MaxHalford/prince">Prince</a></b> (🥉23 ·  ⭐ 760) - Python factor analysis library (PCA, CA, MCA, MFA, FAMD). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/MaxHalford/prince) (👨‍💻 12 · 🔀 130 · 📦 180 · 📋 100 - 33% open · ⏱️ 28.12.2021):

	```
	git clone https://github.com/MaxHalford/prince
	```
- [PyPi](https://pypi.org/project/prince) (📥 18K / month · 📦 5 · ⏱️ 06.10.2020):
	```
	pip install prince
	```
- [Conda](https://anaconda.org/conda-forge/prince-factor-analysis) (📥 9.3K · ⏱️ 30.04.2021):
	```
	conda install -c conda-forge prince-factor-analysis
	```
</details>
<details><summary><b><a href="https://github.com/airbnb/streamalert">StreamAlert</a></b> (🥉22 ·  ⭐ 2.7K) - StreamAlert is a serverless, realtime data analysis framework.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/airbnb/streamalert) (👨‍💻 33 · 🔀 320 · 📋 340 - 24% open · ⏱️ 04.11.2021):

	```
	git clone https://github.com/airbnb/streamalert
	```
</details>
<details><summary><b><a href="https://github.com/ml-tooling/opyrator">opyrator</a></b> (🥉20 ·  ⭐ 2.6K · 💤) - Turns your machine learning code into microservices with web API,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ml-tooling/opyrator) (👨‍💻 4 · 🔀 110 · 📦 31 · 📋 24 - 8% open · ⏱️ 06.05.2021):

	```
	git clone https://github.com/ml-tooling/opyrator
	```
- [PyPi](https://pypi.org/project/opyrator) (📥 140 / month · ⏱️ 04.05.2021):
	```
	pip install opyrator
	```
- [Conda](https://anaconda.org/conda-forge/opyrator) (📥 35 · ⏱️ 08.01.2022):
	```
	conda install -c conda-forge opyrator
	```
</details>
<details><summary><b><a href="https://github.com/EpistasisLab/scikit-rebate">scikit-rebate</a></b> (🥉20 ·  ⭐ 340 · 💤) - A scikit-learn-compatible Python implementation of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/EpistasisLab/scikit-rebate) (👨‍💻 13 · 🔀 62 · 📋 32 - 40% open · ⏱️ 15.02.2021):

	```
	git clone https://github.com/EpistasisLab/scikit-rebate
	```
- [PyPi](https://pypi.org/project/skrebate) (📥 2.5K / month · 📦 40 · ⏱️ 20.03.2021):
	```
	pip install skrebate
	```
- [Conda](https://anaconda.org/conda-forge/skrebate) (📥 24K · ⏱️ 16.02.2021):
	```
	conda install -c conda-forge skrebate
	```
</details>
<details><summary><b><a href="https://github.com/eltonlaw/impyute">impyute</a></b> (🥉20 ·  ⭐ 310) - Data imputations library to preprocess datasets with missing data. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/eltonlaw/impyute) (👨‍💻 11 · 🔀 43 · 📦 130 · 📋 64 - 42% open · ⏱️ 06.11.2021):

	```
	git clone https://github.com/eltonlaw/impyute
	```
- [PyPi](https://pypi.org/project/impyute) (📥 2.1K / month · 📦 3 · ⏱️ 29.04.2019):
	```
	pip install impyute
	```
</details>
<details><summary><b><a href="https://github.com/yzhao062/SUOD">SUOD</a></b> (🥉20 ·  ⭐ 310) - (MLSys 21) An Acceleration System for Large-scare Unsupervised Heterogeneous.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/yzhao062/SUOD) (👨‍💻 1 · 🔀 40 · 📦 410 · 📋 8 - 75% open · ⏱️ 02.10.2021):

	```
	git clone https://github.com/yzhao062/SUOD
	```
- [PyPi](https://pypi.org/project/suod) (📥 35K / month · ⏱️ 01.10.2021):
	```
	pip install suod
	```
</details>
<details><summary><b><a href="https://github.com/pykale/pykale">pykale</a></b> (🥉19 ·  ⭐ 320) - Knowledge-Aware machine LEarning (KALE): accessible machine learning.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pykale/pykale) (👨‍💻 16 · 🔀 39 · 📋 80 - 12% open · ⏱️ 20.01.2022):

	```
	git clone https://github.com/pykale/pykale
	```
- [PyPi](https://pypi.org/project/pykale) (📥 46 / month · ⏱️ 13.10.2021):
	```
	pip install pykale
	```
</details>
<details><summary><b><a href="https://github.com/alegonz/baikal">baikal</a></b> (🥉18 ·  ⭐ 590 · 💤) - A graph-based functional API for building complex scikit-learn.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/alegonz/baikal) (👨‍💻 2 · 🔀 29 · 📦 3 · 📋 20 - 30% open · ⏱️ 11.04.2021):

	```
	git clone https://github.com/alegonz/baikal
	```
- [PyPi](https://pypi.org/project/baikal) (📥 660 / month · 📦 1 · ⏱️ 15.11.2020):
	```
	pip install baikal
	```
- [Conda](https://anaconda.org/conda-forge/cython-blis) (📥 1.2M · ⏱️ 04.11.2021):
	```
	conda install -c conda-forge cython-blis
	```
</details>
<details><summary><b><a href="https://github.com/rasbt/biopandas">BioPandas</a></b> (🥉18 ·  ⭐ 410) - Working with molecular structures in pandas DataFrames. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rasbt/biopandas) (👨‍💻 8 · 🔀 90 · 📋 39 - 38% open · ⏱️ 04.01.2022):

	```
	git clone https://github.com/rasbt/biopandas
	```
- [PyPi](https://pypi.org/project/biopandas) (📥 2.5K / month · 📦 9 · ⏱️ 24.09.2021):
	```
	pip install biopandas
	```
- [Conda](https://anaconda.org/conda-forge/biopandas) (📥 96K · ⏱️ 31.08.2021):
	```
	conda install -c conda-forge biopandas
	```
</details>
<details><summary><b><a href="https://github.com/jmschrei/apricot">apricot</a></b> (🥉16 ·  ⭐ 400) - apricot implements submodular optimization for the purpose of selecting.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jmschrei/apricot) (👨‍💻 4 · 🔀 40 · 📥 10 · 📦 22 · 📋 24 - 25% open · ⏱️ 18.11.2021):

	```
	git clone https://github.com/jmschrei/apricot
	```
- [PyPi](https://pypi.org/project/apricot-select) (📥 300 / month · 📦 3 · ⏱️ 28.09.2020):
	```
	pip install apricot-select
	```
</details>
<details><summary><b><a href="https://github.com/jrieke/traingenerator">traingenerator</a></b> (🥉13 ·  ⭐ 1.1K · 💤) - A web app to generate template code for machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jrieke/traingenerator) (👨‍💻 3 · 🔀 160 · 📋 16 - 81% open · ⏱️ 29.04.2021):

	```
	git clone https://github.com/jrieke/traingenerator
	```
</details>
<details><summary>Show 15 hidden projects...</summary>

- <b><a href="https://github.com/datalad/datalad">datalad</a></b> (🥈32 ·  ⭐ 280) - Keep code, data, containers under control with git and git-annex. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/deepmind/pysc2">pysc2</a></b> (🥈29 ·  ⭐ 7.4K · 💀) - StarCraft II Learning Environment. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/explosion/cython-blis">Cython BLIS</a></b> (🥈28 ·  ⭐ 180) - Fast matrix-multiplication as a self-contained Python library no.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/modAL-python/modAL">modAL</a></b> (🥉24 ·  ⭐ 1.6K · 💀) - A modular active learning framework for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/JustGlowing/minisom">minisom</a></b> (🥉23 ·  ⭐ 1K) - MiniSom is a minimalistic implementation of the Self Organizing Maps. <code><a href="https://tldrlegal.com/search?q=CC-BY-3.0">❗️CC-BY-3.0</a></code>
- <b><a href="https://github.com/Project-MONAI/MONAILabel">MONAILabel</a></b> (🥉23 ·  ⭐ 200 · ➕) - MONAI Label is an intelligent open source image labeling and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/cleanlab/cleanlab">cleanlab</a></b> (🥉22 ·  ⭐ 2.6K) - The standard package for machine learning with label errors,.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/flennerhag/mlens">mlens</a></b> (🥉21 ·  ⭐ 710 · 💀) - ML-Ensemble high performance ensemble learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/vecxoz/vecstack">vecstack</a></b> (🥉21 ·  ⭐ 650 · 💀) - Python package for stacking (machine learning technique). <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/kLabUM/rrcf">rrcf</a></b> (🥉19 ·  ⭐ 350 · 💀) - Implementation of the Robust Random Cut Forest algorithm for anomaly.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/pandas-ml/pandas-ml">pandas-ml</a></b> (🥉18 ·  ⭐ 280 · 💀) - pandas, scikit-learn, xgboost and seaborn integration. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/solegalli/feature_engine">Feature Engine</a></b> (🥉18 ·  ⭐ 12) - Feature engineering package with sklearn like functionality. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/facebookresearch/NeuralCompression">NeuralCompression</a></b> (🥉16 ·  ⭐ 240 · ➕) - A collection of tools for neural compression enthusiasts. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/dstackai/dstack">dstack</a></b> (🥉12 ·  ⭐ 180) - An open-source tool to rapidly develop data applications with Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/Palashio/nylon">nylon</a></b> (🥉12 ·  ⭐ 78 · 💤) - An intelligent, flexible grammar of machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>

---

## Related Resources

- [**Papers With Code**](https://paperswithcode.com): Discover ML papers, code, and evaluation tables.
- [**Sotabench**](https://sotabench.com): Discover & compare open-source ML models.
- [**Google Dataset Search**](https://toolbox.google.com/datasetsearch): Dataset search engine by Google.
- [**Dataset List**](https://www.datasetlist.com/): List of the biggest ML datasets from across the web.
- [**Awesome Public Datasets**](https://github.com/awesomedata/awesome-public-datasets): A topic-centric list of open datasets.
- [**Best-of lists**](https://best-of.org): Discover other best-of lists with awesome open-source projects on all kinds of topics.
- [**best-of-python-dev**](https://github.com/ml-tooling/best-of-python-dev): A ranked list of awesome python developer tools and libraries.
- [**best-of-web-python**](https://github.com/ml-tooling/best-of-web-python): A ranked list of awesome python libraries for web development.

## Contribution

Contributions are encouraged and always welcome! If you like to add or update projects, choose one of the following ways:

- Open an issue by selecting one of the provided categories from the [issue page](https://github.com/ml-tooling/best-of-ml-python/issues/new/choose) and fill in the requested information.
- Modify the [projects.yaml](https://github.com/ml-tooling/best-of-ml-python/blob/main/projects.yaml) with your additions or changes, and submit a pull request. This can also be done directly via the [Github UI](https://github.com/ml-tooling/best-of-ml-python/edit/main/projects.yaml).

If you like to contribute to or share suggestions regarding the project metadata collection or markdown generation, please refer to the [best-of-generator](https://github.com/best-of-lists/best-of-generator) repository. If you like to create your own best-of list, we recommend to follow [this guide](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

For more information on how to add or update projects, please read the [contribution guidelines](https://github.com/ml-tooling/best-of-ml-python/blob/main/CONTRIBUTING.md). By participating in this project, you agree to abide by its [Code of Conduct](https://github.com/ml-tooling/best-of-ml-python/blob/main/.github/CODE_OF_CONDUCT.md).

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

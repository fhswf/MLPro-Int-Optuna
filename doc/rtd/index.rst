.. MLPro Documentations documentation master file, created by
   sphinx-quickstart on Wed Sep 15 12:06:53 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

MLPro-Int-Optuna - Integration of Optuna into MLPro
=================================================

Welcome to MLPro-Int-Optuna, an extension to MLPro to integrate the Optuna package.
MLPro is a middleware framework for standardized machine learning in Python. It is
developed by the South Westphalia University of Applied Sciences, Germany, and provides
standards, templates, and processes for hybrid machine learning applications. Optuna, in
turn, provides state-of-the-art algorithms for hyper parameter tuning in the context of machine
learning model development.

MLPro-Int-Optuna provides wrapper classes that enable the use of the Hyper Parameter Tuning mechanism
in your MLPro applications. The use of these wrappers is illustrated in following example programs.



**Preparation**
   Before running the examples, please install the latest versions of MLPro, Optuna, and MLPro-Int-Optuna as follows:

   .. code-block:: bash

      pip install mlpro-int-optuna[full] --upgrade


**See also**
   - `MLPro - Machine Learning Professional <https://mlpro.readthedocs.io>`_
   - `MLPro-BF-ML - Sub-framework for machine learning <https://mlpro.readthedocs.io/en/latest/content/02_basic_functions/mlpro_bf/sub/layer4_machine_learning/03_training_and_tuning.html>`_
   - `Optuna - Distributed Asynchronous Hyper-parameter Optimization <https://optuna.org/>`_
   - `Further MLPro extensions <https://mlpro.readthedocs.io/en/latest/content/04_extensions/main.html>`_
   - `MLPro-Int-Optuna on GitHub <https://github.com/fhswf/MLPro-Int-Optuna>`_

.. toctree::
   :hidden:
   :maxdepth: 2
   :caption: HOME


   self

.. toctree::
   :maxdepth: 2
   :caption: EXAMPLE POOL
   :glob:

   content/01_examples_pool/*

.. toctree::
   :maxdepth: 2
   :caption: API REFERENCES
   :glob:

   content/02_api_references/*

.. toctree::
   :maxdepth: 2
   :caption: ABOUT
   :glob:

   content/03_about/*

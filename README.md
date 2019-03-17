# case-study-WenjieLuo2333
case-study-WenjieLuo2333 created by GitHub Classroom

## Chosen Project: Keras<br>
### Brief Intro<br>
  Keras is a high-level neural networks API, capable of running on top of Tensorflow, Theano, and CNTK.<sup>[[1]](https://towardsdatascience.com/introduction-to-deep-learning-with-keras-17c09e4f0eb2)</sup><br>
  In this case study, I will focus more on a tensorflow backend Keras.<br>
  #### Chosen Languase<br>
  In my opinion, Keras is a high-level lib on Tf, Theano, CNTK written in python.<br>
  However, the backends are not pure-python frameworks.<br>
  Tensorflow and Theano's core is written in a combination of highly-optimized C++ and CUDA(Gor GPU calculation) and then packaged with user-friendly API written in Python.<br>
  CNTK is a pure C++ framework developed by CNTK.<br>
  However, the tensorflow backend Keras should be the most commonly used one.<br><br>
  #### Why choose such languages.
  The core of the Keras backends are all in C++ because of the faster working efficiency.<br>
  C++ is a Compiled language that will be compiled into bytecode before running. However, Python is an Interpreted Language which means the python will be run row by row. And each time when you run a python scripts, the interpreter works once. Thus it will have slower execution speed compared with languages like C++.<br>
  However, Python is probably the most comfortable language for users and it also that easy to integrate and have control to a C++ backend.<sup>[[2]](https://stackoverflow.com/questions/35677724/tensorflow-why-was-python-the-chosen-language)</sup><br/>Due to the user-friendly characteristic, almost all the deep learning frameworks offer python API.<br>
  I will use Python even if the project is developed today because of the ease of programming.<br><br>
  #### Build System for Keras
  Cmake and Bazel is used to build. However, according to the [Tensorflow Install Guide](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/contrib/cmake) that CMAKE build is deprecated for TensorFlow and Bazel is recommanded.GCC and [NVCC](https://en.wikipedia.org/wiki/NVIDIA_CUDA_Compiler) are needed to build a tensorflow based Keras with GPU acceleration.<br><br>
  #### Frameworks and libraries used in Keras
  ```CNTK```/```Tensorflow```/```Theano```<br>
  ```numpy```
  Quote from [Keras Team](https://github.com/keras-team/keras/tree/master/keras/backend)
  

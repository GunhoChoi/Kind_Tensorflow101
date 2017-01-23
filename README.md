# What is Tensorflow?

- 텐서플로우란 무엇인가? (공식사이트번역 -> https://gist.github.com/haje01/202ac276bace4b25dd3f)
- 먼저 텐서플로우를 설치하자 (https://marcnu.github.io/2016-08-17/Tensorflow-v0.10-installed-from-scratch-Ubuntu-16.04-CUDA8.0RC-cuDNN5.1-1080GTX/)
- 튜토리얼은 Tensorflow version r0.12 Ubuntu 16.04, GPU enabled, Python 3.5, CUDA toolkit 8.0, CuDNN v5인 상태로 작성하였습니다.

# Tensorflow_Tutorial

1. 텐서플로우를 사용하기에 앞서 필요한 기본 변수들 = [ Variable, Constant, Placeholder ]
2. 텐서플로우로 기본적인 Linear function을 만들어보자 = [ y=w*x+b ]
3. 그나저나 텐서플로우를 써야하는 이유는 무엇일까? = [ only Numpy vs Numpy & Tensorflow ]
4. 그렇다면 이번엔 Convolutional Neural Network를 짜보자 = [ tf.conv2d(), tf.max_pool() ]
5. 매번 학습시킬순 없으니까 학습시킨 모델을 저장하고 불러오는 방법을 알아보자 = [ tf.train.Saver() ]
6. 모델이 깊어질수록 코드만으로 전체를 파악하기는 힘들다. 또한 정확도나 error를 시각화해서 보고싶다면? = [ Tensorboard ]
7. 이미 학습된 유명한 모델들을 가져다 쓰고 싶을때는 어떻게 할까? = [ Pretrained_Models ]

# Tensorflow Tools

1. 제일 기본이되는 Tensorflow API (https://www.tensorflow.org/api_docs/python/)
2. Tensorflow Visual Debugger (https://github.com/ericjang/tdb)
3. Hvass-Labs Tensorflow Tutorial (https://github.com/Hvass-Labs/TensorFlow-Tutorials)
4. Another Tensorflow Tutorial (https://github.com/nlintz/TensorFlow-Tutorials)
5. 텐서플로우 코드를 더 간단하게 바꿔주는 tf.slim (https://github.com/tensorflow/tensorflow/blob/a304537954a865752ad1b18461e6bd67b36082db/tensorflow/contrib/slim/README.md)

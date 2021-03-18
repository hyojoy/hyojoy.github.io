---
title: colab에서 tensorflow 특정 버전 깔기 >3< (by tensorflow1)
tags:
  - tensorflow
  - colab
---

colab에서 기존에 있는 tensorflow2 를 이용하지 않고 1을 이용하고 싶어졌다. 

즉 특정 버전을 깔려고 한거여..

<!--more-->

4.  pip install 로 다음 명령어 입력

```python
!pip uninstall tensorflow
!pip install --ignore-installed --upgrade tensorflow==1.15
```



2. ************런타임 다시 실행하기 꼭 눌러줘야함 *************

​     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~타란~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

```python
import tensorflow as tf
tf.__version__
1.15.0

```

3. 확인 완료



기존에 있는 tensorflow version 무시하고 새로 설치 성공


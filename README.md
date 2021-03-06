# TensorFlow in JavaScript

![Javascript for TensorFlow](docs/images/tensorflow-js.gif)

TensorFlow Handbook for JavaScript/TypeScript

- This repository is the [JavaScript Chapter](https://tf.wiki/zh/deployment/javascript.html) for [简单粗暴TensorFlow | A Concise Handbook of TensorFlow](https://tf.wiki)
- Read from this repository: <https://huan.github.io/tensorflow-handbook-javascript/>

## TODO

- [ ] save metadata
- [ ] finish chat script
- [ ] good default super parameters
- [ ] InputLayer to use a shape as `[null]` for dynamic size

## Usage

TL;DR:

```shell
npm install
npm start
```

### 1 Install

```shell
npm install
```

### 2 Train

```shell
npm run train -- --batch_size 32 --epochs 3 --latent_dim 64 --num_samples 10000 dist/
```

### 3 Chat

```shell
npm run chat
```

### 4 Web Demo

1. Regression: <https://huan.github.io/tensorflow-handbook-javascript/regression.html>
1. MobileNet: <https://huan.github.io/tensorflow-handbook-javascript/mobilenet.html>

## TURORIAL

- [简单粗暴TensorFlow | A Concise Handbook of TensorFlow](https://tf.wiki)
- [Machine Learning For Front-End Developers With Tensorflow.js](https://www.smashingmagazine.com/2019/09/machine-learning-front-end-developers-tensorflowjs/)

## My Slide

[![Machine Learning in JavaScript](docs/images/machine-learning-in-javascript.png)](https://docs.google.com/presentation/d/10u2hKAz4VjryCYr-oHxcxX4HzFeKOir7lq79ASV6TIA/edit?usp=sharing)

> Google Slide: <https://docs.google.com/presentation/d/10u2hKAz4VjryCYr-oHxcxX4HzFeKOir7lq79ASV6TIA/edit?usp=sharing>

## My Contribution

- [TensorFlow.js Example: Sequence-to-Sequence English-French Translation](https://github.com/tensorflow/tfjs-examples/blob/master/translation/translation.ts)
    - [PR#243: Add native JavaScript(TypeScript) to replace translation.py](https://github.com/tensorflow/tfjs-examples/pull/243)

## Author

[Huan](https://github.com/huan) [(李卓桓)](http://linkedin.com/in/zixia), Google Developers Expert in Machine Learning (ML GDE), <zixia@zixia.net>

[![Profile of Huan LI (李卓桓) on StackOverflow](https://stackoverflow.com/users/flair/1123955.png)](https://stackoverflow.com/users/1123955/huan)

## Copyright & License

- Code & Docs © 2019-now Huan LI (李卓桓) <zixia@zixia.net>
- Code released under the Apache-2.0 License
- Docs released under Creative Commons

[中文版](README_cn.md)

# DeepSpeech on PaddlePaddle

![License](https://img.shields.io/badge/license-Apache%202-red.svg)
![python version](https://img.shields.io/badge/python-3.7+-orange.svg)
![support os](https://img.shields.io/badge/os-linux-yellow.svg)

*DeepSpeech on PaddlePaddle* is an open-source implementation of end-to-end Automatic Speech Recognition (ASR) engine, with [PaddlePaddle](https://github.com/PaddlePaddle/Paddle) platform. Our vision is to empower both industrial application and academic research on speech recognition, via an easy-to-use, efficient and scalable implementation, including training, inference & testing module, and demo deployment.


## Models

* [Baidu's Deep Speech2](http://proceedings.mlr.press/v48/amodei16.pdf)

## Setup

* python>=3.7
* paddlepaddle>=2.0.0

- Run the setup script for the remaining dependencies

```bash
git clone https://github.com/PaddlePaddle/DeepSpeech.git
cd DeepSpeech
pushd tools; make; popd
source tools/venv/bin/activate
bash setup.sh
```

- Source venv before do experiment.

```bash
source tools/venv/bin/activate
```

## Getting Started

Please see [Getting Started](docs/src/geting_started.md) and [tiny egs](examples/tiny/README.md).

## More Information  

* [Install](docs/src/install.md)  
* [Getting Started](docs/src/geting_stared.md)  
* [Data Prepration](docs/src/data_preparation.md)  
* [Data Augmentation](docs/src/augmentation.md)  
* [Ngram LM](docs/src/ngram_lm.md)  
* [Server Demo](docs/src/server.md)  
* [Benchmark](docs/src/benchmark.md)  
* [Relased Model](docs/src/released_model.md)  
* [FAQ](docs/src/faq.md)  


## Questions and Help

You are welcome to submit questions and bug reports in [Github Issues](https://github.com/PaddlePaddle/DeepSpeech/issues). You are also welcome to contribute to this project.


## License

DeepSpeech is provided under the [Apache-2.0 License](./LICENSE).

## Acknowledgement

We depends on many open source repos. See [References](docs/src/reference.md) for more information.

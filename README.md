# Benchmark Distributed Training Frameworks

![GitHub](https://img.shields.io/github/license/breezeml/benchmark_distributed_training_framework) ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/breezeml/benchmark_distributed_training_framework) ![GitHub commit activity](https://img.shields.io/github/commit-activity/m/breezeml/benchmark_distributed_training_framework)

This repo is used to benchmark different distributed training frameworks. We walkthrough the basic usage of each framework and benchmark the performance of each framework on different hardware.

Another main goal of this repo is to test the user-friendly of each framework. We will try to use each framework to train a simple model and see how easy it is to use.

The following frameworks will be tested:
- [x] Ray
- [ ] Torch Elastic
- [ ] HuggingFace accelerate
- [ ] Horvord
- [ ] MosicML Composer
- [ ] PyTorch Lighting


## :rocket: Quick Start

```bash
# clone the repo
git@github.com:breezeml/benchmark_distributed_training_framework.git

# create a conda env
conda create -n benchmark_distributed_training python=3.8
```

## :hammer: Framework Walkthrough

### Ray [[doc]](https://docs.ray.io/en/latest/train/examples.html)

- [x] simple quick start
- [x] ray cluster on aws
- [ ] ray job submit
- [ ] ray pytorch training
    - [x] mnist
        - [x] M1 Pro Local
        - [x] AWS 4 T4 GPUs
    - [ ] HuggingFace transformer

### Torch Elastic [[doc]](https://pytorch.org/docs/stable/elastic/run.html)

### HuggingFace accelerate [doc](https://huggingface.co/docs/transformers/accelerate)

### Horvord

### MosicML Composer [doc](https://mosaicml.com/docs/)


### PyTorch Lighting

## :chart_with_upwards_trend: Performance Results

- [ ] WIP


## :books: References

- [PyTorch Distributed Training](https://pytorch.org/tutorials/intermediate/dist_tuto.html)

## :memo: License

MIT


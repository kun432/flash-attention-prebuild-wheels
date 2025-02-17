# flash-attention pre-build wheels

This repository provides wheels for the pre-build [flash-attention](https://github.com/Dao-AILab/flash-attention).  

Since building flash-attention takes a **very long time** and is resource-intensive, 
I also build and provide combinations of CUDA and PyTorch that are not officially distributed.

The building Github Actions Workflow can be found [here](./.github/workflows/build.yml).

The built packages is available on the [release page](https://github.com/mjun0812/flash-attention-prebuild-wheels/releases).


## Install

```bash
pip install https://github.com/mjun0812/flash-attention-prebuild-wheels/releases/download/v0.0.0/flash_attn-2.6.3+cu124torch2.5-cp312-cp312-linux_x86_64.whl
```

# [KDD'24] Heterogeneity-Informed Meta-Parameter Learning for Spatiotemporal Time Series Forecasting

**Our work is already accepted by KDD2024 research track. The citation information will be updated when the official proceeding is online.** [![Arxiv link](https://img.shields.io/static/v1?label=arXiv&message=HimNet&color=red&logo=arxiv)](https://arxiv.org/abs/2405.10800)

![method](https://github.com/XDZhelheim/HimNet/assets/57553691/2c56cd09-86b3-4172-aa40-25cac28002fc)

### Citation

```
@article{dong2024heterogeneity,
  title={Heterogeneity-Informed Meta-Parameter Learning for Spatiotemporal Time Series Forecasting},
  author={Dong, Zheng and Jiang, Renhe and Gao, Haotian and Liu, Hangchen and Deng, Jinliang and Wen, Qingsong and Song, Xuan},
  journal={arXiv preprint arXiv:2405.10800},
  year={2024}
}
```

### Performance on Spatiotemporal Forecasting Benchmarks

![image](https://github.com/XDZhelheim/HimNet/assets/57553691/fad0564a-f6f7-4971-85b8-822810a26e1d)

### Required Packages

```
pytorch>=1.12
numpy
pandas
matplotlib
pyyaml
pickle
torchinfo
```

### Training Commands

```bash
cd scripts/
python train.py -d <dataset> -g <gpu_id>
```

`<dataset>`:
- METRLA
- PEMSBAY
- PEMS04
- PEMS07
- PEMS08

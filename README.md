# [KDD'24] Heterogeneity-Informed Meta-Parameter Learning for Spatiotemporal Time Series Forecasting

Zheng Dong*, Renhe Jiang*, Haotian Gao, Hangchen Liu, Jinliang Deng, Qingsong Wen, and Xuan Song#. 2024. Heterogeneity-Informed Meta-Parameter Learning for Spatiotemporal Time Series Forecasting. _In Proceedings of the 30th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD '24)._ (*Equal Contribution, #Corresponding Author)

[![ACM](https://img.shields.io/static/v1?label=ACM&message=10.1145/3637528.3671961&color=blue&logo=acm)](https://dl.acm.org/doi/abs/10.1145/3637528.3671961) &emsp;&emsp; [![Arxiv link](https://img.shields.io/static/v1?label=arXiv&message=2405.10800&color=red&logo=arxiv)](https://arxiv.org/abs/2405.10800) (including additional PEMS03 results)

![method](https://github.com/user-attachments/assets/0e2f4006-505c-407d-bffa-7f39f4184540)

### Citation

```
@inproceedings{dong2024heterogeneity,
  title={Heterogeneity-Informed Meta-Parameter Learning for Spatiotemporal Time Series Forecasting},
  author={Dong, Zheng and Jiang, Renhe and Gao, Haotian and Liu, Hangchen and Deng, Jinliang and Wen, Qingsong and Song, Xuan},
  booktitle={Proceedings of the 30th ACM SIGKDD Conference on Knowledge Discovery and Data Mining},
  pages={631--641},
  year={2024}
}
```

### Performance on Spatiotemporal Forecasting Benchmarks

![HimNet-table-03](https://github.com/user-attachments/assets/a4a7c44f-3abb-4b71-9249-43bbb01ef70d)

### Required Packages

```
pytorch>=1.12
numpy
pandas
matplotlib
pyyaml
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
- PEMS03
- PEMS04
- PEMS07
- PEMS08

# [KDD'24] Heterogeneity-Informed Meta-Parameter Learning for Spatiotemporal Time Series Forecasting

**Our work is already accepted by KDD2024 research track. The citation information will be updated when the official proceeding is online.**

![method](https://github.com/XDZhelheim/HimNet/assets/57553691/eddef061-567d-44b4-8be3-09812ce73016)

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

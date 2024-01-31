# HimNet

**Heterogeneity-Informed Meta-Parameter Learning for Spatiotemporal Time Series Forecasting**

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

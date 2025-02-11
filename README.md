# TerraTorch-Examples
Examples for fine-tuning Prithvi on EO downstream tasks via TerraTorch

## Notebook examples

Sen1Floods11 Tutorial: [prithvi_v2_eo_300_tl_unet_sen1floods11.ipynb](prithvi_v2_eo_300_tl_unet_sen1floods11.ipynb)

[Open in Colab](https://colab.research.google.com/github/blumenstiel/TerraTorch-Examples/blob/main/prithvi_v2_eo_300_tl_unet_sen1floods11.ipynb)

HLS Burn Scars Tutorial: [prithvi_v2_eo_300_tl_unet_burnscars.ipynb](prithvi_v2_eo_300_tl_unet_burnscars.ipynb)

[Open in Colab](https://colab.research.google.com/github/blumenstiel/TerraTorch-Examples/blob/main/prithvi_v2_eo_300_tl_unet_burnscars.ipynb)

Multi-temporal Crop Tutorial: [prithvi_v2_eo_300_tl_unet_multitemporal_crop.ipynb](prithvi_v2_eo_300_tl_unet_multitemporal_crop.ipynb)

[Open in Colab](https://colab.research.google.com/github/blumenstiel/TerraTorch-Examples/blob/main/prithvi_v2_eo_300_tl_unet_multitemporal_crop.ipynb)

## Config examples for CLI

Sen1Floods11 config: [prithvi_v2_eo_300_tl_unet_sen1floods11.yaml](configs%2Fprithvi_v2_eo_300_tl_unet_sen1floods11.yaml)

Fine-tuning via CLI:
```shell
terratorch fit -c configs/prithvi_v2_eo_300_tl_unet_sen1floods11.yaml
```

HLS Burn Scars config: [prithvi_v2_eo_300_tl_unet_burnscars.yaml](configs%2Fprithvi_v2_eo_300_tl_unet_burnscars.yaml)

Fine-tuning via CLI:
```shell
terratorch fit -c configs/prithvi_v2_eo_300_tl_unet_burnscars.yaml
```

Multi-temporal Crop config: 

Fine-tuning via CLI:
```shell
terratorch fit -c configs/prithvi_v2_eo_300_tl_unet_multitemporal_crop.yaml
```
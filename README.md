# ADAM-ADMM
A Unified, Systematic Framework of Structured Weight Pruning for DNNs

## Content

`caffe-admm/` Customized Caffe for non-structured pruning (structured pruning version will be released soon)

`prototxt/` Sample prototxt for non-structured pruning

## Results
### 1. CaffeNet non-structured pruing

| compression ratio | top-1 | top-5 | download link |
|---|---|---|---|
| conv2-5 16.1x | 57.50% | 80.28% | http://bit.ly/2NUgpn4 |
| conv2-5 40.5x | 55.38% | 78.64% | http://bit.ly/2vm6jnl |

### 2. CaffeNet structured pruing

| compression ratio | top-1 | top-5 | download link |
|---|---|---|---|
| conv2-5 1.5x | 59.04% | 81.65% | http://bit.ly/2vlgWXD |
| conv2-5 4.8x | 57.47% | 80.15% | http://bit.ly/2NYF1Lv |
| conv2-5 13.2x | 55.33% | 78.82% | http://bit.ly/2NYqzmB |

## Our paper

"ADAM-ADMM: A Unified, Systematic Framework of Structured Weight Pruning for DNNs" (https://arxiv.org/abs/1807.11091)

## Citation

If you use these models or code in your research, please cite:

```
@article{zhang2018admm,
  title={ADAM-ADMM: A Unified, Systematic Framework of Structured Weight Pruning for DNNs},
  author={Zhang, Tianyun and Zhang, Kaiqi and Ye, Shaokai and Li, Jiayu and Tang, Jian and Wen, Wujie and Fardad, Makan and Wang, Yanzhi},
  journal={arXiv preprint arXiv:1807.11091},
  year={2018}
}
```
# Table Recognition
Table Recognition is an open source table recognition toolbox based on PyTorch.

## Supported methods

- [ ] [LGPMA](demo/table_recognition/lgpma) (ICDAR 2021)

## Development Environment
The recommended environment requirements can be found in [mmdetection](https://github.com/open-mmlab/mmdetection/). Follows are the lowest compatible environment.

| Basic Env   | version |
| :---------- | ------- |
| Python      | 3.6+    |
| cuda        | 10.0+   |
| cudnn       | 7.6.3+  |
| pytorch     | 1.3.0+  |
| torchvision | 0.4.1+  |
| opencv      | 3.0.0+  |

# Installation and Development Instruction 

To Download the repository and install the davarocr, please follow the instructions:

```shell
git clone https://github.com/cv-small-snails/tablerecognition.git
cd tablerecognition/
bash setup.sh
```

This script will automatically download and install the "mmdetection" and "mmcv-full". You can also manually install them followinging the [official instructions](https://github.com/open-mmlab/mmdetection/)

Going to the specific algorithm's directory to see more details.

## License
This project is released under the [Apache 2.0 license](./LICENSE)
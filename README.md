# UNet-Pancreas-segmentation
用Unet进行胰腺分割，数据来自Medical Segmentation Decathlon，nii格式转化成png
## Usage

### 1. Prepare data
数据下载链接: https://pan.baidu.com/s/1WkmbLB_x9iw656I_2Vw5Kw 提取码: kn2e       

```bash
.
├── image
│   ├──pancreas_305
│   ├──pancreas_308
│   └──...
└── label
    ├── pancreas_305
    ├── pancreas_308          
    └──...          
```

### 2. Environment

### 3. Train/Test

- Run the train script. 

```bash
python train.py 
```

- Run the test script.

```bash
python test.py
```

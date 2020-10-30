# raspberrypi-wheels
Wheels built on Raspberry Pi 4 8GB for python 3.8.6 for pytorchm spacy and fastai.

## Description <a name="description"></a>
The following wheels have been compiled on a Raspberry Pi 4 8GB with Ubuntu 20.10
```
hostnamectl
Static hostname: raspberrypi
Icon name: computer
Machine ID: ...
Boot ID: ...
Operating System: Ubuntu 20.10
Kernel: Linux 5.8.0-1006-raspi
Architecture: arm64


uname -a
Linux raspberrypi 5.8.0-1006-raspi #9-Ubuntu SMP PREEMPT Fri Oct 16 12:55:30 UTC 2020 aarch64 aarch64 aarch64 GNU/Linux
```
- Apache Arrow 3.0.0: built following instructions from the Apache official [repo](https://github.com/apache/arrow/blob/master/docs/source/developers/python.rst).
- Pytorch 1.7.0: instructions
```
sudo apt-get install python3-numpy python3-wheel python3-setuptools python3-future python3-yaml python3-six python3-requests python3-pip python3-pillow openmpi-bin
pip install pyyaml wheel numpy ninja setuptools cmake cffi typing_extensions future six requests dataclasses
pip install torch-1.6.0a0+b31f58d-cp37-cp37m-linux_aarch64.whl
pip install torchvision-0.7.0a0+78ed10c-cp37-cp37m-linux_aarch64.whl
```


## Contents <a name="contents"></a>
- pyarrow-3.0.0.dev55+gf6501a5ee-cp38-cp38-linux_aarch64.whl
- torch-1.6.0a0+b31f58d-cp37-cp37m-linux_aarch64.whl [download here](https://drive.google.com/file/d/1ooH36atI6PpuS4rWTR_3tm7Ul87sOveA/view?usp=sharing)
- torchvision-0.7.0a0+78ed10c-cp37-cp37m-linux_aarch64.whl
- blis-0.4.1-cp37-cp37m-manylinux2014_aarch64.whl 
- spacy-2.2.4-cp37-cp37m-manylinux2014_aarch64.whl

## Fastai Installation
Pytorch, torchvision, blis and spacy have to be installed from wheels as packages are not available for this platform.
```
sudo apt install libatlas3-basesudo 
pip3 install numpy
python3 -m pip install Pillow==6.1
pip install torch-1.6.0a0+b31f58d-cp37-cp37m-linux_aarch64.whl 
pip install torchvision-0.7.0a0+78ed10c-cp37-cp37m-linux_aarch64.whl
pip install blis-0.4.1-cp37-cp37m-manylinux2014_aarch64.whl 
pip install spacy-2.2.4-cp37-cp37m-manylinux2014_aarch64.whl
pip install fastai --no-deps

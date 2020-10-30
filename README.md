# raspberrypi-wheels
Wheels built on Raspberry Pi 4 8GB for python 3.8.6

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
pip install torch-1.7.0a0-cp37-cp37m-linux_aarch64.whl
pip install torchvision-0.8.0a0+45f960c-cp37-cp37m-linux_aarch64.whl
```


## Contents <a name="contents"></a>
- pyarrow-3.0.0.dev55+gf6501a5ee-cp38-cp38-linux_aarch64.whl
- torch-1.7.0a0-cp37-cp37m-linux_aarch64.whl [download here](https://drive.google.com/file/d/1nYbF8AusjemBqW_jmw3ENXKGVWFSVTsr/view?usp=sharing)
- torchvision-0.8.0a0+45f960c-cp37-cp37m-linux_aarch64.whl [download here](https://drive.google.com/file/d/1rpmMtl3F2J397JDDqyj7uDJYvdEF-Jwl/view?usp=sharing)

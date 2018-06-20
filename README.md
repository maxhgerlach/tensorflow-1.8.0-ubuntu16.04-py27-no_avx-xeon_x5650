# tensorflow-1.8.0-ubuntu16.04-py27-no_avx-xeon_x5650

Tensorflow 1.8.0 wheel built for Python 2.7 without GPU on a Ubuntu 16.04 VM
running on a Xeon X5650 CPU that does not support AVX instructions (it's older
than Sandy Bridge).

Usage:

```
pip install tensorflow-1.8.0-cp27-cp27mu-linux_x86_64.whl
```

This could be useful if your CPU is too old for the official Tensorflow package
on PyPI.

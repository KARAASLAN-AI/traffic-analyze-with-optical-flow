# traffic-analyze-with-optical-flow

In this application, optical flow performed on traffic data.

Downloading video data on my drive
https://drive.google.com/drive/folders/1_Y7Xy3hWqVj_crhCLRrxnxWzUgjhw8fw?usp=sharing

##  Test with Opencv-CUDA

> For Opencv-CUDA installation follow this link: <br/>
https://www.youtube.com/watch?v=YsmhKar8oOc

``` 
python demo.py --video video/ada.m4v --device gpu
```

![gpu_flow](https://github.com/KARAASLAN-AI/traffic-analyze-with-optical-flow/blob/main/images/flow_gpu.gif)

## Test on cpu

``` 
python demo.py --video video/ada.m4v --device cpu
```

![cpu_flow](https://github.com/KARAASLAN-AI/traffic-analyze-with-optical-flow/blob/main/images/flow_cpu.gif)

## Contact

Mahmut KARAASLAN : mkaraaslan719@gmail.com



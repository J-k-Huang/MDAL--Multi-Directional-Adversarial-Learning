# MDAL--Multi-Directional-Adversarial-Learning
## Environment
* python   3.5.4  
* pytorch  1.0.0  
* numpy    1.15.2  
* torchvision  0.6.1  
## Benchmark
* Office-31 contains 4652 images across 31 classes from three domains: Amazon (A), DSLR (D), and Webcam (W). Office-31 dataset can be found [here](https://faculty.cc.gatech.edu/~judy/domainadapt/)
* Office-Home contains 15 500 images of 65 classes from four domains: Ar, Cl, Pr, and Rw. Office-Home dataset can be found [here](https://www.hemanthdv.org/officeHomeDataset.html)
* ImageCLEF-DA contins 12 common classes. ImageCLEF-DA dataset can be found [here](https://www.imageclef.org/2014/adaptation)
## Demo  
Train on task of p->c on ImageCLEF-DA
```  
cd MDAL--Multi-Directional-Adversarial-Learning
python trainxin_image_pc.py CDAN+E
```
## Contact  
If you have any problem about our code, feel free to contact jkhuang@cqu.edu.cn

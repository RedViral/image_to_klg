# image_to_klg
This is the code for co-fusion and elastic-fusion, which can convert images to klg file. enjoy it! 

The main.cpp is an using example for tum rgbd datasets.


## how to combile  
mkdir build  
cd build  
cmake ..  
make  

## how to use for tum rgbd datasets  
There need two params which are assiostions.txt(in which directroy also include rgb and depth dirs) and savepath  
Example: ./toklg   .../yourTumDataAssociationFile.txt   .../youSaveFile.klg 

By the way, the tum rgbd datasets can be downloaded at http://vision.in.tum.de/data/datasets/rgbd-dataset

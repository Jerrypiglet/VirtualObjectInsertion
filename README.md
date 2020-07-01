# Virtual Object Insertion
This repository contains the code to generate the object insertion results in paper [Inverse rendering for complex indoor scenes: Shape, spatially-varying lighting and svbrdf from a single image, CVPR 2020](https://drive.google.com/file/d/17K3RrWQ48gQynOhZHq1g5sQgjLjoMiPk/view). Please visit our [project webpage](http://cseweb.ucsd.edu/~viscomp/projects/CVPR20InverseIndoor/) for more information. 

We hope that the code can help reproduce the photorealistic object insertion results in our paper and compare future lighting estimation methods more easily. Please consider citing the paper if you find the code useful. Please contact [Zhengqin Li](zhl378@eng.ucsd.edu) if you have any questions.

# Results and Comparisons
The original models were trained by extending the SUNCG dataset with an SVBRDF-mapping. Since SUNCG is not available now due to copyright issues, we are not able to release the original models. Instead, we rebuilt a new high-quality synthetic indoor scene dataset and trained our models on it. We will release the new dataset in the near future. Some object insertion results on real images generated using our network trained on the new dataset are shown below.
![](http://cseweb.ucsd.edu/~viscomp/projects/CVPR20InverseIndoor/github/objectInsertion_test.png)
The quantitative and qualitative comparisons with prior works on object insertion are shown below. 
![](http://cseweb.ucsd.edu/~viscomp/projects/CVPR20InverseIndoor/github/objectInsertion.png)
![](http://cseweb.ucsd.edu/~viscomp/projects/CVPR20InverseIndoor/github/quantitative_objectInsertion.png)
Compared with our networks trained on SUNCG-based dataset, our networks trained on new dataset can predict more consistent lighting color and intensity. Therefore, it achieves better performance in user study. 

# Prerequisites
To run our code, you will need
* matlab
* python 
* Optix renderer. This is the an Optix-based GPU renderer implemented mainly in this project. Please find the renderer from this [link](https://github.com/lzqsd/OptixRenderer)

# Data 


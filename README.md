# Windows-64x-Caffe-Framework-Deepdream-installer

installer for complete caffe and pytorch deeplearning enviroment, designed to be as independant and self sufficient as possable, runs perfect even if fully offline since it includes everything it needs. (internet is required for initial installation). the caffe framework allows for older legacy codes / models to be fully compatable, and it runs projects very fast. we compliment it with pytorch for newer and advanced implimentations to provide the best of both worlds

Simple installation pictorial is located here: https://docs.google.com/document/d/1XBctrqGxNFSnIeFpS5KilV7HHQnWDgUesHikJdtHRkM/edit

Download link for entire project is located here: https://drive.google.com/file/d/1f0HPZ9A1O4nkRYT7U0ryX_xKH5AO-Gya/view

Yowza, that’s a big file. Try again with a file smaller than 25MB.
github does not like that i condensed everything down to a single 1.9 Gb .ZIP Archive so I am hosting everything on google docs/drive. Atleast their servers are fast. 


Whats Included? 
Caffe(64x) precompiled /w all dependencies/libs/third party(gflags, etc) built in. 
Anaconda2 64x (python version: 2.5)
Operating System and Vs2013 dependencies.
All BVLC ilsvrc12 imagenets/models pre-integrated.
BVLC /Examples pre-integrated, was missing from windows build. 
Third party deepdream/style-transfer projects pre-integrated
Added new scripts; helpful for pre/post-processing in some projects
Pytorch examples
BVLC /Data pre-integrated, was missing from windows build. This is for image classification/detection/labeling (etc)

The caffe executables within this project are very fast, smooth running (can run secondary in background) & more freeze/crash resistant on heavy workloads. Everything here will run perfectly fine on a laptop CPU with no graphics card. In the pytorch environment even the VGG19 network model implementations run flawlessly without GPU. (used to crash other caffe installs before project even loaded)

Overview:
Step 1)-  Main setup installation                   
Step 2)-  Installation of conda/python packages
Step 3)-  Deepdream Tests
Step 4)-  Neural Style transfer Tests
Step 5) - Computer Vision; object/image/class detection. Test
Step 6)-  Pytorch-Cpu installation & Tests

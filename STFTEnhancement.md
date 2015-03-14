# Introduction #
Describes how to install, use and experiment with the STFT enhancement
![http://www.sharat.org/Home/Fingerprint2.jpg](http://www.sharat.org/Home/Fingerprint2.jpg)

# Getting the code #
You can obtain a read-only version of the code using the following:
```
svn checkout http://sharat-cubs.googlecode.com/svn/trunk/stft-enhancement 
```
If you would like to contribute code/bug-fixes as well, please send me an e-mail to obtain read/write access to the repository.

# Details #
You can test the code by
```
[oimg,fimg,bwimg,eimg,enhimg] =  fft_enhance_cubs(imread('1_1.tif'));
%oimg -  [OUT] block orientation image(can be viewed using view_orientation_image.m)
%fimg  - [OUT] block frequency image(indicates ridge spacing)
%bwimg - [OUT] shows angular bandwidth image(filter bandwidth adapts near the singular points)
%eimg  - [OUT] energy image. Indicates the 'ridgeness' of a block (can be used for fingerprint segmentation)
%enhimg- [OUT] enhanced image
%img   - [IN]  input fingerprint image (HAS to be of DOUBLE type)
```

# Support #

Please submit all questions, concerns to http://groups.google.com/group/sharat-code .Please prefix [stft](stft.md) to your posts for easier search.
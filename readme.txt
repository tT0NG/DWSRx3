#################################
The executable files for:
NTIRE 2017 Super-Resolution Challenge - Track 1: Bicubic downscaling - x3
#################################
Language: python 2.7
Python package requirement: 
tensorflow w/GPU @ https://github.com/tensorflow/tensorflow
pywt @ https://github.com/PyWavelets/pywt
cv2  @ https://github.com/opencv/opencv
#################################
To execute: 
1. In terminal, type in 'python WvSRx3.py'
2. Then a promote asks for testing data set: 'Please enter the testing path [hit enter to run default set]:' 
3. Hit enter to run default testing set from DIV2K NTIRE which is stored at: ./Testx3Lum
4. The final results will be stored at: ./Resultx3Lum
5. Run FinalColorSRx3.m to generate final color SR and store the results in ./Resultx3Color
##################################
NOTE:
1. The testing data should be bicubic enlarged version of the original down-sampled version. For example, to generate x3 super-resolution results, the original x3 down-sampled low-resolution image should first be enlarged to x3 size, then fed the enlarged version to WvSR (as described in the fact sheet). Use generateTestX3.m to generate enlarged LR luminance image.
2. The WvSR wrights are stored at: ./Weightx3
3. The WvSR model is defined in: netx3.py
4. The script is NOT for training.
###################################
Tiantong@iPAL2017, tong.renly@gmail.com

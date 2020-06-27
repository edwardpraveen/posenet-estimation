## Fall - detection project - Video Classification analysis



**Links to understand further: **

[Link-1](https://www.analyticsvidhya.com/blog/2019/09/step-by-step-deep-learning-tutorial-video-classification-python/)  [Link-2](https://www.analyticsvidhya.com/blog/2018/09/deep-learning-video-classification-python/)



<u>**Pre-requisites:**</u>

- [ ] Understanding CNN, RNN, LSTM architecture


<u>**Creating Video Dataset**</u>

- Create 5 videos under non-falling section (say Warm-up, Jump, Burpees, Walking, Push-ups, Sitting) and One falling video each of 60 seconds

- Use the same camera for all video creation and convert them into 640 X 480 Pxl for our project

  - Camera used - iPhone SE 12 MP which gives 1920 X 1080

  - Click the image below to view for falling video

    

  [![Sample video](https://www.lewybody.org/wp-content/uploads/2013/06/fall.jpg)](https://www.youtube.com/watch?v=zuL7_Huz_Ks)

  

<u>**Installing necessary Libraries**</u>

1. create conda environment for our project

   ```python
   conda create -n falldetection pip scipy pyyaml python=3.6
   ```
   
   

2. Activate conda environment

   ```python
   conda activate falldetection
   ```

3. Install opencv-python and tensorflow 1.14 version

   ```python
   pip install tensorflow==1.14
   pip install opencv-python
   ```

   

4. Clone [Posenet link](https://github.com/rwightman/posenet-python) from github to local. Run webcam.py file. It must open the webcam and check whether it's identifying the skeletal points
5. 













<u>**References**</u>

1. [Understanding CNN architecture](https://www.analyticsvidhya.com/blog/2017/06/architecture-of-convolutional-neural-networks-simplified-demystified/)
2. 
















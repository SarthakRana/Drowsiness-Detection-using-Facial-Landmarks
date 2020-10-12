# Drowsiness Detection using Facial Landmarks

## Here is the link to the demo video - https://bit.ly/33Ovn8O

![](https://www.optalert.com/wp-content/uploads/Drowsy-Driver.jpg)

A drowsiness detector which will detect drowsiness in a driver and sound an alarm if the driver has started to doze off. The dozing is measured using EAR and a frame threshold to know if sufficient time has passed or not while the driver has dozed off. The 2 main concepts used in this project are :
- Facial landmarks.
- Eye aspect ratio.

### Prerequisites

To run this project, you need to have DLib library installed - this is the most important package in this project (and a difficult one to get right in one go). I would __recommend__ to use a unix based OS (I used Linux) for installing DLib as for installing DLib on Windows is a painfull task.

You can follow the steps given here : https://www.pyimagesearch.com/2017/03/27/how-to-install-dlib/

Make sure to install below packages as well:

- opencv-python `pip install opencv-python`
- time `pip install time`
- imutils `pip install imutils`
- argparse `pip install argparse`
- playsound `pip install playsound`
- numpy `pip install numpy`
- scipy `pip install scipy `

### Installing

Use the package manager to install __Drowsiness Detector using Facial Landmarks__ project

Clone the repo.
```
gitclone https://github.com/SarthakRana/Drowsiness-Detection-using-Facial-Landmarks
```

### Usage

1. After installing all packages and setting up the environment successfully, you can fire the `drowsiness_detector.py` file using the CLI. The CLI command takes 2 mandatory arguments :

  1. shape_predictor file. 
  2. An mp3 file for sounding alarm.
  
2. Download shape_predictor dat file from here - https://drive.google.com/file/d/1rFs4CJ8G4Cs_vGHLgwebmygnlFLcDuH-/view?usp=sharing
3. Keep the shape_predictor.dat file in your working directory.
4. Go to your working directory and open the CLI window.
5. Hit the below command in CLI:
```
python3 drowsiness_detector.py --shape_predictor <Enter PATH to shape_predictor.dat file> --alarm <Enter PATH to the mp3 file>
```

## Output
Here are some screenshots from the project:


![](https://github.com/SarthakRana/Drowsiness-Detection-using-Facial-Landmarks/blob/master/Screenshots/op1.png)
![](https://github.com/SarthakRana/Drowsiness-Detection-using-Facial-Landmarks/blob/master/Screenshots/op2.png)


## Roadmap

See the open issues for a list of proposed features (and known issues).
If your issue is not listed in the already open issues, you can open up a new one.

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are greatly appreciated.

  1. Fork the Project.
  2. Create your Feature Branch.
  3. Commit your Changes.
  4. Push to the Branch.
  5. Open a Pull Request.

## Authors

NOTE : Your name will be added here if I merge your pull request.

1. Sarthak Rana (https://www.linkedin.com/in/sarthakrana/)

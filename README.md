# eye-blink-detecton
Eye blink detection using dlib and opencv

## Environment
* win10
* python 3.5.4
* opencv 3.3.1
* imutils 0.4.6
* dlib 18.18
* Anaconda3

## install packages
```
conda intall dlib
conda install opencv3
pip install imutils
```

## sample 
open the terminal 
```
python detect_blinks.py
```

```
python detect_blinks.py -h
optional arguments:
  -h, --help            show this help message and exit
  -p SHAPE_PREDICTOR, --shape-predictor SHAPE_PREDICTOR
                        path to facial landmark predictor
  -v VIDEO, --video VIDEO
                        path to input video file
  -t THRESHOLD, --threshold THRESHOLD
                        threshold to determine closed eyes
  -f FRAMES, --frames FRAMES
                        the number of consecutive frames the eye must be below
                        the threshold
```



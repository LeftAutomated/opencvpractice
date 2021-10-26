# opencvpractice

Practice with opencv

import cv2

# general

waitKey(arg1)
    desc: wait before close
    arg1: int



# reading images
imread(arg1)
    desc: read photo
    arg1: file path

imshow(arg1, arg2)
    desc: show photo
    arg1: window name
    arg2: imread variable

# reading videos
VideoCapture(arg1)
    desc: read video
    arg1: file path
    arg1: 0 is webcam 
    arg1: numbers after 0 order of cams connected

read()
    desc: reads video frame by frame
    desc: returns if frame was successfully read

imshow(arg1, arg2)
    desc: show video
    arg1: window name
    arg2: frame


0xFF==ord('d') if d key is press

release()
destroyAllWindows()
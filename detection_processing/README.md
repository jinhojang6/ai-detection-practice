# Credit

- iArunava : https://github.com/iArunava/YOLOv3-Object-Detection-with-OpenCV


## How to use?

1) Clone the repository and download [weights files](http://bit.ly/keras-detection-practice)

```
git clone https://github.com/iArunava/YOLOv3-Object-Detection-with-OpenCV.git
```

2) Move to the directory and move the weights file to /yolov3-coco
```
cd YOLOv3-Object-Detection-with-OpenCV
```

3) To infer on an image that is stored on your local machine
```
python3 yolo.py --image-path='/path/to/image/'
```
4) To infer on a video that is stored on your local machine
```
python3 yolo.py --video-path='/path/to/video/'
```
5) To infer real-time on webcam
```
python3 yolo.py
```

Note: This works considering you have the `weights` and `config` files at the yolov3-coco directory.
<br/>
If the files are located somewhere else then mention the path while calling the `yolov3.py`. For more details
```
yolo.py --help
```

## Example
```
python3 yolo.py --video-path='./test.mp4'

You will find `output.avi` (takes 4-5 minutes to process 10 seconds video using CPU)
```

## Inference on images

![yolo_img_infer_1](https://user-images.githubusercontent.com/26242097/48849319-15d21180-edcc-11e8-892f-7d894be8d1a6.png)
![yolo_img_infer_2](https://user-images.githubusercontent.com/26242097/48850723-41a2c680-edcf-11e8-8940-aec302cd8aa3.png)
![yolo_infer_3](https://user-images.githubusercontent.com/26242097/48850729-449db700-edcf-11e8-853d-9f3eca6233c9.png)
![yolo_img_infer_4](https://user-images.githubusercontent.com/26242097/48850735-47001100-edcf-11e8-80d6-b474e54fd7af.png)

## Inference on Video

[![yolov3-video](https://user-images.githubusercontent.com/26242097/48851021-0785f480-edd0-11e8-8ce4-cdfb78e8a849.png)](https://www.youtube.com/watch?v=AzmCYs5fAn0)
<small> Click on the image to Play the video on YouTube </small>

## Inference in Real-time

[![yolov3-video](https://user-images.githubusercontent.com/26242097/48862668-0ca56c80-eded-11e8-9482-31d795105983.png)](https://youtu.be/QaxEtpRwmtI)
<small> Click on the image to Play the video on YouTube </small>

## References

1) [PyImageSearch YOLOv3 Object Detection with OpenCV Blog](https://www.pyimagesearch.com/2018/11/12/yolo-object-detection-with-opencv/)

## License

The code in this project is distributed under the MIT License.

# YOLOv5 Object Detection

This project demonstrates object detection using the YOLOv5 model. It includes a Jupyter notebook to process test images, using the pre-trained YOLOv5s model.

---

## Project Structure

```
YOLOv5_object_detection/
|-- images/                 # Folder containing test images
|   |-- test_1.jpg
|   |-- test_2.jpg
|   |-- test_3.jpg
|
|-- weights/                # Folder containing YOLOv5 model weights
|   |-- yolov5s.pt
|
|-- output/                 # Folder where output images with detections are saved
|
|-- object_detection_YOLOv5.ipynb  # Main Jupyter notebook for object detection
```

---

## Requirements

Install the necessary dependencies.


## Getting Started

1. Ensure the `weights/yolov5s.pt` file is downloaded and placed in the `weights` directory.

   - I downloaded the file from the [YOLOv5 release page](https://github.com/ultralytics/yolov5/releases).

2. Place the test images in the `images` directory. I used pixabay for images.

3. Open the Jupyter notebook:

4. Run the notebook to:
   - Load the YOLOv5 model
   - Perform object detection on the test images
   - Visualize and save the results

---

## Usage

- This notebook has a `process_image` function to process individual images. We can adjust the confidence threshold for detections.

```python
process_image("images/test_1.jpg", conf_threshold=0.25)
```

- Output images with bounding boxes and labels will be saved in the `output` directory.

---

## Results

Results will include:

- Visualizations of detected objects with bounding boxes and confidence scores
- Output images saved in the `output` directory

---

## Notes

- We can add more images to the `images` directory and process them using the notebook.

---



# YOLO Object Detection

This repository contains a Python script that performs object detection using the YOLO (You Only Look Once) model.

## Requirements

- Python 3.x
- OpenCV
- Numpy
- Google Colab

## How to Use

1. Clone the repository or download the script.
2. Upload the required files to your Google Drive:
   - The input image you want to perform object detection on.
   - The `coco.names` file containing the names of the classes.
   - The YOLO model files `yolov3.cfg` and `yolov3.weights`.
3. Update the file paths in the script to point to your uploaded files.
4. Run the script in Google Colab or any Python environment that meets the requirements.

## Configuration

- `CON`: Confidence threshold for object detection. Adjust this value to control the detection sensitivity.
- `score_threshold`: Score threshold for non-maximum suppression. Adjust this value to filter out weak detections.
- `nms_threshold`: Non-maximum suppression threshold. Adjust this value to control the overlap between bounding boxes.

## Output

The script will display the original image with bounding boxes drawn around the detected objects and their corresponding confidence scores.

## Note

Make sure to adjust the `CON`, `score_threshold`, and `nms_threshold` values according to your specific use case.

## Credits

- YOLO (You Only Look Once): https://pjreddie.com/darknet/yolo/
- COCO Dataset: http://cocodataset.org/

## License

This project is licensed under the MIT License.

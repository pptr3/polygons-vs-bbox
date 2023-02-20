# polygons-vs-bbox

I conducted an experiment to understand how effective polygon annotations are in object detection tasks compared to bounding box annotations. To do this, I trained a YOLOv5 object detection model on a polygon dataset. The model was designed to predict polygons, but I wanted to evaluate how effective the bounding boxes produced from the predicted polygons were. To achieve this, I converted the polygon predictions into bounding boxes and evaluated the model's performance using standard object detection metrics, including mAP, precision, and recall.



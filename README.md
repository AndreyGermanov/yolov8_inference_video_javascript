# YOLOv8 object detection in videos in a web browser

This is a web interface to [YOLOv8 object detection neural network](https://ultralytics.com/yolov8) that allows to run object detection right in a web browser without any backend using [ONNX runtime](https://onnxruntime.ai/).

This is a source code for a ["How to detect objects in videos in a web browser using YOLOv8 neural network and JavaScript"](https://dev.to/andreygermanov/how-to-detect-objects-in-videos-in-a-web-browser-using-yolov8-neural-network-and-javascript-lfb) tutorial.

# Install

Clone this repository: `git clone git@github.com:AndreyGermanov/yolov8_inference_video_javascript.git`

# Run

You need to run `index.html` using any local webserver, for example internal webserver of Visual Studio Code. Ensure that 
the ONNX runtime library `ort-wasm-simd.wasm`, the model file `yolov8n.onnx` and the `sample.mp4` video file exist in the same folder with `index.html`.

Using the interface, you can press "Play" button to start object detection on the sample video. 


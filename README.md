# Portfolio-Hub

## Phase 1: C# and App Development (September - October)

### C# Weather App 🌦️
- [ ] Research & Learning:
  - [ ] Complete a C# basics tutorial.
  - [ ] Learn how to make API calls in .NET (`HttpClient`).
  - [ ] Choose a UI framework (.NET MAUI is a good choice).
  - [ ] Find a free weather API (e.g., OpenWeatherMap).
- [ ] Development:
  - [ ] Set up the project structure.
  - [ ] Build the core logic to fetch weather data.
  - [ ] Design and build a simple UI to display the current weather.
  - [ ] Add features: 5-day forecast, search by city.
- [ ] Polishing:
  - [ ] Handle errors (no internet, invalid city).
  - [ ] Add comments to the code.
  - [ ] Write a `README.md` file.
  - [ ] Push the final project to GitHub.

Phase 2: Applied AI & Machine Learning (November - December)
Computer Vision: Real-Time Object Detector 📸
This project will use a pre-trained model to detect and identify common objects in a live webcam feed, drawing bounding boxes around them.

[ ] Research & Learning:

[ ] Deepen CV Knowledge: Go beyond classification. Study the fundamental concepts of object detection architectures like YOLO (You Only Look Once) or SSD (Single Shot Detector). Focus on what a "bounding box" and "confidence score" represent.

[ ] Leverage Pre-trained Models: The key skill here isn't training a huge model from scratch, but applying one effectively. Learn to load and use state-of-the-art, pre-trained object detection models from sources like PyTorch Hub, TorchVision, or Hugging Face.

[ ] Master OpenCV: Get comfortable with the OpenCV library (cv2) in Python. Specifically, learn how to capture video from a webcam, process frames (images) from the video stream, and draw shapes and text on them.

[ ] Development:

[ ] Project Setup: Create a new Python project with a virtual environment. Install torch, torchvision, numpy, and opencv-python.

[ ] Load the Model: Write a script to load a pre-trained model (e.g., YOLOv5, or torchvision.models.detection.ssd300_vgg16) and set it to evaluation mode (model.eval()).

[ ] Create the Inference Loop:

[ ] Write the main loop that captures a frame from the webcam.

[ ] Preprocess the frame to the format the model expects (e.g., resize, convert to a tensor, normalize).

[ ] Pass the tensor through the model to get predictions.

[ ] Loop through the predictions and filter out detections with low confidence scores.

[ ] Visualize the Output: For each high-confidence detection, use OpenCV functions (cv2.rectangle, cv2.putText) to draw the bounding box and the object's class name on the original frame. Display the resulting frame in a window.

[ ] Polishing:

[ ] Create a Simple UI (Optional but Recommended): Instead of just a raw OpenCV window, wrap your application in a simple GUI using Tkinter or PyQt. Adding a "Start/Stop Camera" button makes it feel like a complete piece of software.

[ ] Add Performance Metrics: Calculate and display the Frames Per Second (FPS) to show how efficiently your model is running.

[ ] Write a Top-Tier README.md: This is crucial for a visual project. Explain the project, the technology used, and most importantly, include a GIF of the final application in action.

[ ] Push to GitHub: Ensure the code is clean, commented, and the repository is well-organized.

## Phase 3: Semester Break C++ Deep Dive (January)

### C++ 3D Software Renderer 🧊
- [ ] Research & Learning:
  - [ ] Refresh on linear algebra (vectors, matrices).
  - [ ] Study modern C++ concepts (RAII, smart pointers, STL).
  - [ ] Follow a "Renderer from Scratch" tutorial series (e.g., on YouTube).
- [ ] Development:
  - [ ] Set up a C++ build environment (CMake is standard).
  - [ ] Write code to parse a simple 3D model file (like .obj).
  - [ ] Implement matrix transformations for camera and perspective.
  - [ ] Write the core rendering loop to output an image file.

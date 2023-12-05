# cv_object_tracking_tool
Using the OpenCV tracking API that contains implementations of many single object tracking algorithms.

Using a defined initial bounding box, and then initialize the tracker and bounding box and further use the tracker for each and every frame of a video. In other words, using the **motion model**. The motion model is just a fancy way of saying that you know the location and the velocity ( speed + direction of motion ) of the object in previous frames. 

Classifier Detection part is pending and will be updated soon..
A classifier is trained by feeding it positive ( object ) and negative ( background ) examples. If you want to build a classifier for detecting cats, you train it with thousands of images containing cats and thousands of images that do not contain cats. This way the classifier learns to differentiate what is a cat and what is not. 

Let’s look how different tracking algorithms approach this problem of online training.

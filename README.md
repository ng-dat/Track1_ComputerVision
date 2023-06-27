# Track1_ComputerVision

### Requirement 1: 

**1a (Basic):** Use any suitable library/framework to decompose the input clip into individual frames. Perform the following image processing operations on each frame:
Convert the frame to grayscale.
Flip the frame horizontally.
Rotate the frame by a random degree.
Add random noise to the frame.
After processing each frame, save them as individual image files in JPG format.

**1b (Advanced):** Utilize a pre-trained object detection model such as YOLO, SSD, or Fast-RCNN to detect objects in the input clip. Save the detected information of objects (FrameID, Object’s class, Object’s bounding box, Confidence) into a JSON file.

### Requirement 2: 
Create a tool to scrape and download 2000 images from any sources from the internet into 2 categories. Category 1 contains 1000 true images. Category 2 contains 2000 AI-generated images. Resize all images to 300 x 300.
Input: No
Output: 2 folders. Each folder contains 1000 images of true and AI-generated images.

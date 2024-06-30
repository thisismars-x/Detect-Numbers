# Training
In ~/images, I have written digits for a train/evaluation set.

This model was trained using fast.ai and later serialized as a .pkl and exported to ~/fast-ai/f_ai.py
The py- file takes model path and image path as command line args.

# Working
The frontend of the project is based on SDL, read ~/detect.cpp for compilation details
In the backend, I use python to retrieve the loaded image and produce a .txt output file with prediction and probability. 
This is later rendered on screen.

To visit output .txt and loaded image for python, open ~/detection/detect.jpg and ~/detection/prediction.txt

<video width="320" height="240" controls>
  <source src="https://github.com/intruder-404/Detect-Numbers/working/Recording 2024-06-29 160658.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

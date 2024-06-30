# Training
In `~/images`, I have written digits for a train/evaluation set.

This model was trained using fast.ai and later serialized as a `.pkl` and exported to `~/fast-ai/f_ai.py`. The `.py` file takes the model path and image path as command line arguments.

# Working
The frontend of the project is based on SDL. For compilation details, refer to `~/detect.cpp`.

In the backend, I use Python to retrieve the loaded image and produce a `.txt` output file with the prediction and probability. This is later rendered on the screen.

To view the output `.txt` and loaded image for Python, open `~/detection/detect.jpg` and `~/detection/prediction.txt`.

### Demo

Here is an example;
[Click here to watch](https://github.com/intruder-404/Detect-Numbers/blob/main/working/Recording%202024-06-29%20160658.mp4)

Forgive Slavoj Zizek's voice

# Moving Car Image Segmentation
Moving car images were detected by using segmentation method. 

**Input:**
    the video with moving cars' images.
**Output:**
    the video of segmentation results.

**Setup and installation:**
1. Openvino toolkit setup in Ubuntu 18.04
2. ffmpeg setup
3. Create virtual environment and activate it
4. run the command:
python3 app.py --model <path to model> --i <path to input file>

The output images were sent to ffmpeg server for streaming.

**use casses**:
    can be high-way traffic control or monitoring. 

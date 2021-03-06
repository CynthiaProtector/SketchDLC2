# SketchDLC -- A Sketch on the distributed deep learning communication
SketchDLC is based on the popular deep learning framework [MXNet](https://github.com/apache/incubator-mxnet), and I just modify some source code files to capture the communication trace file. Therefore, the file list is almost the same with [MXNet](https://github.com/apache/incubator-mxnet). SketchDLC is proposed to measure the behaviors of distributed deep learning communications.

# Implementation details
The newly added pdf file (implementation-details.pdf) is the manuscript of the first version, which contains some implementation details and a trace sample.

# Features
* SketchDLC is applicable to clusters of different scales.
* Each node will have its own trace file after the capturing process.
* You need to modify the [zmq_van.h](https://github.com/CynthiaProtector/SketchDLC/blob/master/ps-lite/src/zmq_van.h) to assign your own file paths, and then compile the whole project again before capturing the trace files.

# Ask Questions
Please send emails to xuyemaovip@nudt.edu.cn for more details.

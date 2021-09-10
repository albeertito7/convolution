# Convolution

Convolution is a mathematical operation on two funcitons **f** and **g** used to produce a third one interpreted as a modified version.

Mainly is used on probability, statistics, computer vision, natural language processing, image and signal processing, engineering and diferential equations. But, in our case the objectives of the convolution process will be presented applied in the field of image processing.

In this field, the convolution process is widely used to change the intensity of each individual pixel to reflect the intensities of the surrounding area. A common use of convolution is to create image filters as could be blur, sharpen, and edge detection.

# Project

This repository conforms the High-Performance Computing project applied to the operation of convolution. In this way, the project consists in working on the serial solution of the problem and achieving the possible parallelization, in terms of performance and efficiency, with a set of specific technologies.

Therefore, it is divided into three parts:
  1. Implementation with OpenMP
  2. Implementation with MPI
  3. Hybrid Implementation MPI+OpenMP

You will find each solution at the source folder, and a complete comparative report for each solution at reports folder.

# Execution

It was used the Cluster Moore of the University of Lleida which uses the Sun Grid Engine software system.

You can find job launching scripts in their corresponding folder for guidance.

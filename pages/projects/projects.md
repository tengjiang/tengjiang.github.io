---
title: Projects
layout: default
permalink: /projects/
---

# Projects

A curated list of the projects (excluding research projects) I've done.

<br>

## Cesame: A C-like programming language with First-class Functions and More {#cesame}
<!-- ![cesame](/assets/img/cesame-shorter.png) -->


<img src="/assets/img/cesame-shorter.png" alt="bubble-sort" style="width: 80%; display: block; margin: 20px auto;">

<div style="display: flex; align-items: center;">
    <img src="/assets/img/cesame_blk_diagram.png" alt="cesame-arch" style="width: 45%; margin-right: 20px;">
    <p><b><a href="https://github.com/cesame-pl/cesame">Cesame</a></b> is a C-like programming language that features <b>native support for first-class functions</b>. Cesame also supports non-primitive types such as String, Array, Struct, Socket, and File. Cesame abstracts away pointers and stores most data on the heap, except for primitives and references to objects, similar to Java.
    <br>
    The compiler is written in <b>OCaml</b> with C libraries and targets LLVM IR (phases of Cesame compiler illustrated on the left).</p>
</div>

<br>
## FPGA-based Network Switch: A customizable FPGA-based network switch that supports 4 ingress/egress ports. {#dafpgaswitch}

<img src="/assets/img/dafpgaswitch.png" alt="daFPGASwitch" style="width: 80%; display: block; margin: 20px auto;">


**[daFPGASwitch](https://github.com/daFPGASwitch/daFPGASwitch)** is a **customizable FPGA-based network switch** that comes with the following components: A MAC-to-port
lookup table unit, per-ingress-port virtual output queues (VOQs), a queue management unit that manages the mapping
between packets stored in memory and the VOQ, a scheduling unit that controls the dequeuing decision (which packets get
sent to the switching fabric), and a crossbar switching fabric. Different patterns of packet traffic are generated with software
to test the performance of different scheduling algorithms.

<br>
## (MyDB) x (MyMake with cache) in C++
Source Code available upon request. A **simplistic database** that stores structs in binary form, which can be written to/read from with Writer/Reader, along with a **customized mymake program** that mimics and extends GNU make’s functionality by adding a cache layer. Parsing MyMakefile and storing target-rule pairs in .mymake.cache file (with MyDB mentioned above) to avoid RegEx processing, variable mapping, and implicit rules generating overheads.

<br>
## Selected Projects on Parallel Computing {#hpc}
### Accelerating Poisson Equation Solving with CUDA

<!-- ![MPI](/assets/img/CUDA_poster.jpg) -->

<img src="/assets/img/CUDA_poster.jpg" alt="CUDA" style="width: 80%; display: block; margin: 20px auto;">

<!-- Github repo [here](https://github.com/tengjiang/CUDA-3D-poisson-solver). In this project, my goal was to enhance the efficiency of solving the Poisson system of equations on a 3D rectangular grid by parallelizing and offloading calculations to the GPU using CUDA. Specifically, I:

* Optimized binary tree parallel reduction in CUDA up to a warp level. Utilized techniques such as sequential addressing, first add during load, and warp unrolling.
* Numerically computed Poisson equation with Jacobi method, Red & Black Gauss-Seidel method, and Block-wise Gauss-Seidel method on GPU. 
* Tuned hyper-parameters with grid search and optimized memory access with 3-D texture memory. Enhanced the time/bandwidth efficiency by 26 times. -->


GitHub repo **[here](https://github.com/tengjiang/CUDA-3D-poisson-solver)**. In this project, I aimed to optimize **solving the 3D Poisson equation using CUDA** by parallelizing computations on the GPU. Key achievements include:

* Optimized binary tree parallel reduction up to the warp level using techniques like sequential addressing and warp unrolling.
* Implemented Jacobi, Red-Black Gauss-Seidel, and Block-wise Gauss-Seidel methods in CUDA.
* Achieved a 26x speedup by tuning hyper-parameters and optimizing memory access with 3D texture memory.


### AllReduce with MPI
<!-- ![MPI](/assets/img/MPI_poster_new.png) -->
<img src="/assets/img/MPI_poster_new.png" alt="MPI" style="width: 80%; display: block; margin: 20px auto;">

<!-- Github repo [here](https://github.com/tengjiang/mpi-all-reduce). The AllReduce operation reduces the target arrays across all processes to a single array and distributes the resultant array back to all processes.

In this project, I implemented the SUM All Reduce operation, commonly used in Deep Learning to compute the mean of gradients, using four different algorithms: Brute Force, Butterfly, Tree, and Ring AllReduce. These algorithms were designed to address challenges in complex cross-node network environments, such as bandwidth limitations. -->

GitHub repo **[here](https://github.com/tengjiang/mpi-all-reduce)**. In this project, I implemented the SUM AllReduce operation in MPI, commonly used in deep learning to compute gradient means, using four algorithms: Brute Force, Butterfly, Tree, and Ring AllReduce. These algorithms were optimized to **handle bandwidth limitations** in complex cross-node network environments.

<br>
## Time Series Research {#time_series}
![time_series](/assets/img/time_series_all_poster.png)
During my undergraduate studies, I developed an interest in time series and conducted research on using time series to capture the dynamic landscape of China’s burgeoning financial market. Here are the topics I explored during my research.

### Price Discovery & Synergistic Effect: A Probe into the Commodity Futures Market
An Observation of the Chinese Soybean-related Commodity Futures Market from a Time Series Perspective. We found these two key phenomena in the commodity futures market with impulse response analysis, SVECM model, and causality test.

* Price discovery: Co-integration of spot and futures prices.
* Synergistic Effect: the synergistic relationship between related agricultural products.

### Monetary Policy Shocks with SVAR and DSGE: A Comparison between China and the US
Our analysis using SVAR and DSGE models found that higher interest rates in China create positive short-term and negative long-term effects on GDP, while curbing inflation. In contrast, traditional monetary policy struggles with stagflation in highly developed economies like the US.

<br>

## RegexHub
Github repo **[here](https://github.com/tengjiang/RegexHub)**. A platform to find, share and test regular expressions (with convention in Ruby) in one place. Written in Ruby, powered by Ruby on Rails and deployed to Heroku.
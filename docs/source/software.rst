Software
========

CLOUDMESH CLIENT
----------------

-  Indiana University
-  Gregor von Laszewski

-  Cloudmesh Client: an easy to use client to access hypbrid and
   heterogeneous clouds.

-  Documentation: http://cloudmesh.github.io/client/
-  Code: https://github.com/cloudmesh/client

MACHINE LEARNING
----------------

-  Indiana University
-  Saliya Ekanayake, Supun Kamburugamuve, Pulasthi Wickramasinghe, Geoffrey C. Fox

Machine learning is a set of high-performance multidimensional scaling and clustering applications targetted for HPC environments.

Users' guide (work in progress) is available at https://www.gitbook.com/book/esaliya/global-machine-learning-with-dsc-spidal/details

The codes for these are available at,

-  DA-MDS - an implementation of deterministic annealing weighted SMACOF

   Code https://github.com/DSC-SPIDAL/damds

   Releases https://github.com/DSC-SPIDAL/damds/releases

-  DA-PWC - deterministic annealing pairwise clustering

   Code https://github.com/DSC-SPIDAL/dapwc

-  MDSasChisq

   Code https://github.com/DSC-SPIDAL/MDSasChisq/tree/ompi1.8.1

-  DA-VS - deterministic annealing vector sponge (vector clustering)

   Code https://github.com/DSC-SPIDAL/davs

-  Common - a set of common utitlies required by above applications

   Code https://github.com/DSC-SPIDAL/common


SPATIAL DATA ANALYSIS LIBRARY
-----------------------------

-  Stony Brook University/Emory University
-  co-PI: Fusheng Wang

Support of high performance queries and analytics on large volumes of
spatial data has become increasingly important in many application
domains, including geospatial problems in numerous disciplines, location
based services, and emerging medical imaging applications. There are two
major challenges for managing and analyzing massive spatial data: the
explosion of spatial data, and the high computational complexity of
spatial data processing. Our goal is to develop a general library to
support high performance spatial queries and analytics for both 2D and
3D spatial big data that can be fully integrated into MIDAS middleware
to take advantage of various big data platforms.

MIDAS
-----

-  Rutgers University
-  co-PI: Shantenu Jha

As part of the SPIDAL Project, the RADICAL team at Rutgers is developing
a MIddleware for Data-intensive Analysis and Science (MIDAS) to support
the wide range of applications and analytics algorithms that SPIDAL must
support. These application and analytics algorithms must execute
efficiently on current and future generation supercomputers and cloud
platforms, yet must not be bound too tightly to a specific platform.
Given the rapid changes in the infrastructure and platforms, performance
must not come at the cost of portability, extensibility and flexibility.
On the other hand the complexity and overhead of multiple levels of
functionality, indirection and abstractions must be avoided. It is the
role and responsibility of MIDAS to determine a "sweet spot" between the
two extremes. In the short term we will work with application teams to
provide "fast integration" to support the applications. The RADICAL team
will also work with Indiana University to integrate MIDAS with the
advanced analytics algorithms and libraries (SPIDAL) to provide scalable
and interoperable implementations as they are being developed. As SPIDAL
is developed by the project applications, MIDAS will thus provide a
"deeper integration" for the applications.

CINET: A CYBER INFRASTRUCTURE FOR NETWORK SCIENCE
-------------------------------------------------

-  Virginia Polytechnic Institute and State University
-  co-PI: Madhav V. Marathe

Networks are an effective abstraction for representing real systems.
Consequently, network science is increasingly used in academia and
industry to solve problems in many fields. Computations that determine
structure properties and dynamical behaviors offer insights into the
characteristics of real systems. CINET is an open-access, web-based tool
for analyzing networks that represent interactions in large-scale
complex systems. It was developed at Virginia Tech and partially funded
by NSF to provide a large set of networks and the algorithms to analyze
them. Users can also add their own networks to be analyzed by the
provided algorithms. The web-based interface has been designed to
simplify analysis of complex networks for users who are not necessarily
computer scientists. CINET has the following features: (i) it offers
realistic networks from the literature and various random and
deterministic network generators; (ii) it provides many algorithmic
modules and measures to study and characterize networks; (iii) it is
designed for efficient execution of complex algorithms on distributed
high performance computers so that they scale to large networks; and
(iv) it is hosted with web interfaces so that even non-computing experts
without direct access to high performance computing resources can still
reap the system benefits.

WebPlotViz: Browser based Visualization tool
--------------------------------------------

- Indiana University
- Code: https://github.com/DSC-SPIDAL/WebPViz
- Online version: https://spidal-gw.dsc.soic.indiana.edu/

WebPlotViz is a 3D data point browser that visualizes large volume of
3-dimensional data as points in a virtual space on web browser and
enable users to explore the virtual space interactively. Used together with
dimension reduction algorithms such as MDS, WebPlotViz can help users to
discover intrinsic structures of high-dimensional data and browse large
volumes of data points interactively and efficiently in a virtual 3D space.

WebPlotViz uses Three.js JavaScript library
for rendering 3D plots in the browser. Three.js is built using
WebGL technology, which allows GPU-accelerated graphics
using JavaScript. It enables WebPlotViz to visualize 3D plots
consisting of millions of data points seamlessly. WebPlotViz is
designed to visualize sequences of time series 3D data frame
by frame as a moving plot.
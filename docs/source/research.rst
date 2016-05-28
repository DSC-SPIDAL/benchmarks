Research
========

COMPUTATIONAL BIOPHYSICS RESEARCH GROUP
---------------------------------------

-  Arizona State University
-  co-PI: Oliver Beckstein

The lab addresses problems in molecular biology and physical chemistry
and develops computational tools to answer them. As part of the SPIDAL
project, they will use the libraries developed by the partners to
analyze data-intensive biomolecular simulations. Algorithms for
efficiently analyzing large simulations will be implemented as part of
the popular MDAnalysis (mdanalysis.googlecode.com) package. By bringing
“BigData” tools to the computational biophysics community, we to answer
questions on how proteins function in healthy conditions and how they
malfunction in diseases, ultimately leading to physics-inspired answers
on how to improve human health. The SPIDAL project will support the
lab’s overarching aim to quantitatively predict the function and
activity of proteins from the knowledge of their structures alone and so
to better understand biological phenomena at the molecular level, in
particular transmembrane transport processes catalyzed by membrane
proteins such as secondary active transporters and ion channels. The
work contributes to a range of related fields such as structural
biology, physiology, nanobiotechnology as well as ultimately to the
development of new drugs.

CENTER FOR REMOTE SENSING OF ICE SHEETS
---------------------------------------

-  University of Kansas
-  co-PI: John D. Paden

Work at the Center for Remote Sensing of Ice Sheets’ (CReSIS) in
relation to SPIDAL is to use HPC computing to solve large global
optimization problems related to internal layer tracking and generation
of ice bed digital elevation models from 3-D images generated from the
petabyte-scale CReSIS radar dataset (more found here). CReSIS plans to
work with the SPIDAL algorithm development group to apply SPIDAL
optimization and image processing routines to its datasets and will also
be looking at tightly coupling these algorithms to the signal processing
to produce more accurate results with increased efficiency. CReSIS is
helping represent the polar community by acting as a conduit between the
polar community and the SPIDAL algorithm development group on other
problems in polar science that would benefit from the HPC capabilities
being developed by SPIDAL.

HARP: A HADOOP PLUG-IN
----------------------

-  Indiana University
-  co-PI: Judy Qiu

The Salsa Research Group at IU originally introduced Twister iterative
computation using long-running processes or threads with in-memory
caching of invariant data. The research team explored collective
communication (e.g. broadcast, scatter, gather or reduce) on Twister and
Twister4Azure, showing different implementations of abstractions on
different infrastructure (HPC or Azure). Rather than building full
software environments, they then took the next step by building on the
Apache Big Data Stack, adding a separate communication abstraction
called Harp. The Harp prototype introduces the Map-Collective concept as
a plug-in to Hadoop Ecosystem. Harp adds both Map-Collective and data
structure (key-value, graph, array, pixel) abstractions to Hadoop. The
Harp library provides a common set of data abstractions and related
collective communication abstractions to transform Map-Reduce
programming models into Map-Collective models, thereby addressing large
collectives which are a distinctive feature of data intensive and data
mining applications. Harp is currently supported by Hadoop 1.2.1 and
Hadoop 2.2.0. The Harp architecture is an extension on next generation
MapReduce frameworks with YARN resource manager, providing support to
MapCollective applications. Its use in SPIDAL is still being fully
realized.

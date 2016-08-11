Big Data Benchmarks
===================

BigDataBench
------------
BigDataBench [8, 64] is a benchmark suite targeting Internet services.
There is a total of 33 benchmarks (or workloads as the authors refer) implemented out of 42 and they are classified
into 5 application domains – search engine, social network, e-commerce, multimedia data analytics, and bioinformatics.
Moreover, these 33 benchmarks have multiple implementations for some of them, thus totaling 77 tests.
The implementations use several components of the Apache Big Data Stack (ABDS) [65, 66] and some of their commercial
adaptations. An extracted summary of benchmarks from [64]  is given in Table 3.

The latest (version 3.1) handbook [64] of the BigDataBench mentions that each workload is quantified over
45 micro-architectural level metrics from the categories instruction mix, cache behavior, TLB behavior,
branch execution, pipeline behavior, offcore request, snoop response, parallelism, and operation intensity.
The original paper [8] also presents 3 user perceivable metrics – processes requests per second (RPS),
operations per second (OPS), and data processes per second (DPS). Note, each of these are relevant only for some
workloads.

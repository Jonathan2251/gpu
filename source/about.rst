.. _sec-about:

About
======

.. contents::
   :local:
   :depth: 4

Authors
-------

Chen Chung-Shu 陳鍾樞


Build steps
-----------

https://github.com/Jonathan2251/sa/blob/master/README.md


Revision history
----------------

Version 0.4, not released yet.

  opengl.rst: Add section 'Ray Tracing Pipeline'.

Version 0.3, Released March 14, 2026.

  geo-math.rst: refine 'section Projection' and 'section Mapping data in GPU'.
  sw.rst: add 'section Vector Processor'.

Version 0.2, Released Febuary 28, 2026.

  reorganize sections

Version 0.1, Released Febuary 22, 2026.

  Initial version.


Licensing
---------

Chen Chung-Shu


Motivation
-----------

When I began my career as a graphics GPU compiler engineer, I could not find 
a book that clearly explained the material from a compiler engineer’s 
perspective. 
As a result, I decided to write this book and have been adding to it over time 
as I continue my studies.


Preface
-------

Basically, a CPU is a SISD (Single Instruction Single Data) architecture in each
core. The multimedia instructions in CPUs are smaller-scale forms of SIMD (Single
Instruction Multiple Data), while GPUs are large-scale SIMD processors, capable of
coloring millions of image pixels in just a few milliseconds.

Since 2D and 3D graphic processing offers great potential for parallel data
processing, GPU hardware typically includes tens of thousands of functional units
per chip, as seen in products by NVIDIA and other manufacturers.

This chapter provides an overview of how 3D animation is created and executed on
a CPU+GPU system. Following that, it introduces GPU compilers and hardware
features relevant to graphics applications. Finally, it explains how GPUs have
taken on more computational tasks traditionally handled by CPUs, through the
GPGPU (General-Purpose computing on Graphics Processing Units) concept and the
emergence of related standards.

Website: Basic Theory of 3D Graphics with OpenGL [#cg_basictheory]_.



.. [#cg_basictheory] https://www3.ntu.edu.sg/home/ehchua/programming/opengl/CG_BasicsTheory.html

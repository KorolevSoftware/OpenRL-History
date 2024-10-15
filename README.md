# OpenRL-History

#WIKI
[1](https://en.wikipedia.org/wiki/Caustic_Graphics#CausticGL/OpenRL_API) [2](https://en.wikipedia.org/wiki/Brazil_R/S)
# CausticGL/OpenRL API
The OpenRL API (previously called CausticGL) was derived from OpenGL ES 2.0 and added a series of features to both the host API and GLSL required to support ray tracing. Caustic shipped high performance implementations of the API for both SSE and AVX capable Intel CPUs, OpenCL capable GPUs and CUDA support for NVIDIA GPUs.

# OpenRL SDK
The OpenRL API was shipped in a free SDK with implementations for Intel CPUs, OpenCL and CUDA compatible GPUs and the Caustic hardware. Applications built on the OpenRL SDK would automatically detect supporting hardware and use the highest performing available option.

The SDK included a series of example programs, "Profiler" to help debug applications by allowing full inspection of the ray tracing "tree" within a pixel and a tool called "StatsPlotter" which would expose internal performance counters.

# Project use OpenRL
* Unity
* [heatray](https://github.com/galdar496/heatray)
* [OpenRL_Baker](https://github.com/blizmax/OpenRL_Baker)

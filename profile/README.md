## FunGTs

FunGTs is a suite of open-source C++ graphics tools focused on GPU-accelerated rendering, mesh generation, and shader compilation.

---

**[FunGT](https://github.com/FunGTs/FunGT)**
A C++ 3D graphics engine with a multi-backend path tracer supporting CUDA, SYCL, and CPU. Features PBR shading, BVH acceleration, and a modular architecture designed as a Blender-inspired creation suite.

**[FunGT-Mesher](https://github.com/FunGTs/fungt-mesher)**
A SYCL-based 3D model generator that produces geometry enriched with physical material data. AI inference runs entirely through [FunLib](https://github.com/juanchuletas/funlib), a custom SYCL tensor library, with no dependency on third-party AI frameworks.

**[FunGT-Dialect](https://github.com/FunGTs/fungt-dialect)**
An MLIR dialect and compiler for a custom shader language that targets SPIR-V. Provides a typed, lowering pipeline from shader source down to GPU-executable bytecode for use within the FunGT rendering pipeline.

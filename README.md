# ParaLin++

Project page for **"ParaLin++: Accelerating Parallel Diffusion Integrator via Intrinsic Partially Linear Structure"** (IEEE TPAMI submission).

- **Homepage**: https://paralinplus.github.io/
- **Paper**: [paper.pdf](paper.pdf)

ParaLin++ is a step-parity parallel sampling solver for diffusion and flow-matching models. It preserves the full-step discretization while parallelizing the solver iterations. The project studies generation-quality preservation with GenEval, DPG-Bench, and LongTextBench, and reports 1.68× speedup on FLUX.1-dev, 1.21× on Ming-Flash-Omni 2.0, and 2.6×–4.8× on Stable Diffusion-v2 and LSUN Church.

Conference version (ParaLin / ParaSolver): https://github.com/Jianrong-Lu/ParaSolver

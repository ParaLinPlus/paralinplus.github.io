# ParaLin++

Project page for **"Back to the Drawing Board: A Critical Evaluation of Few-Step Solvers for Production Diffusion Models"** (IEEE TPAMI submission).

- 🏠 **Homepage**: https://jianrong-lu.github.io/ParaLinPlus/
- 📄 **Paper**: [paper.pdf](paper.pdf)

ParaLin++ is a step-parity parallel sampling solver for production diffusion models. Our industrial-quality audit (GenEval / DPG-Bench / LongTextBench) shows that few-step solvers which look "quality-lossless" under FID degrade sharply on the metrics production services care about, while step-parity parallelization preserves the full-step Euler profile (1.68× on FLUX.1-dev, 1.21× on Ming-Flash-Omni 2.0, up to 71.4× at 1000-step DDPM).

Conference version (ParaLin / ParaSolver): https://github.com/Jianrong-Lu/ParaSolver

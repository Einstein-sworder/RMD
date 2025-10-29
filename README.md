# Rmd: Robust Modal Decomposition with Constrained Bandwidth

## Abstract
Modal decomposition techniques, such as Empirical Mode Decomposition (EMD), Variational Mode Decomposition (VMD), and Singular Spectrum Analysis (SSA), have advanced time-frequency signal analysis since the early 21st century. These methods are generally classified into two categories: numerical optimization-based methods (EMD, VMD) and spectral decomposition methods (SSA) that consider the physical meaning of signals. The former can produce spurious modes due to the lack of physical constraints, while the latter is more sensitive to noise and struggles with nonlinear signals. Despite continuous improvements in these methods, a modal decomposition approach that effectively combines the strengths of both categories remains elusive.Thus, This paper proposes a Robust Modal Decomposition (RMD) method with constrained bandwidth, which preserves the intrinsic structure of the signal by mapping the time series into its trajectory-GRAM matrix in phase space. Moreover, the method incorporates bandwidth constraints during the decomposition process, enhancing noise resistance.Extensive experiments were conducted to validate its performance: on the synthetic dataset front, we focused on low-SNR sine wave separation tasks and nonlinear nonlinearsignal processing experiments to verify the ability of our method to extract weak signals and handle nonlinear distortions; on real world data, we tested it on a real-collected millimeter-wave micro-motion energy dataset to demonstrate its practical applicability in radar-related micro-motion signature analysis.All code and dataset samples are publicly available on GitHub for reproducibility: https://github.com/Einstein-sworder/RMD.

## Code and Data Release

The **RMD** method code, along with dataset samples, will be made publicly available **after the paper is accepted**. We will provide full access to:

* The **codebase** implementing the RMD algorithm
* **Dataset fragments** used in the experiments

Currently, we offer a **placeholder implementation** based on Variational Mode Decomposition (VMD) for reference.

## Preprint DOI

[Preprint DOI: xxx]

## Requirements

To run the provided placeholder implementation or after the full release, you may need the following dependencies (in addition to any other specific requirements listed later):

* Python 3.x
* NumPy
* Matplotlib (for visualization)
* vmdpy

## Installation

1. Clone the repository:

   ```bash
   git clone 
   cd 
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

## Citation

If you use this method in your research, please cite the paper as follows:

```
@article{yourcitation,
  title={Robust Modal Decomposition with Constrained Bandwidth},
  author={Wang Hao, Zhang Kuang, Hou Chengyu, Yang Yifan, Tan Chengxing},
  journal={Axtrix},
  year={2025},
  doi={xxx},
}
```


# 2D Convolution Algorithm in CUDA

This repository contains the implementation and analysis of 2D convolution algorithms using CUDA, focusing on optimizing performance through shared memory utilization. The study was conducted as part of the Master's Program in High-Performance Computing Engineering at Politecnico di Milano.

## Features
- CUDA-based 2D convolution implementation:
  - **Without Tiling**: Direct shared memory usage.
  - **With Tiling**: Optimized shared memory usage for larger matrices and kernels.
- Performance benchmarks conducted on a Tesla T4 GPU.
- Detailed report with methodology, results, and discussion.

## Repository Structure
- `cuda_example.ipynb`: Jupyter notebook containing the CUDA implementation and experiments.
- `report/2D_Convolution_Report.pdf`: Academic report detailing the project.
- `README.md`: Overview of the repository and usage instructions.

## Prerequisites
- NVIDIA GPU with CUDA support.
- CUDA Toolkit installed.
- Python with the following packages:
  - `numpy`
  - `matplotlib`
  - `numba`

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/2D-Convolution-CUDA.git
   cd 2D-Convolution-CUDA
   ```
2. Open the Jupyter notebook:
   ```bash
   jupyter notebook cuda_example.ipynb
   ```
3. Execute the cells to run the 2D convolution experiments.

## Results
Key findings from the experiments:
- Tiling significantly enhances performance for larger matrices and kernels.
- Memory utilization strategies are critical for high-performance GPU computations.

For detailed results and discussions, refer to the [report](report/2D_Convolution_Report.pdf).

## Authors
- **Salvatore Mariano Librici**  

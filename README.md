
This repository contains essential data files to facilitate the numerical replication of the paper titled "An Exponential Cone Programming Approach for Managing Electric Vehicle Charging" by Li Chen, Long He, and Yangfang (Helen) Zhou (2023), published in Operations Research.

## Paper Reference:
Li Chen, Long He, Yangfang (Helen) Zhou (2023) An Exponential Cone Programming Approach for Managing Electric Vehicle Charging. Operations Research 0(0). [DOI: 10.1287/opre.2023.2460](https://doi.org/10.1287/opre.2023.2460)

### Contents:

1. **large_arrival_rate.p:**
   - This data file contains the calibrated arrival rates used in the numerical study presented in the paper. It is instrumental for reproducing Table 1. 

2. **EV-SAA.html:**
   - Illustrated in this HTML file is a demonstration of how to utilize the aforementioned data file. The provided example solves a Sample Average Approximation (SAA) problem using Python with the Mosek Fusion API.

3. **readme.pdf:**
   - This PDF document includes detailed information about the SAA problem and its specifics within the context of the numerical experiments conducted in the paper.
     
4. **EVECP-COPT.ipynb**
   - This jupyter notebook includes a sample python code (using RSOME and COPT) for comparing the ECP and SAA in the paper. It was illustrated in the COPT online lecture "RSOME + COPT: Using Exponential Cones in Robust Optimization" [Recording in Chinese](https://coridm.d2d.ai/lecture/70) [Slides in English](https://chenli-ora.github.io/docs/talk_slides/COPT.pdf)

Feel free to explore and use these resources for replicating the numerical experiments outlined in the paper. If you encounter any issues or have questions, please refer to the paper for additional guidance or contact the authors directly.

 

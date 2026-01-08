# Supporting Document for *"A Paper"*

This repository provides the supporting materials and simulation data for the paper *“A Paper”*.  
It contains all relevant datasets, region-of-interest (ROI) extractions, and simulation notebooks used in both 2D and 3D analyses.

---
**UpsampledSegments**
[**UpsampledSegments/**](https://github.com/Donny-bla/SpineSegment-USSimulation/tree/main/UpsampledSegments)  
Contains the ground truth segmentation and versions upsampled using different interpolation approaches. Their process of upsampling is available in [**Upsamples.ipynb**](https://github.com/Donny-bla/SpineSegment-USSimulation/blob/main/Upsamples.ipynb), where the mesh-based method implements pySegUpsampler verison 0.1.1 .

---

**ROI Extraction**
ROIs are extracted using  
[**ExtractCrossSectionROI.ipynb**](https://github.com/Donny-bla/SpineSegment-USSimulation/blob/main/ExtractCrossSectionROI.ipynb).

- The extracted ROIs are provided in `.nii.gz` format under [**ROIs/**](https://github.com/Donny-bla/SpineSegment-USSimulation/tree/main/ROIs).  
- Simulations, however, are performed using the corresponding `.npy` versions of these ROIs.

---

**2D Simulation**
Implemented in  
[**CrossSectionSimulation.ipynb**](https://github.com/Donny-bla/SpineSegment-USSimulation/blob/main/CrossSectionSimulation.ipynb).

- **Average runtime:** ~2 minutes on a Intel Core i7-11800H @2.30GHz processor  
- **Results directory:** [**review2Dresults/**](https://github.com/Donny-bla/SpineSegment-USSimulation/tree/main/review2DSimulation) 

---

**3D Simulation**
Implemented in  
[**3DSpineSimulation.ipynb**](https://github.com/Donny-bla/SpineSegment-USSimulation/blob/main/3DCrossSectionSimulation.ipynb)  

- **Average runtime:** ~1.5 hours on a 64 gigabyte, 8-core AMD EPYC 7742 node.  
- **Results directory:** [**review3Dresults/**](https://github.com/Donny-bla/SpineSegment-USSimulation/tree/main/review3DSimulation)
- **Summary data:** [**3Ddata_Chart.txt**](https://github.com/Donny-bla/SpineSegment-USSimulation/blob/main/review3DSimulation/review3Dresults.txt)

---

**Convergence Test** 
CFL number selection and convergence validation (based on 2D simulations) are available in  
[**2DConvergence/**](https://github.com/Donny-bla/SpineSegment-USSimulation/tree/main/2DConvergence).

---
**Data analysis**
Process of data analysis and statistical comparison is available in
[**DataAnalysis**](https://github.com/Donny-bla/SpineSegment-USSimulation/blob/main/DataAnalysis.ipynb)

---

## Notes
- All simulations were conducted using `.npy` ROI files for compatibility and performance reasons.  
- The provided datasets and scripts can be used to reproduce all figures and tables presented in the paper.


## Citation?


---


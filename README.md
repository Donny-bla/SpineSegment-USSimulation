# Supporting Document for *"A Paper"*

This repository provides the supporting materials and simulation data for the paper *“A Paper”*.  
It contains all relevant datasets, region-of-interest (ROI) extractions, and simulation notebooks used in both 2D and 3D analyses.

---
**UpsampledSegments**
[**UpsampledSegments/**](https://github.com/Donny-bla/SpineSegment-USSimulation/tree/main/UpsampledSegments)  
Contains the ground truth segmentation and versions upsampled using different interpolation approaches.

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

- **Average runtime:** ~2 minutes on a standard CPU.  
- **Results directory:** [**2Dresults/**](https://github.com/Donny-bla/SpineSegment-USSimulation/tree/main/2Dresults)  
- **Summary data:** [**2Ddata_Chart.txt**](https://github.com/Donny-bla/SpineSegment-USSimulation/blob/main/2Dresults/2Ddata_Chart.txt)

---

**3D Simulation**
Implemented in  
[**3DCrossSectionSimulation.ipynb**](https://github.com/Donny-bla/SpineSegment-USSimulation/blob/main/3DCrossSectionSimulation.ipynb)  
*(If this is the same as the 2D file, update the link accordingly.)*

- **Average runtime:** ~1.5 hours on a standard workstation.  
- **Results directory:** [**3Dresults/**](https://github.com/Donny-bla/SpineSegment-USSimulation/tree/main/3Dresults)  
- **Summary data:** [**3Ddata_Chart.txt**](https://github.com/Donny-bla/SpineSegment-USSimulation/blob/main/3Dresults/3Ddata_Chart.txt)

---

**Convergence Test** 
CFL number selection and convergence validation (based on 2D simulations) are available in  
[**2DConvergence/**](https://github.com/Donny-bla/SpineSegment-USSimulation/tree/main/2DConvergence).

---

## Notes
- All simulations were conducted using `.npy` ROI files for compatibility and performance reasons.  
- The provided datasets and scripts can be used to reproduce all figures and tables presented in the paper.


## Citation?


---


# Quick start and examples <a name="QuickStart"></a>
The easiest way to start is through the PorPy following examples. 

| Example File                          	                                                                                                        | Description                                                                                                                                                           	|
|------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------	|
| [1_basic_tutorial.ipynb](https://github.com/PortPy-Project/PortPy/blob/master/examples/1_basic_tutorial.ipynb)                	                | Demonstrates the main functionalities of PortPy (e.g., Access data, create an IMRT plan, visualize)                                                                   	|
| [vmat_scp_tutorial.ipynb](https://github.com/PortPy-Project/PortPy/blob/master/examples/vmat_scp_tutorial.ipynb)               	               | Creates a VMAT plan using sequential convex programming                                                                                                               	|
| [vmat_scp_dose_prediction.ipynb](https://github.com/PortPy-Project/PortPy/blob/master/examples/vmat_scp_dose_prediction.ipynb)                 | Predicts 3D dose distribution using deep learning and converts it into a deliverable VMAT plan                                                                        	|
| [3d_slicer_integration.ipynb](https://github.com/PortPy-Project/PortPy/blob/master/examples/3d_slicer_integration.ipynb)           	           | Creates an IMRT plan and visualizes it in 3D-Slicer                                                                                                                   	|
| [imrt_tps_import.ipynb](https://github.com/PortPy-Project/PortPy/blob/master/examples/imrt_tps_import.ipynb)                	                  | 1. Outputs IMRT plan in DICOM RT format and imports it into TPS. <br>2. Outputs IMRT plan optimal fluence in an Eclipse-compatable format and imports it into Eclipse 	|
| [vmat_tps_import.ipynb](https://github.com/PortPy-Project/PortPy/blob/master/examples/vmat_tps_import.ipynb)                 	                 | Outputs VMAT plan in DICOM RT format and imports it into TPS                                                                                                          	|
| [imrt_dose_prediction.ipynb](https://github.com/PortPy-Project/PortPy/blob/master/examples/imrt_dose_prediction.ipynb)            	            | Predicts 3D dose distribution using deep learning and converts it into a deliverable IMRT plan                                                                        	|
| [vmat_global_optimal.ipynb](https://github.com/PortPy-Project/PortPy/blob/master/examples/vmat_global_optimal.ipynb)           	               | Finds a globally optimal VMAT plan                                                                                                                                    	|
| [beam_orientation_global_optimal.ipynb](https://github.com/PortPy-Project/PortPy/blob/master/examples/beam_orientation_global_optimal.ipynb) 	 | Finds globally optimal beam angles for IMRT                                                                                                                           	|
| [dvh_constraint_global_optimal.ipynb](https://github.com/PortPy-Project/PortPy/blob/master/examples/dvh_constraint_global_optimal.ipynb)  	    | Finds a globally optimal plan meeting Dose Volume Histogram (DVH) constraints                                                                                         	|
| [structure_operations.ipynb](https://github.com/PortPy-Project/PortPy/blob/master/examples/structure_operations.ipynb)            	            | Creates new structures by expanding/shrinking the existing ones or using boolean operations                                                                           	|
| [inf_matrix_down_sampling.pynb](https://github.com/PortPy-Project/PortPy/blob/master/examples/inf_matrix_down_sampling.ipynb)         	        | Down-samples beamlets and/or voxels for computational efficiency                                                                                                      	|
| [inf_matrix_sparsification.ipynb](https://github.com/PortPy-Project/PortPy/blob/master/examples/inf_matrix_sparsification.ipynb)       	       | Sparsifies (i.e., truncates) the influence matrix for computational efficiency                                                                                        	|

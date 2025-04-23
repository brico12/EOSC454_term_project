#  Straight-Ray Tomography with Layered Earth and Dipping Layers Models
Author: _An Zhou_

Instructor: _Dr Heagy_
### Project Description
In this project, I first simulated two sets of synthesis data by constructing two models (Layered Earth and Dipping Layers) in a 2D space. Then apply Linear Tikhonov inversion. 

In geophysics, seismic wave velocity is a key physical property that tells the researcher important information about the subsurface condition. By measuring the time seismic waves take to travel between a set of known source and receiver locations, researchers were able to calculate the estimated underlying velocity structure through inversion.

The first physical model involved in this project is Layered Earth model. It simulated the earth environment using horizontal layers. The velocity in each layer is unique and increases with depth. The other model is Dipping Layers model. This model is used to describe a scenario where two regions were separated by an inclined velocity interface, so there exists a sloped geological boundary between regions. 



### Repository Structure
The code file is contained in src folder. The two jupyter notebooks are corresponded to two different models used.

### Instructions

#### Clone this repository
```bash
git clone https://github.com/brico12/EOSC454_term_project
```

#### Go to repository file 
```bash
cd EOSC454_term_project
```

#### Create project environment
```bash
conda env create -f environment.yml
```

#### Activate and add to kernel
```bash
conda activate EOSC454_term_project
python -m ipykernel install --user --name=EOSC454_term_project
```

#### Open JupyterLab
```bash
jupyter lab
```

### Reference
Notes from Dr.Heagy on Canvas:
https://github.com/lheagy/eosc-454/blob/main/lectures/tomography.ipynb

Use of SimPEG:
https://simpeg.xyz/user-tutorials/


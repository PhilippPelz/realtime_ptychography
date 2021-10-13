# Real-time ptychography reconstruction toolbox



This is the code accompanying the paper "Real-time interactive 4D-STEM phase-contrast imaging from electron event representation data" 
to come out in IEEE Signal processing. The functionality can be seen in the two example notebooks in the 'examples' folder. 

Please download the necessary data from [here](https://drive.google.com/file/d/12QjOpIixxsDIjizbaUVHaxJmrgu5lPUG/view?usp=sharing) and 
[here](https://drive.google.com/file/d/1b0zlTCXOBXvnwUkBx-1NT2j6zb9uf2xw/view?usp=sharing) and put them in the example directory

## Get started
You can then set up a conda environment with all dependencies like so:
```
conda env create -f environment.yml
conda activate cu11
```

## Acknowledgements

[Colin Ophus (NCEM/LBL)](https://github.com/cophus) 

[Peter Ercius (NCEM/LBL)](https://foundry.lbl.gov/about/staff/peter-ercius/)

[Mary Scott (NCEM/UCB)](https://github.com/orgs/ScottLabUCB/) 

[Ian Johnson (former LBL)](https://github.com/) 

## How to contribute

Before committing, run

`nbdev_build_lib && nbdev_clean_nbs && nbdev_build_docs`

to compile the notebook into script files, clean the notebooks, and build the documentation.

Do not edit this README directly, rather edit index.ipynb and regenerate the README.

## Citation
If you find our work useful in your research, please cite:
```
@article{pelz2021realtimeptycho,
   title={Real-time interactive 4D-STEM phase-contrast imaging from electron event representation data},
   url={https://arxiv.org/abs/2104.06336},
   author={Pelz, Philipp and Ercius, Peter and Ophus, Colin and Johnson, Ian and Scott, Mary},
   year={2021},
   month={Jul}
}
```

## Contact
If you have any questions, please feel free to email the authors.

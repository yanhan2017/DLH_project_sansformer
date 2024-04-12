# Sansformer
### Original paper: https://arxiv.org/abs/2108.13672
### Original Github link: https://github.com/ykumards/sansformers

#### To run code:
Libraries needed:
- prettytable
- yacs
- einops
- torch_optimizer

To preprocess data:
First run preprocess.py, change MIMIC_PATH to your own path to mimic dataset, this will generate some files in your MIMIC_PATH

To run the main code:
- Edit PATHS in configs/config_axial_sansformer.yml
- python run_mimic_experiment.py --cfg "path-to-config-yaml"

## Common

[arguments.py](./common/arguments.py) - Command line arguments

[camera.py](./common/camera.py) - camera utilities: normalize images,

[custom_dataset.py](./common/custom_dataset.py) - Custom Dataset class

[generators.py](./common/generators.py) - Batched data generator for training, and Non-batched data generator for testing.

[h36m_dataset.py](./common/h36m_dataset.py) - Human3.6m dataset class

[humaneva_dataset.py](./common/humaneva_dataset.py) - HumanEva dataset class

[loss.py](./common/loss.py) - Error calculation functions for training

[mocap_dataset.py](./common/mocap_dataset.py) - CMU MoCap dataset class

[model.py](./common/model.py) - Pytorch machine learning model class for VideoPose3D

[quaternion.py](./common/quaternion.py) - Rotete / inverse quaternion (3D skeleton)

[skeleton.py](./common/skeleton.py) - Skeleton class for manipulating and getting skeleton data

[utils.py](./common/utils.py)

- wrap: wrap a Pytorch function so it can be called with NumPy arrays
- deterministic_random: return random number

[visualization.py](./common/visualization.py) - Visualize video and skelton combination

## data

[convert_cdf_to_mat.m](./data/convert_cdf_to_mat.m) - matlab code to convert CDF file to matlab format file.

[ConvertHumanEva.m](./data/ConvertHumanEva.m) - matlab code to HumanEva dataset to matlab array format file.

[data_utils.py](./data/data_utils.py) - Skeypoints symmetry data, Suggest metadata format, and import pose data from Detectron, CPN, and SH.

[prepare_data_2d_custom.py](./data/prepare_data_2d_custom.py) - Convert/prepare Detectron numpy file for VideoPose3D

[prepare_data_2d_h36m_generic.py](./data/prepare_data_2d_h36m_generic.py) - Convert/prepare Human3.6m dataset for VideoPose3D

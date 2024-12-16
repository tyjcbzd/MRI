# MRI: Multi-Agent Trajectory Prediction based on Multi-Relative Position Integration
This is the official implementation of the paper *MRI: Multi-Agent Trajectory Prediction based on Multi-Relative Position Integration*

To do list:

- Code Implementation


## Introduction




## Gettting Started

### Install dependencies
- Create a new conda virtual env
```
conda create --name MRI python=3.9
conda activate MRI
```

- Install PyTorch according to your CUDA version. We use CUDA = 12.4,  PyTorch_Lighting = 2.4.0
```
conda install pytorch==1.12.0 torchvision==0.13.0 torchaudio==0.12.0 cudatoolkit=11.6 -c pytorch -c conda-forge
```

- Install Argoverse 1 APIs, please follow [argoverse-api](https://github.com/argoai/argoverse-api).

- Install other dependencies
```
pip install scikit-image IPython tqdm ipdb tensorboard
```

### Train from scratch

- Preprocess full Argoverse 1 motion forecasting dataset using the script:


- Launch training using the script:


- For model evaluation, please refer to the following scripts:


### Test from scratch

- Generate files that can be submitted on the [EvalAI](https://eval.ai/web/challenges/challenge-page/454/submission):


## How to Cite


## Acknowledgment
We would like to express sincere thanks to the authors of the following packages and tools:
- [Simpl](https://github.com/HKUST-Aerial-Robotics/SIMPL)
- [HiVT](https://github.com/ZikangZhou/HiVT)
- [LaneGCN](https://github.com/uber-research/LaneGCN/tree/master)

## License
This repository is licensed under [MIT license](https://github.com/tyfelix63/MRI/main/LICENSE).

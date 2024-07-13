---
dataset_info:
  features:
  - name: image
    dtype: image
  - name: objects
    list:
    - name: label
      dtype: string
    - name: source
      dtype: string
    - name: confidence
      dtype: float32
    - name: xmin
      dtype: float32
    - name: xmax
      dtype: float32
    - name: ymin
      dtype: float32
    - name: ymax
      dtype: float32
    - name: is_occluded
      dtype: bool
    - name: is_truncated
      dtype: bool
    - name: is_group_of
      dtype: bool
    - name: is_depiction
      dtype: bool
    - name: is_inside
      dtype: bool
  splits:
  - name: validation
    num_bytes: 11658974770.694
    num_examples: 37306
  - name: test
    num_bytes: 35431142103.872
    num_examples: 112194
  - name: train
    num_bytes: 551135066490.026
    num_examples: 1743042
  download_size: 597325671307
  dataset_size: 598225183364.592
configs:
- config_name: default
  data_files:
  - split: validation
    path: data/validation-*
  - split: test
    path: data/test-*
  - split: train
    path: data/train-*
---

# conflict-git-help
Conflict-Git-Helper 是一个旨在简化 Git 分支合并冲突解决流程的工具。在多人协作的软件开发中，经常会出现不同分支之间的代码冲突，这需要开发者手动解决。Conflict-Git-Helper 旨在提供一种自动化和交互式的方式来处理这些冲突，以提高开发效率和减少错误。

## Qualitative Comparison
<img width="1189" height="599" alt="image" src="https://github.com/user-attachments/assets/4e8fbaad-9414-44c4-9331-325a6fba9f26" />

## Quantitative Results
| Metric | Animer+* | 4DEquine | Ours |
| --- | --- | --- | --- |
| **PA_MPJPE (↓)** | -- | 84.740 | **44.820** |
| **PA_MPVPE (↓)** | -- | 73.072 | **36.595** |
| **PCK@0.1 (↑)** | -- | 0.790 | **0.979** |
| **PCK@0.15 (↑)** | -- | 0.881 | **0.993** |
| **AUC (↑)** | -- | 0.871 | **0.964** |
| **Mean Chamfer Distance (↓)** | 184.0 mm | 302.6 mm | **89.7 mm** |

*Animer+ predicts a different topology i.e. it predicts in the SMAL body model's space so a direct comparison on many metrics is not feasible.


This work was built upon [Animer+](https://github.com/AniMerPlus/AniMerPlus), credit to the authors. Detailed Citations below:

```bash
@inproceedings{lyu2025animer,
  title={AniMer: Animal Pose and Shape Estimation Using Family Aware Transformer},
  author={Lyu, Jin and Zhu, Tianyi and Gu, Yi and Lin, Li and Cheng, Pujin and Liu, Yebin and Tang, Xiaoying and An, Liang},
  booktitle={Proceedings of the Computer Vision and Pattern Recognition Conference},
  pages={17486--17496},
  year={2025}
}
```

```bash
@misc{lyu2025animerunifiedposeshape,
      title={AniMer+: Unified Pose and Shape Estimation Across Mammalia and Aves via Family-Aware Transformer}, 
      author={Jin Lyu and Liang An and Li Lin and Pujin Cheng and Yebin Liu and Xiaoying Tang},
      year={2025},
      eprint={2508.00298},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2508.00298}, 
}
```

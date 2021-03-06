## DENse and Diverse symmetry dataset (DENDI), CVPR 2022
<p align="center">
Ahyun Seo, Byungjin Kim, Suha Kwak, Minsu Cho
</p>

<p align="center">
    <a href="https://arxiv.org/abs/2203.16787">[paper]</a>
    <a href="http://cvlab.postech.ac.kr/research/EquiSym">[project page (EquiSym)]</a>
</p>

Official Dataset proposed in *Reflection and Rotation Symmetry Detection via Equivariant Learning (CVPR 2022)*.

Contributors of this dataset: [Ahyun Seo](https://github.com/ahyunSeo), [Byungjin Kim](https://github.com/kbjpc123), [Yunseon Choi](https://github.com/OMEGA-Y)

Download [onedrive](https://postechackr-my.sharepoint.com/:u:/g/personal/lastborn94_postech_ac_kr/ES2ftVVmTc5Du78EBgfTGy8BwygV_HRa5nWciYeq3cTvoQ?e=y9ETja)


### Environment
```
    conda create --name DENDI python=3.7
    conda activate DENDI
    conda install pytorch==1.7.0 torchvision==0.8.1 -c pytorch
    conda install -c conda-forge matplotlib
    pip install albumentations==0.5.2 shapely opencv-python
    
    mkdir sym_datasets

```

### Datasets

```
.
├── sym_datasets
│   └── DENDI
│       ├── symmetry
│       ├── symmetry_polygon
│       ├── reflection_split.pt
│       ├── rotation_split.pt
│       └── joint_split.pt
└── (...) 
```

### Citation
If you find our code or paper useful to your research work, please consider citing:
```
@inproceedings{seo2022dendi,
    author   = {Seo, Ahyun and Kim, Byungjin and Kwak, Suha and Cho, Minsu},
    title    = {Reflection and Rotation Symmetry Detection via Equivariant Learning},
    booktitle= {The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
    year     = {2022}
}
```

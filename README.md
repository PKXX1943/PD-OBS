# Interpretable Oracle Bone Script Decipherment through Radical and Pictographic Analysis with LVLMs

> Kaixin Peng, Mengyang Zhao, Haiyang Yu, Teng Fu, Bin Li\*

This repository is the implementation of the [paper](https://arxiv.org/abs/2508.10113) "*Interpretable Oracle Bone Script Decipherment through Radical and Pictographic Analysis with LVLMs*". 

Our dataset (PD-OBS) is avaliable  [here](https://drive.google.com/file/d/18ySKhRZUdTfFpmjQNRirEAlM67-QZBt4/view).


## Dataset 

### Statistic

| Component | Count | Description |
|-----------|-------|-------------|
| Characters | 47,157 | Characters collected from [KangXi Dictionary](https://www.kangxizidian.com/) |
| Regular Images | 47,157 | Modern character forms collected from [Handian](https://www.zdic.net/) |
| Ancient Images | 10,968 | Ancient character forms collected from [Open Ancient Chinese Characters Glyphs Database](http://www.ccamc.org/cjkv_oaccgd.php) |
| OBS Categories (Including duplicates) | 11,739 | OBS collected from [HUST-OBC](https://arxiv.org/abs/2401.15365) and [EVOBC](https://arxiv.org/abs/2401.12467) |

### Directory
```
PD-OBS/
  dictionary/
    dictionary.json
    id_to_char.json
  img/
    regular/
    ancient/
    obs/
```
- **`dictionary/dictionary.json`**: Authoritative Dictionary Definitions, radical analysis and pictographic analysis.
- **`dictionary/id_to_char.json/`**: ID-Character mapping.
- **`img/regular/`**: Modern Chinese character writing style images.
- **`img/ancient/`**: Ancient Chinese character writing style images.
- **`img/obs/`**: Corresponding oracle bone script images.

## Train & Inference & Checkpoints

To be released upon paper publication.

## Cite

```

```



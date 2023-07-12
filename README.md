# The Professional Go Annotation Dataset

![Teaser image](./assets/PAGE.png)

The **P**rofession**A**l **G**o Annotation Datas**E**t (**PAGE**) is an extensively annotated Go (weiqi, baduk) dataset for large-scale data-driven analytics. PAGE contains 98,525 games played by 2,007 professional players from 1950 to 2021. Our proposed PAGE incorporates game-level metadata and in-game statistics. The game-level metadata pertinent to games, players, and tournaments is annotated by consolidating data from numerous reliable sources. The comprehensive in-game statistics are generated from [KataGo](https://github.com/lightvector/KataGo).

> **[The Professional Go Annotation Dataset](https://ieeexplore.ieee.org/document/10123061)**<br>
> Yifan Gao, Danni Zhang, Haoyue Li<br>
> IEEE Transactions on Games, 2023

> **[PGD: A Large-scale Professional Go Dataset for Data-driven Analytics](https://ieeexplore.ieee.org/abstract/document/9893704)**<br>
> Yifan Gao<br>
> IEEE Conference on Games (CoG), 2022

## News
#### 2023-04-01
- This project is still quickly updating. Check ToDo list to see what will be released next.
#### 2023-05-11
- Our paper "The Professional Go Annotation Dataset" describing this dataset has been accepted by IEEE Transactions on Games. :tada:
#### 2023-07-11
- Initial public release of the proposed PAGE.
- Dataset is licensed under **CC BY-NC-SA 4.0**, which allows free use for non-commercial purposes only.
- For questions and feedback, please open a Github issue on this repo.


## ToDo
- [ ] work 1.
- [ ] work 2.
- [ ] work 3.
- [ ] work 4.
- [ ] work 5.
- [ ] work 6.
- [ ] work 7.
- [ ] work 8.
- [ ] work 9.
- [ ] work 10.

## Overview
All data is hosted on OneDrive and Baidu NetDisk:

| Path | Size | Files | Format | Description
| :---- | :---: | ----: | :----: | :----------
| PAGE | 59.6 GB | 98,541 | | Main folder
| ownership | 28.5 GB | 98,525 | NumPy | In-game statistics, with multiple NumPy matrixes.
| metadata.csv | 13.3 MB | 1 | CSV | Game-level Metadata.
| recommended_move.h5 | 5.49 GB | 1 | HDF5 | In-game statistics.
| ingame_statistics.h5 | 1.26 GB | 1 | HDF5 | In-game statistics without ownership and recommended move.
| zip | 24.3 GB | 13 | ZIP | Contents of ownership folder as a ZIP archive.

## Download
Baidu NetDisk：**[download link](https://pan.baidu.com/s/1g0mH5GNVsBde-J_kj6SA1Q?pwd=grvo)**<br>
code：grvo

OneDrive: **[download link](https://1drv.ms/f/s!AieKhpO5O-QAlJ8vNuH5K8hxYOcy7A?e=q6vvgx)**<br>
code：PAGE

## Baselines and examples
ToDo

## Analysis your own data
ToDo

## Related resources
ToDo

## Acknowledgements
ToDo
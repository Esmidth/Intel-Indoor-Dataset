# Standard Procedure of dealing with Intel Indoor Dataset

| File Name | Description |
|----|---|
|test1.ipynb| read data for txt(csv) file, drop nan row, save to hdf5 file, which isdata1.h5|
|test2.ipynb| try to convert logs to tensor for training |
|test3.ipynb| try to convert mote_locs.txt to a tensor distribution map |


 ## TODO list
- test2.ipynb
	- [ ] 筛选出一个合适的传感器子集
	- [ ] 判断子集的数量和数据质量
	- [ ] 保存数据到dataloader
## Issue

- 数据集中存在，同一个epoch里有某一个moteid存在两条数据


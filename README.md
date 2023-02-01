# Benidorm UAV Dataset

> Rafael Caballero, Pablo Jiménez, Francisco J. Pérez-Grau, Antidio Viguria and Aníbal Ollero. 2023. Towards Safe Operations in Urban Environments with UAS. **_UNDER REVISION_**

[![](http://img.youtube.com/vi/h-YDWfSdaAo/0.jpg)](http://www.youtube.com/watch?v=h-YDWfSdaAo)

This repository contains the attached data from the above mentioned publication. The following table provides each of the bag files with independent links. Given the large volume of data generated, the files have been compressed. Please remember to perform a _rosbag decompress_ before using them. More info [here](http://wiki.ros.org/rosbag/Commandline#rosbag_decompress).


|               File Name              | Test | Ouster Model | LIDAR Angle (degrees) | GPS Rel. Height (m) | Duration (min:s) | Size (GB) |
|:------------------------------------:|:----:|:------------:|:---------------------:|:-------------------:|:----------------:|-----------|
| [t1_delorean_2021-04-27-10-51-32.bag](https://fadacatecatlas-my.sharepoint.com/:u:/g/personal/rcaballero_catec_aero/EV-CH258O5lKrrDHdx1hjKYBPEcrhsYLskRMjYZEX8VNxA?e=UVEBVws)  |   1  | OS0-128      |           0           |          15         |       6:23       | 6.61      |
| [t2_delorean_2021-04-27-11-13-41.bag](https://fadacatecatlas-my.sharepoint.com/:u:/g/personal/rcaballero_catec_aero/EQvsbrKHXiJHlNN_B6tqhhIBwWxdVInwVwTqJhxSZlmR5w?e=VxVHPS)  |   2  | OS0-128      |           15          |        15-20        |       5:37       | 5.50      |
| [t3_delorean_2021-04-27-11-48-43.bag](https://fadacatecatlas-my.sharepoint.com/:u:/g/personal/rcaballero_catec_aero/EUX11WT1dJdCtUywQzP2S0ABASHvMV2kfnNPLOHXJEJHcw?e=YMnv7D)  |   3  | OS0-128      |           30          |        15-20        |       5:36       | 5.79      |
| [t4_delorean_2021-04-27-12-43-10.bag](https://fadacatecatlas-my.sharepoint.com/:u:/g/personal/rcaballero_catec_aero/EajKry2RQYpAtqw9yJ4n1rQB7XGhy0FTxCaXueFqdRUaOg?e=aNiABd)  |   4  | OS0-128      |           30          |        18-25        |       11:00      | 10.3      |
| [t5_delorean_2021-04-27-13-08-30.bag](https://fadacatecatlas-my.sharepoint.com/:u:/g/personal/rcaballero_catec_aero/EZ-cJ4HSosZHjFhpO01S39ABl-4vlrjw6cIwBlcF24ImMQ?e=CzgWZA)  |   5  | OS0-128      |           0           |          20         |       14:47      | 13.1      |
| [t6_delorean_2021-04-28-10-23-29.bag](https://fadacatecatlas-my.sharepoint.com/:u:/g/personal/rcaballero_catec_aero/EWVP1eN_jF5Ngz9MTdlZc3cBjklX1KRcNugSP4so1Alo-Q?e=hro1G3)                |   6  | OS0-128      |           30          |          20         |       14:42      | 14.1      |
| [t7_delorean_2021-04-28-12-28-26.bag](https://fadacatecatlas-my.sharepoint.com/:u:/g/personal/rcaballero_catec_aero/EXzMXS4MC2FNhCWIW_NIlSMBvP1DJioKrG8kTgFpKQEDwA?e=hxStSD)                |   7  | OS1-64       |           15          |          20         |       15:43      | 8.28      |
| [t8_delorean_2021-04-28-12-58-12.bag](https://fadacatecatlas-my.sharepoint.com/:u:/g/personal/rcaballero_catec_aero/EYlSkUcXiH1Bn-egDjUKYeQBSB6klXnAdo0JFS1Twsi4UA?e=P1zc8O)                |   8  | OS1-64       |           0           |          20         |       8:08       | 4.23      |
| [t9_delorean_2021-04-28-13-14-20.bag](https://fadacatecatlas-my.sharepoint.com/:u:/g/personal/rcaballero_catec_aero/EbWiIF4veTtGiQxVXnXNafQBB7sFo-UaTC_A9T1uumkAUw?e=ElrqHK)                |   9  | OS1-64       |           30          |          45         |       14:45      | 6.98      |
| [t10_delorean_2021-04-29-11-11-19.bag](https://fadacatecatlas-my.sharepoint.com/:u:/g/personal/rcaballero_catec_aero/EUFAMTxXJA5Np_TsBA_JVZcB-sgluiVxEVpxy73ze_m77w?e=0UCJlX)               |  10  | OS1-64       |           15          |          20         |       9:30       | 5.54      |
| [t11_delorean_2021-04-29-12-01-36.bag](https://fadacatecatlas-my.sharepoint.com/:u:/g/personal/rcaballero_catec_aero/EQODlOC6jTtPgawcKTsyJMsB1_OvbFzSlrqVVgxc_IlG5A?e=mOZsCZ) |  11  | OS1-64       |           0           |          20         |       8:23       | 4.76      |

# Calibration

The extrinsic transforms between the different UAV frames are described in the following document: [link](https://fadacatecatlas-my.sharepoint.com/:b:/g/personal/rcaballero_catec_aero/Ecdcm5QHycVAjNdnDkxs_6gBF9_vIXGlV5v8ZCh93DzGww?e=bGz6vA)

Regarding the IMU, find here its intrinsic parameters after 2 hours of static calibration: [link](https://fadacatecatlas-my.sharepoint.com/:u:/g/personal/rcaballero_catec_aero/ESB7egUJIG1PsmFgni_SsyIBGpvsowikkLyCfkIsNOIq7A?e=WyzEXf)

The original bag file for recalibration can be downloaded here: [imu_calib_bagfile](https://fadacatecatlas-my.sharepoint.com/:u:/g/personal/rcaballero_catec_aero/ER7EP61T4SlIskF9gchCeVMBJ-MuSGEvyD6lO6kvSIW6dQ?e=c3d8sJ)

# Citation

If you use this data for any academic work, please cite our original paper: TBD

```bibtex
UNDER REVISION
```

# Funding

This work has been performed within the context of DELOREAN project, funded by the European Commission under contract 870251.
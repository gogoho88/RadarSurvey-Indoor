# RadarSurvey-Indoor
Survey list for radar datasets, papers, and codes (**Indoors+Others**)
Contact: jhchoi93@postech.ac.kr

<!--Dataset-->
| Dataset | Year | Data Type | Annot. Type | Modality | Other | Link | Remarks |
| :----: | :----: | :----: | :----: | :----: | :----: | :----: | ---- |
| IDRad | 2018 | mD | class (ID) | R | - | [Paper](https://ieeexplore.ieee.org/document/8333730)<br> [Website](https://www.imec-int.com/en/IDRad) | * Ghent Univ.<br> * 5 Class<br> * Contact |
| Vid2Doppler | 2021 | mD | class (activity) | C+R | S | [Paper](https://dl.acm.org/doi/abs/10.1145/3411764.3445138)<br> [Github](https://github.com/FIGLAB/Vid2Doppler) | * CMU<br> * 12 Class<br> * Contact |

> **Description & Abbreviations**
> * **[Data Type]** ADC: analog-to-digital converted data, mD: micro-Doppler
> * **[Modality]** C: camera, D: stereo-depth, L: lidar, R: radar
> * **[Other]** C: complex (magnitude+phase) data, T: temporal data, S: scanned data, E: elevation dimensions are added, S: simulated
> * **[Remarks]** Contact: must contact to authors for data acquisition

<!--Paper-->
## Papers
### AI+Radar (Application aspect)
| Year | Journal | Paper | Task | Radar | Link | Remarks |
| :----: | :----: | ---- | ---- | :----: | :----: | :---- |
| 2018 | SIGCOMM | RF-Based 3D Skeletons | 3D skeleton estimation | FMCW Radar (self-made) | [Paper](https://dl.acm.org/doi/10.1145/3230543.3230579) | * MIT |
| 2019 | ICCV | Through-Wall Human Mesh Recovery Using Radio Signals | Mesh estimation | FMCW Radar (self-made) | [Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Zhao_Through-Wall_Human_Mesh_Recovery_Using_Radio_Signals_ICCV_2019_paper.pdf) | * MIT |
| 2020 | ECCV | In-Home Daily-Life Captioning Using Radio Signals | Captioning | FMCW Radar (self-made) | [Paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470103.pdf) | * MIT |
| 2020 | MobiCom | Contactless seismocardiography via deep learning radars | Vital estimation from stationary person | FMCW Radar (TI IWR1443BOOST) | [Paper](https://dl.acm.org/doi/10.1145/3372224.3419982) | * MIT |
| 2021 | CHI | RadarNet: Efficient Gesture Recognition Technique Utilizing a Miniature Radar Sensor | Gesture recognition | FMCW Radar (Soli) | [Paper](https://dl.acm.org/doi/abs/10.1145/3411764.3445367) | * Google |
| 2022 | CHI EA | RaITIn: Radar-Based Identification for Tangible Interactions | Identification for tangible interactions | FMCW Radar (Soli) | [Paper](https://dl.acm.org/doi/abs/10.1145/3491101.3519808) | * Univ. Auckland |

# tensorflow1.15-whl-and-cpp-api-for-win-and-rtx3090
### 中文说明

给30卡在win下使用的tensorflow1.15的whl文件和cpp api，根据nvidia版的tf1.15改造编译，因为是魔改版，建议小心使用。

nvidia版默认开启了一些优化，需要小心的的关闭，这些优化会导致训练不正常以及性能问题，cpp api仅用于进行graph的推理。

我使用 python3.7 cuda11.2 cudnn8.1.0. 进行编译。

### English version

The whl and dll c++ api are for tf1.15 run with win and rtx30xx.

It must be used very carefully.

Nvidia tf use some meta optimizer, when something worng ,close they.

The cpp dll is only used for inference models.

The whl built with python3.7 cuda11.2 cudnn8.1.0.

# cross-re-id

All the links for the features are under the directories "ResNet-50", "ResNet-101", "ResNet-152" and "combinations".
Features of each cameras are saved in seperated mat files named "results_cam#.mat". For the evaluation, copy these feature files to "./feature" directory and set "feature_info.name" in demo.m file (line 6) as "results".

SYSU-MM01 evaluation code: https://github.com/wuancong/SYSU-MM01/tree/master/evaluation

ECN re-ranking code: https://github.com/pse-ecn/expanded-cross-neighborhood

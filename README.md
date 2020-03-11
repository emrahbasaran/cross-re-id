# cross-re-id

### SYSU-MM01

All the links for the features are under the directories "ResNet-50", "ResNet-101", "ResNet-152" and "combinations".

Features of each cameras are saved in seperated mat files named "results_cam#.mat". For the evaluation using the code given in [1], copy these feature files to "./feature" directory and set "feature_info.name" as "results" in demo.m file (line 6).

ECN re-ranking can be applied by using "ECN_rerank.m" script from [2]. Copy this script to "evaluation" directory. Then, change the line 73 of "evaluation_SYSU_MM01.m" as "dist = ECN_rerank(X_probe, X_gallery);" and transpose dist as "dist = dist';".


[1] SYSU-MM01 evaluation code: https://github.com/wuancong/SYSU-MM01/tree/master/evaluation

[2] ECN re-ranking code: https://github.com/pse-ecn/expanded-cross-neighborhood


<br/>

### RegDB

All the links for the features are under the directory "RegDB".

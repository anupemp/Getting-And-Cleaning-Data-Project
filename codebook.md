1. Variable list

> names(data.tidy)
 [1] "activity"                                                    "subject"                                                    
 [3] "TimeDomain_BodyAccelerometer_Mean_X"                         "TimeDomain_BodyAccelerometer_Mean_Y"                        
 [5] "TimeDomain_BodyAccelerometer_Mean_Z"                         "TimeDomain_BodyAccelerometer_StandardDeviation_X"           
 [7] "TimeDomain_BodyAccelerometer_StandardDeviation_Y"            "TimeDomain_BodyAccelerometer_StandardDeviation_Z"           
 [9] "TimeDomain_GravityAccelerometer_Mean_X"                      "TimeDomain_GravityAccelerometer_Mean_Y"                     
[11] "TimeDomain_GravityAccelerometer_Mean_Z"                      "TimeDomain_GravityAccelerometer_StandardDeviation_X"        
[13] "TimeDomain_GravityAccelerometer_StandardDeviation_Y"         "TimeDomain_GravityAccelerometer_StandardDeviation_Z"        
[15] "TimeDomain_BodyAccelerometerJerk_Mean_X"                     "TimeDomain_BodyAccelerometerJerk_Mean_Y"                    
[17] "TimeDomain_BodyAccelerometerJerk_Mean_Z"                     "TimeDomain_BodyAccelerometerJerk_StandardDeviation_X"       
[19] "TimeDomain_BodyAccelerometerJerk_StandardDeviation_Y"        "TimeDomain_BodyAccelerometerJerk_StandardDeviation_Z"       
[21] "TimeDomain_BodyGyroscope_Mean_X"                             "TimeDomain_BodyGyroscope_Mean_Y"                            
[23] "TimeDomain_BodyGyroscope_Mean_Z"                             "TimeDomain_BodyGyroscope_StandardDeviation_X"               
[25] "TimeDomain_BodyGyroscope_StandardDeviation_Y"                "TimeDomain_BodyGyroscope_StandardDeviation_Z"               
[27] "TimeDomain_BodyGyroscopeJerk_Mean_X"                         "TimeDomain_BodyGyroscopeJerk_Mean_Y"                        
[29] "TimeDomain_BodyGyroscopeJerk_Mean_Z"                         "TimeDomain_BodyGyroscopeJerk_StandardDeviation_X"           
[31] "TimeDomain_BodyGyroscopeJerk_StandardDeviation_Y"            "TimeDomain_BodyGyroscopeJerk_StandardDeviation_Z"           
[33] "TimeDomain_BodyAccelerometerMagnitude_mean"                  "TimeDomain_BodyAccelerometerMagnitude_std"                  
[35] "TimeDomain_GravityAccelerometerMagnitude_mean"               "TimeDomain_GravityAccelerometerMagnitude_std"               
[37] "TimeDomain_BodyAccelerometerJerkMagnitude_mean"              "TimeDomain_BodyAccelerometerJerkMagnitude_std"              
[39] "TimeDomain_BodyGyroscopeMagnitude_mean"                      "TimeDomain_BodyGyroscopeMagnitude_std"                      
[41] "TimeDomain_BodyGyroscopeJerkMagnitude_mean"                  "TimeDomain_BodyGyroscopeJerkMagnitude_std"                  
[43] "FrequencyDomain_BodyAccelerometer_Mean_X"                    "FrequencyDomain_BodyAccelerometer_Mean_Y"                   
[45] "FrequencyDomain_BodyAccelerometer_Mean_Z"                    "FrequencyDomain_BodyAccelerometer_StandardDeviation_X"      
[47] "FrequencyDomain_BodyAccelerometer_StandardDeviation_Y"       "FrequencyDomain_BodyAccelerometer_StandardDeviation_Z"      
[49] "FrequencyDomain_BodyAccelerometer_meanFreq_X"                "FrequencyDomain_BodyAccelerometer_meanFreq_Y"               
[51] "FrequencyDomain_BodyAccelerometer_meanFreq_Z"                "FrequencyDomain_BodyAccelerometerJerk_Mean_X"               
[53] "FrequencyDomain_BodyAccelerometerJerk_Mean_Y"                "FrequencyDomain_BodyAccelerometerJerk_Mean_Z"               
[55] "FrequencyDomain_BodyAccelerometerJerk_StandardDeviation_X"   "FrequencyDomain_BodyAccelerometerJerk_StandardDeviation_Y"  
[57] "FrequencyDomain_BodyAccelerometerJerk_StandardDeviation_Z"   "FrequencyDomain_BodyAccelerometerJerk_meanFreq_X"           
[59] "FrequencyDomain_BodyAccelerometerJerk_meanFreq_Y"            "FrequencyDomain_BodyAccelerometerJerk_meanFreq_Z"           
[61] "FrequencyDomain_BodyGyroscope_Mean_X"                        "FrequencyDomain_BodyGyroscope_Mean_Y"                       
[63] "FrequencyDomain_BodyGyroscope_Mean_Z"                        "FrequencyDomain_BodyGyroscope_StandardDeviation_X"          
[65] "FrequencyDomain_BodyGyroscope_StandardDeviation_Y"           "FrequencyDomain_BodyGyroscope_StandardDeviation_Z"          
[67] "FrequencyDomain_BodyGyroscope_meanFreq_X"                    "FrequencyDomain_BodyGyroscope_meanFreq_Y"                   
[69] "FrequencyDomain_BodyGyroscope_meanFreq_Z"                    "FrequencyDomain_BodyAccelerometerMagnitude_mean"            
[71] "FrequencyDomain_BodyAccelerometerMagnitude_std"              "FrequencyDomain_BodyAccelerometerMagnitude_meanFreq"        
[73] "FrequencyDomain_BodyBodyAccelerometerJerkMagnitude_mean"     "FrequencyDomain_BodyBodyAccelerometerJerkMagnitude_std"     
[75] "FrequencyDomain_BodyBodyAccelerometerJerkMagnitude_meanFreq" "FrequencyDomain_BodyBodyGyroscopeMagnitude_mean"            
[77] "FrequencyDomain_BodyBodyGyroscopeMagnitude_std"              "FrequencyDomain_BodyBodyGyroscopeMagnitude_meanFreq"        
[79] "FrequencyDomain_BodyBodyGyroscopeJerkMagnitude_mean"         "FrequencyDomain_BodyBodyGyroscopeJerkMagnitude_std"         
[81] "FrequencyDomain_BodyBodyGyroscopeJerkMagnitude_meanFreq"    

2. Dataset structure

str(data.tidy)
'data.frame':	180 obs. of  81 variables:
 $ activity                                                   : chr  "LAYING" "SITTING" "STANDING" "WALKING" ...
 $ subject                                                    : int  1 1 1 1 1 1 2 2 2 2 ...
 $ TimeDomain_BodyAccelerometer_Mean_X                        : num  0.222 0.261 0.279 0.277 0.289 ...
 $ TimeDomain_BodyAccelerometer_Mean_Y                        : num  -0.04051 -0.00131 -0.01614 -0.01738 -0.00992 ...
 $ TimeDomain_BodyAccelerometer_Mean_Z                        : num  -0.113 -0.105 -0.111 -0.111 -0.108 ...
 $ TimeDomain_BodyAccelerometer_StandardDeviation_X           : num  -0.928 -0.977 -0.996 -0.284 0.03 ...
 $ TimeDomain_BodyAccelerometer_StandardDeviation_Y           : num  -0.8368 -0.9226 -0.9732 0.1145 -0.0319 ...
 $ TimeDomain_BodyAccelerometer_StandardDeviation_Z           : num  -0.826 -0.94 -0.98 -0.26 -0.23 ...
 $ TimeDomain_GravityAccelerometer_Mean_X                     : num  -0.249 0.832 0.943 0.935 0.932 ...
 $ TimeDomain_GravityAccelerometer_Mean_Y                     : num  0.706 0.204 -0.273 -0.282 -0.267 ...
 $ TimeDomain_GravityAccelerometer_Mean_Z                     : num  0.4458 0.332 0.0135 -0.0681 -0.0621 ...
 $ TimeDomain_GravityAccelerometer_StandardDeviation_X        : num  -0.897 -0.968 -0.994 -0.977 -0.951 ...
 $ TimeDomain_GravityAccelerometer_StandardDeviation_Y        : num  -0.908 -0.936 -0.981 -0.971 -0.937 ...
 $ TimeDomain_GravityAccelerometer_StandardDeviation_Z        : num  -0.852 -0.949 -0.976 -0.948 -0.896 ...
 $ TimeDomain_BodyAccelerometerJerk_Mean_X                    : num  0.0811 0.0775 0.0754 0.074 0.0542 ...
 $ TimeDomain_BodyAccelerometerJerk_Mean_Y                    : num  0.003838 -0.000619 0.007976 0.028272 0.02965 ...
 $ TimeDomain_BodyAccelerometerJerk_Mean_Z                    : num  0.01083 -0.00337 -0.00369 -0.00417 -0.01097 ...
 $ TimeDomain_BodyAccelerometerJerk_StandardDeviation_X       : num  -0.9585 -0.9864 -0.9946 -0.1136 -0.0123 ...
 $ TimeDomain_BodyAccelerometerJerk_StandardDeviation_Y       : num  -0.924 -0.981 -0.986 0.067 -0.102 ...
 $ TimeDomain_BodyAccelerometerJerk_StandardDeviation_Z       : num  -0.955 -0.988 -0.992 -0.503 -0.346 ...
 $ TimeDomain_BodyGyroscope_Mean_X                            : num  -0.0166 -0.0454 -0.024 -0.0418 -0.0351 ...
 $ TimeDomain_BodyGyroscope_Mean_Y                            : num  -0.0645 -0.0919 -0.0594 -0.0695 -0.0909 ...
 $ TimeDomain_BodyGyroscope_Mean_Z                            : num  0.1487 0.0629 0.0748 0.0849 0.0901 ...
 $ TimeDomain_BodyGyroscope_StandardDeviation_X               : num  -0.874 -0.977 -0.987 -0.474 -0.458 ...
 $ TimeDomain_BodyGyroscope_StandardDeviation_Y               : num  -0.9511 -0.9665 -0.9877 -0.0546 -0.1263 ...
 $ TimeDomain_BodyGyroscope_StandardDeviation_Z               : num  -0.908 -0.941 -0.981 -0.344 -0.125 ...
 $ TimeDomain_BodyGyroscopeJerk_Mean_X                        : num  -0.1073 -0.0937 -0.0996 -0.09 -0.074 ...
 $ TimeDomain_BodyGyroscopeJerk_Mean_Y                        : num  -0.0415 -0.0402 -0.0441 -0.0398 -0.044 ...
 $ TimeDomain_BodyGyroscopeJerk_Mean_Z                        : num  -0.0741 -0.0467 -0.049 -0.0461 -0.027 ...
 $ TimeDomain_BodyGyroscopeJerk_StandardDeviation_X           : num  -0.919 -0.992 -0.993 -0.207 -0.487 ...
 $ TimeDomain_BodyGyroscopeJerk_StandardDeviation_Y           : num  -0.968 -0.99 -0.995 -0.304 -0.239 ...
 $ TimeDomain_BodyGyroscopeJerk_StandardDeviation_Z           : num  -0.958 -0.988 -0.992 -0.404 -0.269 ...
 $ TimeDomain_BodyAccelerometerMagnitude_mean                 : num  -0.8419 -0.9485 -0.9843 -0.137 0.0272 ...
 $ TimeDomain_BodyAccelerometerMagnitude_std                  : num  -0.7951 -0.9271 -0.9819 -0.2197 0.0199 ...
 $ TimeDomain_GravityAccelerometerMagnitude_mean              : num  -0.8419 -0.9485 -0.9843 -0.137 0.0272 ...
 $ TimeDomain_GravityAccelerometerMagnitude_std               : num  -0.7951 -0.9271 -0.9819 -0.2197 0.0199 ...
 $ TimeDomain_BodyAccelerometerJerkMagnitude_mean             : num  -0.9544 -0.9874 -0.9924 -0.1414 -0.0894 ...
 $ TimeDomain_BodyAccelerometerJerkMagnitude_std              : num  -0.9282 -0.9841 -0.9931 -0.0745 -0.0258 ...
 $ TimeDomain_BodyGyroscopeMagnitude_mean                     : num  -0.8748 -0.9309 -0.9765 -0.161 -0.0757 ...
 $ TimeDomain_BodyGyroscopeMagnitude_std                      : num  -0.819 -0.935 -0.979 -0.187 -0.226 ...
 $ TimeDomain_BodyGyroscopeJerkMagnitude_mean                 : num  -0.963 -0.992 -0.995 -0.299 -0.295 ...
 $ TimeDomain_BodyGyroscopeJerkMagnitude_std                  : num  -0.936 -0.988 -0.995 -0.325 -0.307 ...
 $ FrequencyDomain_BodyAccelerometer_Mean_X                   : num  -0.9391 -0.9796 -0.9952 -0.2028 0.0382 ...
 $ FrequencyDomain_BodyAccelerometer_Mean_Y                   : num  -0.86707 -0.94408 -0.97707 0.08971 0.00155 ...
 $ FrequencyDomain_BodyAccelerometer_Mean_Z                   : num  -0.883 -0.959 -0.985 -0.332 -0.226 ...
 $ FrequencyDomain_BodyAccelerometer_StandardDeviation_X      : num  -0.9244 -0.9764 -0.996 -0.3191 0.0243 ...
 $ FrequencyDomain_BodyAccelerometer_StandardDeviation_Y      : num  -0.834 -0.917 -0.972 0.056 -0.113 ...
 $ FrequencyDomain_BodyAccelerometer_StandardDeviation_Z      : num  -0.813 -0.934 -0.978 -0.28 -0.298 ...
 $ FrequencyDomain_BodyAccelerometer_meanFreq_X               : num  -0.1588 -0.0495 0.0865 -0.2075 -0.3074 ...
 $ FrequencyDomain_BodyAccelerometer_meanFreq_Y               : num  0.0975 0.0759 0.1175 0.1131 0.0632 ...
 $ FrequencyDomain_BodyAccelerometer_meanFreq_Z               : num  0.0894 0.2388 0.2449 0.0497 0.2943 ...
 $ FrequencyDomain_BodyAccelerometerJerk_Mean_X               : num  -0.9571 -0.9866 -0.9946 -0.1705 -0.0277 ...
 $ FrequencyDomain_BodyAccelerometerJerk_Mean_Y               : num  -0.9225 -0.9816 -0.9854 -0.0352 -0.1287 ...
 $ FrequencyDomain_BodyAccelerometerJerk_Mean_Z               : num  -0.948 -0.986 -0.991 -0.469 -0.288 ...
 $ FrequencyDomain_BodyAccelerometerJerk_StandardDeviation_X  : num  -0.9642 -0.9875 -0.9951 -0.1336 -0.0863 ...
 $ FrequencyDomain_BodyAccelerometerJerk_StandardDeviation_Y  : num  -0.932 -0.983 -0.987 0.107 -0.135 ...
 $ FrequencyDomain_BodyAccelerometerJerk_StandardDeviation_Z  : num  -0.961 -0.988 -0.992 -0.535 -0.402 ...
 $ FrequencyDomain_BodyAccelerometerJerk_meanFreq_X           : num  0.132 0.257 0.314 -0.209 -0.253 ...
 $ FrequencyDomain_BodyAccelerometerJerk_meanFreq_Y           : num  0.0245 0.0475 0.0392 -0.3862 -0.3376 ...
 $ FrequencyDomain_BodyAccelerometerJerk_meanFreq_Z           : num  0.02439 0.09239 0.13858 -0.18553 0.00937 ...
 $ FrequencyDomain_BodyGyroscope_Mean_X                       : num  -0.85 -0.976 -0.986 -0.339 -0.352 ...
 $ FrequencyDomain_BodyGyroscope_Mean_Y                       : num  -0.9522 -0.9758 -0.989 -0.1031 -0.0557 ...
 $ FrequencyDomain_BodyGyroscope_Mean_Z                       : num  -0.9093 -0.9513 -0.9808 -0.2559 -0.0319 ...
 $ FrequencyDomain_BodyGyroscope_StandardDeviation_X          : num  -0.882 -0.978 -0.987 -0.517 -0.495 ...
 $ FrequencyDomain_BodyGyroscope_StandardDeviation_Y          : num  -0.9512 -0.9623 -0.9871 -0.0335 -0.1814 ...
 $ FrequencyDomain_BodyGyroscope_StandardDeviation_Z          : num  -0.917 -0.944 -0.982 -0.437 -0.238 ...
 $ FrequencyDomain_BodyGyroscope_meanFreq_X                   : num  -0.00355 0.18915 -0.12029 0.01478 -0.10045 ...
 $ FrequencyDomain_BodyGyroscope_meanFreq_Y                   : num  -0.0915 0.0631 -0.0447 -0.0658 0.0826 ...
 $ FrequencyDomain_BodyGyroscope_meanFreq_Z                   : num  0.010458 -0.029784 0.100608 0.000773 -0.075676 ...
 $ FrequencyDomain_BodyAccelerometerMagnitude_mean            : num  -0.8618 -0.9478 -0.9854 -0.1286 0.0966 ...
 $ FrequencyDomain_BodyAccelerometerMagnitude_std             : num  -0.798 -0.928 -0.982 -0.398 -0.187 ...
 $ FrequencyDomain_BodyAccelerometerMagnitude_meanFreq        : num  0.0864 0.2367 0.2846 0.1906 0.1192 ...
 $ FrequencyDomain_BodyBodyAccelerometerJerkMagnitude_mean    : num  -0.9333 -0.9853 -0.9925 -0.0571 0.0262 ...
 $ FrequencyDomain_BodyBodyAccelerometerJerkMagnitude_std     : num  -0.922 -0.982 -0.993 -0.103 -0.104 ...
 $ FrequencyDomain_BodyBodyAccelerometerJerkMagnitude_meanFreq: num  0.2664 0.3519 0.4222 0.0938 0.0765 ...
 $ FrequencyDomain_BodyBodyGyroscopeMagnitude_mean            : num  -0.862 -0.958 -0.985 -0.199 -0.186 ...
 $ FrequencyDomain_BodyBodyGyroscopeMagnitude_std             : num  -0.824 -0.932 -0.978 -0.321 -0.398 ...
 $ FrequencyDomain_BodyBodyGyroscopeMagnitude_meanFreq        : num  -0.139775 -0.000262 -0.028606 0.268844 0.349614 ...
 $ FrequencyDomain_BodyBodyGyroscopeJerkMagnitude_mean        : num  -0.942 -0.99 -0.995 -0.319 -0.282 ...
 $ FrequencyDomain_BodyBodyGyroscopeJerkMagnitude_std         : num  -0.933 -0.987 -0.995 -0.382 -0.392 ...
 $ FrequencyDomain_BodyBodyGyroscopeJerkMagnitude_meanFreq    : num  0.176 0.185 0.334 0.191 0.19 ...
> 

3. Summary of variables

Summary(data.tidy)

> summary(data.tidy)
   activity            subject     TimeDomain_BodyAccelerometer_Mean_X TimeDomain_BodyAccelerometer_Mean_Y TimeDomain_BodyAccelerometer_Mean_Z
 Length:180         Min.   : 1.0   Min.   :0.2216                      Min.   :-0.040514                   Min.   :-0.15251                   
 Class :character   1st Qu.: 8.0   1st Qu.:0.2712                      1st Qu.:-0.020022                   1st Qu.:-0.11207                   
 Mode  :character   Median :15.5   Median :0.2770                      Median :-0.017262                   Median :-0.10819                   
                    Mean   :15.5   Mean   :0.2743                      Mean   :-0.017876                   Mean   :-0.10916                   
                    3rd Qu.:23.0   3rd Qu.:0.2800                      3rd Qu.:-0.014936                   3rd Qu.:-0.10443                   
                    Max.   :30.0   Max.   :0.3015                      Max.   :-0.001308                   Max.   :-0.07538                   
 TimeDomain_BodyAccelerometer_StandardDeviation_X TimeDomain_BodyAccelerometer_StandardDeviation_Y TimeDomain_BodyAccelerometer_StandardDeviation_Z
 Min.   :-0.9961                                  Min.   :-0.99024                                 Min.   :-0.9877                                 
 1st Qu.:-0.9799                                  1st Qu.:-0.94205                                 1st Qu.:-0.9498                                 
 Median :-0.7526                                  Median :-0.50897                                 Median :-0.6518                                 
 Mean   :-0.5577                                  Mean   :-0.46046                                 Mean   :-0.5756                                 
 3rd Qu.:-0.1984                                  3rd Qu.:-0.03077                                 3rd Qu.:-0.2306                                 
 Max.   : 0.6269                                  Max.   : 0.61694                                 Max.   : 0.6090                                 
 TimeDomain_GravityAccelerometer_Mean_X TimeDomain_GravityAccelerometer_Mean_Y TimeDomain_GravityAccelerometer_Mean_Z
 Min.   :-0.6800                        Min.   :-0.47989                       Min.   :-0.49509                      
 1st Qu.: 0.8376                        1st Qu.:-0.23319                       1st Qu.:-0.11726                      
 Median : 0.9208                        Median :-0.12782                       Median : 0.02384                      
 Mean   : 0.6975                        Mean   :-0.01621                       Mean   : 0.07413                      
 3rd Qu.: 0.9425                        3rd Qu.: 0.08773                       3rd Qu.: 0.14946                      
 Max.   : 0.9745                        Max.   : 0.95659                       Max.   : 0.95787                      
 TimeDomain_GravityAccelerometer_StandardDeviation_X TimeDomain_GravityAccelerometer_StandardDeviation_Y
 Min.   :-0.9968                                     Min.   :-0.9942                                    
 1st Qu.:-0.9825                                     1st Qu.:-0.9711                                    
 Median :-0.9695                                     Median :-0.9590                                    
 Mean   :-0.9638                                     Mean   :-0.9524                                    
 3rd Qu.:-0.9509                                     3rd Qu.:-0.9370                                    
 Max.   :-0.8296                                     Max.   :-0.6436                                    
 TimeDomain_GravityAccelerometer_StandardDeviation_Z TimeDomain_BodyAccelerometerJerk_Mean_X TimeDomain_BodyAccelerometerJerk_Mean_Y
 Min.   :-0.9910                                     Min.   :0.04269                         Min.   :-0.0386872                     
 1st Qu.:-0.9605                                     1st Qu.:0.07396                         1st Qu.: 0.0004664                     
 Median :-0.9450                                     Median :0.07640                         Median : 0.0094698                     
 Mean   :-0.9364                                     Mean   :0.07947                         Mean   : 0.0075652                     
 3rd Qu.:-0.9180                                     3rd Qu.:0.08330                         3rd Qu.: 0.0134008                     
 Max.   :-0.6102                                     Max.   :0.13019                         Max.   : 0.0568186                     
 TimeDomain_BodyAccelerometerJerk_Mean_Z TimeDomain_BodyAccelerometerJerk_StandardDeviation_X TimeDomain_BodyAccelerometerJerk_StandardDeviation_Y
 Min.   :-0.067458                       Min.   :-0.9946                                      Min.   :-0.9895                                     
 1st Qu.:-0.010601                       1st Qu.:-0.9832                                      1st Qu.:-0.9724                                     
 Median :-0.003861                       Median :-0.8104                                      Median :-0.7756                                     
 Mean   :-0.004953                       Mean   :-0.5949                                      Mean   :-0.5654                                     
 3rd Qu.: 0.001958                       3rd Qu.:-0.2233                                      3rd Qu.:-0.1483                                     
 Max.   : 0.038053                       Max.   : 0.5443                                      Max.   : 0.3553                                     
 TimeDomain_BodyAccelerometerJerk_StandardDeviation_Z TimeDomain_BodyGyroscope_Mean_X TimeDomain_BodyGyroscope_Mean_Y TimeDomain_BodyGyroscope_Mean_Z
 Min.   :-0.99329                                     Min.   :-0.20578                Min.   :-0.20421                Min.   :-0.07245               
 1st Qu.:-0.98266                                     1st Qu.:-0.04712                1st Qu.:-0.08955                1st Qu.: 0.07475               
 Median :-0.88366                                     Median :-0.02871                Median :-0.07318                Median : 0.08512               
 Mean   :-0.73596                                     Mean   :-0.03244                Mean   :-0.07426                Mean   : 0.08744               
 3rd Qu.:-0.51212                                     3rd Qu.:-0.01676                3rd Qu.:-0.06113                3rd Qu.: 0.10177               
 Max.   : 0.03102                                     Max.   : 0.19270                Max.   : 0.02747                Max.   : 0.17910               
 TimeDomain_BodyGyroscope_StandardDeviation_X TimeDomain_BodyGyroscope_StandardDeviation_Y TimeDomain_BodyGyroscope_StandardDeviation_Z
 Min.   :-0.9943                              Min.   :-0.9942                              Min.   :-0.9855                             
 1st Qu.:-0.9735                              1st Qu.:-0.9629                              1st Qu.:-0.9609                             
 Median :-0.7890                              Median :-0.8017                              Median :-0.8010                             
 Mean   :-0.6916                              Mean   :-0.6533                              Mean   :-0.6164                             
 3rd Qu.:-0.4414                              3rd Qu.:-0.4196                              3rd Qu.:-0.3106                             
 Max.   : 0.2677                              Max.   : 0.4765                              Max.   : 0.5649                             
 TimeDomain_BodyGyroscopeJerk_Mean_X TimeDomain_BodyGyroscopeJerk_Mean_Y TimeDomain_BodyGyroscopeJerk_Mean_Z
 Min.   :-0.15721                    Min.   :-0.07681                    Min.   :-0.092500                  
 1st Qu.:-0.10322                    1st Qu.:-0.04552                    1st Qu.:-0.061725                  
 Median :-0.09868                    Median :-0.04112                    Median :-0.053430                  
 Mean   :-0.09606                    Mean   :-0.04269                    Mean   :-0.054802                  
 3rd Qu.:-0.09110                    3rd Qu.:-0.03842                    3rd Qu.:-0.048985                  
 Max.   :-0.02209                    Max.   :-0.01320                    Max.   :-0.006941                  
 TimeDomain_BodyGyroscopeJerk_StandardDeviation_X TimeDomain_BodyGyroscopeJerk_StandardDeviation_Y TimeDomain_BodyGyroscopeJerk_StandardDeviation_Z
 Min.   :-0.9965                                  Min.   :-0.9971                                  Min.   :-0.9954                                 
 1st Qu.:-0.9800                                  1st Qu.:-0.9832                                  1st Qu.:-0.9848                                 
 Median :-0.8396                                  Median :-0.8942                                  Median :-0.8610                                 
 Mean   :-0.7036                                  Mean   :-0.7636                                  Mean   :-0.7096                                 
 3rd Qu.:-0.4629                                  3rd Qu.:-0.5861                                  3rd Qu.:-0.4741                                 
 Max.   : 0.1791                                  Max.   : 0.2959                                  Max.   : 0.1932                                 
 TimeDomain_BodyAccelerometerMagnitude_mean TimeDomain_BodyAccelerometerMagnitude_std TimeDomain_GravityAccelerometerMagnitude_mean
 Min.   :-0.9865                            Min.   :-0.9865                           Min.   :-0.9865                              
 1st Qu.:-0.9573                            1st Qu.:-0.9430                           1st Qu.:-0.9573                              
 Median :-0.4829                            Median :-0.6074                           Median :-0.4829                              
 Mean   :-0.4973                            Mean   :-0.5439                           Mean   :-0.4973                              
 3rd Qu.:-0.0919                            3rd Qu.:-0.2090                           3rd Qu.:-0.0919                              
 Max.   : 0.6446                            Max.   : 0.4284                           Max.   : 0.6446                              
 TimeDomain_GravityAccelerometerMagnitude_std TimeDomain_BodyAccelerometerJerkMagnitude_mean TimeDomain_BodyAccelerometerJerkMagnitude_std
 Min.   :-0.9865                              Min.   :-0.9928                                Min.   :-0.9946                              
 1st Qu.:-0.9430                              1st Qu.:-0.9807                                1st Qu.:-0.9765                              
 Median :-0.6074                              Median :-0.8168                                Median :-0.8014                              
 Mean   :-0.5439                              Mean   :-0.6079                                Mean   :-0.5842                              
 3rd Qu.:-0.2090                              3rd Qu.:-0.2456                                3rd Qu.:-0.2173                              
 Max.   : 0.4284                              Max.   : 0.4345                                Max.   : 0.4506                              
 TimeDomain_BodyGyroscopeMagnitude_mean TimeDomain_BodyGyroscopeMagnitude_std TimeDomain_BodyGyroscopeJerkMagnitude_mean
 Min.   :-0.9807                        Min.   :-0.9814                       Min.   :-0.99732                          
 1st Qu.:-0.9461                        1st Qu.:-0.9476                       1st Qu.:-0.98515                          
 Median :-0.6551                        Median :-0.7420                       Median :-0.86479                          
 Mean   :-0.5652                        Mean   :-0.6304                       Mean   :-0.73637                          
 3rd Qu.:-0.2159                        3rd Qu.:-0.3602                       3rd Qu.:-0.51186                          
 Max.   : 0.4180                        Max.   : 0.3000                       Max.   : 0.08758                          
 TimeDomain_BodyGyroscopeJerkMagnitude_std FrequencyDomain_BodyAccelerometer_Mean_X FrequencyDomain_BodyAccelerometer_Mean_Y
 Min.   :-0.9977                           Min.   :-0.9952                          Min.   :-0.98903                        
 1st Qu.:-0.9805                           1st Qu.:-0.9787                          1st Qu.:-0.95361                        
 Median :-0.8809                           Median :-0.7691                          Median :-0.59498                        
 Mean   :-0.7550                           Mean   :-0.5758                          Mean   :-0.48873                        
 3rd Qu.:-0.5767                           3rd Qu.:-0.2174                          3rd Qu.:-0.06341                        
 Max.   : 0.2502                           Max.   : 0.5370                          Max.   : 0.52419                        
 FrequencyDomain_BodyAccelerometer_Mean_Z FrequencyDomain_BodyAccelerometer_StandardDeviation_X FrequencyDomain_BodyAccelerometer_StandardDeviation_Y
 Min.   :-0.9895                          Min.   :-0.9966                                       Min.   :-0.99068                                     
 1st Qu.:-0.9619                          1st Qu.:-0.9820                                       1st Qu.:-0.94042                                     
 Median :-0.7236                          Median :-0.7470                                       Median :-0.51338                                     
 Mean   :-0.6297                          Mean   :-0.5522                                       Mean   :-0.48148                                     
 3rd Qu.:-0.3183                          3rd Qu.:-0.1966                                       3rd Qu.:-0.07913                                     
 Max.   : 0.2807                          Max.   : 0.6585                                       Max.   : 0.56019                                     
 FrequencyDomain_BodyAccelerometer_StandardDeviation_Z FrequencyDomain_BodyAccelerometer_meanFreq_X FrequencyDomain_BodyAccelerometer_meanFreq_Y
 Min.   :-0.9872                                       Min.   :-0.63591                             Min.   :-0.379518                           
 1st Qu.:-0.9459                                       1st Qu.:-0.39165                             1st Qu.:-0.081314                           
 Median :-0.6441                                       Median :-0.25731                             Median : 0.007855                           
 Mean   :-0.5824                                       Mean   :-0.23227                             Mean   : 0.011529                           
 3rd Qu.:-0.2655                                       3rd Qu.:-0.06105                             3rd Qu.: 0.086281                           
 Max.   : 0.6871                                       Max.   : 0.15912                             Max.   : 0.466528                           
 FrequencyDomain_BodyAccelerometer_meanFreq_Z FrequencyDomain_BodyAccelerometerJerk_Mean_X FrequencyDomain_BodyAccelerometerJerk_Mean_Y
 Min.   :-0.52011                             Min.   :-0.9946                              Min.   :-0.9894                             
 1st Qu.:-0.03629                             1st Qu.:-0.9828                              1st Qu.:-0.9725                             
 Median : 0.06582                             Median :-0.8126                              Median :-0.7817                             
 Mean   : 0.04372                             Mean   :-0.6139                              Mean   :-0.5882                             
 3rd Qu.: 0.17542                             3rd Qu.:-0.2820                              3rd Qu.:-0.1963                             
 Max.   : 0.40253                             Max.   : 0.4743                              Max.   : 0.2767                             
 FrequencyDomain_BodyAccelerometerJerk_Mean_Z FrequencyDomain_BodyAccelerometerJerk_StandardDeviation_X
 Min.   :-0.9920                              Min.   :-0.9951                                          
 1st Qu.:-0.9796                              1st Qu.:-0.9847                                          
 Median :-0.8707                              Median :-0.8254                                          
 Mean   :-0.7144                              Mean   :-0.6121                                          
 3rd Qu.:-0.4697                              3rd Qu.:-0.2475                                          
 Max.   : 0.1578                              Max.   : 0.4768                                          
 FrequencyDomain_BodyAccelerometerJerk_StandardDeviation_Y FrequencyDomain_BodyAccelerometerJerk_StandardDeviation_Z
 Min.   :-0.9905                                           Min.   :-0.993108                                        
 1st Qu.:-0.9737                                           1st Qu.:-0.983747                                        
 Median :-0.7852                                           Median :-0.895121                                        
 Mean   :-0.5707                                           Mean   :-0.756489                                        
 3rd Qu.:-0.1685                                           3rd Qu.:-0.543787                                        
 Max.   : 0.3498                                           Max.   :-0.006236                                        
 FrequencyDomain_BodyAccelerometerJerk_meanFreq_X FrequencyDomain_BodyAccelerometerJerk_meanFreq_Y FrequencyDomain_BodyAccelerometerJerk_meanFreq_Z
 Min.   :-0.57604                                 Min.   :-0.60197                                 Min.   :-0.62756                                
 1st Qu.:-0.28966                                 1st Qu.:-0.39751                                 1st Qu.:-0.30867                                
 Median :-0.06091                                 Median :-0.23209                                 Median :-0.09187                                
 Mean   :-0.06910                                 Mean   :-0.22810                                 Mean   :-0.13760                                
 3rd Qu.: 0.17660                                 3rd Qu.:-0.04721                                 3rd Qu.: 0.03858                                
 Max.   : 0.33145                                 Max.   : 0.19568                                 Max.   : 0.23011                                
 FrequencyDomain_BodyGyroscope_Mean_X FrequencyDomain_BodyGyroscope_Mean_Y FrequencyDomain_BodyGyroscope_Mean_Z
 Min.   :-0.9931                      Min.   :-0.9940                      Min.   :-0.9860                     
 1st Qu.:-0.9697                      1st Qu.:-0.9700                      1st Qu.:-0.9624                     
 Median :-0.7300                      Median :-0.8141                      Median :-0.7909                     
 Mean   :-0.6367                      Mean   :-0.6767                      Mean   :-0.6044                     
 3rd Qu.:-0.3387                      3rd Qu.:-0.4458                      3rd Qu.:-0.2635                     
 Max.   : 0.4750                      Max.   : 0.3288                      Max.   : 0.4924                     
 FrequencyDomain_BodyGyroscope_StandardDeviation_X FrequencyDomain_BodyGyroscope_StandardDeviation_Y FrequencyDomain_BodyGyroscope_StandardDeviation_Z
 Min.   :-0.9947                                   Min.   :-0.9944                                   Min.   :-0.9867                                  
 1st Qu.:-0.9750                                   1st Qu.:-0.9602                                   1st Qu.:-0.9643                                  
 Median :-0.8086                                   Median :-0.7964                                   Median :-0.8224                                  
 Mean   :-0.7110                                   Mean   :-0.6454                                   Mean   :-0.6577                                  
 3rd Qu.:-0.4813                                   3rd Qu.:-0.4154                                   3rd Qu.:-0.3916                                  
 Max.   : 0.1966                                   Max.   : 0.6462                                   Max.   : 0.5225                                  
 FrequencyDomain_BodyGyroscope_meanFreq_X FrequencyDomain_BodyGyroscope_meanFreq_Y FrequencyDomain_BodyGyroscope_meanFreq_Z
 Min.   :-0.395770                        Min.   :-0.66681                         Min.   :-0.50749                        
 1st Qu.:-0.213363                        1st Qu.:-0.29433                         1st Qu.:-0.15481                        
 Median :-0.115527                        Median :-0.15794                         Median :-0.05081                        
 Mean   :-0.104551                        Mean   :-0.16741                         Mean   :-0.05718                        
 3rd Qu.: 0.002655                        3rd Qu.:-0.04269                         3rd Qu.: 0.04152                        
 Max.   : 0.249209                        Max.   : 0.27314                         Max.   : 0.37707                        
 FrequencyDomain_BodyAccelerometerMagnitude_mean FrequencyDomain_BodyAccelerometerMagnitude_std FrequencyDomain_BodyAccelerometerMagnitude_meanFreq
 Min.   :-0.9868                                 Min.   :-0.9876                                Min.   :-0.31234                                   
 1st Qu.:-0.9560                                 1st Qu.:-0.9452                                1st Qu.:-0.01475                                   
 Median :-0.6703                                 Median :-0.6513                                Median : 0.08132                                   
 Mean   :-0.5365                                 Mean   :-0.6210                                Mean   : 0.07613                                   
 3rd Qu.:-0.1622                                 3rd Qu.:-0.3654                                3rd Qu.: 0.17436                                   
 Max.   : 0.5866                                 Max.   : 0.1787                                Max.   : 0.43585                                   
 FrequencyDomain_BodyBodyAccelerometerJerkMagnitude_mean FrequencyDomain_BodyBodyAccelerometerJerkMagnitude_std
 Min.   :-0.9940                                         Min.   :-0.9944                                       
 1st Qu.:-0.9770                                         1st Qu.:-0.9752                                       
 Median :-0.7940                                         Median :-0.8126                                       
 Mean   :-0.5756                                         Mean   :-0.5992                                       
 3rd Qu.:-0.1872                                         3rd Qu.:-0.2668                                       
 Max.   : 0.5384                                         Max.   : 0.3163                                       
 FrequencyDomain_BodyBodyAccelerometerJerkMagnitude_meanFreq FrequencyDomain_BodyBodyGyroscopeMagnitude_mean
 Min.   :-0.12521                                            Min.   :-0.9865                                
 1st Qu.: 0.04527                                            1st Qu.:-0.9616                                
 Median : 0.17198                                            Median :-0.7657                                
 Mean   : 0.16255                                            Mean   :-0.6671                                
 3rd Qu.: 0.27593                                            3rd Qu.:-0.4087                                
 Max.   : 0.48809                                            Max.   : 0.2040                                
 FrequencyDomain_BodyBodyGyroscopeMagnitude_std FrequencyDomain_BodyBodyGyroscopeMagnitude_meanFreq FrequencyDomain_BodyBodyGyroscopeJerkMagnitude_mean
 Min.   :-0.9815                                Min.   :-0.45664                                    Min.   :-0.9976                                    
 1st Qu.:-0.9488                                1st Qu.:-0.16951                                    1st Qu.:-0.9813                                    
 Median :-0.7727                                Median :-0.05352                                    Median :-0.8779                                    
 Mean   :-0.6723                                Mean   :-0.03603                                    Mean   :-0.7564                                    
 3rd Qu.:-0.4277                                3rd Qu.: 0.08228                                    3rd Qu.:-0.5831                                    
 Max.   : 0.2367                                Max.   : 0.40952                                    Max.   : 0.1466                                    
 FrequencyDomain_BodyBodyGyroscopeJerkMagnitude_std FrequencyDomain_BodyBodyGyroscopeJerkMagnitude_meanFreq
 Min.   :-0.9976                                    Min.   :-0.18292                                       
 1st Qu.:-0.9802                                    1st Qu.: 0.05423                                       
 Median :-0.8941                                    Median : 0.11156                                       
 Mean   :-0.7715                                    Mean   : 0.12592                                       
 3rd Qu.:-0.6081                                    3rd Qu.: 0.20805                                       
 Max.   : 0.2878                                    Max.   : 0.42630                                       
> 

4. Show a few rows of the dataset

> head(data.tidy)
            activity subject TimeDomain_BodyAccelerometer_Mean_X TimeDomain_BodyAccelerometer_Mean_Y TimeDomain_BodyAccelerometer_Mean_Z
1             LAYING       1                           0.2215982                        -0.040513953                          -0.1132036
2            SITTING       1                           0.2612376                        -0.001308288                          -0.1045442
3           STANDING       1                           0.2789176                        -0.016137590                          -0.1106018
4            WALKING       1                           0.2773308                        -0.017383819                          -0.1111481
5 WALKING_DOWNSTAIRS       1                           0.2891883                        -0.009918505                          -0.1075662
6   WALKING_UPSTAIRS       1                           0.2554617                        -0.023953149                          -0.0973020
  TimeDomain_BodyAccelerometer_StandardDeviation_X TimeDomain_BodyAccelerometer_StandardDeviation_Y TimeDomain_BodyAccelerometer_StandardDeviation_Z
1                                      -0.92805647                                     -0.836827406                                      -0.82606140
2                                      -0.97722901                                     -0.922618642                                      -0.93958629
3                                      -0.99575990                                     -0.973190056                                      -0.97977588
4                                      -0.28374026                                      0.114461337                                      -0.26002790
5                                       0.03003534                                     -0.031935943                                      -0.23043421
6                                      -0.35470803                                     -0.002320265                                      -0.01947924
  TimeDomain_GravityAccelerometer_Mean_X TimeDomain_GravityAccelerometer_Mean_Y TimeDomain_GravityAccelerometer_Mean_Z
1                             -0.2488818                              0.7055498                             0.44581772
2                              0.8315099                              0.2044116                             0.33204370
3                              0.9429520                             -0.2729838                             0.01349058
4                              0.9352232                             -0.2821650                            -0.06810286
5                              0.9318744                             -0.2666103                            -0.06211996
6                              0.8933511                             -0.3621534                            -0.07540294
  TimeDomain_GravityAccelerometer_StandardDeviation_X TimeDomain_GravityAccelerometer_StandardDeviation_Y
1                                          -0.8968300                                          -0.9077200
2                                          -0.9684571                                          -0.9355171
3                                          -0.9937630                                          -0.9812260
4                                          -0.9766096                                          -0.9713060
5                                          -0.9505598                                          -0.9370187
6                                          -0.9563670                                          -0.9528492
  TimeDomain_GravityAccelerometer_StandardDeviation_Z TimeDomain_BodyAccelerometerJerk_Mean_X TimeDomain_BodyAccelerometerJerk_Mean_Y
1                                          -0.8523663                              0.08108653                            0.0038382040
2                                          -0.9490409                              0.07748252                           -0.0006191028
3                                          -0.9763241                              0.07537665                            0.0079757309
4                                          -0.9477172                              0.07404163                            0.0282721096
5                                          -0.8959397                              0.05415532                            0.0296504490
6                                          -0.9123794                              0.10137273                            0.0194863076
  TimeDomain_BodyAccelerometerJerk_Mean_Z TimeDomain_BodyAccelerometerJerk_StandardDeviation_X TimeDomain_BodyAccelerometerJerk_StandardDeviation_Y
1                             0.010834236                                          -0.95848211                                           -0.9241493
2                            -0.003367792                                          -0.98643071                                           -0.9813720
3                            -0.003685250                                          -0.99460454                                           -0.9856487
4                            -0.004168406                                          -0.11361560                                            0.0670025
5                            -0.010971973                                          -0.01228386                                           -0.1016014
6                            -0.045562545                                          -0.44684389                                           -0.3782744
  TimeDomain_BodyAccelerometerJerk_StandardDeviation_Z TimeDomain_BodyGyroscope_Mean_X TimeDomain_BodyGyroscope_Mean_Y TimeDomain_BodyGyroscope_Mean_Z
1                                           -0.9548551                     -0.01655309                     -0.06448612                      0.14868944
2                                           -0.9879108                     -0.04535006                     -0.09192415                      0.06293138
3                                           -0.9922512                     -0.02398773                     -0.05939722                      0.07480075
4                                           -0.5026998                     -0.04183096                     -0.06953005                      0.08494482
5                                           -0.3457350                     -0.03507819                     -0.09093713                      0.09008501
6                                           -0.7065935                      0.05054938                     -0.16617002                      0.05835955
  TimeDomain_BodyGyroscope_StandardDeviation_X TimeDomain_BodyGyroscope_StandardDeviation_Y TimeDomain_BodyGyroscope_StandardDeviation_Z
1                                   -0.8735439                                 -0.951090440                                   -0.9082847
2                                   -0.9772113                                 -0.966473895                                   -0.9414259
3                                   -0.9871919                                 -0.987734440                                   -0.9806456
4                                   -0.4735355                                 -0.054607769                                   -0.3442666
5                                   -0.4580305                                 -0.126349195                                   -0.1247025
6                                   -0.5448711                                  0.004105184                                   -0.5071687
  TimeDomain_BodyGyroscopeJerk_Mean_X TimeDomain_BodyGyroscopeJerk_Mean_Y TimeDomain_BodyGyroscopeJerk_Mean_Z
1                         -0.10727095                         -0.04151729                         -0.07405012
2                         -0.09367938                         -0.04021181                         -0.04670263
3                         -0.09960921                         -0.04406279                         -0.04895055
4                         -0.08999754                         -0.03984287                         -0.04613093
5                         -0.07395920                         -0.04399028                         -0.02704611
6                         -0.12223277                         -0.04214859                         -0.04071255
  TimeDomain_BodyGyroscopeJerk_StandardDeviation_X TimeDomain_BodyGyroscopeJerk_StandardDeviation_Y TimeDomain_BodyGyroscopeJerk_StandardDeviation_Z
1                                       -0.9186085                                       -0.9679072                                       -0.9577902
2                                       -0.9917316                                       -0.9895181                                       -0.9879358
3                                       -0.9929451                                       -0.9951379                                       -0.9921085
4                                       -0.2074219                                       -0.3044685                                       -0.4042555
5                                       -0.4870273                                       -0.2388248                                       -0.2687615
6                                       -0.6147865                                       -0.6016967                                       -0.6063320
  TimeDomain_BodyAccelerometerMagnitude_mean TimeDomain_BodyAccelerometerMagnitude_std TimeDomain_GravityAccelerometerMagnitude_mean
1                                -0.84192915                               -0.79514486                                   -0.84192915
2                                -0.94853679                               -0.92707842                                   -0.94853679
3                                -0.98427821                               -0.98194293                                   -0.98427821
4                                -0.13697118                               -0.21968865                                   -0.13697118
5                                 0.02718829                                0.01988435                                    0.02718829
6                                -0.12992763                               -0.32497093                                   -0.12992763
  TimeDomain_GravityAccelerometerMagnitude_std TimeDomain_BodyAccelerometerJerkMagnitude_mean TimeDomain_BodyAccelerometerJerkMagnitude_std
1                                  -0.79514486                                    -0.95439626                                   -0.92824563
2                                  -0.92707842                                    -0.98736420                                   -0.98412002
3                                  -0.98194293                                    -0.99236779                                   -0.99309621
4                                  -0.21968865                                    -0.14142881                                   -0.07447175
5                                   0.01988435                                    -0.08944748                                   -0.02578772
6                                  -0.32497093                                    -0.46650345                                   -0.47899162
  TimeDomain_BodyGyroscopeMagnitude_mean TimeDomain_BodyGyroscopeMagnitude_std TimeDomain_BodyGyroscopeJerkMagnitude_mean
1                            -0.87475955                            -0.8190102                                 -0.9634610
2                            -0.93089249                            -0.9345318                                 -0.9919763
3                            -0.97649379                            -0.9786900                                 -0.9949668
4                            -0.16097955                            -0.1869784                                 -0.2987037
5                            -0.07574125                            -0.2257244                                 -0.2954638
6                            -0.12673559                            -0.1486193                                 -0.5948829
  TimeDomain_BodyGyroscopeJerkMagnitude_std FrequencyDomain_BodyAccelerometer_Mean_X FrequencyDomain_BodyAccelerometer_Mean_Y
1                                -0.9358410                              -0.93909905                             -0.867065205
2                                -0.9883087                              -0.97964124                             -0.944084550
3                                -0.9947332                              -0.99524993                             -0.977070848
4                                -0.3253249                              -0.20279431                              0.089712726
5                                -0.3065106                               0.03822918                              0.001549908
6                                -0.6485530                              -0.40432178                             -0.190976721
  FrequencyDomain_BodyAccelerometer_Mean_Z FrequencyDomain_BodyAccelerometer_StandardDeviation_X FrequencyDomain_BodyAccelerometer_StandardDeviation_Y
1                               -0.8826669                                           -0.92443743                                           -0.83362556
2                               -0.9591849                                           -0.97641231                                           -0.91727501
3                               -0.9852971                                           -0.99602835                                           -0.97229310
4                               -0.3315601                                           -0.31913472                                            0.05604001
5                               -0.2255745                                            0.02433084                                           -0.11296374
6                               -0.4333497                                           -0.33742819                                            0.02176951
  FrequencyDomain_BodyAccelerometer_StandardDeviation_Z FrequencyDomain_BodyAccelerometer_meanFreq_X FrequencyDomain_BodyAccelerometer_meanFreq_Y
1                                           -0.81289156                                  -0.15879267                                   0.09753484
2                                           -0.93446956                                  -0.04951360                                   0.07594608
3                                           -0.97793726                                   0.08651536                                   0.11747895
4                                           -0.27968675                                  -0.20754837                                   0.11309365
5                                           -0.29792789                                  -0.30739520                                   0.06322008
6                                            0.08595655                                  -0.41873500                                  -0.16069721
  FrequencyDomain_BodyAccelerometer_meanFreq_Z FrequencyDomain_BodyAccelerometerJerk_Mean_X FrequencyDomain_BodyAccelerometerJerk_Mean_Y
1                                   0.08943766                                  -0.95707388                                  -0.92246261
2                                   0.23882987                                  -0.98659702                                  -0.98157947
3                                   0.24485859                                  -0.99463080                                  -0.98541870
4                                   0.04972652                                  -0.17054696                                  -0.03522552
5                                   0.29432270                                  -0.02766387                                  -0.12866716
6                                  -0.52011479                                  -0.47987525                                  -0.41344459
  FrequencyDomain_BodyAccelerometerJerk_Mean_Z FrequencyDomain_BodyAccelerometerJerk_StandardDeviation_X
1                                   -0.9480609                                                -0.9641607
2                                   -0.9860531                                                -0.9874930
3                                   -0.9907522                                                -0.9950738
4                                   -0.4689992                                                -0.1335866
5                                   -0.2883347                                                -0.0863279
6                                   -0.6854744                                                -0.4619070
  FrequencyDomain_BodyAccelerometerJerk_StandardDeviation_Y FrequencyDomain_BodyAccelerometerJerk_StandardDeviation_Z
1                                                -0.9322179                                                -0.9605870
2                                                -0.9825139                                                -0.9883392
3                                                -0.9870182                                                -0.9923498
4                                                 0.1067399                                                -0.5347134
5                                                -0.1345800                                                -0.4017215
6                                                -0.3817771                                                -0.7260402
  FrequencyDomain_BodyAccelerometerJerk_meanFreq_X FrequencyDomain_BodyAccelerometerJerk_meanFreq_Y FrequencyDomain_BodyAccelerometerJerk_meanFreq_Z
1                                        0.1324191                                       0.02451362                                      0.024387945
2                                        0.2566108                                       0.04754378                                      0.092392003
3                                        0.3141829                                       0.03916190                                      0.138581479
4                                       -0.2092620                                      -0.38623714                                     -0.185530281
5                                       -0.2531643                                      -0.33758970                                      0.009372239
6                                       -0.3770231                                      -0.50949553                                     -0.551104284
  FrequencyDomain_BodyGyroscope_Mean_X FrequencyDomain_BodyGyroscope_Mean_Y FrequencyDomain_BodyGyroscope_Mean_Z
1                           -0.8502492                          -0.95219149                          -0.90930272
2                           -0.9761615                          -0.97583859                          -0.95131554
3                           -0.9863868                          -0.98898446                          -0.98077312
4                           -0.3390322                          -0.10305942                          -0.25594094
5                           -0.3524496                          -0.05570225                          -0.03186943
6                           -0.4926117                          -0.31947461                          -0.45359721
  FrequencyDomain_BodyGyroscope_StandardDeviation_X FrequencyDomain_BodyGyroscope_StandardDeviation_Y FrequencyDomain_BodyGyroscope_StandardDeviation_Z
1                                        -0.8822965                                       -0.95123205                                        -0.9165825
2                                        -0.9779042                                       -0.96234504                                        -0.9439178
3                                        -0.9874971                                       -0.98710773                                        -0.9823453
4                                        -0.5166919                                       -0.03350816                                        -0.4365622
5                                        -0.4954225                                       -0.18141473                                        -0.2384436
6                                        -0.5658925                                        0.15153891                                        -0.5717078
  FrequencyDomain_BodyGyroscope_meanFreq_X FrequencyDomain_BodyGyroscope_meanFreq_Y FrequencyDomain_BodyGyroscope_meanFreq_Z
1                             -0.003546796                              -0.09152913                             0.0104581257
2                              0.189153021                               0.06312707                            -0.0297839207
3                             -0.120293021                              -0.04471920                             0.1006076351
4                              0.014784499                              -0.06577462                             0.0007733216
5                             -0.100453729                               0.08255115                            -0.0756762068
6                             -0.187450248                              -0.47357479                            -0.1333739043
  FrequencyDomain_BodyAccelerometerMagnitude_mean FrequencyDomain_BodyAccelerometerMagnitude_std FrequencyDomain_BodyAccelerometerMagnitude_meanFreq
1                                     -0.86176765                                     -0.7983009                                          0.08640856
2                                     -0.94778292                                     -0.9284448                                          0.23665501
3                                     -0.98535636                                     -0.9823138                                          0.28455529
4                                     -0.12862345                                     -0.3980326                                          0.19064372
5                                      0.09658453                                     -0.1865303                                          0.11918714
6                                     -0.35239594                                     -0.4162601                                         -0.09774335
  FrequencyDomain_BodyBodyAccelerometerJerkMagnitude_mean FrequencyDomain_BodyBodyAccelerometerJerkMagnitude_std
1                                             -0.93330036                                             -0.9218040
2                                             -0.98526213                                             -0.9816062
3                                             -0.99254248                                             -0.9925360
4                                             -0.05711940                                             -0.1034924
5                                              0.02621849                                             -0.1040523
6                                             -0.44265216                                             -0.5330599
  FrequencyDomain_BodyBodyAccelerometerJerkMagnitude_meanFreq FrequencyDomain_BodyBodyGyroscopeMagnitude_mean
1                                                  0.26639115                                      -0.8621902
2                                                  0.35185220                                      -0.9584356
3                                                  0.42222010                                      -0.9846176
4                                                  0.09382218                                      -0.1992526
5                                                  0.07649155                                      -0.1857203
6                                                  0.08535241                                      -0.3259615
  FrequencyDomain_BodyBodyGyroscopeMagnitude_std FrequencyDomain_BodyBodyGyroscopeMagnitude_meanFreq
1                                     -0.8243194                                       -0.1397750127
2                                     -0.9321984                                       -0.0002621867
3                                     -0.9784661                                       -0.0286057725
4                                     -0.3210180                                        0.2688443675
5                                     -0.3983504                                        0.3496138955
6                                     -0.1829855                                       -0.2193033761
  FrequencyDomain_BodyBodyGyroscopeJerkMagnitude_mean FrequencyDomain_BodyBodyGyroscopeJerkMagnitude_std
1                                          -0.9423669                                         -0.9326607
2                                          -0.9897975                                         -0.9870496
3                                          -0.9948154                                         -0.9946711
4                                          -0.3193086                                         -0.3816019
5                                          -0.2819634                                         -0.3919199
6                                          -0.6346651                                         -0.6939305
  FrequencyDomain_BodyBodyGyroscopeJerkMagnitude_meanFreq
1                                               0.1764859
2                                               0.1847759
3                                               0.3344987
4                                               0.1906634
5                                               0.1900007
6                                               0.1142773




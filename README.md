# SemEval2020
## OffensEval - Task 12 

System  developed  for  the  SemEval-2020  competition  on  MultilingualOffensive  Language  Identification  in  Social  Media  where  we achieved 2nd position in Turkish sub-task and  6th position in Greek Subtask. The goal of task was the identifying the Offensive Language in Social Media. 

### Macro Averaged F1-Scores of test sets


| Model  | Turkish | Greek |
| ------------- | ------------- | -------------|
| CNN-LSTM  | 0.773  |   |
| BiLSTM- Attention  |  0.781  | |
| BERTurk   |  0.808  |  |
| GreekBERT  |    |0.832  |
| Ensemble  |  0.816  | |






| Model  | Language | Embedding | UnderSampling | Val F1 | Val Acc | Test F1 | Test Acc |
| ------------- | ------------- | -------------|-------------|-------------|-------------|-------------|-------------|

|CNN |Tur |Twitter W2V | Without | 0.739  |0.857  |  0.747  | 0.861 |
|CNN |Tur | Twitter W2V | With | 0.733  | 0.847  | 0.738   |0.857 |

|BiLSTM |Tur | Twitter W2V | Without | 0.733 | 0.867|  0.747  | 0.864 |
|BiLSTM | Tur |Twitter W2V | With | 0.755  |  0.857 | 0.748  |0.865 |

|CNN-LSTM |Tur | Twitter W2V | Without | 0.742  |  0.855| 0.766   | 0.863|
|CNN-LSTM |Tur | Twitter W2V | With | 0.751  |  0.867 | 0.773   | 0.865|

|CNN-LSTM |Tur | Public FastText  | Without  | 0.722   | 0.862  | 0.710   |  0.856  |
|CNN-LSTM |Tur | Public FastText | With  | 0.720   | 0.851  | 0.726    | 0.852  |

|CNN-LSTM |Tur | Public W2V  | Without  | 0.711   |  0.856 |  0.717  |0.856  |
|CNN-LSTM |Tur | Public W2V | With  |0.731    |0.85   | 0.739    | 0.857  |

|CNN-LSTM | Tur |Twitter FastText  | Without  |0.743   | 0.851  |0.756   |  0.853|
|CNN-LSTM |Tur | Twitter FastText | With  |  0.767   | 0.874  | 0.753   | 0.864|

|BiLSTM-Att |Tur | Public W2V  | Without  | 0.679   | 0.847  |  0.681  | 0.844 |
|BiLSTM-Att |Tur | Public W2V | With  | 0.707   |  0.827 | 0.721    |0.844   |

|BiLSTM-Att  |Tur | Public FastText | Without  | 0.684    | 0.849 | 0.698   | 0.850 |
|BiLSTM-Att  | Tur |Public FastText | With  |  0.698   | 0.839  | 0.726   | 0.846 |

|BiLSTM-Att  |Tur | Twitter FastText | Without  | 0.735  | 0.852 |  0.721  | 0.867|
|BiLSTM-Att  |Tur | Twitter FastText | With  |  0.738   |  0.866 | 0.747  |0.861 |

|BiLSTM-Att | Tur |Twitter W2V | Without  |0.763  |0.859 | 0.781  | 0.871|
|BiLSTM-Att |Tur | Twitter W2V | With  |  0.748 | 0.870| 0.760  | 0.868|

|BERTurk |Tur | - | Without  | 0.814  | 0.888  | 0.806  | 0.877  |

|BERTurk |Tur | - | With  | 0.789   | 0.866  | 0.808   | 0.873 |
| GreekBERT  | Greek|- | Without| - | - | 0.832| - |


|Ensemble |Tur |-| Without  |  0.822 |   0.896   | 0.813 | 0.887|

|Ensemble |Tur |-| With  |  0.809 |   0.881  | 0.816 | 0.883| 


All models are written in Google Collaboratory environment to take advantage of free GPU.



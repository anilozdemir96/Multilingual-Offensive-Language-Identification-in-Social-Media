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


| Model  | Language | Embedding | UnderSampling | Val F1 | Val Acc | Test F1 | Test Acc
| ------------- | ------------- | -------------|
| CNN | Tur |  |   | | | | | |
| CNN   |Tur  |  | | | | | |
| BiLSTM  | Tur |  0.808  |   | | | | | |
| BiLSTM   |Tur|        |   | | | | | | 
| CNN-LSTM |Tur ||         |   | | | | | |
| CNN-LSTM  |Tur|         |   | | | | | |
| CNN-LSTM  |Tur|         |   | | | | | |
| CNN-LSTM  |Tur|         |   | | | | | |
| CNN-LSTM  |Tur |        |   | | | | | |
| CNN-LSTM  |Tur|       |   | | | | | |
| CNN-LSTM  |Tur|      |   | | | | | |
| CNN-LSTM  |Tur |     |   | | | | | |
| BiLSTM-Att  |Tur |      |   | | | | | |
| BiLSTM-Att  |Tur  |     |   | | | | | ||
| BiLSTM-Att  |Tur  |    |   | | | | | |
| BiLSTM-Att  | Tur |   |   | | | | | |
| BiLSTM-Att  |Tur  |   |   | | | | | |
| BiLSTM-Att  |Tur  |   |   | | | | | |
| BiLSTM-Att  |Tur  |   |   | | | | | |
| BiLSTM-Att  |Tur  |   |   | | | | | |
|GreekBERT  | Greek  |  |   | | | | | |
| BERTurk  | Tur |  |   | | | | | |
| BERTurk  | Tur |  |   | | | | | |
| Ensemble  |Tur |   |   | | | | | |
| Ensemble  |Tur |   |   | | | | | |

All models are written in Google Collaboratory environment to take advantage of free GPU.



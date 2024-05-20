# Division of labour

## Tracking progress

When you start working on the first free part, write down your name next to the part, en mark it with "in progress" until you're finished.

| when | what | who | status |
| - | - | - | - |
| 18 May @ 13:00 | create repo | Juliet | DONE |
| 19 May @ 13:00 | Part 1: data preprocessing | Juliet | DONE |
| 19 May @ 15:30 | Part 2: data modelling | Hina  | DONE |
| 20 May @ ??:?? | Part 3: model deployment | Megan | DONE |
| 20 May @ 18:00 | "reveal" and review | Hina, Megan, Juliet | |

## Log

When you are finished with your part, you can write down the info that the person working on the next part needs here. Specifically the info about the input file for the next part is important: those are the "tick marks" so to speak. The next person should not *read* any files they are not working on, but things such as dimensions of the dataset can be inferred of course. So what you write down as "tick marks" hand makes sure that the next person can continue, and you can give your own take on that.

### Part 1: data preprocessing

- File(s) created: `raw_data.txt`, `preprocessed_data.csv`, `data_preprocessing.ipynb`
- Input file for Part 2: `preprocessed_data.csv`
- Info about input file for Part 2: `preprocessed_data.csv` contains an index column, 12 categorical features `x1` - `x12`, and a categorical label `y`

Other remarks: -

### Part 2: data modelling

- File(s) created: `model.pickle`, `data_modelling.ipynb`
- Input file for Part 3: `model.pickle`
- Info about input file for Part 3: `model.pickle` contains a trained and fitted model (sklearn.tree.DecisionTreeClassifier, accuracy of 76,2%). This model can be called using the `predict` method. 

Other remarks: Python version 3.7.4, sklearn version 0.21.3

### Part 3: model deployment

- File(s) created: model_deployment.ipynb

Other remarks: scikit-learn 0.23.2, python 3.8.5, numpy 1.19.5

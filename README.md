# DREAMCAP

서윤 정하 유진
![image](https://user-images.githubusercontent.com/67910856/199668641-aa901287-ee98-4b8b-8802-c5a4a14f5d92.png)

### TRAIN

```shell
sh train.sh
```
- `train_config.json` must be modified as you want to train.
    - `config`: Directory of Configuration Python File
    - `work_dir`: Directory to save Log & Checkpoint File
    - `resume_from`: Whether to do Resume
    - `validate`: Whether to validate during train
    - and so on,,,


### TEST

#### Closed Set Evaluation

```shell
sh test_closed_set.sh
```

#### Get Uncertainty Threshold & OpenSet Evaluation&Comparison

```shell
sh test_open_set.sh
```

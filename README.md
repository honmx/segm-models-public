# PyTorch Segmentation models Trainer
 Код для обучения моделей сегментации. Модели сетей взяты из этой библиотеки: https://github.com/qubvel/segmentation_models.pytorch

## Пример запуска обучения <a name="run-example"></a>

**ВНИМАНИЕ: пути к каталогам должны быть без кириллицы. ( Пути к наборам данных, к каталогам куда будут сохраняться результаты.)**

### Запуск алгоритма: <br/>
Запустить обучение сети можно одной строкой: <br/>
*bash train.sh* <br/>

В файле train.sh необходимо корректно указать путь до набора данных <br/>
и метку которым покрашена разметка целевого класса в строке CLASS_LIST="210" <br/>

Для изменения параметров запуска можно поменять их в файле train_my.sh <br/>
Или же запустить через терминал файл train.py и передать новые параметры <br/>

```
python3 train.py [-h] [-m MODEL] [--encoder ENCODER] [--image-size IMAGE_SIZE]
                [--exp-name EXP_NAME] [--class-list CLASS_LIST]
                [--max-mask-val MAX_MASK_VAL] [-b BATCH] [-lr LR] [-e EPOCHS]
                [-a AUGMENTATION] [-w WORKERS] -d DATASET
                [--add-dirs ADD_DIRS] [-log LOG_DIR] [-val VAL_DIR]
                [--add-val-dirs ADD_VAL_DIRS] [--adv-freq ADV_FREQ]
                [--use-only-add-val] [--cpu] [--device DEVICE] [--seed SEED]
```

### [Ссылка на оригинальный репозиторий](https://github.com/Segment-Something/segm-models-public)

## Проделанная работа
Над проектом работали:
- Вишняков Глеб Игоревич
- Клименко Максим Вячеславович
- Баженов Роман Алексеевич

[Ссылка на таблицу с результатами экспериментов](https://docs.google.com/spreadsheets/d/111ssqZVccITWekw1X-LL3mQxX3jzATtKx0pXtpGyROs/edit#gid=0)

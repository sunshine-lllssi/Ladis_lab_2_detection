# Dataset 
Был предоставлен датасет для детекции посетителей и сотрудников магазина. 
Yolo_dataset полностью подготовлен и готов к обучению модели.

## Внутренняя структура:
```text
├── data.yaml
├── sample_sub.csv
├── yolo_dataset
│   └── yolo_dataset
|       └── data.yaml
|       └── train
|           └── images
│               ├── 0209-10_00864300.jpg
│               ├── 0209-10_00864400.jpg
│               └── ...
|           └── labels
│               ├── 0209-10_00864300.txt
│               ├── 0209-10_00864400.txt
│               └── ...
└── test_images
     └── test_images
           ├── 1.1_00-00-00-000.jpg
           ├── 1.1_00-00-12-500.jpg
           └── ...
```

## data.yaml
names:
  0: customer (посетители магазина)
  1: staff (сотрудники в форме)

path: /kaggle/input/dl-lab-2-stuff-detection/yolo_dataset/yolo_dataset

train: train/images
val: train/

## После выполения дополнительного задания в датасете появидись новые данные
https://storage.yandexcloud.net/shelfsense/data-science/storeview/datasets/add_data.zip

## Наш датасет, который мы использовали в одном из представленных кодов (датасет с добавлением новых данных):
https://drive.google.com/drive/folders/1uDynEIAYhP0L3fmI7LJNJB8a4a19rbK2?usp=drive_link


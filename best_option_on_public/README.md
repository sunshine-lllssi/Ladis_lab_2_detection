# Лучший результат на public

## Результаты 

public: 0.64060

private: 0.66949

# Модель

yolo11m.pt

# Обучение

Мы провели два этапа обучения модели:
1) Основное обучение — модель обучалась с нуля на нашем наборе данных. Результаты этого этапа сохранялись в папку lab2. 

2) Дообучение  — мы взяли лучшую модель с первого этапа и продолжили её обучение с меньшей скоростью обучения (learning rate = 0.0005), меньшим количесвом эпох (epochs=45), меньшим размером(imgsz=720), добавили warmup_epochs=0, patience=10, copy_paste=0.25. 

# Веса моделей: лучшие по метрикам (best.pt) и финальные (last.pt)

https://drive.google.com/drive/folders/1gueVToCLh184KUc5qmrnMGKSaK5iwDsB

# Таблицы с метриками по эпохам

https://github.com/sunshine-lllssi/Ladis_lab_2_detection/blob/main/best_option_on_public/results%20(7).csv

https://github.com/sunshine-lllssi/Ladis_lab_2_detection/blob/main/best_option_on_public/results%20(6).csv

# Графики обучения 

Обучение - https://github.com/sunshine-lllssi/Ladis_lab_2_detection/blob/main/best_option_on_public/results%20(8).png

Дообучение - https://github.com/sunshine-lllssi/Ladis_lab_2_detection/blob/main/best_option_on_public/results%20(7).png

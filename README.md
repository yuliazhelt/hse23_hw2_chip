# hse23_hw2_chip


## Ссылка на Colab
[Colab](https://colab.research.google.com/drive/1r4mt78J1kJdABqnQ1ssXQvJkLfSyNeFc?usp=sharing)

## Анализ FastQC
Подрезания и фильтрации решила не делать, так как все отчёты выглядели нормально.

ENCFF394HYQ | ENCFF435IRD | ENCFF282SBH
--- | --- | ---
![Image](data/HYQ_1.jpg) | ![Image](data/IRD_1.jpg) | ![Image](data/SBH_1.jpg)
![Image](data/HYQ_2.jpg) | ![Image](data/IRD_2.jpg) | ![Image](data/SBH_2.jpg)
![Image](data/HYQ_3.jpg) | ![Image](data/IRD_3.jpg) | ![Image](data/SBH_3.jpg)
![Image](data/HYQ_4.jpg) | ![Image](data/IRD_4.jpg) | ![Image](data/SBH_4.jpg)
![Image](data/HYQ_5.jpg) | ![Image](data/IRD_5.jpg) | ![Image](data/SBH_5.jpg)




## Таблица со статистикой по каждому из 3 образцов:
![Image Title](data/table_report.jpg)

Процент выравнивания оказался таким низким, потому что мы проводили выравнивание ридов только на одной из 23 пар хромосом, которая составляет лишь небольшую часть генома человека, откуда ~3.5% выравнивай достаточно хороший результат.

## Диаграммы Венна

1 реплика с ENCODE | ENCODE с 1 репликой
--- | ---
![Image Title](data/HYQ_KIF_venn.jpg) | ![Image Title](data/KIF_HYQ_venn.jpg)

2 реплика с ENCODE | ENCODE с 2 репликой
--- | ---
![Image Title](data/IRD_KIF_venn.jpg) | ![Image Title](data/KIF_IRD_venn.jpg)

Количество пересечений довольно невелико. Это опять же обусловлено тем, что мы производили выравнивание только по одной хромосоме.

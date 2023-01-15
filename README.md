# cross_pt_7
Разработка кроссплатформенных приложений Практическое задание 6.2 Искаков Мансур Вариант 4

Задание:
![изображение](https://user-images.githubusercontent.com/51114487/212562396-ee734ee8-5a09-4cc2-aaf6-8c0ef865f03e.png)
Вариант 4:
![изображение](https://user-images.githubusercontent.com/51114487/212562409-79e165ee-3bd3-4858-bd7e-7b23bf1aa28c.png)


Использую компонент QTableWiget для выбора любимой каши согласно задаче. Создал функцию table_clicked для отслеживания нажатия по ячейке:
В ходе выполнения задачи, выяснилось что обязательным условием для срабатывания cellClicked было добавление элементов, а не только столбцы описания ячеек, иначе события нажатия по ячейке не срабатывала:
![изображение](https://user-images.githubusercontent.com/51114487/212562919-b1d43c6d-c141-4a8b-acc0-edc8bd147297.png)

То есть cellClicked срабатывает только при клике по ячейке:
<img width="706" alt="1" src="https://user-images.githubusercontent.com/51114487/212562315-0480f774-adf1-40bd-9f94-d4794d46d041.png">

Использование компонетнта QListWiget по похожему принципу:
<img width="665" alt="2" src="https://user-images.githubusercontent.com/51114487/212562316-6ac2f568-8871-43ef-9b4d-7d24d0ceb34a.png">

Использование компонетнта QComboBox:
<img width="675" alt="3" src="https://user-images.githubusercontent.com/51114487/212562312-bbf74f4c-90fc-4eb9-be1d-e6902e3143e9.png">

Итог в QTableWiget, ячейки заполняются из массива:
<img width="736" alt="4" src="https://user-images.githubusercontent.com/51114487/212562314-e4529d6f-5069-4962-9cfe-f291787479ed.png">

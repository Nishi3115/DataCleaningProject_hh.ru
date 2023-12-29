# Проект №1 Анализ резюме из HeadHunter
## Оглавление

[1. Описание проекта](https://github.com/Nishi3115/DataCleaningProject_hh.ru?tab=readme-ov-file/README.md#Описание-проекта)  
[2. Краткая информация о данных](https://github.com/Nishi3115/DataCleaningProject_hh.ru?tab=readme-ov-file/README.md#Краткая-информация-о-данных)  
[3. Этапы работы](https://github.com/Nishi3115/DataCleaningProject_hh.ru?tab=readme-ov-file/README.md#Этапы-работы)  
[4. Результаты](https://github.com/Nishi3115/DataCleaningProject_hh.ru?tab=readme-ov-file/README.md#Результаты)  

### Описание проекта
Компания HeadHunter хочет построить модель, которая бы автоматически определяла примерный уровень заработной платы, подходящей пользователю, исходя из информации, которую он указал о себе. Но, как вы знаете, прежде чем построить модель, данные необходимо преобразовать, исследовать и очистить.

### Краткая информация о данных
В таблице представлена информация о 44744 соискателей и 12 признаков для каждого из них. Основные признаки: возраст, прошлое место работы, опыт работы, готовность к командировкам, город проживания, образование. 

### Этапы работы

* Исследование структуры данных  
    + Посмотреть в каких данных есть пропуски  
    + Посмотреть на количество уникальных элементов в различных столбцах  
* Преобразование данных  
    + Отсекаем лишнюю информацию в столбцах с образованием и информации о возрасте  
    + Преобразуем опыт работы в месяцы  
    + Разбиваем признаки Занятость и График на несколько признаков-мигалок.
    + Преобразуем желаемую ЗП в рубли  
* Исследование зависимостей и их анализ
* Очистка данных от дубликатов и пустых значений  

### Результаты
В результате мы имеем подготовленную базу данных на которой можно удобно обучать модель для предсказания желаемой ЗП. Имеется достаточное количество графиков, по которым можно понять какие признаки влияют на размер желаемой ЗП.

[Ссылка на датасет](https://drive.google.com/file/d/1Kb78mAWYKcYlellTGhIjPI-bCcKbGuTn/view?usp=sharing)
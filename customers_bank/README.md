<div style="border:solid Blue 2px; padding: 40px">

<h2><b>Описание проекта</b></h2>

### Цель 
Построить модель прогнозирования ухода клиентов банка.
### Задачи
Загрузить и подготовить данные. 
Иследовать баланс классов, обучить модель без учёта дисбаланса.
Улучшить качество модели, учитывая дисбаланс классов. 
Обучить разные модели и найдите лучшую. Провести финальное тестирование.
### Инструменты
- Pandas
- Sklearn
### Результат
- Исследованы модели с балансом и дисбалансом классов
    - ***LogisticRegression***,
    - ***DecisionTreeClassifier***, 
  - ***RandomForestClassifier***
- Применены несколько способов борьбы с дисбалансом классов
  - ***upsampling***
  - ***downsampling***
  - ***balanced***
- F1 метрика итоговой модели 0.63

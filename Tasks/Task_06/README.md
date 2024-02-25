# **ЗАДАНИЕ 06. ПРЕДСКАЗАНИЕ СТОИМОСТИ ПОДЕРЖАННОГО АВТОМОБИЛЯ**

<center> <img src = https://mtdata.ru/u30/photoB82A/20119654497-0/original.jpg alt="drawing" style="width: 800px; height:400px;">

## **Содержание**

1. [Описание задания](https://github.com/Licharg/SkillFactory/blob/master/Tasks/Task_06/README.md#Описание-задания)  
2. [Решаемая задача](https://github.com/Licharg/SkillFactory/blob/master/Tasks/Task_06/README.md#Решаемая-задача)

    2.1 [Условия](https://github.com/Licharg/SkillFactory/blob/master/Tasks/Task_06/README.md#Условия)

    2.2 [Метрики](https://github.com/Licharg/SkillFactory/blob/master/Tasks/Task_06/README.md#Метрики)

    2.3 [Навыки](https://github.com/Licharg/SkillFactory/blob/master/Tasks/Task_06/README.md#Навыки)

3. [Информация о данных](https://github.com/Licharg/SkillFactory/blob/master/Tasks/Task_06/README.md#Информация-о-данных)  
4. [Этапы работы над заданием](https://github.com/Licharg/SkillFactory/blob/master/Tasks/Task_06/README.md#Этапы-работы-над-заданием)  
5. [Результаты](https://github.com/Licharg/SkillFactory/blob/master/Tasks/Task_06/README.md#Результаты)
6. [Выводы](https://github.com/Licharg/SkillFactory/blob/master/Tasks/Task_06/README.md#Выводы)

### **Описание задания**

Компании, которая продает подержанные автомобили, необходимо построить модель для предсказания адекватной стоимости машины по ее характеристикам из объявления.

:arrow_up: [к содержанию](https://github.com/Licharg/SkillFactory/blob/master/Tasks/Task_06/README.md#Содержание)

### **Решаемая задача**

- Обучить две модели МО и затем выполнить подбор гиперпараметров с целью улучшения целевой метрики $F_1$-score с помощью четырех предложенных методов. Сравнить результаты и оформить решение в виде ноутбука `.ipynb`.
- Загрузить решение на соревнование в [Kaggle](https://www.kaggle.com/competitions/sf-dst-predict-car-price) Predict car price (Предсказание стоимости подержанного автомобиля).

#### **Условия**

- Данное соревнование является бессрочным и доступно для всех потоков.
- Срок выполнения соревнования устанавливается индивидуально в каждом потоке.
- Тестовая выборка представлена в Лидерборде целиком. Поэтому лучшие и победные решения буду проверяться на их "адекватность" (чтоб не было подгонки под тестовую выборку).
- Разрешено использовать любые `ML` алгоритмы и библиотеки (кроме `DL`).
- Делаем реальный `ML` продукт, который потом сможет нормально работать на новых данных.

#### **Метрики**

- Метрикой в данном соревновании является `MAE` - среднее абсолютное отклонение (`mean absolute error`). Подробности по [ссылке](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_absolute_error.html).
- Ваш сабмит в соревнование должен выглядеть как `sample_submission.csv` файл - содержать 10697 строк с предсказаниями для каждого `row_ID` от 35000 до 45696 включительно.

#### **Навыки**

- практиковать навыки работы с моделями МО;
- освоить на практике работу с базовыми и продвинутыми методами оптимизации гиперпараметров;
- практиковать работу в среде `Google Colab`;
- повторить навыки работы с `Git`, `GitHub` посредством добавления отчета о проделанной работе в портфолио.

:arrow_up: [к содержанию](https://github.com/Licharg/SkillFactory/blob/master/Tasks/Task_06/README.md#Содержание)

### **Информация о данных**

- Данные представлены в соревновании [Kaggle](https://www.kaggle.com/competitions/sf-dst-predict-car-price/data), кроме того они выложены в папке `data`
- К данному соревнованию подготовлен `baseline`, который может помочь сформировать собственное победное решение.
  
:arrow_up: [к содержанию](https://github.com/Licharg/SkillFactory/blob/master/Tasks/Task_06/README.md#Содержание)

### **Этапы работы над заданием**

- Обучить обе модели и предсказать результат, используя гиперпараметры по умолчанию (`baseline`-решение).  
- Оптимизировать гиперпараметры обеих моделей с помощью базовых методов `GridSearchCV` и `RandomizedSearchCV`.  
- Оптимизировать гиперпараметры обеих моделей с помощью продвинутых библиотек `Hyperopt` и `Optuna`.  
- Сравнить полученные результаты, сделать выводы.

:arrow_up: [к содержанию](https://github.com/Licharg/SkillFactory/blob/master/Tasks/Task_06/README.md#Содержание)

### **Результаты**

- Обучены обе модели машинного обучения: `LogisticRegression` и `RandomForestClassifier`.  
- Оптимизированы гиперпараметры моделей с помощью четырех методов, использована кросс-валидация.  
- Написаны подробные выводы по каждому методу, сделан общий вывод на основе результатов.  
- [Отчет](https://github.com/Licharg/SkillFactory/blob/master/Tasks/Task_06/Task_06_Predict_Car_Price.ipynb) в формате `Jupiter Notebook` загружен на `GitHub`.
- Получен фидбэк по выполненному проекту, который можно посмотреть по [ссылке](https://disk.yandex.ru/i/0x3rO6LYunn4aQ)

:arrow_up: [к содержанию](https://github.com/Licharg/SkillFactory/blob/master/Tasks/Task_06/README.md#Содержание)

### **Выводы**

В процессе работы над заданием успешно реализованы обозначенные практики:

- улучшены навыки работы с моделями МО;
- проведено знакомство на практике с базовыми и продвинутыми методами оптимизации гиперпараметров;  
- получено понимание особенностей применения каждого из методов оптимизации для последующих задач;  
- углублены навыки работы в среде `Google Colab`;  
- написан эффективный воспроизводимый код на `Python`;  
- код составлен в соответствии с `PEP 8`.

:arrow_up: [к содержанию](https://github.com/Licharg/SkillFactory/blob/master/Tasks/Task_06/README.md#Содержание)

Если информация по заданию представляется Вам интересной и полезной, я буду Вам благодарен за отметку моего репозитория и профиля звездами ⭐️⭐️⭐️!  

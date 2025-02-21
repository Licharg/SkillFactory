# **ПРОЕКТ 1. АНАЛИЗ РЕЗЮМЕ ИЗ `HEADHUNTER`**

<center> <img src = https://ffb.ranepa.ru/images/hh-ru.jpg alt="drawing" style="width: 800px; height:400px;" </center>

## **Содержание**

1. [Описание проекта](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_1/README.md#Описание-проекта)  
2. [Решаемая задача](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_1/README.md#Решаемая-задача)

    2.1 [Условия](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_1/README.md#Условия)

    2.2 [Метрики](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_1/README.md#Метрики)

    2.3 [Навыки](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_1/README.md#Навыки)

3. [Информация о данных](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_1/README.md#Информация-о-данных)  
4. [Этапы работы над проектом](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_1/README.md#Этапы-работы-над-проектом)  
5. [Результаты](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_1/README.md#Результаты)
6. [Выводы](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_1/README.md#Выводы)

### **Описание проекта**

Анализ базы резюме `HeadHunter` с целью её подготовки для использования в модели машинного обучения, определяющей примерный уровень заработной платы, подходящей соискателю на основании информации, которую тот указал о себе.

:arrow_up:[к содержанию](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_1/README.md#Содержание)

### **Решаемая задача**

Часть соискателей не указывает желаемую заработную плату, когда составляет своё резюме. Поэтому имеющуюся в распоряжении базу резюме с сайта поиска вакансий `hh.ru` необходимо преобразовать, исследовать и очистить.

#### **Условия**

- В ходе каждого этапа работы над проектом необходимо выполнить блоки практических заданий в `jupyter-notebook` по предложенному шаблону и ответить на контрольные вопросы на платформе `SkillFactory`. Посредством ответов на эти вопросы проверяется верность решений в заданиях.
- Задания выполняются последовательно.
- С целью разведывательного анализа разрешено использовать любую из изученных библиотек визуализации: `Matplotlib`, `Seaborn` и `Plotly`. Однако рекомендуется выбрать `Plotly` ввиду ее интерактивности.
- В остальном разрешается использовать только изученные в курсе переменные, структуры данных, циклы, функции, библиотеки, методы, правила и стандарты (включая `PEP 8`).

#### **Метрики**

- За ответы на все контрольные вопросы на платформе можно максимально набрать 30 баллов.
- За выводы по разведывательному анализу в `jupyter-notebook` можно получить еще 10 баллов: 8 основных и 2 дополнительных (за проверку собственных гипотез).  
- Итого: 40 баллов.
- Для успешного выполнения проекта необходимо набрать 21 балл.

#### **Навыки**

- Закрепить последовательность этапов предобработки данных;
- Улучшить навыки использования изученных методов для преобразования данных;
- Углубить знания методов библиотек визуализации и различных типов графиков для исследования зависимостей в данных;
- Улучшить навык формулирования выводов на основе проанализированной информации;
- Развить способность выдвигать гипотезы о зависимостях в данных, подтверждать или опровергать их с помощью графиков;
- Улучшить навыки использования языка разметки `MarkDown`;
- Улучшить навыки работы с `IDE VS Code`, `Git`, `GitHub` (посредством добавления отчета о проекте в портфолио);
- Улучшить навыки составления эффективного воспроизводимого код на `python` в соответствии с `PEP 8`.

:arrow_up:[к содержанию](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_1/README.md#Содержание)

### **Информация о данных**

- Для работы предоставляется база резюме, выгруженная с сайта поиска вакансий `hh.ru`.
- Ввиду ее большого размера (455,5 Мб) она не может быть загружена на сайт `GitHub`, поэтому для воспроизведения кода данного проекта предлагается скачать базу по ссылке [база резюме](https://drive.google.com/file/d/1_l4Bbc1xrUnQyDTsLzRP0EOaz-myM3yK/view?usp=share_link) и сохранить ее в папку `data/` проекта.
- Дополнительно предоставляетя таблица котировок валют с целью конвертации желаемых зарплат соискателей из базы. Эта таблица находится в [папке проекта](https://github.com/Licharg/SkillFactory/tree/master/Projects/Project_1/data) и не требует дополнительных действий.
  
:arrow_up:[к содержанию](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_1/README.md#Содержание)

### **Этапы работы над проектом**

- Базовый анализ структуры данных.
- Преобразование данных.
- Разведывательный анализ.
- Очистка данных.
- Оформление проекта и загрузка на `GitHub`.

:arrow_up:[к содержанию](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_1/README.md#Содержание)

### **Результаты**

По итогам работы над проектом:

- Предоставлены ответы на все контрольные вопросы на платформе `SkillFactory`, за что начислено 30 баллов;
- Сформулированы развёрнутые выводы по 8-ми обязательным пунктам разведывательного анализа, а также по 2-м дополнительным;
- Подготовлен [отчет](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_1/Project-1_Resumes_Analysis.ipynb) об анализе базы данных резюме в формате `jupiter-notebook` с рекомендациями, на какие признаки стоит обратить внимание при создании модели машинного обучения.
- Проведена очистка данных, позволяющая подать обработанную базу резюме на вход модели обучения.

:arrow_up:[к содержанию](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_1/README.md#Содержание)

### **Выводы**

- В процессе работы над проектом укрепилось понимание важности анализа и предобработки данных перед их последующим использованием в моделях машинного обучения, бизнесе;
- Обнаружились возможные "подводные камни" неполноты данных, а вместе с ними отработаны приемы обработки и очистки данных;
- Расширились знания способов визуализации взаимосвязей признаков в данных;
- Успешно реализованы все обозначенные практики;
- Получен фидбэк по выполненному проекту, который можно посмотреть по [ссылке](https://disk.yandex.ru/i/kruIxH11lDCuKw)

:arrow_up:[к содержанию](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_1/README.md#Содержание)

Если информация по этому проекту покажется вам интересной или полезной, то я буду очень вам благодарен, если отметите репозиторий и профиль ⭐️⭐️⭐️-дами

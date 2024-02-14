# **ПРОЕКТ 0. ПРОГРАММА УГАДАЙ ЧИСЛО**

<center> <img src = https://i.ytimg.com/vi/Dk9a6K0X2uQ/maxresdefault.jpg?7857057827 alt="drawing" style="width: 800px; height:400px;" </center>

## **Содержание**

1. [Описание проекта](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_0/README.md#Описание-проекта)  
2. [Решаемая задача](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_0/README.md#Решаемая-задача)

    2.1 [Условия](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_0/README.md#Условия)

    2.2 [Метрики](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_0/README.md#Метрики)

    2.3 [Навыки](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_0/README.md#Навыки)

3. [Информация о данных](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_0/README.md#Информация-о-данных)  
4. [Этапы работы над проектом](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_0/README.md#Этапы-работы-над-проектом)  
5. [Результаты](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_0/README.md#Результаты)
6. [Выводы](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_0/README.md#Выводы)

### **Описание проекта**

Угадать загаданное компьютером число за минимальное число попыток.

:arrow_up: [к содержанию](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_0/README.md#Содержание)

### **Решаемая задача**

Нужно написать программу, которая угадывает число за минимальное число попыток.

#### **Условия**  

- Компьютер загадывает целое число от 0 до 100, и нам его нужно угадать. Под «угадать», подразумевается «написать программу, которая угадывает число».
- Алгоритм учитывает информацию о том, больше ли случайное число или меньше нужного нам.

#### **Метрики**

- Результаты оцениваются по среднему количеству попыток при 1000 повторений. Необходимо добиться минимального количества попыток.

- КРИТЕРИИ ОЦЕНИВАНИЯ:
  - 1 балл — Программа находит число меньше чем за 20 попыток. Если данное условие не выполняется, выставляется 0 баллов за это и все остальные условия.
  - 1 балл — Код решения загружен на `GitHub`.
  - 1 балл — `GitHub` оформлен соответствующим образом.
  - 1 балл — Код соответствует стандарту `PEP8`.
  - 1 балл — Код воспроизводим: зафиксированы версии библиотек в виде файла `requirements.txt` или иного формата файлов конфигураций.
- Максимально возможное количество баллов за задание — 5.

#### **Навыки**

- Учимся писать хороший код на `Python`.
- Учимся работать с `IDE`.
- Учимся работать с `GitHub`.

:arrow_up: [к содержанию](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_0/README.md#Содержание)

### **Информация о данных**

- На вход функции отгадывания `random_predict` последовательно подаются "загаданные" числа из листа чисел в 1000 элементов, сгенерированных произвольным образом в интервале от 1 до 100. С целью воспроизводитости фиксируется значение `seed`.
- Представлен шаблон [baseline](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_0/baseline.py) из скринкаста.
  
:arrow_up: [к содержанию](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_0/README.md#Содержание)

### **Этапы работы над проектом**

- Изучение задания проекта.
- Анализ проекта прототипа.
- Внесение изменений в прототип проекта.
- Проверка работоспособности программы.
- Подготовка файла `README`.
- Копирование проекта в удалённый репозитарий.
- Устранение ошибок программного обепечения во время работы над проектом.
- Выкладывание проекта на проверку в `GitHub`.

:arrow_up: [к содержанию](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_0/README.md#Содержание)

### **Результаты**

- При отгадывании 1000 случайных чисел алгоритм показывает среднее количество попыток, равное 6, что полностью удовлетворяет условиям задачи.
- Итоговая оценка 5 из 5 баллов:
    1. Программа находит число меньше чем за 20 попыток — Выполнено (1 балл);
    2. Код решения загружен на GitHub — Выполнено (1 балл);
    3. GitHub оформлен соответствующим образом — Выполнено (1 балл);
    4. Код соответствует PEP8 — Выполнено (1 балл);
    5. Код воспроизводим — Выполнено (1 балл).
- Подготовлен [отчет](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_0/Project-0_Guess_The_Number_Program.py) об анализе базы данных резюме в формате `jupiter-notebook` с рекомендациями, на какие признаки стоит обратить внимание при создании модели машинного обучения.

:arrow_up: [к содержанию](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_0/README.md#Содержание)

### **Выводы**

В процессе работы над проектом успешно реализованы обозначенные практики:

- написан эффективный воспроизводимый код на `Python`;
- код составлен в соответствии с `PEP 8`;
- улучшены навыки работы в `IDE VS Code`;
- улучшены навыки использования `GitHub` и оформления сопроводительной документации.
- Получен фидбэк по выполненному проекту, который можно посмотреть по [ссылке](https://disk.yandex.ru/i/sxlN7_l1g--k6A)

:arrow_up: [к содержанию](https://github.com/Licharg/SkillFactory/blob/master/Projects/Project_0/README.md#Содержание)

Если информация по этому проекту покажется вам интересной или полезной, то я буду очень вам благодарен, если отметите репозиторий и профиль ⭐️⭐️⭐️-дами.

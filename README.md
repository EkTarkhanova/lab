**Проект "Система учета и анализа финансовых данных"**

**Описание проекта**
Проект "Система учета и анализа финансовых данных" представляет собой программное решение, разработанное на языке Python, для автоматизации процесса учета и анализа финансовых данных в небольших и средних компаниях. Программа предоставляет функциональность для ввода, хранения, обработки и анализа данных о финансовых операциях, а также генерации отчетов и статистических данных.

**Требования**
Для работы с программой необходимо наличие установленного интерпретатора Python версии 3 или выше на компьютере. Также потребуется установка следующих дополнительных библиотек:
- pandas: используется для работы с таблицами и обработки данных.
- matplotlib: используется для графического представления аналитических данных.

Для установки библиотек можно использовать менеджер пакетов pip, выполнив следующие команды в командной строке:

pip install pandas
pip install matplotlib


**Установка**
1. Склонировать репозиторий с помощью команды:
   

   git clone https://github.com/username/project.git
   

2. Перейти в директорию проекта:
   

   cd project
   

   
**Использование**
1. Запустить программу с помощью команды:
   

   python main.py
   

   Программа будет запущена в текстовом режиме и предложит ввести данные о финансовых операциях.
   
2. Ввести данные о финансовых операциях в формате CSV. Структура файла должна быть следующей:
   

   Дата,Описание,Сумма,Тип
   2022-01-01,Оплата поставщику,1000,Расход
   2022-01-02,Зарплата сотрудникам,2000,Расход
   2022-01-03,Поступление от клиента,5000,Доход
   

   Поле "Дата" должно быть в формате "гггг-мм-дд", поле "Тип" - "Расход" или "Доход".

3. Выбрать одну из доступных функций программы, введя соответствующую цифру из меню:
   - 1: Просмотреть список всех операций
   - 2: Показать статистику по расходам и доходам за заданный период
   - 3: Сгенерировать отчет по операциям за заданный период

**Руководство пользователя**
Программа представляет собой текстовый интерфейс, который помогает вести учет финансовых операций и получать аналитическую информацию о расходах и доходах компании.

При запуске программы открывается главное меню со следующими опциями:

1. Просмотреть список всех операций: позволяет вывести на экран все ранее введенные финансовые операции в виде таблицы.

2. Показать статистику по расходам и доходам за заданный период: предлагает пользователю ввести дату начала и дату окончания периода, за который требуется вывести статистику. Программа выводит на экран суммарные расходы и доходы за данный период, а также график с распределением расходов и доходов по категориям.

3. Сгенерировать отчет по операциям за заданный период: пользователь указывает дату начала и дату окончания периода, за который требуется сгенерировать отчет. Программа создает HTML-файл с таблицей всех операций за этот период и сохраняет его на диск.

**Пример использования**
1. Запускаем программу с помощью команды:
   

   python main.py
   


2. Вводим данные о финансовых операциях:
   

   Введите путь к файлу с данными: data.csv
   


3. Вводим команду "2" для просмотра статистики по расходам и доходам:
   

   Меню:
   1. Просмотреть список всех операций
   2. Показать статистику по расходам и доходам за заданный период
   3. Сгенерировать отчет по операциям за заданный период
   Введите номер выбранной опции: 2
   


4. Вводим даты начала и окончания периода:
   

   Введите дату начала периода (гггг-мм-дд): 2022-01-01
   Введите дату окончания периода (гггг-мм-дд): 2022-01-31
   


5. Программа выводит статистику и график:
   

   Суммарные расходы за период: 3000
   Суммарные доходы за период: 5000
   


**Вклад в проект**
Если вы хотите внести в проект изменения или улучшения, будет здорово, если вы присоединитесь к разработке и отправите нам запрос на слияние (Pull Request). Вы также можете создать задачу (Issue), сообщить об ошибке или предложить новую функциональность. Мы очень рады вашим идеям и вкладу в развитие проекта.

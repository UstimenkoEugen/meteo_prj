# **Тема. Метеостанція**

### Загальний опис проектованої системи.

Система повинна забезпечувати відображення в реальному часі, архівування та звітування...

### Вимоги до функцій і задач

Система повинна передбачати виконання натупних функцій:

1.	Вимірюваня температури, вологості, тиску,наявність дощу з періодичністю не більше 5 секунд.
2.	Відображення плинних значень показників на локальномуWEB-інтерфейсі та віддалено за допомогою Телеграм-бота та мобільного застосунку.
3.	Архівування значень показників в локальну базу даних середнє за останні 5 хвилин
4.	Відображення значень показників у вигляді трендів за останні 60 хвилин на: локальному ВЕБ-ітерфейсі, мобільному за стосунку, GoogleWorksheet

### Вимоги до видів забезпечення.

**Вимоги до апаратного забезпечення**

Необхідно використання наступних засобів:

*	RaspberryPI3, або аналогічний, що має вбудований бездротовий зв’язок, або модуль WI-FI.
*	Датчик тиску, температури та вологості.
*	Цифровий тепловий зонд.
*	Датчик дощу
*	Два резистори потужністю 4,7 КОм.
*	Деякі гвинтові клемні колодки з кріпленням на друковану плату на 5мм
*	Макет, кілька проводів перемичок
*	Інтегральна схема аналого-цифрового перетворювача
*	Водонепроникнікорпуси
*	Смартфон з Android >V5
*	Джерело живлення 12чи 220v

Програмні засоби та Інтернет-сервіси

Необхідне використання наступних програмних засобів:

*	Node-RED як база для розробки ПЗ + dashboard для локального веб-інтерфейсу
*	Система керування базами даних розгорнута наRPI(MariaDB)
*	Gitта GitHub: як основа для проектування, розробки ПЗ та документації
*	Веб-сайт для онлайн доступу для звітів на базіGoogleSites
*	Telegram-ботдля ведення статистики та для відображення інформації
*	IoTPanelабо MqTTool

# **Розділ 2. Розробкаархітектури та необхідної проектної документації.**

### **Технічна структура системи.**

Технічна структура системи показана на рисунку.



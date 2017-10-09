
<h2>Техническое задание</h2><br/>

Требуется спроектировать REST сервис для приложения “Календарь отпусков“. Сервис должен позволять:<br/>

• Получать список сотрудников (ФИО, должность) с возможностью сортировки и фильтрации<br/>
• Создавать новых сотрудников<br/>
• Получать таблицу отпусков с сортировкой и фильтрацией по временному интервалу<br/>
• Создавать новые отпуска<br/>
• Редактировать отпуска<br/>
• Удалять отпуска<br/>
 
Приложение должно отвечать следующим бизнес требованиям:<br/>

• Максимальное количество дней отпуска в году - 24 календарных дня<br/>
• Минимальный непрерывный период отпуска - 2 календарных дня<br/>
• Максимальный непрерывный период отпуска - 15 календарных дней<br/>
• Минимальный период между периодами отпуска равен размеру первого отпуска (если сотрудник был в отпуске 10 дней, в последующие 10 дней он не может брать отпуск)<br/>
• В отпуске имеют право находиться не более 50% сотрудников одной должности (если в компании 5 бухгалтеров, одновременно в отпуске может быть не более 2)<br/>
• Отредактировать или удалить можно только предстоящий отпуск<br/>
 
Техническая часть:<br/>

• Реализация на языке С#/.Net или Scala, использование фреймворков и библиотек по желанию<br/>
• Для хранения информации использовать базу данных на основе файла распространяемого с приложением: SQL Express, SQL Compact или любого другого аналога<br/>
• Обязательно наличие юнит-тестов<br/>
• Наличие Swagger документации приветствуется, но не обязательно<br/>
• Наличие авторизации приветствуется<br/>
• Исходные файлы должны быть размещены в github<br/>

# sentimentdictionary-uk
## З чим тут можна познайомитися?
Тут подано **тональний словник української мови** (далі: Словник).
</br>

## Трохи з історії створення Словника
Цей Словник було створено протягом 2020-2023 років. Словник був створений на основі: </br>
• 2 списків слів, які були попередньо частково розмічені студентами Донецького національного університету імені Василя Стуса, філологічного факультету, кафедри загального та прикладного мовознавства й слов’янської філології (обсяг першого списку становив 40 567 слововживань, а другого – 7 000 лексем); </br>
• 3 списків слів, які були відібрані й упорядковані в ході роботи; </br>
• власними доповненнями слів та словосполучень, які були помічені в ході прослуховування та прочитання новин. 
</br>

Важливо❗️❗️❗️ </br>
▶️ Це лише перша версія словника. Найближчим часом будуть представлені релізи з доповненнями.
</br>
▶️ Омонімія у першій версії словника ще не знята.
</br>

## Можливості Словника
В останнє десятиліття **автоматичний аналіз настроїв, або тональний аналіз, сентимент-аналіз** (клас методів аналізу в комп'ютерній лінгвістиці, призначений для виявлення в текстах емоційно забарвленої лексики) широко застосовується в різних сферах життя. Наприклад, це може бути аналіз настроїв у новинних текстах чи аналіз відгуків на Інтернет-сайтах із метою фільтрації відгуків на позитивні та негативні. Великий обсяг інформації, який зростає та змінюється щодня, специфіка мови новин роблять таку задачу доволі складною.
</br>
Одним із найголовніших етапів процесу розробки системи сентимент-аналізу є ***створення тонального словника окремої мови***.
Нині для української мови є лише один тональний словник української мови в вільному доступі (проект групи [lang-uk](https://github.com/lang-uk/tone-dict-uk/blob/master/tone-dict-uk-manual.tsv)), обсяг якого становить 6 859 слів. Востаннє цей тональний словник  редагувався експертами в вересні 2016 року. 
</br>
Оскільки активний словниковий склад мови постійно змінюється, ***виникає потреба в створенні нового тонального словника для української мови***, який буде містити найбільш вживані та найбільш частотні слова, що й зумовлює створення Словника, який подано у двох файлах ("tonSUM.1.0") у різних форматах.
</br>

Пояснення щодо 2 форматів: </br>
🔹️ .tsv = колонки таблиці розділені табуляцією; </br>
🔹️ .csv = колонки таблиці розділені комами. </br>
<p> Надалі планується викласти створений словник та детальні інструкції й описи його створення в Інтернет з можливістю вільного доступу.
Словник може бути використаний для сентимент-аналізу (аналізу тонального настрою тексту). </p>
</br>

Отже, початково ❗️ Словник створено для визначення емоційної настроєності текстів новин. ❗️

## Трохи про вигляд словника
Нижче представлено фрагмент вигляду Словника.
</br>

Word//word combination | Sentiment scores |   |   |   |   |   |   |   | Average sentiment score
--- | --- | --- | --- | --- | --- | --- | --- | --- | ---
артистка | 1 | 1 | 1 | 1 |  |  |  | 2 | 1,20
багатий | 0 | 1 | 2 | 1 | 1 | 2 | 2 | 2 | 1,38
</br>

Пояснення щодо вигляду Словника: </br>
✅️ у 1-ій колонці представлено *слово* або *словосполучення* (Word//word combination); </br>
✅️ у колонках від 2-ої до 9-ої представлено *оцінку тональності* (Sentiment scores) для слова або словосполучення, яке / які подано у 1-ій колонці; </br>
✅️ у 10-ій колонці представлено *середню оцінку тональності* (Average sentiment score), яке розраховано автоматично (за допомогою вбудованих функцій у Google Таблицях) шляхом поділу суми вказаних оцінок на їхню кількість.
</br>

Оцінки були виставлені або студентами Донецького національного університету імені Василя Стуса (які укладали списки для створення майбутнього словника), або експертами. Це було здійснено для того, щоб всі слова та словосполучення мали хоча б 5 оцінок включно з моєю, яка представлена у 9-ій колонці. Відповідно, максимальна кількість оцінок – це 8.
</br>
 
 В ході визначення тональності слова та словосполучення було запропоновано використовувати таку шкалу:
 Оцінка  | Значення оцінки
 --- | ---
 2 | дуже позитивно
 1 | позитивно
 0 | нейтрально
 -1 | негативно
 -2 | дуже негативно
</br> 

👉 В такий спосіб було надано тональність для **14 856** слів та словосполучень, які і представлено у першій версії Словника.

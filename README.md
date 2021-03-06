Інформація
====
У сховищі знаходиться реалізація стилю оформлення бібліографії у документі Microsoft Word 2010/2013 відповідно до вимог стандарту ДСТУ 7.1:2006.

Оригінальна робота (звідки форк)
====
Оригінальне джерело https://github.com/irandom/docs Андрєя Рогожнікова.

# Стиль бібліографії відповідно до вимог ДСТУ 7.1:2006

Даний стиль відповідає (частково) стандарту ДСТУ 7.1:2006. Може використовуватись у Microsoft Office Word для автоматизації оформлення бібліографічних посилань (переліку літератури).

Ознайомитись з стандартом: [Книжкова палата України](http://www.ukrbook.net/biblzak.html).

## Підтримка

Поточний файл з стилем бібліографії, в подальшому просто файл, підтримує Office 2013 (перевірено в ньому). Можливо він працюватиме з іншими версіями пакету MS Word, не перевіряв.

Використовувати стиль у Office 2007 не вийде (див. опис в оригінальній роботі).

## Як застосувати стиль

Файл з описом стилю у форматі *.xsl слід скопіювати у теку, яка містить файли з бібліографічними стилями, я саме

* Для Office 2010:  [System Volume]:\Program Files\Microsoft Office\Office 14\Bibliography\Style
* Для Office 2013:  [System Volume]:\Users\\[User Name]\AppData\Roaming\Microsoft\Bibliography\Style

В меню MS Word Посилання|Стиль обрати стиль «ДСТУ 7.1-2006» і працювати з джерелами. При створенні джерала слід обов'язково вказувати мову, інакше буде встановлена англійська мова.

На жаль аби скористатися сортуванням за іменами авторів, потрібно обробити документ (*.docx) програмою — BibWord Extender. Детально на [сторінці](http://det-random.livejournal.com/28819.html) або див. сайт [автори BibWord англійською](http://bibword.codeplex.com/wikipage?title=BibWord%20Extender&referringTitle=FAQ).

## Відомі проблеми

Трапляється, що в переліку літератури номери колонок не відображаються (не зустрічав, не забувайте встановлювати оновлення на MS Office) - або крапки або порожні місця. Це коли стиль абзацу (не плутати з стилем бібліографії) має не нульовий відступ, і кількість просто "з"їжджає" праворуч, звичайно його там не побачити. Для виправлення достатньо змінити стиль або виділити першу колонку (перелік літератури це є таблиця) та встановити для нього нульовий відступ.

## Подальший розвиток

Додавання нових можливостей, виправлення помилок та недопрацювань, повідомлення про недопрацювання та звичайно про альтернативні реалізації бібліографічних стилів вітаються.

# Начало работы

## Установка и обновление

Инструкций по установке и обновлению смотрите, пожалуйста, на [сайте загрузок](https://apps.ankiweb.net).

## Видео

Для быстрого погружения в Anki, пожалуйста, посмотрите эти вступительные видео.
Они были сделаны в предыдущей версии программы Anki, но концепция та же.
(На английском. С русскими или англ. субтитрами)

- [Общие колоды и обзор основ](http://www.youtube.com/watch?v=QS2G-k2hQyg&yt:cc=on)

- [Синхронизация](https://www.youtube.com/watch?v=YkiM4DPzSVc&list=PLGgmaKOIHykFoomqkBJAyGiDQ2kyiuTao&yt:cc=on)

- [Переключение порядка карточек](http://www.youtube.com/watch?v=DnbKwHEQ1mA&yt:cc=on)

- [Оформление карточек](http://www.youtube.com/watch?v=F1j1Zx0mXME&yt:cc=on)

- [Вписывание ответа](http://www.youtube.com/watch?v=5tYObQ3ocrw&yt:cc=on)

Если YouTube блокируется в вашей стране, вы можете [скачать эти видео](https://apps.ankiweb.net/downloads/archive/screencasts/2.0/).

## Основные понятия

### Карточки

Пара вопрос-ответ называется 'карточкой'. Это название происходит от бумажных
флэш-карточек (англ. *flashcard*) [прим. перев. Ещё встречается перевод как
"дидактическая карточка"] с вопросом на одной стороне и ответом на обратной.
В Anki карточка на самом деле не выглядит как бумажная карточка и когда
отображается ответ, то вопрос остается видимым (по умолчанию, такое поведение
может быть изменено). Например, если вы изучаете основы химии, то можете увидеть
такой вопрос:

    В: Химический символ кислорода?

После обдумывания и принятия решения, что ответом является О, вы нажимаете
кнопку показа ответа и Anki показывает вам:

    В: Химический символ кислорода?
    О: О

Убедившись в своей правоте вы можете сообщить Anki, насколько легко вам было
вспомнить ответ, и Anki подберёт время следующего показа карточки.

### Колоды

'Колода' -- это группа карточек. Вы можете размещать карточки в разных колодах
для изучения отдельных частей вашей коллекции карточек, вместо того чтобы учить
все сразу. У каждой колоды могут быть разные настройки, например, сколько новых
карточек показывать каждый день или как долго следует ждать до следующего
показа карточки.

Колоды могут содержать другие колоды, что позволяет вам организовать их в
древовидную структуру. В Anki используется "::" как показатель разных уровней.
Так в названии колоды "Китайский::Ханзи" отмечается, что колода "Ханзи"
является частью колоды "Китайский".

Чтобы собирать колоды в дерево, вы можете либо именовать их с "::" между каждым
уровнем, либо мышкой перетаскивать и отпускать из списка колод. Колоды,
вложенные в другие колоды (в названии которых хоть раз встречается "::") часто
называют 'подколодами', а колоды верхнего уровня иногда называют 'суперколодами'
или 'родительскими'.

Anki запускается с единственной колодой под названием "по умолчанию" (англ.
*default*); все карточки, которые каким-то образом отделились от других колод,
будут попадать сюда. Anki скроет колоду по умолчанию, если в ней нет карт и вы
добавили другие колоды. Или же вы можете переименовать эту колоду и использовать
ее для других карточек.

Колоды больше всего подходят для объединения широких категорий карточек, а не
для таких конкретных тем, как "пищевые глаголы" или "урок 1". Более подробную
информацию об этом см. в разделе [правильное использование колод](editing.md#Правильное-использование-колод).

Информацию о том, как колоды влияют на порядок отображения в них карточек,
смотрите в разделе [порядок отображения](studying.md#Порядок-отображения)

### Записи и поля

При создании флэш-карточек часто бывает необходимо сделать более одной
карточки, относящихся к одной информации. Например, если вы изучаете
французский и узнаёте, что слово "bonjour" означает "здравствуйте", то вы
можете создать одну карточку, которая показывает вам "bonjour" и просит вас
вспомнить "здравствуйте", а другую карточку, которая показывает вам
"здравствуйте" и просит вас вспомнить "bonjour". Одна карточка проверяет вашу
способность узнавать иностранное слово, а другая -- умение воспроизвести его.

Используя бумажные флэш-карточки, у вас только один вариант -- написать всю
информацию дважды, по одному разу на каждой карточке. Некоторые компьютерные
программы облегчают создание флэш-карточек, предоставляя возможность
перевернуть лицевую и оборотную стороны карточки. Эта ситуация получше, чем с
бумажными карточками, но есть два основных недостатка:

- Поскольку подобные программы отслеживают вашу способность к распознаванию и
  воспроизведению информации по-отдельности, карточки, как правило, не
  показываются в оптимальное время, что означает, что вы либо забываете больше
  чем хотелось, либо занимаетесь больше, чем необходимо.

- Поменять местами вопрос и ответ можно только в том случае, если вам нужна
  в точности одинаковая информация на обеих сторонах. Это означает, что вы не
  можете, например, отобразить дополнительную информацию на обратной стороне
  каждой карточки.

Anki решает эти проблемы, позволяя вам разделить содержимое ваших карточек на
отдельные части информации. Вы можете указать Anki, какие части информации
вы хотите на каждой из карточек и Anki позаботится о создании их для вас, а так
же обновит их если вы сделаете какие-либо изменения в будущем.

Представьте, что мы хотим поучить французский словарь и добавлять номер
страницы на обратной стороне каждой карточки. Мы хотим, чтобы наши карточки
выглядели так:

    В: Bonjour
    О: Здравствуйте
       Страница #12

И:

    В: Здравствуйте
    О: Bonjour
       Страница #12

В этом примере у нас есть три, связанных между собой, части информации:
французское слово, русское значение и номер страницы. Объединив их вместе, они
будут выглядеть вот так:

    Французский: Bonjour
    Русский: Здравствуйте
    Страница: 12

В Anki эта связанная информация называется 'запись', а каждый фрагмент информации называется 'поле'. Так что мы можем сказать, что у этого типа записи имеется
три поля: французский, русский и страница.

Чтобы добавлять или изменять поля, нажмите кнопку "Поля…​" в процессе добавления
или изменения записи. Дополнительные сведения о полях см. в разделе [Настройка полей](editing.md#Настройка-полей).

### Типы карточек

Для того чтобы Anki создавала карточки на основе наших записей, мы должны
предоставить ей шаблон (англ. *blueprint*) в котором указано, какие поля должны
быть показаны на лицевой или обратной стороне каждой карточки. Этот шаблон и
называется 'типом карточки'. Каждый тип записи может иметь одну или несколько
типов карточек; когда вы добавляете запись, Anki создаст по одной карточке для
каждого типа карточек.

У каждого типа карточки есть два 'шаблона', один для вопроса и один для ответа.
В приведённом выше французском примере мы хотели, чтобы карта распознавания
выглядела так:

    В: Bonjour
    О: Здравствуйте
       Страница #12

Для этого мы можем задать шаблоны вопросов и ответов следующим образом:

    В: {{Французский}}
    О: {{Русский}}<br>
       Страница #{{Страница}}

Заключая название поля в двойные фигурные скобки, мы указываем Anki заменять
этот раздел фактической информацией из этого поля. Всё, что не окружено
фигурными скобками остаётся в неизменном виде на каждой карточке. (Например, мы
не должны вводить "Страница \#" в поле "Страница" при добавлении материала -- он
добавляется автоматически на каждую карточку.) &lt;br&gt; -- это специальный
код, который указывает Anki перейти к следующей строке; дополнительные сведения
доступны в разделе [Шаблоны карточек](templates/intro.md).

The production card templates work in a similar way:

    В: {{Французский}}
    О: {{Русский}}<br>
       Страница #{{Страница}}

Однажды создав тип карточки, в дальнейшем, каждый раз добавляя новую запись,
карточка будет создаваться на основе этого типа карточки. Типы карточек
упрощают содержание в единообразном состоянии оформления ваших карточек и могут
значительно облегчить добавление информации.

Для добавления и изменения типов карточек, нажмите кнопку "Карточки…​" во время добавления или изменения записи. Дополнительные сведения о типах карточек см. в разделе [Шаблоны карточек](templates/intro.md).

### Типы записей

Anki позволяет создавать различные типы записей для различного материала. У каждого типа записи имеется свой набор полей и типов карточек. Хорошей идеей будет создание отдельных типов записей для каждой обширной темы которую вы изучаете. Для этого, в приведённом выше французском примере, можно создать тип записи с названием "Французский". Если бы мы хотели изучать столицы, мы могли бы создать для этого отдельный тип записи, с такими полями, как "Страна" и "Столица".

<!----------------------------------------------------------------------------->
When Anki checks for duplicates, it only compares other notes of the
same type. Thus if you add a capital city called “Orange” using the
capital city note type, you won’t see a duplicate message when it comes
time to learn how to say “orange” in French.

When you create a new collection, Anki automatically adds some standard
note types to it. These note types are provided to make Anki easier for
new users, but in the long run it’s recommended you define your own note
types for the content you are learning. The standard note types are as
follows:

Basic  
Has Front and Back fields, and will create one card. Text you enter in
Front will appear on the front of the card, and text you enter in Back
will appear on the back of the card.

Basic (and reversed card)  
Like Basic, but creates two cards for the text you enter: one from
front→back and one from back→front.

Basic (optional reversed card)  
This is a front→back card, and optionally a back→front card. To do this,
it has a third field called “Add Reverse.” If you enter any text into
that field, a reverse card will be created. More information about this
is available in the [Cards and Templates](templates/intro.md) section.

Cloze  
A note type which makes it easy to select text and turn it into a cloze
deletion (e.g., “Man landed on the moon in \[…​\]” → “Man landed on the
moon in 1969”). More information is available in the [cloze
deletion](editing.md#cloze-deletion) section.

To add your own note types and modify existing ones, you can use Tools →
Manage Note Types from the main Anki window.

Notes and note types are common to your whole collection rather than
limited to an individual deck. This means you can use many different
types of notes in a particular deck, or have different cards generated
from a particular note in different decks. When you add notes using the
Add window, you can select what note type to use and what deck to use,
and these choices are completely independent of each other. You can also
change the note type of some notes [after you’ve already created
them](browsing.md).

### Collection

Your 'collection' is all the material stored in Anki – your cards,
notes, decks, note types, deck options, and so on.

## Shared Decks

You can watch [a video about Shared Decks and Review
Basics](http://www.youtube.com/watch?v=QS2G-k2hQyg&yt:cc=on) on YouTube.

The easiest way to get started with Anki is to download a deck of cards
someone has shared:

1.  Click the “Get Shared” button at the bottom of the deck list.

2.  When you’ve found a deck you’re interested in, click the “Download”
    button to download a deck package.

3.  Double-click on the downloaded package to load it into Anki, or
    File→Import it.

Please note that it’s not currently possible to add shared decks
directly to your AnkiWeb account. You need to import them with the
desktop program, then synchronize to upload them to AnkiWeb.

Creating your own deck is the most effective way to learn a complex
subject. Subjects like languages and the sciences can’t be understood
simply by memorizing facts — they require explanation and context to
learn effectively. Furthermore, inputting the information yourself
forces you to decide what the key points are, leading to a better
understanding.

If you are a language learner, you may be tempted to download a long
list of words and their translations, but this won’t teach you a
language any more than memorizing scientific equations will teach you
astrophysics. To learn properly, you need textbooks, teachers, or
exposure to real-world sentences.

    Do not learn if you do not understand.
    --SuperMemo

Most shared decks are created by people who are learning material
outside of Anki – from textbooks, classes, TV, etc. They select the
interesting points from what they learn and put them into Anki. They
make no effort to add background information or explanations to the
cards, because they already understand the material. So when someone
else downloads their deck and tries to use it, they’ll find it very
difficult as the background information and explanations are missing.

That is not to say shared decks are useless – simply that for complex
subjects, they should be used as a 'supplement' to external material,
not as a 'replacement' for it. If you’re studying textbook ABC and
someone has shared a deck of ideas from ABC, that’s a great way to save
some time. And for simple subjects that are basically a list of facts,
such as capital city names or pub quiz trivia, you probably don’t need
external material. But if you attempt to study complex subjects without
external material, you will probably meet with disappointing results.

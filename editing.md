# Добавление/изменение

## Добавление карточек и записей

Вспомним из [основ](getting-started.md), что в Anki мы добавляем записи, а не
карточки, и уже из них Anki создаёт нам карточки. Нажав 'Добавить' в главном окне
появится окно добавления записей.

В верхней левой части окна отображается текущий тип записи. Если он не указан
как "Basic", то, возможно, вы добавили некоторые типы записей вместе со
скачанными когда-то общими колодами. Следующий текст предполагает, что выбран
тип "Basic".

В верхней правой части окна отображается колода, в которую будут добавляться
карточки. Если хотите добавить карточки в новую колоду, вы можете нажать на
названии колоды и затем нажать 'Добавить'.

Под типом записи вы увидите несколько кнопок и области под названиями "Лицевая"
(англ. *Front*) и "Обратная" (англ. *Back*). Лицевая и Обратная области
называются 'полями' и вы можете добавлять, удалять и переименовывать их, щелкнув
по кнопке "Поля…​" выше.

Под полями находится другая область под названием "Метки". Метки --- это
ярлыки, которые вы можете прикрепить к вашим записям, чтобы упростить их
организацию и поиск. Вы можете оставить метки пустыми, если хотите, или
добавить одну или несколько из них. Метки разделяются знаком пробела. Если в
метках указано

    словарь уточнить_у_репетитора

…​то у записи которую вы добавите будет две метки.

При вводе лицевого и обратного текста, вы можете нажать кнопку "Добавить" или
сочетание клавиш Ctrl+Enter (Command+Enter на Mac) для добавления записи в
коллекцию. После чего, карточка будет создана и добавлена в выбранную вами
колоду. Если вы захотите изменить добавленную карточку, вы можете нажать кнопку
истории для поиска недавно добавленных карточек в [обзоре](browsing.md).

Anki проверяет первое поле на уникальность, поэтому предупредит, если вы
внесёте две карточки в Лицевом поле которых будут одинаковые данные, например,
"яблоко". Проверка уникальности ограничивается текущим типом записи, так, если
вы изучаете несколько языков, две карточки с одинаковой Лицевой стороной не
будут отображаться как повторы, пока у вас будут разные типы записей для
каждого языка.

Anki не проверяет на повторы другие поля автоматически из соображений
эффективности, но в обозревателе есть функция "Найти повторы", которую можно
запускать периодически.

Дополнительные сведения о кнопках между типом записи и полями см. в разделе
[редактор](editing.md).

Разным людям нравится повторять по-разному,но есть некоторые общие концепции,
о которых следует помнить. Отличное введение --- [эта статья](http://www.supermemo.com/articles/20rules.htm) на сайте SuperMemo. В частности:

-   **Будь проще**: Чем короче карточки, тем легче их повторять. У вас может
    возникнуть соблазн включить много информации "на всякий случай", но
    повторения станут мучительными очень быстро.

-   **Не запоминай без понимания**: Если вы изучаете язык, старайтесь избегать
    больших списков слов. Лучше всего изучать языки в контексте, что означает
    видеть использование этих слов в предложении. Так же представьте, что вы
    изучаете компьютерный курс. Пытаясь запомнить горы сокращений, вам будет
    очень трудно добиться прогресса. Но уделив время на понимание ключевых
    принципов, стоящих за этими сокращениями намного упростит их изучение.

## Добавление типа записи

В то время как основных типов записей достаточно для карточек с одним словом
или фразой с каждой стороны, как только вы захотите добавлять больше одного
фрагмента информации на лицевую или обратную стороны, лучше начать делить эту
информацию на большее количество полей.

Вы можете подумать: "но я хочу лишь одну карточку, так почему я не могу просто
добавить аудио, картинку, подсказку и перевод в Лицевом поле?" Если вы
предпочитаете делать именно так, то это нормально. Но недостатком этого подхода
является то, что вся информация оказывается склеенной. Если вы захотите
отсортировать ваши корточки по подсказке, то не сможете этого сделать т.к. эта
информация будет смешана с другим содержимым. Вы также не сможете делать такие
вещи как, например, перенос аудио с лицевой стороны на оборотную без
кропотливого копирования и вставки его для каждой отдельной записи. Держа
информацию в разных полях, вы значительно облегчаете настройку внешнего вида
ваших карточек в дальнейшем.

Чтобы создать новый тип записи, выберите Инструменты → Управлять типами записей
в главном окне Anki. Затем нажмите "Добавить", чтобы добавить новый тип записи.
Теперь вы увидите другой экран, в котором предлагается выбрать тип записи как
основу нового типа. "Добавить" означает, создание нового типа на основе того,
который изначально идёт с Anki. "Клонировать" означает, создание нового типа на
основе того, который ужу находится в вашей коллекции. Например, если вы уже
создали тип французский словарь, то, возможно вы захотите клонировать его при
создании типа немецкий словарь.

После выбора ОК вам будет предложено назвать новый тип. Тема материала, который
вы сейчас изучаете, будет хорошим выбором, например, такие вещи как "Японский",
"Викторина" и так далее. Выбрав имя, закройте окно Типы записей и вы вернётесь
в окно добавления.

## Настройка полей

Для настройки полей, нажмите кнопку "Поля…​" при добавлении или изменении
записи, или когда тип записи выделен в окне Управления типами записей.

<!----------------------------------------------------------------------------->
You can add, remove, or rename fields by clicking the appropriate
buttons. To change the order in which the fields appear in this dialog
and the add notes dialog, you can use the reposition button, which asks
for the numerical position you want the field to have. So if you want to
change a field to be the new first field, enter “1”.

Do not use 'Tags', 'Type', 'Deck', 'Card', or 'FrontSide' as field
names, as they are [special fields](templates/fields.md#special-fields) and will not work
properly.

The options at the bottom of the screen allow you to edit various
properties of the fields to be used when adding and editing the cards.
This is *not* where you customize what appears on your cards when
reviewing; for that, please see [templates](templates/intro.md).

**Editing Font** allows you to customize the font and size used when
editing notes. This is useful if you want to make unimportant
information smaller, or increase the size of foreign characters which
are hard to read. The changes you make here do not affect how cards
appear when reviewing: to do that, please see the
[templates](templates/intro.md) section. If you have enabled the “type in the
answer” function, however, the text you type will use the font size
defined here. (For information about how to change the actual font face
when typing the answer, please see the [checking your
answer](templates/fields.md#checking-your-answer) section.)

**Sort by this field…​** tells Anki to show this field in the Sort Field
column of the browser. You can use this to sort cards by that field.
Only one field can be the sort field at once.

When **Remember last input…​** is checked, Anki will not clear out this
field’s content after a note is added. If you find yourself entering the
same content into multiple notes, you may find this useful.

**Reverse text direction** is useful if you are studying languages that
display text from right to left (RTL), such as Arabic or Hebrew. This
setting currently only controls editing; to make sure the text displays
correctly during review, you’ll need to adjust your
[template](templates/styling.md).

After you’ve added fields, you’ll probably want to add them to the front
or back of your cards. For more information on that, please see the
[templates](templates/intro.md) section.

## Changing Deck / Note Type

While adding, you can click on the top left button to change note type,
and the top right button to change deck. The window that opens up will
not only allow you to select a deck or note type, but also to add new
decks or manage your note types.

## Правильное использование колод

Decks are designed to divide your content up into broad categories that
you wish to study separately, such as English, Geography, and so on. You
may be tempted to create lots of little decks to keep your content
organized, such as “my geography book chapter 1”, or “food verbs”, but
this is not recommended, for the following reasons:

-   Lots of little decks mean you end up reviewing cards in a
    recognizable order. Whether it’s because you’re clicking on each
    deck in turn (which is slow) or you’ve added a number of decks under
    a single parent deck, you’ll end up seeing all the “chapter 1” or
    “food verb” cards together. This makes it easier to answer the
    cards, as you can guess them from the context, which leads to weaker
    memories. When you need to recall the word or phrase outside Anki,
    you won’t have the luxury of being shown related content first!

-   Anki was not designed to handle many decks (more than several
    dozen), and it will slow down as you add more – especially if you’re
    studying on a mobile client. A few extra decks is not going to make
    a noticeable difference, but if you have many decks the delays will
    start to add up.

Instead of creating lots of little decks, it’s a better idea to use tags
and/or fields to classify your content. Instead of creating a “food
verbs” decks for example, you could add those cards to your main
language study deck, and tag the cards with “food” and “verb”. Each card
can have multiple tags, which means you can do things like search for
all verbs, or all food-related vocabulary, or all verbs that are related
to food.

For those who like to stay very organized, you can add fields to your
notes to classify your content, such as “book”, “page”, and so on. Anki
supports searching in specific fields, which means you can do a search
for “book:'my book' page:63” and immediately find what you’re looking
for.

Anki’s [custom study and filtered deck](filtered-decks.md) features make this
especially powerful, as you can create temporary decks out of search
terms. This allows you to review your content mixed together in a single
deck most of the time (for optimum memory), but also create temporary
decks when you need to focus on particular material, such as before a
test. The general rule is that if you always want to be able to study
some content separately, it should be in a normal deck, and if you only
occasionally need to be able to study it separately (for a test, when
under a backlog, etc), tags/fields and filtered decks are better.

## Features

The editor is shown when [adding notes](editing.md), [editing a
note](studying.md) during reviews, or [browsing](browsing.md).

On the top left are two buttons, which open the [fields](editing.md#customizing-fields) and
[cards](templates/intro.md) windows.

On the right are buttons that control formatting. Bold, italic and
underline work like they do in a word processing program. The next two
buttons allow you to subscript or superscript text, which is useful for
chemical compounds like H<sub>2</sub>O or simple math equations like
x<sup>2</sup>.

The Fx button clears any formatting in the currently selected text. This
includes colours, bold, etc.

The next two buttons allow you to change text colour.

The \[…​\] button is visible when a cloze note type is selected.

You can use the paperclip button to select audio, images and videos from
your computer’s hard drive to attach to your notes. Alternatively, you
can copy the media onto your computer’s clipboard (for instance, by
right-clicking an image on the web and choosing 'Copy Image') and paste
it into the field that you want to place it in. For more information
about media, please see the [media](media.md) section.

The microphone icon allows you to record from your computer’s microphone
and attach the recording to the note.

The last button shows more advanced features, such as editing the
underlying HTML of a field, and shortcuts to add MathJax or
[LaTeX](math.md) to your notes.

Most of the buttons have shortcut keys. You can hover the mouse cursor
over a button to see its shortcut.

When pasting text, Anki will strip most formatting by default. If you
hold down the shift key while pasting, Anki will preserve more
formatting.

## Заполнение пропусков

'Cloze deletion' is the process of hiding one or more words in a
sentence. For example, if you have the sentence:

    Canberra was founded in 1913.

…​and you create a cloze deletion on “1913”, then the sentence would
become:

    Canberra was founded in [...].

Sometimes sections that have been removed in this fashion are said to be
'occluded'.

For more information on why you might want to use cloze deletion, see
rule number 5 [here](http://www.supermemo.com/articles/20rules.htm).

Anki provides a special cloze deletion type of note, to make creating
clozes easy. To create a cloze deletion note, select the Cloze note
type, and type some text into the "Text" field. Then drag the mouse over
the text you want to hide to select it, and click the \[…​\] button.
Anki will replace the text with:

    Canberra was founded in {{c1::1913}}.

The “c1” part means that you’ve created one cloze deletion on the
sentence. You can create more than one deletion if you’d like. For
example, if you select Canberra and click \[…​\] again, the text will
now look like:

    {{c2::Canberra}} was founded in {{c1::1913}}.

When you add the above note, Anki will create two cards. The first card
will show:

    Canberra was founded in [...].

…​on the question, with the full sentence on the answer. The other card
will have the following on the question:

    [...] was founded in 1913.

You can also elide multiple sections on the same card. In the above
example, if you change c2 to c1, only one card would be created, with
both Canberra and 1913 hidden. If you hold down alt (option on a Mac)
while creating a cloze, Anki will automatically use the same number
instead of incrementing it.

Cloze deletions don’t need to fall on word boundaries, so if you select
“anberra” rather than “Canberra” in the above example, the question
would appear as “C\[…​\] was founded in 1913”, giving you a hint.

You can also give yourself hints that don’t match the text. If you
replace the original sentence with:

    Canberra::city was founded in 1913

…​and then press \[…​\] after selecting "Canberra::city", Anki will
treat the text after the two colons as a hint, changing the text into:

    {{c1::Canberra::city}} was founded in 1913

When the card comes up for review, it will appear as:

    [city] was founded in 1913.

For information on testing your ability to type in a cloze deletion
correctly, please see the section on [typing answers](templates/fields.md#checking-your-answer).

Please note that overlapping clozes are not supported. For example, the
following field is invalid:

    {{c1::Canberra was {{c2::founded}}}} in 1913

If you need to create clozes from overlapping text, add another Text
field to your cloze, add it to the [template](templates/intro.md), and then when
creating notes, paste the text into two separate fields, like so:

    Text1 field: {{c1::Canberra was founded}} in 1913

    Text2 field: {{c2::Canberra}} was founded in 1913

The default cloze note type has a second field called Extra, that is
shown on the answer side of each card. It can be used for adding some
usage notes or extra information.

The cloze note type is treated specially by Anki, and cannot be created
based on a regular note type. If you wish to customize it, please make
sure to clone the existing Cloze type instead of another type of note.
Things like formatting can be customized, but it is not possible to add
extra card templates to the cloze note type.


## Inputting Foreign Characters and Accents

All modern computers have built in support for typing accents and
foreign characters, and multiple ways to go about it. The method we
recommend is using a keyboard layout for the language you want to learn.

Languages with a separate script like Japanese, Chinese, Thai and so on
have their own layouts specifically for that language.

European languages that use accents may have their own layout, but can
often by typed on a generic "international keyboard" layout. These work
by typing the accent, then the character you want accented - eg an
apostrophe (') then the letter a (a) gives á.

To add the international keyboard on Windows machines, please see
<https://support.microsoft.com/en-au/kb/306560>

To add it on Macs, please see
<http://www.macworld.com/article/1147039/os-x/accentinput.html>

Keyboards for a specific language are added in a similar way, but we can
not cover them all here. For more information, please try searching
Google for "input Japanese on a mac", "type Chinese on Windows 10", and
so on.

If you’re learning a right to left language, there are lots of other
things to consider. Please see [this
page](http://dotancohen.com/howto/rtl_right_to_left.html) for more
information.

The toolkit Anki is built on has trouble dealing with a few input
methods, such as holding down keys to select accented characters on Mac
OS X, and typing characters by holding down the alt key and typing a
numeric code on Windows.

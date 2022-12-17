# Добавление/изменение

<!-- toc -->

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
названии колоды и затем нажать "Добавить".

Под типом записи вы увидите несколько кнопок и области под названиями "Лицевая"
(англ. *Front*) и "Обратная" (англ. *Back*). Лицевая и Обратная области
называются 'полями' и вы можете добавлять, удалять и переименовывать их, щелкнув
по кнопке "Поля…​" выше.

Под полями находится другая область под названием "Метки". Метки — это
ярлыки, которые вы можете прикрепить к вашим записям, чтобы упростить их
организацию и поиск. Вы можете оставить метки пустыми, если хотите, или
добавить одну или несколько из них. Метки разделяются знаком пробела. Если в
метках указано

    словарь уточнить_у_репетитора

…​то у записи которую вы добавите будет две метки.

При вводе лицевого и обратного текста, вы можете нажать кнопку "Добавить" или
сочетание клавиш <kbd>Ctrl</kbd>+<kbd>Enter</kbd> (<kbd>Command</kbd>+<kbd>Enter</kbd> на Mac)
для добавления записи в коллекцию. После чего, карточка будет создана и
добавлена в выбранную вами колоду. Если вы захотите изменить добавленную
карточку, вы можете нажать кнопку истории для поиска недавно добавленных карточек
в [обзоре](browsing.md).

Дополнительные сведения о кнопках между типом записи и полями см. в разделе
[редактор](editing.md).

### Проверка на дубликаты

Anki проверяет первое поле на уникальность, поэтому предупредит, если вы
внесёте две карточки в Лицевом поле которых будут одинаковые данные, например,
"яблоко". Проверка уникальности ограничивается текущим типом записи, так, если
вы изучаете несколько языков, две карточки с одинаковой Лицевой стороной не
будут отображаться как повторы, пока у вас будут разные типы записей для
каждого языка.

Anki не проверяет на повторы другие поля автоматически из соображений
эффективности, но в обозревателе есть функция "Найти повторы", которую можно
запускать периодически.

###  Эффективное обучение

Разным людям нравится повторять по-разному, но есть некоторые общие концепции,
о которых следует помнить. Отличное введение — [эта статья](http://www.supermemo.com/articles/20rules.htm) на сайте SuperMemo. В частности:

- **Будь проще**: Чем короче карточки, тем легче их повторять. У вас может
  возникнуть соблазн включить много информации "на всякий случай", но повторения
  станут мучительными очень быстро.

- **Не запоминай без понимания**: Если вы изучаете язык, старайтесь избегать
  больших списков слов. Лучше всего изучать языки в контексте, что означает
  видеть использование этих слов в предложении. Так же представьте, что вы
  изучаете компьютерный курс. Пытаясь запомнить горы сокращений, вам будет очень
  трудно добиться прогресса. Но уделив время на понимание ключевых принципов,
  стоящих за этими сокращениями намного упростит их изучение.

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

Вы можете добавлять, удалять или переименовывать поля, нажимая соответствующие
кнопки. Чтобы изменить порядок, в котором поля отображаются в этом диалоговом
окне и окне добавления записей, можно использовать кнопку переместить, которая
запрашивает порядковый номер, который должно иметь поле. Так, если вы хотите
переместить поле на место первого поля, введите "1".

Не используйте в качестве имен полей 'Tags', 'Type', 'Deck', 'Card' или
'FrontSide', так как это [специальные поля](templates/fields.md#Специальные-поля)
и они не будут работать правильно.

Опции в нижней части экрана позволяют изменять различные свойства полей,
которые будут использоваться при добавлении и редактировании карточек. Здесь
вы _не_ настраиваете то, что появляется на карточках при повторении; для этого
смотрите раздел [шаблоны](templates/intro.md).

**Шрифт в редакторе** позволяет настроить шрифт и размер шрифта при
редактировании записей. Это полезно, если вы хотите сделать неважную информацию
меньше или увеличить размер иностранных символов, которые трудно прочитать.
Сделанные здесь изменения не влияют на то, как отображаются карточки при
повторении: для этого смотрите раздел [шаблоны](templates/intro.md). Однако,
если у вас включена функция "с вводом ответа", текст, который вы вводите, будет
использовать заданный здесь размер шрифта. (Информацию о том, как изменить
реальный вид шрифта при вводе ответа, смотрите в разделе
[проверка своего ответа](templates/fields.md#Проверка-своего-ответа).)


**Сортировать по этому полю…​** указывает Anki отображать это поле в столбце
Поле сортировки обозревателя. Это можно использовать для сортировки карточек по
этому полю. Одновременно только одно поле может быть полем сортировки.

**Направление текста справа-налево** полезно при изучении языка который
отображает текст справа-налево (англ. *right to left (RTL)*), например, арабский
или иврит. В настоящее время этот параметр управляет только редактированием;
чтобы убедиться, что текст отображается правильно во время повторения,
необходимо настраивать свой [шаблон](templates/styling.md).

После добавления полей, вы можете разместить их на лицевой или на обратной
стороне карточек. Более подробную информацию cм. в разделе [шаблоны](templates/intro.md).

## Изменение колоды/типа записи

В окне добавления записи нажмите на кнопку в левом верхнем углу чтобы изменить тип записи
или кнопку в правом верхнем углу чтобы переключиться на другую колоду.
В открывшемся окне можно также добавить новые колоды и управлять типами записей.

## Organizing Content

### Правильное использование колод

[Колоды](getting-started.md#decks) созданы чтобы разбить карточки на обширные категории,
которые будут изучаться по отдельности: английский, география и т. д.
Вы можете создать много маленьких колод для поддержания порядка,
например "мой учебник географии глава 1" или "глаголы, связанные с едой".
Однако, так делать не рекомендуется по следующим причинам:

- Из-за множества маленьких колод карты будут показываться в одинаковом порядке.
  Старые версии планировщика могут сортировать новые карточки только в порядке добавления.
  К тому же, если вы собирались нажимать на колоды по порядку (это долго),
  то карточки из "главы 1" и "глаголов" будут показываться вместе.
  Поэтому отвечать на вопросы будет проще, основываясь на контексте,
  и информация будет закрепляться хуже.
  Когда нужно будет вспомнить слово или фразу вне Anki,
  сопутствующей информации может не быть!

- Добавление сотен колод, особенно на более ранних версиях Anki,
  может вызвать подтормаживание, а очень большие древа колод с тысячами
  записей могут "сломать" отображение списка колод на версиях Anki до 2.1.50.

### Использование меток

Вместо создания множества маленьких колод, лучше разделять записи
при помощи меток и/или полей. Метки помогают эффективнее искать записи,
находить конкретную информацию и организовать всю коллекцию.
Есть много хороших способов использовать метки и поля. Предварительно подумайте,
каким образом вы будете ими пользоваться; так будет проще решить, какой подход выбрать.

Некоторые предпочитают организовывать карточки путем создания колод,
но у меток есть серьезное преимущество: у одной записи может быть несколько
меток, но одна карта может находиться только в одной колоде. Это делает метки
более мощным и гибким решением в большинстве случаев. Метки можно расположить
в виде дерева [таким же способом, как и колоды](getting-started.md#decks).

К примеру, вместо создания колоды "глаголы, связанные с едой", добавьте карточки
в колоду для изучаемого языка и добавьте карточкам метки "еда" и "глагол". 
Так как у карточек может быть много меток, можно
[найти](searching.md#tags-decks-cards-and-notes) все глаголы, или все
связанные с едой слова, или все глаголы, связанные с едой.

Метки можно добавить в окне редактирования или через [обозреватель](browsing.md).
Там же метки можно удалить, переименовать или реорганизовать. Обратите внимание:
метки работают на уровне [записи](getting-started.md#notes--fields). Указав метку
для карты, все связанные карты также получат эту метку. Если нужно отметить
только одну карту, не изменяя связанные, то стоит воспользоваться флагами.

### Использование флагов

Флаги схожи с метками, но они показываются во время обучения на экране просмотра
в виде цветной иконки в верхней правой части окна. Также вы можете найти карты с флагом
в окне Обзора и создать из них фильтрованную колоду или переименовать флаг в обозревателе.
В отличие от меток, у одной карты может быть только один флаг. Еще одно важное отличие:
флаги работают на уровне [карты](getting-started.md#cards), а значит если отметить карту
флагом, то связанные карты не будут отмечены.

Поставить/снять флаг можно во время повторения карточек
(нажатием <kbd>CTRL</kbd> + <kbd>1-7</kbd> на Windows или
<kbd>CMD</kbd> + <kbd>1-7</kbd> на Mac) или через [обозреватель.](browsing.md)


### Метка "marked" ("отмечено")

Anki ведет себя по особому когда встречает метку "marked". There are options in the review
screen and browse screen to add and remove the "marked" tag. The review screen 
will show a star when the current card's note has that tag. And cards are 
shown in a different color in the browse screen when their note is marked.

Примечание: метка "marked" нужна для обратной совместимости с более старыми
версиями Anki; в большинстве случаев лучше использовать флаги.


### Использование полей

Если вы - очень организованный человек, то можете добавить поля своим
записям, такие как "книга", "страница" и т.д. Anki поддерживает
поиск по конкретным полям, что позволяет ввести `"book:my book" page:63`
и быстро найти то, что вас интересует.

### Дополнительные занятия и фильтрованные колоды

С помощью [дополнительных занятий и фильтрованных колод](filtered-decks.md)
вы можете создать временную колоду на основании результатов поиска.
Это позволяет повторять карточки в случайном порядке большую часть времени
(для лучшего закрепления) и создать временную колоду при необходимости
сделать упор на определенной теме, например, перед экзаменом.
Общее правило следующее: если материал требует отдельного изучения, то
ему место в обычной колоде; если же материал будет отдельно изучаться
только при необходимости (перед экзаменом, при отставании и т.д.), то
лучше создать фильтрованную колоду с помощью меток, флагов и полей. 

## Функции редактора

Редактор отображается при [добавлении записей](editing.md),
[их редактировании](studying.md) во время изучения и в [обозревателе](browsing.md).

В левом верхнем углу находятся кнопки, которые открывают окна 
[полей](editing.md#customizing-fields) и [карточек](templates/intro.md) соответственно.

Правее находятся кнопки форматирования. Жирный шрифт, курсив и подчеркивание
работают как в текстовом процессоре. Следующие две кнопки позволяют
указать верхний и нижний индекс, что полезно при написании химических формул
(H<sub>2</sub>O) и простых математических выражений (x<sup>2</sup>).

Кнопка с иконкой ластика сбрасывает форматирование выделенного
текста — включая цвет, жирность шрифта и т.д.

Следующие три кнопки 
The next three buttons allow creating lists, text alignment and text indent.
Then, there are two buttons to allow you to change text colour.

The \[…​\] button is visible when a cloze note type is selected.

You can use the paper-clip button to select audio, images, and videos from
your computer's hard drive and attach them to your notes. Alternatively, you
can copy the media onto your computer's clipboard (for instance, by
right-clicking an image on the web and choosing 'Copy Image') and paste
it into the field that you want to place it in. For more information
about media, please see the [media](media.md) section.

The microphone icon allows you to record from your computer's microphone
and attach the recording to the note.

The Fx button shows shortcuts to add MathJax or
[LaTeX](math.md) to your notes.

The `</>` button allows editing the underlying HTML of a field.

Anki 2.1.45+ supports adjusting sticky fields directly from the editing screen.
If you click on the pin icon on the right of a field, Anki will not clear out
the field's content after a note is added. If you find yourself entering the
same content into multiple notes, you may find this useful. On previous Anki
versions, sticky fields were toggled from the Fields screen.

Most of the buttons have shortcut keys. You can hover the mouse cursor
over a button to see its shortcut.

When pasting text, Anki will keep most formatting by default. If you
hold down the <kbd>Shift</kbd> key while pasting, Anki will strip most of the
formatting. Under Preferences, you can toggle "Paste without shift
key strips formatting" to modify the default behaviour.

## Заполнение пропусков

'Cloze deletion' is the process of hiding one or more words in a
sentence. For example, if you have the sentence:

    Canberra was founded in 1913.

…​and you create a cloze deletion on "1913", then the sentence would
become:

    Canberra was founded in [...].

Sometimes sections that have been removed in this fashion are said to be
'occluded'.

For more information on why you might want to use cloze deletion, see
Rule 5 [here](http://www.supermemo.com/articles/20rules.htm).

Anki provides a special cloze deletion type of note, to make creating
clozes easy. To create a cloze deletion note, select the Cloze note
type, and type some text into the "Text" field. Then drag the mouse over
the text you want to hide to select it, and click the \[…​\] button.
Anki will replace the text with:

    Canberra was founded in {{c1::1913}}.

The "c1" part means that you have created one cloze deletion on the
sentence. You can create more than one deletion if you'd like. For
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
both Canberra and 1913 hidden. If you hold down <kbd>Alt</kbd> (<kbd>Option</kbd> on a Mac)
while creating a cloze, Anki will automatically use the same number
instead of incrementing it.

Cloze deletions don't need to fall on word boundaries, so if you select
"anberra" rather than "Canberra" in the above example, the question
would appear as "C\[…​\] was founded in 1913", giving you a hint.

You can also give yourself hints that don't match the text. If you
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

All modern computers have built-in support for typing accents and
foreign characters, and multiple ways to go about it. The method we
recommend is by using a keyboard layout for the language you want to learn.

Languages with a separate script like Japanese, Chinese, Thai, and so on,
have their own layouts specific to that language.

European languages that use accents may have their own layout, but can
often by typed on a generic "international keyboard" layout. These work
by typing the accent, then the character you want accented - e.g. an
apostrophe (') then the letter a (a) gives á.

To add the international keyboard on Windows machines, please see
<http://www.techlanguage.com/tips/us_international.html>

To add it on Macs, please see
<http://www.macworld.com/article/1147039/os-x/accentinput.html>

Keyboards for a specific language are added in a similar way, but we can
not cover them all here. For more information, please try searching
Google for "input Japanese on a mac", "type Chinese on Windows 10", and
so on.

If you are learning a right-to-left language, there are lots of other
things to consider. Please see [this
page](http://dotancohen.com/howto/rtl_right_to_left.html) for more
information.

The toolkit on which Anki is built has trouble dealing with a few input
methods, such as holding down keys to select accented characters on macOS, 
and typing characters by holding down the <kbd>Alt</kbd> key and typing a
numeric code on Windows.

## Unicode Normalization

Text like `á` can be represented in multiple ways on a computer, such as
using a specific code for that symbol, or by using a standard `a` and then
another code for the accent on top. This causes problems when mixing input
from different sources, or using different computers - if your computer
handles keyboard input in one form, but the content is stored in a different
form, it will not match when searching, even though the end result appears
identical.

To ensure content can easily be found in searches, Anki normalizes the text
to a standard form. For most users this process is transparent, but if you
are studying certain material like archaic Japanese symbols, the normalization
process can end up converting them to a more modern equivalent.

If you want character variants preserved, the following in the [debug console](./misc.md)
will turn off normalization:

```python
mw.col.conf["normalize_note_text"] = False
```

Any content added after that will remain untouched. The trade-off is that you may
find it difficult to search for the content if you're switching between operating
systems, or pasting content from mixed sources.

# Изучение

Когда вы нашли колоду которая вам нравится или добавили несколько записей
самостоятельно --- пора начинать обучение.

## Колоды

Заучивание карточек в Anki осуществляется в пределах выбранной в настоящий
момент колоды и любых подколод которые она содержит.

На экране колод ваши колоды представлены в виде списка. В нем присутствуют два
числовых столбца: 'К просмотру' и 'Новые'. 'К просмотру' --- это количество
ожидающих повторения и уже разучиваемые карточки. 'Новые' --- это количество
новых карточек, которые подготовлены к заучиванию в этот день.

При нажатии на колоду она станет 'текущей колодой' и Anki переключится на экран
изучения. Вы можете вернуться к списку колод, чтобы изменить выбранную в данный
момент колоду в любое время, нажав на 'Колоды' в верхней части главного окна.
(Можно также использовать действие Учить колоду для выбора новой колоды с
клавиатуры или нажать клавишу 's' для изучения выбранной в данный момент
колоды.)

Можно нажать кнопку шестерёнки справа от колоды, чтобы переименовать или удалить
колоду, изменить её параметры или [экспортировать](exporting.md) её.

Если в колоде имеются подколоды, карточки отобразятся из [каждой колоды по
очереди](studying.md#Порядок-отображения).

## Общие сведения об изучении

После нажатия на колоду для изучения, вы увидите экран на котором показано
сколько карточек у вас запланировано на сегодня. Это называется экраном
'обзора колоды'. Карточки разделены на три типа:

- **Новые** --- это карточки, которые вы скачали или добавлены вручную, но
  никогда раньше не изучали.

- **Изучаемые** --- это карточки, которые недавно были показаны первый раз и
  сейчас в процессе изучения.

- **Повторяемые** --- это карточки, которые были изучены ранее, а теперь должны
  быть пересмотрены, чтобы вы их не забыли.

Чтобы начать сеанс заучивания, нажмите кнопку **Учить**. Anki будет показывать
вам карточки до тех пор, пока запланированные на сегодня карточки не закончатся.

В процессе изучения можно вернуться к обзору, нажав клавишу "s" на клавиатуре.

## Вопросы

При показе карточки, сперва показывается только вопрос. Подумав над ответом,
нажмите либо кнопку **Показать ответ**, либо пробел на клавиатуре --- будет
показан ответ. Это нормально, если вам потребуется немного времени, чтобы
вспомнить ответ, но, как правило, если вы не можете ответить в течение 10
секунд, скорее всего, лучше сдаться и показать ответ, чем продолжать пытаться
его вспомнить. 

Когда покажется ответ, вам следует сравнить его с тем который вы придумали и
сообщить Anki, на сколько точно вы запомнили. Если вы не уверены в точности
сравнения ответов, вы можете указать Anki [предлагать вам набирать ответ с клавиатуры](templates/fields.md#Проверка-своего-ответа), а не просто показывать его вам.

Количество кнопок, доступных для оценки ответа, зависит от того, является ли
карточка 'изучаемой' или 'повторяемой'.

## Обучение

При изучении новых или переучивании забытых карточек, Anki будет показывать
карточки по одному или нескольку раз, чтобы помочь вам их запомнить. Каждый
такой показ называется 'обучающий шаг'. По умолчанию установлено два
шага: 1 минута и 10 минут. Количество и продолжительность таких шагов можно
изменить в [настройках колоды](deck-options.md).

В процессе обучения доступны три кнопки оценки:

**Снова** --- перемещает карточку обратно к первому шагу.

**Хорошо** --- перемещает карточку на следующий шаг. Если карточка была на
последнем шаге, то она переводится [прим. перев. *из изучаемой*] в повторяемую
карточку (она 'выпускник' (англ. *graduate*)). По умолчанию, карточка достигнув
конца обучающих шагов, будет показана снова на следующий день, затем задержки
между показами будут увеличиваться (смотрите следующий раздел).

**Легко** --- немедленно переводит карточку в повторяемую, даже если остались
ещё шаги. По умолчанию, карточка будет показана повторно через 4 дня, затем
задержки между показами будут увеличиваться. Лёгкая кнопка не будет показана,
если вы в режиме переучивания, и это задаст тот же интервал, что и "хорошо".

Когда карточки показываются в первый раз, они начинают на первом шаге. Это
означает, что ответив **Хорошо** на карточке с первого раза покажет её ещё раз
через 10 минут, а первый шаг в 1 минуту будет пропущен. Если вы нажмёте Снова,
карточка вернется через 1 минуту.

Вы можете использовать клавиши 1, 2 и 3 на клавиатуре, для выбора конкретной
кнопки, где 1 --- это **Снова**. Нажатие клавиши пробела выбирает **Хорошо**. 

Если нет других карточек для показа, Anki снова покажет изучаемые карточки,
даже если их задержка полностью не закончилась. Если вы предпочитаете ждать
всю обучающую задержку, вы можете изменить поведение в [настройках](preferences.md).

## Повторение

Когда карточка уже была изучена и готова к повторению, есть четыре кнопки для
оценки ответа:

**Снова** --- помечает ваш ответ как неверный и указывает Anki чаще показывать
карточку в будущем. Карточка считается 'забытой' (англ. *lapsed*). Смотрите
раздел [забытые](deck-options.md) для получения более подробной информации о
том, как обрабатываются забытые повторения.

**Трудно** --- показывает карточку с чуть большей задержкой, чем в прошлый раз
и указывает Anki чаще показывать карточку в будущем.

**Хорошо** --- сообщает Anki, что последняя задержка была примерно правильной и
лёгкость карточки не нуждается в уменьшении или увеличении. При значении
лёгкости по умолчанию, задержка перед следующим показом карточки будет примерно
в 2,5 раза дольше чем в предыдущий раз, так что если бы вы в прошлый раз ждали
10 дней, чтобы увидеть карточку, то следующая задержка составит около 25 дней.

<!----------------------------------------------------------------------------->
**Easy** tells Anki you found the delay too short. The card will be
scheduled further into the future than 'Good', and Anki will schedule
the card less frequently in the future. Because 'Easy' rapidly increases
the delay, it’s best used for only the easiest of cards. Usually you
should find yourself answering 'Good' instead.

As with learning cards, you can use 1-4 on the keyboard to select an
answer. Pressing the spacebar will select 'Good'.

## Due Counts

When only the question is shown, Anki shows three numbers like 12 + 34 +
56 at the bottom of the screen. These represent the new cards, cards in
learning, and cards to review. If you’d prefer not to see the numbers,
you can turn them off in Anki’s preferences.

In the old scheduler, the numbers count _reviews_ needed to finish all the
cards in that queue, not the number of _cards_. If you have multiple
steps configured for lapsed cards, the number will increase by more than
one when you fail a card, since that card needs to be shown several times.

In the new scheduler, the numbers count _cards_, so the number will always
increase by one regardless of the steps remaining.

When the answer is shown, Anki shows an estimate of the next time a card
will be shown above each button. If you’d prefer not to see the
estimates, you can disable them in Anki’s [preferences](preferences.md).

Anki additionally adds a small amount of random variation to the next
due times, in order to prevent cards that were introduced together and
always rated the same from always staying next to each other. This
variation is not shown on the time estimates but will be applied after
selecting the button.

## Editing and More

You can click the **Edit** button in the bottom left to edit the current
note. When you finish editing, you’ll be returned to study. The editing
screen works very similarly to the [add notes](editing.md) screen.

At the bottom right of the review screen is a button labeled **More**.
This button provides some other operations you can do on the current
card or note:

Flag Card  
Adds a colored marker to the card, or toggles it off. Flags will appear during
study, and you can search for flagged cards in the Browse screen. This is useful
when you want to take some action on the card at a later date, such as looking
up a word when you get home.

Mark Note  
Adds a “marked” tag to the current note, so it can be easily found in the
browser. This is similar to flagging individual cards, but works with a tag
instead, so if the note has multiple cards, all cards will appear in a search
for the marked tag. Most users will want to use flags instead - marking is
mainly left around for compatibility with older Anki versions.

Bury Card / Note  
Hides a card or all of the note’s cards from review until the next day.
(If you want to unbury cards before then, you can click the “unbury”
button on the [deck overview](studying.md#study-overview) screen.) This is useful if
you cannot answer the card at the moment or you want to come back to it
another time. Burying can also [happen automatically](studying.md#siblings-and-burying) for
cards of the same note. If cards were in learning when they are buried,
they are moved back to the new card queue or review queue prior to being
buried.

Suspend Card / Note  
Hides a card or all of the note’s cards from review until they are
manually unsuspended (by clicking the suspend button in the browser).
This is useful if you want to avoid reviewing the note for some time,
but don’t want to delete it. If cards were in learning when they are
suspended, they are moved back to the new card queue or review queue
prior to being suspended.

Delete Note  
Deletes the note and all of its cards.

Options  
Edit the options for the current deck.

Replay Audio  
If the card has audio on the front or back, play it again.

Record Own Voice  
Record from your microphone for the purposes of checking your
pronunciation. This recording is temporary and will go away when you
move to the next card. If you want to add audio to a card permanently,
you can do that in the edit window.

Replay Own Voice  
Replay the previous recording of your voice (presumably after showing
the answer).

## Порядок отображения

Studying will show cards from the selected deck and any decks it
contains. Thus, if you select your “French” deck, the subdecks
“French::Vocab” and “French::My Textbook::Lesson 1” will be shown as
well.

For new cards and reviews, Anki fetches cards from the decks in
alphabetical order. So in the above example, you would get cards first
from “French”, then “My Textbook”, and finally “Vocab”. You can use this
to control the order cards appear in, placing high priority cards in
decks that appear higher in the list. When computers sort text
alphabetically, the “-” character comes before alphabetical characters,
and “\~” comes after them. So you could call the deck “-Vocab” to make
them appear first, and you could call the other deck “\~My Textbook” to
force it to appear after everything else.

New cards and reviews are fetched separately, and Anki won’t wait until
both queues are empty before moving on to the next deck, so it’s
possible you’ll be exposed to new cards from one deck while seeing
reviews from another deck, or vice versa. If you don’t want this, click
directly on the deck you want to study instead of one of the parent
decks.

Since cards in learning are somewhat time-critical, they are fetched
from all decks at once and shown in the order they are due.

To control the order reviews from a given deck appear in, or change new
cards from ordered to random order, please see the [deck
options](deck-options.md). For more fine-grained ordering of new cards, you
can change the order in the [browser](browsing.md).

## Siblings and Burying

Recall from [the basics](getting-started.md) that Anki can create more than one
card for each thing you input, such as a front→back card and a
back→front card, or two different cloze deletions from the same text.
These related cards are called 'siblings'.

When you answer a card that has siblings, Anki can prevent the card’s
siblings from being shown in the same session by automatically 'burying'
them. Buried cards are hidden from review until the clock rolls over to
a new day or you manually unbury them using the “Unbury” button that’s
visible at the bottom of the [deck overview](studying.md#study-overview) screen. Anki
will bury siblings even if the siblings are not in the same deck (for
instance, if you use the [deck override](templates/intro.md) feature).

You can enable burying from the [deck options](deck-options.md) screen -
there are separate settings for new cards and reviews.

Anki will only bury siblings that are new or review cards. It will not
hide cards in learning, as time is of the essence for those cards. On
the other hand, when you study a learning card, any new/review siblings
will be buried.

## Keyboard Shortcuts

Most of the common operations in Anki have keyboard shortcuts. Most of
them are discoverable in the interface: menu items list their shortcuts
next to them, and hovering the mouse cursor over a button will generally
show its shortcut in a tooltip.

When studying, either space or enter will show the answer. When the
answer is shown, you can use space or enter to select the Good button.
You can use the 1-4 keys to select a specific ease button. Many people
find it convenient to answer most cards with space and keep one finger
on 1 for when they forget.

The "Study Deck" item in the Tools menu allows you to quickly switch to
a deck with the keyboard. You can trigger it with the '/' key. When
opened, it will display all of your decks and show a filter area at the
top. As you type characters, Anki will display only decks matching the
characters you type. You can add a space to separate multiple search
terms, and Anki will show only decks that match all the terms. So “ja 1”
or “on1 ja” would both match a deck called “Japanese::Lesson1”.

## Falling Behind

If you fall behind in your reviews, Anki will prioritize cards that have
been waiting the longest. It does this by taking the cards that have
been waiting the longest and showing them to you in a random order up
until your daily review limit. This ordering ensures that no cards will
be left waiting indefinitely, but it means that if you introduce new
cards, their reviews won’t appear until you’ve gotten through your
backlog.

If you wish to change the order of the overdue reviews, you can do so by
creating a [filtered deck](filtered-decks.md).

When you answer cards that have been waiting for a while, Anki factors
in that delay when determining the next time a card should be shown.
Please see the section on Anki’s spaced-repetition
[algorithm](faqs.md) for more information.

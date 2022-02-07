# Изучение

<!-- toc -->

Когда вы нашли колоду которая вам нравится или добавили несколько записей
самостоятельно — пора начинать обучение.

## Колоды

Заучивание карточек в Anki осуществляется в пределах выбранной в настоящий
момент колоды и любых подколод которые она содержит.

На экране колод ваши колоды представлены в виде списка. В нем присутствуют три
числовых столбца. 'Новые' — это количество новых карточек, которые подготовлены
к заучиванию в этот день. Вторая колонка отображает количество карточек
изучаемых в данный момент. 'К просмотру' — это количество ожидающих повторения. 

При нажатии на колоду она станет 'текущей колодой' и Anki переключится на экран
изучения. Вы можете вернуться к списку колод, чтобы изменить выбранную в данный
момент колоду в любое время, нажав на 'Колоды' в верхней части главного окна.
(Можно также использовать действие Учить колоду для выбора новой колоды с
клавиатуры или нажать клавишу <kbd>s</kbd> для изучения выбранной в данный
момент колоды.)

Можно нажать кнопку шестерёнки справа от колоды, чтобы переименовать или удалить
колоду, изменить её [параметры](deck-options.md) или [экспортировать](exporting.md) её.

## Общие сведения об изучении

После нажатия на колоду для изучения, вы увидите экран на котором показано
сколько карточек у вас запланировано на сегодня. Это называется экраном
'обзора колоды'. Карточки разделены на три типа:

- **Новые** — это карточки, которые вы скачали или добавлены вручную, но
  никогда раньше не изучали.

- **Изучаемые** — это карточки, которые недавно были показаны первый раз и
  сейчас в процессе изучения.

- **Повторяемые** — это карточки, которые были изучены ранее, а теперь должны
  быть пересмотрены, чтобы вы их не забыли.

Чтобы начать сеанс заучивания, нажмите кнопку **Учить**. Anki будет показывать
вам карточки до тех пор, пока запланированные на сегодня карточки не закончатся.

В процессе изучения можно вернуться к обзору, нажав клавишу <kbd>s</kbd> на клавиатуре.

## Вопросы

При показе карточки, сперва показывается только вопрос. Подумав над ответом,
нажмите либо кнопку **Показать ответ**, либо пробел на клавиатуре — будет
показан ответ. Это нормально, если вам потребуется немного времени, чтобы
вспомнить ответ, но, как правило, если вы не можете ответить в течение 10
секунд, скорее всего, лучше сдаться и показать ответ, чем продолжать пытаться
его вспомнить. 

Когда покажется ответ, вам следует сравнить его с тем который вы придумали и
сообщить Anki, на сколько точно вы запомнили. Если вы не уверены в точности
сравнения ответов, вы можете указать Anki [предлагать вам набирать ответ с клавиатуры](templates/fields.md#Проверка-своего-ответа), а не просто показывать его вам.

## Изучаемые/Переучиваемые карточки

При изучении новых карточек или переучивании забытых, Anki будет показывать
карточки по одному или нескольку раз, чтобы помочь вам их запомнить. Каждый
такой показ называется 'обучающий шаг'. По умолчанию установлено два
шага: 1 минута и 10 минут. Количество и продолжительность таких шагов можно
изменить в [настройках колоды](deck-options.md).

<!-- ----------------------------------------------------------------------- -->
There are four rating buttons when learning:

**Снова** — перемещает карточку обратно к первому шагу.

**Hard**  repeats the current step after the first step, and is the average 
of Again and Good on the first step.

**Good** moves the card to the [next step](deck-options.md#learning-steps). If the card was on the final
step, the card is converted into a review card (it 'graduates'). By
default, once the card has reached the end of the learning steps, the
card will be shown again the next day, then at increasingly long delays
(see the next section).

**Easy** immediately converts the card into a review card, even if there
were steps remaining. [By default](deck-options.md#easy-interval), the card will be shown again 4 days
later, and then at increasingly long delays. In the v1 scheduler, the "Easy" button will not be
shown if you are in relearning mode as it would give the same interval
as “Good.” With the [v2 scheduler+](https://faqs.ankiweb.net/the-anki-2.1-scheduler.html),
when cards are in relearning, the "Easy" button boosts the interval by 1 day.

Когда карточки показываются в первый раз, они начинают на первом шаге. Это
означает, что ответив **Хорошо** на карточке с первого раза покажет её ещё раз
через 10 минут, а первый шаг в 1 минуту будет пропущен. Если вы нажмёте Снова,
карточка вернется через 1 минуту.

You can use the <kbd>1</kbd>, <kbd>2</kbd>, <kbd>3</kbd> and <kbd>4</kbd> keys on your keyboard to select a particular
button, where <kbd>1</kbd> is **Again**. Pressing <kbd>Space</kbd> or <kbd>Enter</kbd> will select
**Good**.

If there are no other cards to show you, Anki will show learning cards
again even if their delay has not elapsed completely. If you’d prefer to
wait the full learning delay, you can change this behaviour in 
[Preferences>Scheduling>Learn Ahead Limit](preferences.md).

## Review Cards

Когда карточка уже была изучена и готова к повторению, есть четыре кнопки для
оценки ответа:

**Снова** — помечает ваш ответ как неверный и указывает Anki чаще показывать
карточку в будущем. Карточка считается 'забытой' (англ. *lapsed*). Смотрите
раздел [забытые](deck-options.md#Забытые) для получения более подробной
информации о том, как обрабатываются забытые повторения.

**Hard** by default, shows the card at a [slightly longer delay](deck-options.md#hard-interval) 
than last time, and tells Anki to show the card more frequently in the future.

**Good** tells Anki that the last delay was about right, and the card
easiness doesn’t need to be adjusted down or up. At the [default starting
easiness](deck-options.md#starting-ease), the card will be shown again approximately 2 1/2 times longer
than the previous time, so if you had waited 10 days to see the card
previously, the next delay would be about 25 days.

**Easy** tells Anki you found the delay too short. The card will be
scheduled [further into the future than 'Good'](deck-options.md#easy-bonus), and Anki will schedule
the card less frequently in the future. Because 'Easy' rapidly increases
the delay, it’s best used for only the easiest of cards. Usually you
should find yourself answering 'Good' instead.

As with learning cards, you can use <kbd>1</kbd>, <kbd>2</kbd>, <kbd>3</kbd> and <kbd>4</kbd> on the keyboard to select an
answer. Pressing the <kbd>spacebar</kbd> or <kbd>Enter</kbd> will select **Good**.

See [Deck Options](deck-options.md) and the [FAQ](https://faqs.ankiweb.net/what-spaced-repetition-algorithm.html)
to learn more about how the algorithm works. 

## Due Counts 

Когда показывается только вопрос, Anki показывает в нижней части экрана три
числа вроде 12 + 34 + 56. Они обозначают новые карточки, изучаемые карточки и
повторяемые карточки. Если вы предпочитаете не видеть этих цифр, вы можете
отключить их в настройках Anki.

In the v1 scheduler, the numbers count _reviews_ needed to finish all the
cards in that queue, not the number of _cards_. If you have multiple
steps configured for lapsed cards, the number will increase by more than
one when you fail a card, since that card needs to be shown several times.

From the v2 scheduler, the numbers count _cards_, so the number will always
increase by one regardless of the steps remaining.

Когда отображается ответ, Anki выводит примерное время следующего показа
карточки над каждой кнопкой. Если вы предпочитаете не видеть оценок, вы можете
отключить их в [настройках](preferences.md) Anki.

## Fuzz Factor

When you select an ease button on a review card, Anki also applies a small amount of random “fuzz”
to prevent cards that were introduced at the same time and given the same ratings
from sticking together and always coming up for review on the same day. This fuzz
will appear on the answer buttons when the [v3 scheduler](https://faqs.ankiweb.net/the-2021-scheduler.html) is enabled, so if
you are using a previous version and you’re noticing a slight discrepancy between
what you select and the intervals your cards actually get, this is probably the
cause.

Learning cards are also given up to 5 minutes of extra delay so that they 
don’t always appear in the same order, but answer buttons won't reflect that. It 
is not possible to turn this feature off.

## Правка и ещё

Для изменения текущей заметки нажмите кнопку **Правка** в левом нижнем углу.
Завершив редактирование вы будете возвращены к обучению. Экран редактирования
работает аналогично экрану [добавления записи](editing.md)

В правом нижнем углу экрана просмотра находится кнопка **Ещё**. Эта кнопка
предоставляет несколько других операций, которые можно выполнить с текущей
карточкой или записью:

- [**Flag Card**](editing.md#using-flags): Adds a colored marker to the card, or toggles it off. Flags will appear during
study, and you can search for flagged cards in the Browse screen. This is useful
when you want to take some action on the card at a later date, such as looking
up a word when you get home. If you're using Anki 2.1.45+, you can also rename flags 
from the [browser](browsing.md).    

- **Отложить карточку / запись**: Прячет карточку или все карточки записи от
показа до следующего дня. (Если вы хотите вернуть карточки раньше, нажмите
кнопку "вернуть" в окне [обзора колоды](studying.md#Общие-сведения-об-изучении).)
Это полезно, если в данный момент вы не можете ответить на карточку или хотите
вернуться к ней в другой раз. Откладывание также может [произойти автоматически](studying.md#Связанные-и-отложенные) для карточек одной записи.

   Со старым планировщиком, если карточки находятся в процессе изучения на момент
   их откладывания, то сперва они перемещаются обратно в очередь новых карточек
   или очередь повторяемых перед тем как быть отложенными.

   Однако с [планировщиком 2.1](https://faqs.ankiweb.net/the-anki-2.1-scheduler.html),
   откладывание карточек не сбрасывает шаги изучения карточки.

- **Set Due Card**: Make cards review cards, and [make them due on a certain date.](browsing.md#cards)

- **Исключить карточку / запись**: Прячет карточку или все карточки записи от
   показа до тех пор, пока они не будут включены вручную (нажатием кнопки
   исключения–включения в окне обзора). Это полезно, если вы не хотите повторять
   запись некоторое время, но не хотите удалять её.
   Со старым планировщиком, если карточки находятся в процессе изучения на
   момент их исключения, то сперва они перемещаются обратно в очередь новых
   карточек или очередь повторяемых перед исключением.

   Однако с [планировщиком 2.1](https://faqs.ankiweb.net/the-anki-2.1-scheduler.html),
   исключение карточек не сбрасывает шаги изучения карточки.

- **Настройки**: Редактировать настройки текущей колоды.

- **Сведения о карточке**: Отображает [статистику](stats.md#card-info) по карточке.

- [**Mark Note**](editing.md#the-marked-tag): Adds a “marked” tag to the current note, so it can be easily found in the
browser. This is similar to flagging individual cards, but works with a tag
instead, so if the note has multiple cards, all cards will appear in a search
for the marked tag. Most users will want to use flags instead. 

- **Удалить запись**: Удаляет запись и все её карточки.

- **Повторное воспроизведение аудио**: Если у карточки есть аудио на лицевой или оборотной стороне, воспроизводит его повторно.

- **Аудио на паузу**: приостанавливает воспроизведение звука.

- **Аудио -5с / +5с**: Переход назад / вперед на 5 секунд в воспроизводимом аудио.

- **Записать свой голос**: Запись с микрофона для проверки произношения. Это
временная запись и она исчезнет при переходе к следующей карточке. Если вы
хотите добавить на карточку постоянную аудио-запись, то это можно сделать в окне редактирования.

- **Воспроизвести свой голос**: Воспроизвести предыдущую запись своего голоса (предположительно, после показа ответа).

## Порядок отображения

В процессе изучения показываются карточки из текущей выбранной колоды и всех
колод, которые она содержит. Таким образом, если вы выберете колоду
"Французский", подколоды "Французский::Словарь" и "Французский::Моя тетрадь::Урок 1"
также будут показаны.

The way Anki fetches cards from the decks depends on the algorithm used:

- With the v1 scheduler, when a deck has subdecks, the cards will appear from [each deck in
turn](studying.md#display-order).

- With the [v2 scheduler](https://faqs.ankiweb.net/the-anki-2.1-scheduler.html),
when a deck has subdecks, reviews are taken from all children decks
at once. The review limit of the child decks is ignored - only the limit of the
deck you clicked on applies.

- With the [v3 scheduler](https://faqs.ankiweb.net/the-2021-scheduler.html)
each child deck's limit is also enforced, and you do not need to see the cards 
in deck order either. See the [deck options](deck-options.md#review-sort-order) section of the manual for more information.

By default, for new cards, Anki fetches cards from the decks in
alphabetical order. So in the above example, you would get cards first
from “French”, then “My Textbook”, and finally “Vocab”. You can use this
to control the order cards appear in, placing high priority cards in
decks that appear higher in the list. When computers sort text
alphabetically, the “-” character comes before alphabetical characters,
and “\~” comes after them. So you could call the deck “-Vocab” to make
them appear first, and you could call the other deck “\~My Textbook” to
force it to appear after everything else.

Новые и повторяемые карточки выбираются отдельно, и Anki не будет ждать, пока
закончатся обе очереди, прежде чем перейти к следующей колоде, так что
возможно, вам будут показываться новые карточки из одной колоды и повторяемые
из другой, и наоборот. Если вам это не подходит, нажимайте непосредственно
на колоду которую хотите изучать, а не на родительские колоды.

Изучаемые карточки, поскольку у них, так сказать, жесткий временной режим,
выбираются из всех колод одновременно и отображаются в порядке своей очереди.

Для управления порядком, в котором появляются карточки из определённой колоды,
или изменения порядка показа новых карточек из упорядоченного в произвольный,
смотрите в [настройках колоды](deck-options.md). Ещё более точно настроить
порядок появления новых карточек можно в [обозревателе](browsing.md).

## Связанные и отложенные

Вспомним из [основ](getting-started.md), что Anki может создавать более одной
карточки из каждой записи, например, карточки лицо→оборот и оборот→лицо, или
два разных заполнения пропусков из одного текста. Такие карточки, относящиеся к
одной записи, называются 'связанными'.

Отвечая на одну из связанных карточек, Anki может предотвращать показ связанных
с ней карточек в этот же день, автоматически 'откладывая' их. Отложенные
карточки скрыты от повтора до тех пор, пока на часах не наступит следующий день
или вы вручную не вернёте их при помощи кнопки "Вернуть" отображаемой внизу
экрана [обзора колоды](studying.md#Общие-сведения-об-изучении). Anki отложит
связанные карточки даже если они находятся в разных колодах (например, если вы
используете функцию [подмена колоды](templates/intro.md)).

Вы можете включить откладывание в окне [настроек колоды](deck-options.md) —
отдельно для новых и повторяемых карточек.

Anki будет откладывать связанные карточки, которые являются новыми или
повторяемыми. Изучаемые карточки не будут скрываться, поскольку время для них
имеет существенное значение. С другой стороны, заучивая карточку которая
является изучаемой, любые новые/повторяемые карточки будут отложены.

Note: A card cannot be buried and suspended at the same time. Suspending a
buried card will unbury it. Burying a suspended card does not work on Anki
2.1.49+, whereas on earlier versions, it will unsuspend the card.

## Клавиатурные сокращения

Для большинства общих действий в Anki имеются клавиатурные сокращения. Многие
из них легко обнаружить в элементах интерфейса: рядом с пунктами меню
отображаются их клавиатурные сокращения, а наведение курсора мыши на кнопку, как
правило, показывает её клавиатурное сокращение во всплывающей подсказке.

Во время обучения, как <kbd>Пробел</kbd> так и клавиша <kbd>Enter</kbd> покажут
ответ. Когда покажется ответ, вы можете использовать клавиши <kbd>Пробела</kbd>
или <kbd>Enter</kbd> для выбора кнопки Хорошо. Для выбора конкретной кнопки
лёгкости можно использовать клавиши <kbd>1</kbd>–<kbd>4</kbd>. Многим людям
удобно отвечать на большинство карточек клавишей <kbd>Пробела</kbd> и держать
один палец на цифре <kbd>1</kbd>, на случай если забыли ответ.

Пункт "Учить колоду" в меню Инструменты позволяет вам быстро переключиться на
другую колоду с помощью клавиатуры. Вызвать его можно клавишей '/'. Будучи
открытым, в нём отображаются все ваши колоды и строка фильтра сверху. По мере
ввода символов, Anki будет отображать только те колоды которые соответствуют
введённым вами символам. Можно добавить пробел для разделения нескольких
условий поиска, и Anki покажет только колоды, соответствующие всем условиям.
Так "яп 1" или "ок1 яп" в обоих случаях будут соответствовать колоде
"Японский::Урок1".

## Отставание

Если вы отстали от графика повторения, Anki отдаст предпочтение карточкам,
которые ждут дольше всех. Она выбирает карточки ожидающие дольше всех и
показывает их в случайном порядке до тех пор, пока не будет исчерпан суточный
лимит показов. Такой порядок гарантирует, что никакие карточки не останутся в
состоянии вечного ожидания, однако это означает, что если вы добавите новых
карточек, то не увидите их до тех пор, пока не наверстаете отставание.

Если вы хотите изменить порядок просмотра просроченных карточек, вы можете это
сделать с помощью создания [фильтрованной колоды](filtered-decks.md).

Отвечая на карточки, некоторое время находившиеся в ожидании, Anki учитывает
эту задержку при определении времени следующего показа карточки. Дополнительную
информацию смотрите в разделе про [алгоритм](https://faqs.ankiweb.net/due-times-after-a-break.html) интервальных повторений
Anki.

Task Force Arma 3 Radio
=======================
[TeamSpeak](http://www.teamspeak.com/) радио плагин для Arma 3.

###[Вики](https://github.com/michail-nikolaev/task-force-arma-3-radio/wiki)&nbsp;&nbsp;[![](http://img.shields.io/badge/Версия-0.9.7 от 26.10.2014-blue.svg?style=flat)](https://github.com/michail-nikolaev/task-force-arma-3-radio/releases)&nbsp;[![](http://img.shields.io/badge/Скачать-120_МБ-green.svg?style=flat)](https://github.com/michail-nikolaev/task-force-arma-3-radio/releases/download/0.9.7/0.9.7.zip)&nbsp;[![](http://img.shields.io/badge/Лицензия-APL--SA-red.svg?style=flat)](https://github.com/michail-nikolaev/task-force-arma-3-radio/blob/master/LICENSE.md)&nbsp;[![](http://img.shields.io/github/issues/michail-nikolaev/task-force-arma-3-radio.svg?label=Задачи&style=flat)](https://github.com/michail-nikolaev/task-force-arma-3-radio/issues)
[![Task Force Arma 3 Radio](https://raw.githubusercontent.com/Tourorist/TPS/master/tfar/tfar_manw.jpg)](https://github.com/michail-nikolaev/task-force-arma-3-radio)

##Поддержите нас на [Make Arma Not War](http://makearmanotwar.com/entry/pMP8c7vSS4#.VA1em_nV9UD)

###Установка
* Скачайте [архив с рацией 0.9.7](https://github.com/michail-nikolaev/task-force-arma-3-radio/releases/download/0.9.7/0.9.7.zip) и распакуйте его.
* Скопируйте содержимое папки `TeamSpeak 3 Client` в корневую папку TeamSpeak.
* Скопируйте содержимое папки `Arma 3` в папку с игрой – `...\SteamApps\common\Arma 3`.

> [TFAR](http://radio.task-force.ru/) использует последнюю версию [СBA](http://www.armaholic.com/page.php?id=18767) (Community Base Addons). Поэтому, если этот мод у вас уже установлен – Windows предложит перезаписать поверх содержимого папки.

###Настройка
* Убедитесь, что в TeamSpeak клавиша <kbd>Caps Lock</kbd> не используется для разговора.
* Также в Arma 3 отключите разговор по внутренней связи (VON) по нажатию <kbd>Caps Lock</kbd> (чтобы не двоиться).
* Откройте список плагинов в TeamSpeak – `Settings> Plugins`.
 1. Включите `Task Force Arma 3 Radio`.
 2. Отключите `ACRE` и `radio ts ARMA3.ru version`, если они есть, чтобы избежать конфликтов.
 3. На всякий случай внизу слева можно нажать кнопку Reload All для перезагрузки всех плагинов.
* Убедитесь, что громкость оповещений в TeamSpeak не отключена – `Options> Payback> Sound Pack Volume` – установите в положительное значение.
* Запустите игру с аддонами `@CBA_A3` и `@task_force_radio`. Это можно сделать, прописав в ярлыке игры имена модов после EXE файла `…\arma3.exe -mod=@CBA_A3;@task_force_radio`, но рекомендуется включить необходимые моды в настройках игры – `Settings> Expansions`.
* Зайдите в тот же канал, где находятся другие игроки, играющие с данной рацией, либо вас перебросит в канал `TaskForceRadio` в случае его наличия при старте миссии.

> Если ник в профиле игры и TeamSpeak совпадает – плагин изменит ваш ник в TS в процессе игры.
>
> Не рекомендуется использовать плагин при одновременном подключении к нескольким серверам в TeamSpeak.
>
> Рекомендуется отключить встроенные звуки оповещений TeamSpeak – `Options> Notifications> Sound Pack: "Sounds Deactivated"`. Для применения этой опции необходимо перезапустить TeamSpeak.

###Использование
| Клавиши | Действие |
| :--- | :--- |
| Кнопка&nbsp;разговора&nbsp;в&nbsp;TS | Прямая речь. |
| <kbd>Caps Lock</kbd> | Разговор по рации. |
| <kbd>Ctrl</kbd>+<kbd>Caps Lock</kbd> | Разговор по рации дальней связи. |
| <kbd>Ctrl</kbd>+<kbd>P</kbd> | Открыть интерфейс рации ближней связи (рация должна быть в слоте инвентаря). В том случае, если у вас имеются несколько раций - вы сможете выбрать требуемую. Также есть возможность установить рацию как активную (ту, которая будет использоваться для передачи). Кроме того, существует возможность скопировать настройки для раций и другой радиостанции, если она использует аналогичный код шифрования.
| <kbd>Num [1-8]</kbd> | Быстрое переключение каналов рации ближней связи. | 
| <kbd>Alt</kbd>+<kbd>P</kbd> | Открыть интерфейс рации дальней связи - она должна быть надета на спину, либо вы должны быть в технике за водителя, стрелка, командира или помощника пилота. Если доступно несколько раций - вам будет предложено выбрать. Также одну из них можно установить как активную. Кроме того, существует возможность скопировать настройки для раций и другой радиостанции, если она использует аналогичный код шифрования. |
| <kbd>Ctrl</kbd>+<kbd>Num [1-9]</kbd> | Быстрое переключение каналов рации дальней связи. |
| <kbd>Ctrl</kbd>+<kbd>Tab</kbd> | Изменить громкость прямой речи. Можно говорить шепотом (Whispering), нормально (Normal) и кричать (Yelling). Не влияет на громкость сигнала в радио передаче. |
| <kbd>Shift</kbd>+<kbd>P</kbd> | Открыть интерфейс переговорного устройства для водолазов (на вас должен быть надет ребризер). | 
| <kbd>Ctrl</kbd>+<kbd>~</kbd> | Разговор по переговорному устройству для водолазов. |
| <kbd>Ctrl</kbd>+<kbd>]</kbd> | Следующая рация ближней связи. |
| <kbd>Ctrl</kbd>+<kbd>[</kbd> | Предыдущая рация ближней связи. |
| <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>]</kbd> | Следующая рация дальней связи. |
| <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>[</kbd> | Предыдущая рация дальней связи. |
| <kbd>Ctrl</kbd>+<kbd>[←,↑,→]</kbd> | Изменение стерео режима рации ближней связи. |
| <kbd>Alt</kbd>+<kbd>[←,↑,→]</kbd> | Изменение стерео режима рации дальней связи. |
| <kbd>T</kbd> | Передача на дополнительном канале рации командира. |
| <kbd>Y</kbd> | Передача на дополнительном канале рации дальней связи. |
| <kbd>Esc</kbd> | Выход из интерфейса рации. |

###Рации
| Рация | Сторона | Диапазон /Дальность | 
| :--- | :--- | :--- |
| :radio: [AN/PRC-152](https://ru.wikipedia.org/wiki/AN/PRC-152)<br><sup>(командира)</sup>  | <span style="color:blue">Синие</span> | 30-512 МГц<br>/5 км |
| :radio: [RF-7800S-TR](http://rf.harris.com/capabilities/tactical-radios-networking/rf-7800s-tr.asp)<br /><sup>(бойца)</sup> | <span style="color:blue">Синие</span> | 30-512 МГц<br>/2 км |
| :radio: [RT-1523G (ASIP)](https://en.wikipedia.org/wiki/SINCGARS#Models)<br><sup>(ранцевая)</sup> | <span style="color:blue">Синие</span> | 30-87 МГц<br>/20 км<br><sup>(30 км для бортовой)</sup> |
| :radio: [AN/ARC-210](http://www.rockwellcollins.com/~/media/Files/Unsecure/Products/Product%20Brochures/Communcation%20and%20Networks/Communication%20Radios/ARC-210%20Integrated%20Comm%20Systems%20white%20paper.aspx)<br><sup>(авиационная)</sup> | <span style="color:blue">Синие</span> | 30-87 МГц<br>/40 км |
| :radio: [AN/PRC148-JEM](https://en.wikipedia.org/wiki/AN/PRC-148#AN.2FPRC-148_JTRS_Enhanced_MBITR_.28JEM.29)<br><sup>(командира)</sup> | <span style="color:green">Независимые</span> | 30-512 МГц<br>/5 км | 
| :radio: [AN/PRC-154](http://www.gdc4s.com/anprc-154a-rifleman-radio.html)<br><sup>(бойца)</sup> | <span style="color:green">Независимые</span> | 30-512 МГц<br>/2 км | 
| :radio: [AN/PRC-155](http://www.gdc4s.com/anprc-155-2-channel-manpack.html)<br><sup>(ранцевая)</sup> | <span style="color:green">Независимые</span> | 30-87 МГц<br>/20 км<br><sup>(30 км для бортовой)</sup> | 
| :radio: [AN/ARC-164](https://ru.wikipedia.org/wiki/AN/ARC-164)<br><sup>(авиационная)</sup> | <span style="color:green">Независимые</span> | 30-87 МГц<br>/40 км |
| :radio: [FADAK](http://www.iran.ru/news/politics/87228/Iran_prodemonstriroval_tri_novyh_obrazca_voennogo_naznacheniya)<br><sup>(командира)</sup> | <span style="color:red">Красные</span> | 30-512 МГц<br>/5 км | 
| :radio: [PNR-1000A](http://elbitsystems.com/Elbitmain/files/Tadiran%20PNR1000A_2012.pdf)<br><sup>(бойца)</sup> | <span style="color:red">Красные</span> | 30-512 МГц<br>/2 км | 
| :radio: [MR3000](http://www.rohde-schwarz.com/en/product/mr300xh-u-productstartpage_63493-10291.html)<br><sup>(ранцевая)</sup> | <span style="color:red">Красные</span> | 30-87 МГц<br>/20 км<br><sup>(30 км для бортовой)</sup> | 
| :radio: [MR6000L](http://www.rohde-schwarz.com/en/product/mr6000l-productstartpage_63493-9143.html)<br><sup>(авиационная)</sup> | <span style="color:red">Красные</span> | 30-87 МГц<br>/40 км | 
| :radio: Приемопередатчик<br><sup>(подводный)</sup> | Все | 32-41 кГц<br>/70-300 м<br><sup>(в&nbsp;зависимости&nbsp;от&nbsp;уровня&nbsp;волн)</sup> |

> Рации ближней связи (ручные, класса командира или бояца) и радиостанции дальнего вещания (ранцевые, бортовые, авиационные) одной фракции поддерживают единый протокол, поэтому могут связываться друг с другом. В случае если передача осуществляется по ближней – сигнал будет высокочастотным. В случае передачи по дальней – низкочастотным. 

> На качество радио сигнала также влияет ландшафт местности. Наименее благоприятное положение – вы находитесь прямо за крутым холмом. Если вы начнете двигаться от края холма в направлении противоположном вещающему игроку – сигнал будет улучшаться. Наиболее благоприятная позиция – прямая видимость до или от объекта вещания.

> Рация командира и радиостанции дальней связи позволяют одновременно принимать и передавать два канала. Нажатие на рации «Настроить дополнительный канал» сделает текущий канал дополнительным. Переключившись на другой канал вы будет слышать два канала – активный и дополнительный.

####Распределение
* По умолчанию рация дальней связи выдается лидерам отрядов. Если у данного игрока изначально надет рюкзак, то он будет автоматически сброшен на землю при выдаче ему рации.

* Рация ближней связи выдается игрокам, у которых есть `ItemRadio` в инвентаре. Первоначальная раздача раций может потребовать нескольких секунд ожидания — следите за игровыми сообщениями в центре экрана.

####В технике
* Рация дальней связи доступна в технике водителю, командиру, стрелку и помощнику пилота. Не вся техника имеет бортовые радиостанции.

* У каждого слота техники своя рация, которая должна быть настроена отдельно. Если вы планируете пересаживаться с места на места в технике, то предварительно настройте рацию на всех слотах — например, на слоте водителя и на слоте стрелка.

* Техника делиться  на открытую и закрытую (изолированную). Если вы находитесь в изолированной технике, то почти не будете слышать голоса снаружи (и наоборот). Однако если вы выглянете из техники, то будете слышать как голоса внутри, так и снаружи.

####Радиоперехват
* Рации можно поднимать у убитых игроков, передавать их друг другу. При этом они сохраняют все настройки (каналы, частоты, громкость). 

> Рекомендуется поднимать рации открывая инвентарь на том месте, где она лежит (чтобы она не пропала из-за ошибок игры). 

* Настройки рации в технике также сохраняются.
* По умолчанию все рации используют коды шифрования специфические для каждой отдельной фракции. Таким образом, даже если вы узнаете частоту которую использует ваш противник, вы всё равно не сможете прослушивать их переговоры просто введя её на своей собственной рации. Чтобы перехватывать разговоры (и говорить в эфир) противника - необходимо сначала каким-либо образом захватить вражескую радию.

> Для того, чтобы прослушивать ранцевую рациостанцию противника рекомендуется находиться в своей технике. В таком порядке вы можете следить за эфиром противника через ранцевую, и передавать союзникам информацию используя бортовую радиостанцию в технике, как активную.

####Водолазам
* Вы не можете говорить голосом находясь под водой (даже в водолазном костюме). Однако на близком расстоянии ваш собеседник сможет расслышать что-либо очень невнятное (исключение – если вы под водой в изолированной технике).
* Находясь под водой, вы невнятно и слабо слышите голоса на суше.
* Для связи между водолазами используйте Переговорное устройство.
* Вы не можете пользоваться радио связью под водой (ни говорить, ни слышать). Если нужно что-то передать на сушу — всплывайте на поверхность. Исключение – подводный аппарат на перископной глубине, т.к. в нем водолазам можно использовать рацию дальней связи.

###Режимы работы плагина
Плагин поддерживает два режима работы — **серьезный** и **упрощенный**. 

* **Упрощенный** используется по умолчанию. Он предназначен главным образом для кооперативных игр. Его особенностью является то, что игроки с плагином и в игре слышат мертвых, не играющих, играющих на другом сервере и играющих без плагина игроков минуя рацию (просто как через TeamSpeak). Это делает менее удобным игры против людей, но позволяет вашему другу без проблем узнать, где вы играете, какая у вас частота и т.д. Разумеется, те кто играет на одном сервере со включенными аддонами и плагинами будут слышать друг друга по «законам» рации с учетом расстояния и частот.

* **Серьезный** предназначен для проведения игр, где игроки играют против других игроков. Для его активации в TeamSpeak необходимо создать канал с названием `TaskForceRadio` и паролем `123`. Игроки должны включить плагин рации, зайти на сервер и, разойдясь по каналам сторон, проходить инструктаж. После загрузки миссии, через несколько секунд игроки будут переброшены в канал `TaskForceRadio`. В данном случае игроки будут слышать только живых игроков, со включенным плагином, играющих на этом же сервере. Мертвые игроки, в свою очередь, могут общаться друг с другом. Если мертвый игрок респавниться — он снова будет слышать только живых. После того, как игра заканчивается, игроки перебрасываются в канал, в котором они проходили инструктаж до игры.

###Решение проблем
* `Pipe error 230` – вы скорее всего вы забыли включить плагин в TeamSpeak.
* Плагин в TS показываться красным и не загружается - скорее всего вам нужно обновить TeamSpeak.
* Если что-то поломалось – попробуйте перезапустить плагин.
* Функция по нажатию <kbd>Caps Lock</kbd> не работает — возможная причина в геймерской клавиатуре, где код данной клавишы отличается от стандартного. Попробуйте изменить используемые клавиши (путем редактирования <code>userconfig</code>).
* Если из-за ошибки или еще чего-то вы перестали слышать других игроков даже вне игры, откройте `Setup 3D Sound` в TeamSpeak и кликните `Center All`.
* Для устранения возможных ошибок с плагином разработчикам может потребоваться лог TeamSpeak. Чтобы его скопировать зайдите в `Tools> Client Log`, поставьте все галочки сверху и — выделив весь текст через <kbd>Ctrl</kbd>+<kbd>A</kbd> — скопируйте его в буфер обмена.
* Если TeamSpeak упал при использовании плагина, то он покажет окошко с описанием того где можно найти дамп (путь к файлу). Буду очень благодарен за этот файлик!

###Администраторам TS
На всякий случай уменьшите уровень защиты от флуда — `правый клик по серверу> Edit Virtual Server> More> Anti Flood` — поставьте значения `30`, `300`, `3000` (сверху вниз).

###Разработчикам
Если данная разработка будет как-либо популярна, то хотелось бы избежать кучи несовместимых форков. По этой причине, в случае желания внесения изменений связывайтесь со мной - велика вероятность, что ваши разработки будут включены в главную ветку. Ждем [запросов на включение](https://github.com/michail-nikolaev/task-force-arma-3-radio/pulls?q=is%3Apr+is%3Aclosed) ваших изменений. :smile:

###Спасибки
* Отряду [Task Force Arrowhead](http://forum.task-force.ru/) за тестирование, поддержку, терпение и всяческую помощь.
* [MTF](http://forum.task-force.ru/index.php?action=profile;u=7) ([varzin](https://github.com/varzin)) за помощь с графикой и документацией.
* [Hardckor](http://forum.task-force.ru/index.php?action=profile;u=14) за помощь с графикой.
* [Shogun](http://forum.task-force.ru/index.php?action=profile;u=13) за помощь с графикой.
* [Блендеру](http://arma3.ru/forums/index.php/user/41-blender/) за шрифт.
* [vinniefalco](https://github.com/vinniefalco) за [DSP фильтры](https://github.com/vinniefalco/DSPFilters).
* [WOG](http://wogames.info/) и лично [TRUE](http://wogames.info/profile/TRUE/) за помощь в тестировании.
* [Music DSP Collection](https://github.com/music-dsp-collection) за компрессор.
* [Avi](http://arma3.ru/forums/index.php/user/715-avi/) за инспекцию кода.
* [Vaulter](http://arma3.ru/forums/index.php/user/1328-vaulter/) ([GitHub](https://github.com/andrey-zakharov)) за помощь в разработке.
* Дине за перевод.
* [Zealot](http://forums.bistudio.com/member.php?125460-zealot111) ([GitHub](https://github.com/Zealot111)) за помощь в разработке и полезные скрипты.
* [NouberNou](http://forums.bistudio.com/member.php?56560-NouberNou) за советы и конкуренцию.
* [Megagoth1702](http://forums.unitedoperations.net/index.php/user/2271-megagoth1702/) за свою давнюю работу по эмуляции звучания рации.
* [Naught](http://forums.unitedoperations.net/index.php/user/6555-naught/) за инспекцию кода.
* [Andy230](http://forums.bistudio.com/member.php?100692-Andy230) за перевод.
* [L-H](http://forums.bistudio.com/member.php?87524-LordHeart) ([GitHub](https://github.com/CorruptedHeart)) за помощь с кодом.
* [NorX_Aengell](http://forums.bistudio.com/member.php?99450-NorX_Aengell) за перевод на французский.
* [lukrop](http://forums.bistudio.com/member.php?78022-lukrop) ([GitHub](https://github.com/lukrop)) за помощь с кодом.
* [nikolauska](http://forums.bistudio.com/member.php?75014-nikolauska) ([GitHub](https://github.com/nikolauska)) за помощь с SQF кодом.
* [Kavinsky](https://github.com/kavinsky) за AN/PRC-154, RF-7800S-TR и другие рации.
* [JonBons](http://forums.bistudio.com/member.php?81374-JonBons) ([GitHub](https://github.com/JonBons)) за помощь с кодом.
* [ramius86](https://github.com/ramius86) за перевод на итальянский.
* Killzone Kid за [статьи](http://killzonekid.com/arma-scripting-tutorials-float-to-string-position-to-string/).
* [Krypto202](http://www.armaholic.com/users.php?m=details&id=45906&u=kripto202) ([GitHub](https://github.com/kripto202)) за звуки.
* [pastor399](http://forums.bistudio.com/member.php?128853-pastor399) ([GitHub](https://github.com/pastor399)) за модель рюкзаков и текстуры.
* [J0nes](http://forums.bistudio.com/member.php?96513-J0nes) за помощь с моделями.
* [Raspu86](http://forums.bistudio.com/member.php?132083-Raspu86) ([GitHub](https://github.com/Raspu86)) за модель рюкзаков.
* [Gandi](http://forums.bistudio.com/member.php?111588-Gandi) за текстуры.
* [Pixinger](https://github.com/Pixinger) за помощь с [Зевсом](http://arma3.com/dlc/zeus).
* [whoozle](https://github.com/whoozle) за звуковой движок и помощь.
* [MastersDisaster](https://www.freesound.org/people/MastersDisaster/) за [звук переключателя](https://www.freesound.org/people/MastersDisaster/sounds/218115/).
* [CptDavo](http://forums.bistudio.com/member.php?75211-CptDavo) за помощь с текстурами.
* [KoffeinFlummi](https://github.com/KoffeinFlummi) за помощь с кодом.
* [R.m.K Gandi](http://steamcommunity.com/profiles/76561197984744647/) за текстуры рюкзаков.
* [Pomigit](http://forums.bistudio.com/member.php?97133-pomigit) за паттерны текстур.
* [Priestylive](https://plus.google.com/u/0/113553519889377947218/posts) за текстуры для [BWMOD](http://bwmod.de/).
* [Audiocustoms](http://forums.bistudio.com/member.php?98703-audiocustoms) ([SoundCloud](https://soundcloud.com/audiocustoms)) за звуки раций.
* [EvroMalarkey](http://forums.bistudio.com/member.php?104272-EvroMalarkey) ([GitHub](https://github.com/evromalarkey)) за перевод на чешский.
* [Tourorist](https://github.com/Tourorist) за помощь с документацией.
* Разработчикам [RHS](http://www.rhsmods.org/) за помощь в интеграции.
* Всем, кто делал видео и статьи с обзорами.
* Всем пользователям (особенно тем, что нашли баги).
* Извините, если кого-то случайно забыл.

§align:center
##### §nМеня пи*#@ло током, помогите, моя база горит у меня на глазах!11§n
§table{width:100%,render_cells:false} 
§img[https://cdn.fastcup.net/logos/teams/10649_7k9i72bea.png]{border_colour:0x0,border_colour_hover:0x0,width:100}



Если вы столкнулись с недопониманием того или иного аспекта с энергией, которая используеться в разных модификациях, то возможно эта страница поможет вам разобраться.

§3
§4
§5
§colour[#85c7a4]Базу, в виде редстоун-сигнала я опущу, ведь и без меня/вас §link[https://www.youtube.com/watch?v=tDxKhiJfgYk]{alt_text:всякие энтузиасты (например этот)} уже успели сделать свой первый компьютер, а в данный момент вы находитесь в растерянности. От банального запитывания всякого рода хранилищ и испытывания трудностей с подачей энергией (неужели так трудно проверить провода или режимы приёма/подачи энергии?), до полутора часовой борьбы за хранилище возле вашего дома, которое больше вашего §link[https://github.com/erogenousbeef-zz/BigReactors]{alt_text:реактора} в 4 раза, в страхе от того, что одно об другое *каким-то образом* взорвётся к хуям, просто потому что один мод - §link[https://github.com/Draconic-Inc/Draconic-Evolution]{alt_text:Draconic Evolution}, а другой - §link[https://github.com/erogenousbeef-zz/BigReactors]{alt_text:"Big Reactors/Extreme Reactors (здесь порт)"}, когда на деле это просто невозможно.

Всю информацию я буду брать из открытых источников во избежание спорных моментов.
Все моды вы сможете найти на §link[https://github.com]{alt_text:GitHub} или же §link[https://www.curseforge.com]{alt_text:CurseForge}. 
*Я же прикрепилю ссылки сюда для тех модов, которые я использовал для написания этой небольшой статейки.*

§4(Крайне не советую брать моды с каких-либо других сайтов, кроме этих двух) 
§6Исключение: Автор вывел на свой сайт/указал другой/альтернативный источник и.т.д.

§5
§5
§5
#####--- Конвертация и с чем её употреблять ---

Для начала вам нужно найти и установить мод, который позволяет конвертировать ту или иную энергию.
В моём случае это будет §link[https://github.com/Xalcon/EnergyConverters]{alt_text:"Energy Converters"} для 1.12.2 версии.

Весь процесс конвертации до банальности прост.
Данная модификация поддерживает все типы энергии, которые встречаются на версии 1.12.2
Крафт конвертеров будет зависеть от того или иного мода.
Например, чтобы создать Производитель Ультравысокого напряжения в базовой модификации §link[https://www.curseforge.com/minecraft/mc-mods/industrial-craft]{alt_text:"IndustrialCraft 2"}, нужно использовать для крафта Трансформаторы СВН (Сверх Высокого Напряжения) и.т.д.

Всего же данная модификация поддерживает 4 основных видов энергии, это:
######*RF/FE, MJ, EU, Tesla

§8На самом деле, когда я описал выше про RF, я имею в виду начало миграции с версии 1.12.2 на общую энергию ForgeEnergy, вместо устаревшего RedstoneFlux API. 
Итого, можно официально считать, что встречается всего 3 типа энергии в модификациях, связанных на построении сети.

Как описано выше:


§cRF: §link[https://github.com/CoFH/RedstoneFlux-1.12-Legacy]{alt_text:"RedstoneFlux API"}
Заменил за собой MinecraftJoules

§7MJ: MinecraftJoules
Предшественник RedstoneFlux, который был впервые построен и реализован в §link[https://github.com/BuildCraft/BuildCraft]{alt_text:"BuildCraft"} ещё в 2012 году.

§2EU: EnergyUnit
§2Можно считать прорадителем энергетики в модификациях. Появившийся на год раньше, чем MJ и был реализован в IC

§3Tesla: §link[https://www.curseforge.com/minecraft/mc-mods/tesla]{alt_text:"Tesla API"}
§3Цитируя автора данной АПИшки: "*The API was originally made as a fun side project, but received a lot of unexpected attention from other developers. It was not created as a crusade to kill other power API or anything like that.*"

§3У данного типа энергии нет зависимости к стандартам и всё варьируется от интеграции к другим модам.
§3По словам автора "1 Tesla = 1 RF"

§3

И мастодонт этой статьи
####§6Forge Energy
§6он же FE
Этот гигачад появился в Forge на официальном уровне в 1.12 и как раз с этой версии началась миграция RF на FE.
 Большинство модов, которые появились с нуля, а не портируются на новые версии кубача, наверняка используют именно FE интеграцию. 

Как пример:
- Crystal Flux (CF; §link[https://www.curseforge.com/minecraft/mc-mods/actually-additions/files?sort=datecreated]{alt_text:"Actually Additions"})
- Micro Infinity (µI; §link[https://github.com/SleepyTrousers/EnderIO]{alt_text:"Ender IO"})
- Immersive Flux (IF; §link[https://github.com/Blusunrize/ImmersiveEngineering]{alt_text:"Immersive Engineering"})

Всё это одна большая сеть, а не иная/своя энергия.
Из теории к...

§3
§3
#####--- Практика ---
После душного текста можно приступить к тому, зачем ты сюда пришёл.
§4Однако всё же тебе придётся почитать текст выше. Полезно будет.
§3
§3
Как ты мог понять из текста выше, то используемый в этой статье мод для конвертеров имеет 4 вида энергии на 1.12.2, которые чаще всего встречаются.
Из чего можно сделать вывод, что ты можешь построить <условный> реактор из IC2/Генератор на углях из Драконика/{вставьте_здесь_ваш_источник_энергии} и использовать его в совокупности с другими модификациями.

Сеть для примера будет довольно примитивна, но именно так я обычно её разворачиваю при прохождениях на месяцы вперёд.

*После постройки ЭкстримРеактора передо мной стояла цель запитать несколько сетей одновременно*
 *а именно:*
*1. Подать энергию на карьер BuildCraft для добычи ресурсов*
*2. Подать энергию для инфраструктуры IC2 по её переработке*
*3. Подать энергию для структуры из* §link[https://appliedenergistics.github.io/]{alt_text:"Applied Energistics 2"}*, чтобы хранить просто ОГРОМНОЕ количество ресурсов, добываемых из карьера*
*4. Аккумулировать избыточную энергию, т.к. реактору нельзя простаивать, иначе он будет за зря выгорать, а это обычно пустая трата урана и времени на его добычу*

§8Ссылка на данный мод с реакторами находится в самом начале страницы.
Решение:
1. На выход из реактора была поставлена RF Розетка => весь поток из реактора определяется как RedstoneFlux
2. Создаётся конвертер-потребитель FE (не забывай, что в 99% случаев FE = RF) и ставится на выход реактора
3. Ставится вплотную к потребителю мост из этого же мода, куда скапливается временная энергия (буфер)
§24. Ставится конвертер-производитель вплотную к мосту для той или иной цели.

§8Поясняю
BuildCraft - MJ:
Если мне нужно запитать карьер из BuildCraft (а ты ведь знаешь, что он использует MJ, да?), то я создаю MJ производитель и просто подключаю его как стандартную сеть из этого мода, т.е. на "сбор" энергии всегда идёт деревянная труба.
§8

IC2 - EU:
Зависит от энергоуровня твоей инфраструктуры. 
Если хочешь 1 энергоуровень, делаешь Производитель низкого напряжения.
Если хочешь сразу 5 энергоуровень, то помимо Производителя ультравысокого напряжения придётся сделать Трансформатор СВН на поток, т.к. даже при использовании Стекловолоконного провода - твоя МФСУ не выдержит и подорвёт тебе структуру, т.к. на вход будет идти поток 5 энергоуровня (8192 юнита), когда её предел на поступление всего в 4096 юнитов.
§8

Draconic Evolution и остальные модификации - FE/RF:
Без комментариев, тут даже и конвертер не нужен будет.
Достаточно просто будет напрямую провести поток на хранение/питание.

Помимо того, что я расписал про производители, так эти конвертеры могут работать и в обратную сторону, т.е. все они могут быть и потребителями, а на производство то, что вам будет нужно.

К примеру, если у вас переизбыток EU энергии из IC2 и вы решили, что вам пора взяться за Draconic Evolution, то достаточно рядом поставить потребитель N-энергоуровня рядом с вашем хранилищем EU энергии и отдать через мост по производителю RF в условное ядро хранения через энергокристаллы.
§8
§8
Удобство и сочетание этих модов состоит в том, что тебе не придётся бегать с места на место и следить, а не разряжен ли у тебя генератор на углях/бензине в одной стороне, пока у тебя плохо пропитывается преобразователь на другой части базы.
Ты просто стоишь и заполняешь один реактор на всю общую инфраструктуру из нескольких модов.
§8
§8
§8
§8

####§cИмей в виду!
Что при конвертации некая часть энергии теряется.
Связанно это с тем, что она имеет общий стандарт, который тянется ещё с 2011 года.
§8*Старше тебя кстати.*


###§61 EU = 0.4 MJ = 4 RF/FE = 6,55 gJ
§8Не буду отрицать, что в каких-то модификациях есть и отклонение от данного стандарта, но всё же.
§8
§8
§8
На этом я могу закрыть тему касательно энергетики.
Если что-то осталось от твоего горящего дома, то в следующий раз, когда будешь разворачивать огромную структуру, куда утекает вся энергия впустую - тебе это поможет.

-- by Unlucky / 14.06.2022 --



§align:center
##### §nДуши существ§n

§stack[draconicevolution:mob_soul,1,0,{EntityName:"[Random-Display]"}]{size:92} 

§rule{colour:0x606060,height:3,width:100%,top_pad:0}
Души можно выбить с существ, если убить их оружием с зачарованием "Жнец".

Шанс выпадения крайне низок.
Для враждебных существ шанс составляет 1 к 1000, а для нейтральных существ 1 к 800 (можно изменить в конфиге), но это только для оружия Виверны.
Шанс можно увеличить с помощью зачарования "Жнец".

Инструменты DE, по сути, имеют встроенный модификатор Жнеца, эквивалентное ур. 1 для Виверны, ур 2 для Дракониевого и ур. 3 для Посоха силы Дракона.
Расчет для определения вашего шанса выпадения - это базовый шанс выпадения, деленный на оружие, встроенное в модификатор Жнеца, плюс уровень заклинания Жнеца.

Таким образом, расчет, скажем, для Драконьего Меча со Жнецом 5 будет следующим,
Встроенный = 2,
Жнец = 5,
Шанс = 1000 / (2 + 5)

Результат: Вероятность выпадения составляет 1 к 142

Если модификатор Жнец равен 0 (то есть оружие, не являющееся DE, без заклинания Жнеца), вероятность получения души равна 0.

Некоторые моды могут использовать модификатор Жнеца на своем оружии, но на момент написания этой статьи я не знаю ни одного человека, который бы это сделал.


Основное применение души - это установка типа спавна для Стабилизированного спавнера, но их также можно использовать для создания соответствующей сущности, нажав ПКМ по блоку с душой (при этом душа расходуется).

§rule{colour:0x606060,height:3,width:100%,top_pad:0}
§recipe[draconicevolution:mob_soul]{spacing:2}
# netmmo

открытый мир, устройства которого общаются через сеть
игрок подключается к терминалу (ssh), через мини-игру или ресурсы, выполняет actions или грузит скрипт
ворует данные, деньги, скрипты

**Payload**
AOE: Local Network
Actions: scp /home/joe/banking/.session
Script: None

**Payload**
AOE: Direct
Actions: shutdown
Script: None

**Payload**
AOE: Near 
Actions: upload script
Script: _anal destroyer.sh_

## концепт локальных сетей

сеть поделена на участки (пр. соты 4g), при нахождении в участке устройство для подключения пользуется сетью, для усложнения возможно добавить слоистость сети, например:

_корп. X подключена к публичной сети N13 и держит приватную сеть (корпоративную)
хакер подключается к публичной сети, получает доступ к шлюзу корп. сети и спускается в корпоративный слой сети, где доступны платежные интерфейсы корп. X_

_шлюз действует как firewall_

## концепт данных

данные устройства - хэши паролей, сессии приложений, скрипты других пользователей

_платежный интерфейс корп. Х содержит в себе сессии клиентов банка, с которых извлекаются деньги при помощи автоматических скриптов (данные + время => деньги)_

## концепт скриптов 

для выполнения действий игрок подключается к терминалу устройства и ищет что стащить 
**и так с каждым устройством.**

скрипт - набор действий выполняющийся при загрузке в устройство, чтобы автоматизировать это дело. в начале они недоступны, стоят прилично, чтобы это было endgame инструментом, например для массовых диверсий: _война корпораций :)_

## квесты

отследите устройство с сигнатурой 0000AF14
_мы выясняем, в какой сети оно находится, подключаясь к терминалам сети - как в ctOS в Watch Dogs, каждая будет сужать радиус поиска, затем идем лично в это место и ищем устройство (сигнатура может быть в данных устройства)
либо вручную, либо скриптом_

## сканер малого радиуса

опасный метод, ведь это заметно. ты ходишь, подключаясь к устройствам в радиусе пары метров и запускаешь малые скрипты - без массового поражения. 

## антивирус?

в системе может быть программа, которая будет затруднять поиск файлов, либо не пускать незваных гостей. если это серьёзный софт, то можно и по лицу получить..
_а при сканировании малого радиуса некоторые модели такого софта определяют местоположение любопытного хакера_

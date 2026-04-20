# EDDLocalOrganicView
Plugin for EDDiscovery. Shows organic signals of planets in the current star system.
![Screenshoot of plugin window](https://github.com/Denis-VG/EDDLocalOrganicView/blob/main/LOSW_Screenshot.jpg)

# Description
The author was inspired to create this plugin for the popular program [EDDiscovery](https://github.com/EDDiscovery/EDDiscovery), which is essential for comfortable gameplay in Elite Dangerous, because of the lack of decent alternatives for displaying organic signals (exobiology). In EDDiscovery, you can request the organic scan history, but it takes a lot of time. When you're deeply engaged in exobiology and possess many scan log entries, numbering in the hundreds or thousands, the program experiences prolonged freezing. The Scans (table) tab offers a partial solution, but the overwhelming amount of complexly structured information hinders the rapid identification of required data. The author wanted only local information for a specific system, structured and comfortable for analysis, to avoid straining their eyes and brain figuring out what had already been scanned and what hadn't. With the plugin, you can also see the approximate cost of the scan. As far as I understand, the program does not account for the bonus for discovering new species (subspecies) of organics, nor the bonus added in-game for species you have already discovered before.

# Installation
Installing the plugin in EDDiscovery is extremely simple. You need to copy `#DVGSoft.LocalOrganicScanViewer.dll#` to the folder `%%LOCALAPPDATA%%\EDDiscovery\DLL` if you have the full installed version (not tested – the author uses the Portable version), or to `%%PATH_TO_EDDISCOVERY%%\Data\DLL` if you are using the Portable version of the program. And agree, when launching EDDiscovery, to the loading and running of the plugin.
More details: [HERE](https://github.com/EDDiscovery/EDDiscovery/wiki/5.1-Extending-EDD-with-DLLs)

The plugin requires [.NET Framework 4.8](https://dotnet.microsoft.com/ru-ru/download/dotnet-framework/net48) to run.

# Описание
На создание плагина для популярной программы [EDDiscovery](https://github.com/EDDiscovery/EDDiscovery), которая просто необходима для комфортной игры в Elite Dangerous, автора сподвигло отсутствие нормальных альтернатив для отображения органических сигналов (экзобиология). В EDDiscovery можно запросить историю сканирования органики, но это отнимает большое количество времени. Программа надолго зависает, особенно, если вы плотно занимаетесь экзобиологией и у вас несколько сотен, а то и тысяч записей в журнале сканирования. Вкладка сканы(таблица) частично решает вопрос, но обилие информации и ее запутанность мешает сходу определить нужные данные, приходится тщательно вычитывать то, что нужно конкретно по органическим сигналам. Автору захотелось иметь только локальную информацию по конкретной системе, максимально структурированную и комфортную для анализа, чтобы не ломать глаза и голову, в попытках понять, что уже отсканировано, а что нет. Плагин так же показывает примерную стоимость сканов. Наколько я понял, программа не учитывает премию за открытие новых видов (подвидов) органики и премию, добавляемую в игре за уже открытые вами виды ранее.

# Установка
Установка плагина в EDDiscovery предельно проста. Необходимо скопировать #DVGSoft.LocalOrganicScanViewer.dll# в папку %%LOCALAPPDATA%% \ EDDiscovery \DLL, если у вас полноценная установленная версия (не проверено, автор пользуется Portable версией), или %%PATH_TO_EDDISCOVERY%%\Data\DLL, если вы используете Portable версию программы. И согласиться, при запуске EDDiscovery с загрузкой и запуском плагина.
Подробнее: [ЗДЕСЬ](https://github.com/EDDiscovery/EDDiscovery/wiki/5.1-Extending-EDD-with-DLLs). 

Плагин требует установки [.NET Framework 4.8](https://dotnet.microsoft.com/ru-ru/download/dotnet-framework/net48) для своей работы.

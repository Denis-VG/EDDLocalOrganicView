# EDDLocalOrganicView
Plugin for EDDiscovery. Shows organic signals of planets in the current star system.
![Screenshoot of plugin window](https://github.com/Denis-VG/EDDLocalOrganicView/blob/main/LOSW_Screenshot.jpg)

# Description
The author was inspired to create this plugin for the popular program [EDDiscovery](https://github.com/EDDiscovery/EDDiscovery), which is essential for comfortable gameplay in Elite Dangerous, due to the lack of decent alternatives for displaying organic signals (exobiology). In EDDiscovery, you can request the organic scan history, but it takes a lot of time. The program freezes for a long time, especially if you are heavily involved in exobiology and have several hundred or even thousand entries in the scan log. The Scans tab (table) partially solves the problem, but the abundance of information and its complexity make it difficult to quickly identify the necessary data; you have to carefully read through what specifically relates to organic signals. The author wanted to have only local information for a specific system, as structured and comfortable for analysis as possible, so as not to strain your eyes and brain trying to figure out what has already been scanned and what hasn't. The plugin also shows the approximate scan value. As far as I understand, the program does not account for the value of discovering new species (subspecies) of organics, nor the bonus added in-game for species you have already discovered before.

# Installation
Installing the plugin in EDDiscovery is extremely simple. You need to copy `#DVGSoft.LocalOrganicScanViewer.dll#` to the folder `%%LOCALAPPDATA%%\EDDiscovery\DLL` if you have the full installed version (not tested – the author uses the Portable version), or to `%%PATH_TO_EDDISCOVERY%%\Data\DLL` if you are using the Portable version of the program. And agree, when launching EDDiscovery, to the loading and running of the plugin.
More details: [HERE](https://github.com/EDDiscovery/EDDiscovery/wiki/5.1-Extending-EDD-with-DLLs)

The plugin requires .NET Framework 4.8 to run.

# Описание
На создание плагина для популярной программы [EDDiscovery](https://github.com/EDDiscovery/EDDiscovery), которая просто необходима для комфортной игры в Elite Dangerous, автора сподвигло отсутствие нормальных альтернатив для отображения органических сигналов (экзобиология). В EDDiscovery можно запросить историю сканирования органики, но это отнимает большое количество времени. Программа надолго зависает, особенно, если вы плотно занимаетесь экзобиологией и у вас несколько сотен, а то и тысяч записей в журнале сканирования. Вкладка сканы(таблица) частично решает вопрос, но обилие информации и ее запутанность мешает сходу определить нужные данные, приходится тщательно вычитывать то, что нужно конкретно по органическим сигналам. Автору захотелось иметь только локальную информацию по конкретной системе, максимально структурированную и комфортную для анализа, чтобы не ломать глаза и голову, в попытка понять, что уже отсканировано, а что нет. Плагин так же показывает примерную стоимость сканов. Наколько я понял, программа не учитывает стоимость за открытие новых видов (подвидов) органики и премию, добавляемую в игре за уже открытые вами виды ранее.

# Установка
Установка плагина в EDDiscovery предельно проста. Необходимо скопировать #DVGSoft.LocalOrganicScanViewer.dll# в папку %%LOCALAPPDATA%% \ EDDiscovery \DLL, если у вас полноценная установленная версия (не проверено, автор пользуется Portable версией), или %%PATH_TO_EDDISCOVERY%%\Data\DLL, если вы используете Portable версию программы. И согласиться, при запуске EDDiscovery с загрузкой и запуском плагина.
Подробнее: [ЗДЕСЬ](https://github.com/EDDiscovery/EDDiscovery/wiki/5.1-Extending-EDD-with-DLLs). 

Плагин требует установки .NET Framework 4.8 для своей работы.

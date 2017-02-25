# WPSPIN.sh
27 октября 2014 года, человеком под ником hacker404 был опубликован скрипт, позволяющий проводить тестирование WIFI роутеров с включенным WPS. Скрипт включал в себя встроенный генератор и базу дефолтных WPS-Pin для некоторых моделей беспроводных роутеров.
Скрипт прекрасно работал и показывал хорошие результаты до выхода релиза Kali Linux 2.
С выходом нового релиза Kali, скрипт перестал работать, т.к. изменился формат вывода обновленного airmon-ng...

Пришло время вдохнуть новую жизнь в скрипт ;-)

Внес изменения в код для корректной работы на Kali Linux 2. Добавил автоматическое переключение беспроводного адаптера из режима Monitor в режим Managed и запуск службы network-manager при нажатии EXIT, Restart и прерыванием работы Reaver по нажатии CTRL+C.
Теперь нет необходимости вручную менять режим адаптера после завершения работы скрипта. 
Весь остальной функционал остался без изменений.


# Google Translate

October 27, 2014, a man of the script was published under the name hacker404, allowing the testing of WIFI routers enabled WPS. The script includes built-in generator and database default WPS-Pin for some models of wireless routers.
The script worked perfectly and showed good results before the release of Kali Linux Release 2.
With the new release of Kali, the script stopped working because It changes the output format of the updated airmon-ng ...

It's time to breathe new life into the script ;-)

Make changes to the code to work correctly on Kali Linux 2. Added automatic switching of the wireless adapter from the mode "Monitor" in mode Managed and start the network-manager by pressing EXIT, Restart and interrupt Reaver works on pressing CTRL + C.
Now there is no need to manually change the adapter mode after the completion of the script.
All other functionality remains unchanged.

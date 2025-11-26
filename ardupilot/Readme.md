## Контроллера SpeedyBee F405V3
Верхная сторона
![Сторона](img\speedybee_side1.png)
Нижная сторона
![Сторона](img\speedybee_side2.png)
Проект сделан на котроллере SpeedyBee F405V3 на прошивке ARDUPILOT версии [4.6.3](https://firmware.ardupilot.org/Copter/stable-4.6.3/)
1. Заходим в режим Boot(нажатием кнопки и подключая к компютеру)
2. Открываем программу STM32CubeProgrammer выбираем USB port и открываем файл с прошивкой arducopter_with_bl.hex(с загрузчиком)
![STM32CubeProgrammer](img\STM32CubeProgrammer.png)
3. Открываем MissionPlanner без конекта выбераем вкладку SETUP->Install Firmware. 
![MissionPlanner](img\MissionPlanner.png)
Вид Copter соглашаемся и жмем Bootloader Update
4. Connect и загружаем настройки(файл.param) Config->Full parameter list->load from fail
![MissionPlanner_param](img\MissionPlanner_param.png)
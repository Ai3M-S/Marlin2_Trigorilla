# AI3MS_Marlin2
 Marlin 2 for Anycubic i3 Mega-S

1. только для ТМС2208 с НЕ развёрнутыми разъёмами
2. поддержка 12864 RepRapDiscount Full Graphic Smart Controller
3. поддержка пищалки (пищит при срабатывании концевиков и при конце печати)
4. поддержка датчика обрыва филамента с возможностью его отключения
5. все ускорения и передвижения Mega-S забиты прямо в прошивку
6. отключен бутскрин для ускорения запуска

сделать обязательно ибо потеряем половину функционала принтера:

1. Открываем пинаут платы: https://4pda.ru/forum/index.php?s=&showtopic=941733&view=findpost&p=98419272
2. Берём плату-переходник от стокового экрана
3. Удлиняем провода от этой платки для термисторов и концевиков (всего нужно 10 проводов) 

ENG:

1. only non-reversed TMC2208
2. only 12864 RepRapDiscount Full Graphic Smart Controller
3. beeper/buzzer support
4. filament runout sensor support
5. disabled bootscreen
6. all accelerations and movements are hardcoded

NECESSARY:
1. Open Trigorilla`s pinout: https://4pda.ru/forum/index.php?s=&showtopic=941733&view=findpost&p=98419272
2. take hub from stock screen
3. lengthen all wires from hub for termistors and endstops (only 10 wires) 

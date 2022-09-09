layout: page
title: "Export from Krita"
permalink: /lesson-01/

Здравствуйте друзья, в этом видео я покажу как перенести анимацию из программы крита в программу Опен Тунз, чтобы потом сделать с ней различные операции, в частности - раскрашивать. 
Делать это мы будем на примере вот этой анимации.

*Ковёр*

Первое, что нужно сделать - это убедиться, что в файле с нашей анимацией установлено разрешение 120dpi, иначе при импорте в ОпенТунз она у нас будет отображаться с некорректным размером.

Выбираем сверху меню image и там scale image to new size. В этом файле, например, стоит разрешение 6000 dpi. Меняем. 
Далее, убедимся что у нас установлена галочка “Отдельно указать размер для печати”. Это нужно для того, чтобы размеры в пикселях не поменялись, а изменилось только разрешение. Жмём OK.

Следующим шагом, нужно обязательно добавить белый фон, тогда оупен тунз лучше распознает контур. Поэтому, создаём новый слой и заливаем его белым цветом. Из меню “правка” выбираем “залить цветом переднего плана”.
Далее нам нужно замкнуть области. Здесь у нас хороший контур, поэтому единственное, что нужно сделать, это добавить линию снизу, чтобы замкнуть нижнюю часть персонажа. Обязательно делаем это на отдельном слое, так она появится сразу на всех кадрах и при раскрашивании в ОпенТунз нам не придется замыкать область на всех кадрах вручную. 

Переходим к экспорту анимации. Выбираем сверху файл, рендер анимейшн. Здесь нам необходимо уделить внимание следующим пунктам. 
Во-первых, нам нужно убедиться, что мы экспортируем в секвенцию изображений. 
Во-вторых, обязательно нужно выбрать формат файла изображения тифф. Этот формат лучше поддерживается программой опен тунз.
Далее мы выбираем путь, куда будем экспортировать секвенцию. 

Теперь очень внимательно. В поле base name пишем frame и ставим точку. Эта точка обязательна, иначе… ОупенТунз не распознает наши файлы как секвенцию. 
Ну и наконец последнее, но не менее важное, ставим галочку рядом с пунктом Только уникальные кадры (only unique frames). Тогда крита будет экспортировать только ключевые кадры. Это сохранит не только ваше время и силы, но и память на вашем компьютере. 

С настройками закончили, нажимаем ok и ждем когда анимация экспортируется. Готово. Секвенция готова к импорту в Опен Тунз. Собственно этим мы и будем заниматься в следующем видео.
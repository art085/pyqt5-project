Paint (Picasso)

Осторожно, нужен PyQt5! Также на Ubuntu не работает весь фунционал!
Установка: pip install pyqt5 (Windows)
           pip3 install pyqt5 (Ubuntu)

Цель и причина создания

Программа создана с целью развлечения, возможно успокоения нервов, ну тут человек сам решает, зачем нужна эта программа.
Пришла идея, когда кто-то в Painte игрался, и подумали, почему бы не сделать аналог, естественно он сделан :)

Что использовано

Использован естественно pyqt5, также os, random, types. Ну и компы двоих людей с их руками (на одном из компов полетел жесткий диск во время разработки).

Функционал

Открытие нового файла (значок картины) - открывает файл (png).
Сохранение файла (значок диска) - сохраняет файл (png).
Ползунок - делает толщину кисти.
Пирог - можно щелчком поменять пирог, при щелчке на лист выскакивает пирог :)
Текст - можно напечатать текст (на разных шрифтах, а также курсивов, жирным и с нижним подчеркиванием).
Ластик - стирает нарисованное (как настоящий ластик, не сразу).
Так же есть инструменты, которые делают фигуры (прямоугольник, эллипс, многоугольники, закругление углов).
Есть кисточка с заливкой (с ними понятно, с карандашом тоже).
Также пипетка и спрей (зачем они нужны обычным людям, но мало ли).
А теперь про то, что на Ubuntu не работает!
Например, переход из негатива и наоборот (нет чертовой строки сверху, на Windows есть!)
Также отражение зеркально (и по вертикали, и по горизонтали).
Также можно все стереть (это для фанатов Гоголя, возможно и для самого Гоголя).
Можно конечно открыть чужую фотку и изуродовать её, но как я говорил, каждый человек из приложения вытаскивает свой мотив и свою цель, так что это проблемы юзеров :)
Процесс создания

Начали работать в прошлое воскресенье, все вроде бы шло хорошо, но тут у Арсена полетел жесткий диск, проблема в том, что сгорело немало кода. Пришлось целую кучу строк кода восстанавливать, учитывая, что проект вышел где-то на 1500 строк кода (это немало). Целых 3 дня было убито на восстановление кода, но он в итоге восстановлен, правда Арсен не мог коммиты делать, пришлось самому сделать коммиты (хоть бы не завалить проект). Также была проблема с тестированием (спасибо тупому PyCharmу), главное установил же библиотеку через командную, а через среду программирования я забыл, как добавлять библиотеки. Хорошо, что догадался через IDLE открывать и запускать программу. Также заметил конфликты на Ubuntu, где как раз нельзя было сделать негатив и зеркалить изображение.

Заключение

Самое главное, мы поняли, что надо использовать репозитории, чтобы больше не было таких “приколов”. Также мы поняли, что разработка это довольно интересный, но трудный процесс. Особенно когда ты школьник (студент), но тебя в школе (универе) напрягают совсем другим (особенно по профильным, особенно перед АКР). У профессиональных разработчиков задачи конечно потруднее, но им уже ничто и никто не мешает в принципе. Заметно, что промышленное программирование явно отличается от спортивного (на уроках обсуждали это, чем отличается обычная школьная (олимпиадная) программа от промышленной). Естественно приходилось чаще тестировать функционал (повезло, что писали код нормально и осмысленно, а как иначе). Что же можно добавить? Честно, мы не знаем, и сейчас даже знать не хотим. Уж слишком много физических и моральных страданий принесло написание (восстановление) кода, что просто лень думать над тем, как можно улучшить проект.











Artem and Arsen :)

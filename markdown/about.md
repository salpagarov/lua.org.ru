# Lua@two_cols

## Что такое Lua?

Это мощный, эффективный, легковесный, внедряемый скриптовый язык. Поддерживает процедурное, объектно-ориентированное, функциональное и управлемое данными программирование, а также может быть языком описания данных.

Lua сочетает простой процедурный синтаксис с мощью конструкций для описания данных (на основе ассоцативных массивов) и расширяемой семантики. Lua динамически типизируем, запускается интепретируемым байткодом с регистровой виртуальной машиной и автоматическим управление памятью с инкрементальным сборщиком мусора, делающее его идеальным для конфигрурирования, скриптинга и быстрого прототипирования.

## Откуда взялся Lua?

Lua спроектирован, реализован и поддерживается командой PUC-Rio, бразильского Папского Католического Университета Рио-де-Жанейро. Lua появился и вырос в Tecgraf (ранее "Группа технологий компьютерной графики") PUC-Rio. Сейчас Lua базируется в LuaLab, лаборатории Департамента компьютерных изысканий PUC-Rio.

## Что это за имя?

"Lua" (произносится "Луа") в переводе с португальского означает "Луна". Это не акроним и не аббревиатура, просто слово. Точнее, имя - имя естественного спутника Земли и языка программирования. Как и большинство имен, оно пишется строчными буквами и начинается с заглавной. Пожалуйста, не пишите "LUA", этот акроним для разных людей имеет [разные значения](http://acronyms.thefreedictionary.com/lua). Правильно писать "Lua".

## Присоединяйтесь к сообществу

Есть несколько мест для встреч с Lua-сообществом, где  вы сможете научиться, помочь другим и внести свой вклад иным способо. Одно из них - список почтовой рассылки, очень активный и дружественный.

Вы можете лично встретиться с частью сообщества на Lua Workshop.

## Поддержка Lua

Вы можете поддержать проект Lua приобретением книги, опубликованной Lua.org, или пожертвованиями.

## Зачем выбирать Lua?

### Lua надежен

Lua используется во многих промышленных приложениях (например, Adobe's Photoshop Lightroom), акцентируется на встраиваемые системы (например, Ginga middleware для цифрового TV в Бразилии) и игры (например, World of Warcraft и Angry Birds). В настоящее время Lua лидирует среди скриптовых языков в игровой индустрии. Для изучающих Lua есть цельное справочное руководство и несколько книг. Некоторые версии Lua созданы и используются в серьезных приложениях с момента появления в 1993 году. Lua представлен на HOPL III, Третьей конференции ACM SIGPLAN History of Programming Languages в 2007. Lua получил награду Front Line Award 2011 от Game Developers Magazine.

### Lua быстр

Lua заслужил свою репутацию производительностью. Быть "быстрым как Lua" стремятся многие скриптовые языки. Некоторые тесты показывают, что Lua самый быстрый среди интепретируемых языков. Lua быстр не только в специально написанных тестовых программах, но и в реальной жизни тоже. Существенная часть больших приложений написана на Lua.

Если вам нужно ещё большая скорость, попробуйте LuaJIT, независимую реализацию Lua c Just-In-Time компилятором.

### Lua переносим

Lua поставляется небольшим пакетом и собирается "из коробки" на всех платформах, где есть стандартный компилятор C. Lua запускается на всех разновидностях Unix и Windows, на мобильных устройствах (Android, iOS, BREW, Symbian, Windows Phone), на встроенных микропроцессорах (таких как ARM и Rabbit, для приложений вроде Lego MindStorms), на мэйнфреймах IBM и так далее.

О других причинах, почему Lua является хорошим выбором для ограниченных устройств, прочтите это [резюме](http://lua-users.org/lists/lua-l/2007-11/msg00248.html) Майка Пола. Взгляните также на [постер](http://www.schulze-mueller.de/download/lua-poster-090207.pdf) Тима Мюллера.

### Lua встраиваем

Lua быстрый язык маленького размера и вы можете легко встроить его в ваше приложение. У Lua простой и хорошо документированный API, предоставляющий мощную интеграцию с кодом на других языках. Расширить Lua библиотеками на других языках очень легко. Расширить с помощью Lua возможности программы на другом языке тоже очень легко. Lua используется для расширения программ не только на C и C++, но также и на Java, C#, Smalltalk, Fortran, Ada, Erlang и даже на других скриптовых языках, таких как Perl и Ruby.

### Lua мощен (но прост)

Фундаментальная концепция проектирования Lua - предоставлять *мета-механизмы* для реализации возможностей вместо предоставления самих возможностей напрямую в языке. Например, несмотря на то, что Lua не является чистым объектно-ориентированным языком, он предоставляет мета-механизмы для реализации классов и наследования. Мета-махенизмы Lua экономят на сущностях и сохраняют язык маленьким, позволяя расширить семантику нетрадиционными путями.

### Lua компактен

Добавление Lua к приложению не раздувает его. Архив для Lua 5.3.4, который содержит исходный код и документацию, занимает 297К в сжатом виде и 1.1М в несжатом. Исходный код содержит около 24000 строк кода на C. Под 64-битным Linux интерпретатор Lua со всеми встроенными стандартными библиотеками занимает 246К, а библиотека Lua занимает 421К.

### Lua свободен

Lua - свободное программное обеспечение с открытым исходным кодом, распростаняется под [очень либеральной лицензией](https://www.lua.org/license.html) (хорошо известной лицензией MIT). Он может использоваться в любых целях, включая коммерческие, абсолютно бесплатно. Просто [скачайте](https://www.lua.org/download.html) и пользуйтесь. 

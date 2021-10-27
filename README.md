<p>
	<img src="https://raw.githubusercontent.com/Shulhin/CSS-MachineX/master/app/assets/img/preview.jpg" alt="CSS-MachineX">
</p>
<h2>Начать</h2>
<p>Clone:</p>
<pre>git clone https://github.com/agragregra/Simple-Starter .; rm -rf trunk .gitignore readme.md .git</pre>
<p>Установить значение <strong>gmWatch = false</strong>, если не установлен в систему <strong>graphicsmagick</strong>.</p>
<p>Переименовать файл ht.access в .htaccess</p>

<h2>О сборке</h2>
<p>В сборку включена живая перезагрузка (на localhost), babel и webpack для модульности. Jquery подключено через CDN, при желании можно убрать.</p>
<h3>Что выполняет таскер:</h3>
<ul>
	<li>Добавляет префиксы для стилей</li>
	<li>Сжимает картинки благодаря graphicsmagick</li>
	<li>Включены sourcemaps в режиме работы над проектом</li>
	<li>Собирает sass стили и js скрипты, сжимает их в единый файл</li>
	<li>Объединяет media запросы воедино при сборке проекта</li>
	<li>Добавляет к файлам main.min.css и app.js "? + число" для обновления кэша на стороне клиента при выгрузке проекта на хостинг</li>
</ul>

<h2>Архитектура проекта</h2>
<p>
	<img src="https://raw.githubusercontent.com/Shulhin/CSS-MachineX/master/app/assets/img/architecture.jpg" alt="Структура проекта">
</p>

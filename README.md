Auto anchor plugin v 1.0
Плагин предназначен для поиска якорных сслылок и плавного скрола к ним

1. Для устаовки плагина нужно:
    прописсть ссылкам data атрибут:
        <a href="#link" data-anchor="true">Link</a>
2. Присвоить id блоку:
        <div id="link">
            ...
            </div>
3. Подключить скрипт: 
    (подключать скрипт можно как ваш общий js файл так и в html страницу предварительно обернув 
    его тегом <script>...</script>
//include scroll
jQuery( document ).ready(function( $ ) {
	$.getScript("/js/g-scroll-lite.js", function(){
        scrollspeed = 800 //значение задается в милесекундах
	});
});
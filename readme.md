<h1> Skytraffic Starter Template</h1>


<p>Author: <a href="http://skytraffic.ru" target="_blank">skytraffic</a></p>

<p>OptimizedHTML is all-inclusive, optimized for Google PageSpeed start HTML5 template with Bootstrap 4 sources, Gulp, Sass, Browsersync, Autoprefixer, Clean-CSS, Uglify, Imagemin, Vinyl-FTP and Bower (libs path) support. The template contains a <strong>.htaccess</strong> file with caching rules for web server.</p>

<p>Starter Template uses the best practices of web development and optimized for Google PageSpeed.</p>

<p>Совместимость с браузерами: IE11+ (без Bootstrap4 - IE9+)</p>

<p>The template uses a Sass with <strong>SCSS</strong> syntax and project structure with source code in the directory <strong>app/</strong> and production folder <strong>dist/</strong>, that contains ready project with optimized HTML, CSS, JS and images.</p>

<h2>Как пользоваться</h2>

<ol>	
	<li>Установить <a href="https://nodejs.org" target="_blank">Node.js</a>, если не установлен;</li>
	<li>Распаковать шаблон в нужную папку</li>
	<li>Установить node модули: <strong>npm i</strong>;</li>
	<li>Запустить проект: <strong>gulp</strong>.</li>
</ol>

<h2>Gulp tasks:</h2>

<ul>
	<li><strong>gulp</strong>: run default gulp task (sass, js, watch, browserSync) for web development;</li>
	<li><strong>build</strong>: build project to <strong>dist</strong> folder (cleanup, image optimize, removing unnecessary files);</li>
	<li><strong>deploy</strong>: project deployment on the server from <strong>dist</strong> folder via <strong>FTP</strong>;</li>
	<li><strong>rsync</strong>: project deployment on the server from <strong>dist</strong> folder via <strong>RSYNC</strong>;</li>
	<li><strong>clearcache</strong>: clear all gulp cache.</li>
</ul>

<h2>Guides</h2>

<ol>
	<li>All HTML files should have similar initial content as in <strong>app/index.html</strong>;</li>
	<li><strong>Template Basic Images Start</strong> comment in app/index.html - all your custom template basic images (og:image for social networking, favicons for a variety of devices);</li>
	<li><strong>Custom Browsers Color Start</strong> comment in app/index.html: set the color of the browser head on a variety of devices;</li>
	<li><strong>Custom HTML</strong> comment in app/index.html - all your custom HTML;</li>
	<li>For installing new jQuery library, just run the command "<strong>bower i plugin-name</strong>" in the terminal. Libraries are automatically placed in the folder <strong>app/libs</strong>. Bower must be installed in the system (npm i -g bower). Then place all jQuery libraries paths in the <strong>'libs'</strong> task (gulpfile.js);</li>
	<li>All custom JS located in <strong>app/js/common.js</strong>;</li>
	<li>All Sass vars placed in <strong>app/sass/_vars.scss</strong>;</li>
	<li>All media queries placed in <strong>app/sass/_media.scss</strong>;</li>
	<li>All jQuery libraries CSS styles placed in <strong>app/sass/_libs.scss</strong>;</li>
	<li>Rename <strong>ht.access</strong> to <strong>.htaccess</strong> before place it in your web server. This file contain rules for files caching on web server.</li>
</ol>

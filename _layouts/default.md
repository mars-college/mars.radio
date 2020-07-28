<!DOCTYPE html>
<html lang="en">
	<head>
		<!-- Global site tag (gtag.js) - Google Analytics -->
        <script async src="https://www.googletagmanager.com/gtag/js?id=UA-172226953-1"></script>
        <script>
            window.dataLayer = window.dataLayer || [];
            function gtag(){dataLayer.push(arguments);}
            gtag('js', new Date());
            gtag('config', 'UA-172226953-1');
        </script>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=yes">
		<title>{{page.title}}</title>
		<link rel="stylesheet" type="text/css" href="/css/styles.css">
		<link rel="icon" href="/favicon.png">
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
        <script src="/js/jquery.fitvids.js"></script>
		<script src="/js/scripts.js"></script>
	</head>
	<body>
        <header class="main_header">
            <a class="hamburger" href="#">&#9776;</a>
            <nav class="main_nav">
                <ul>
                    <li><a href="/martians">Coaches</a></li>
                    <li><a href="/syllabus">Syllabus</a></li>
                    <li><a href="/faq">FAQ</a></li>
                    <li><a href="/form">Contact</a></li>
                </ul>
            </nav>
            <h1>
                <a href="/index.html">Cyber Arts Camp</a>
            </h1>
        </header>
		{{content}}
	</body>
</html>

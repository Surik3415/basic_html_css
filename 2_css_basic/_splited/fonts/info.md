шрифти можна качати з google fonts(or extantion on vs_code)

можна імпортити в sass(css) file або на пряму в хедр html документу

* <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:ital@0;1&family=Roboto:ital@0;1&display=swap" rel="stylesheet">

* @import url('https://fonts.googleapis.com/css2?family=Montserrat:ital@0;1&family=Roboto:ital@0;1&display=swap')


якщо в гуглі немає шрифтів, то можна пошукати на сайті nomail.com.ua
скачається розширення otf(а треба ttf, svg, woff). Щоб з ним працювати треба конвертувати шрифт. Це можна зробити на сайті font2web.com 
https://www.fontconverter.io/ 

з font2web.com качається набір шрифтів.Здається кожен з файлів треба для окремого браузера 

для підключення шрифтів треба в css зазначити @font-face
https://developer.mozilla.org/ru/docs/Web/CSS/@font-face

@font-face {
  font-family: "Open Sans";
  src:
    url("/fonts/OpenSans-Regular-webfont.woff2") format("woff2"),
    url("/fonts/OpenSans-Regular-webfont.woff") format("woff");
  font-weight: bold
}
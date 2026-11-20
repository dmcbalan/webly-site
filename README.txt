WEBLY — ДМИТРІЙ БАЛАН, сайт-портфоліо веб-розробника
====================================================
Домен: https://webly.com.ua (GitHub Pages, файл CNAME)

ФАЙЛИ
index.html                 уся сторінка (HTML, стилі та скрипти всередині)
404.html                   сторінка «не знайдено» (GitHub Pages віддає її сам)
CNAME                      домен для GitHub Pages — не видаляти
robots.txt, sitemap.xml    для пошуковиків (у sitemap оновлюйте <lastmod> після великих змін)
site.webmanifest           іконки/кольори для «додати на головний екран»
og-image.jpg               прев'ю 1200×630 для Telegram/Facebook/Viber
favicon.png, favicon-32.png, apple-touch-icon.png   іконки (логотип Webly)
assets/images/dmytro-balan.webp (+ -sm.webp)        фото в Hero; .png — запасний варіант для старих браузерів
assets/images/projects/    скриншоти робіт (мокапи 1400×789 + -sm 800px)

ЯК ДОДАТИ ПРОЄКТ У ПОРТФОЛІО
1. Покладіть два файли в assets/images/projects/: назва.jpg (1400 px завширшки) і назва-sm.jpg (800 px).
2. В index.html у секції id="roboty" скопіюйте будь-яку картку:
   - з посиланням на сайт —  <a class="pj rv" data-cat="…" href="https://…" target="_blank" rel="noopener"> … </a>
   - без посилання (NDA) —   <article class="pj rv" data-cat="…"> … </article>
3. Змініть картинки (src/srcset), alt, назву <h3>, опис <p>, домен у .pj-url і теги.
4. data-cat = категорія для фільтра: landing | corp | shop | move

ВІДГУКИ — масив REVIEWS унизу index.html. Кількість (53 / 124) і рейтинг 4.98 змінюйте вручну в HTML.
АКЦІЯ — секція id="aktsiya"; таймер циклічний (12 днів), дата старту PROMO_START у скрипті.
СТЕК — масив STACK там же. Слова в бігучих стрічках — атрибут data-mq у HTML (через кому).
ФОРМА — відкриває чат t.me/dmcbalan з готовим текстом заявки (змінна TG у скрипті).
ПРЕЛОАДЕР — показується лише при першому відкритті сайту за сесію браузера.

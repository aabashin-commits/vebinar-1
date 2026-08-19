# Файловая структура

```
vebinar-1/
├── CLAUDE.md            — этот файл (поддерживать актуальным)
├── index.html           — единственная страница
├── css/
│   ├── base.css         — @font-face, CSS-переменные (копия токенов school), reset, типографика
│   ├── layout.css       — .container, кнопки .btn*, .section-card, .pill, .hl, .eyebrow
│   ├── header.css       — липкая шапка + мобильное меню
│   ├── countdown.css    — обратный отсчёт (компонент, стоит дважды)
│   ├── hero.css         — первый экран
│   ├── hook.css         — крючок + сравнение «крестики» / «галочки» (что не важно / что важно)
│   ├── extremes.css     — две крайности + строка-вывод «а нужно — посередине»
│   ├── year-path.css    — программа подготовки: 4 опоры + врезка «маленькая группа»
│   ├── first-class.css  — синяя секция «что ждёт в 1 классе» + режим дня
│   ├── speakers.css     — карточки спикеров + программа вебинара
│   ├── offer.css        — три бонуса участникам
│   ├── faq.css          — аккордеон
│   ├── final-cta.css    — финальный баннер с регистрацией
│   ├── footer.css       — футер
│   └── mobile-cta.css   — липкая плашка CTA на планшете и телефоне
├── js/
│   ├── main.js          — window.openForm (дефолт), lockScroll/unlockScroll, делегирование CTA
│   ├── header.js        — бургер-меню
│   ├── countdown.js     — ⚠️ ДАТА ЭФИРА + таймер + подстановка даты в разметку
│   ├── faq.js           — данные вопросов + рендер аккордеона
│   ├── mobile-cta.js    — показ липкой плашки после первого экрана
│   └── bitrix.js        — переключение CTA на CRM-форму (когда её подключат)
└── assets/
    ├── fonts/           — Onest variable (woff2, сабсеты cyrillic/latin/latin-ext) + OFL.txt
    ├── favicon/         — набор фавиконок (копия из school)
    └── img/
        ├── logo.svg          — цветное лого (шапка)
        ├── logo_footer.svg   — белое лого (футер)
        ├── green-check.svg   — галочка в списке «настоящая готовность»
        ├── hero/kid.webp     — вырезка девочки в hero (848×1372)
        ├── decor/            — grid.svg, wave.svg, swirl.webp, spark-*.svg,
        │                       boy.webp (⚠️ ПОЛНЫЙ кадр 424×272 = boy-mobile.webp из school.
        │                       Десктопный кроп school 424×220 брать нельзя: у него
        │                       обрезана макушка, а у нас картинка прижата к низу)
        └── speakers/         — фото спикеров, круглый кроп 400×400
```

Появился новый файл или файл переименован → сразу отразить здесь.


---

← [CLAUDE.md](../CLAUDE.md) · [README.md](../README.md)

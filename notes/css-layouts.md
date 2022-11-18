Компонування, чи «лейаути»
=

Responsive vs Adaptive Layouts
-
-	Media Queries
-	Mobile First

Grid vs Flexbox
-

### Flexible box

- [Basic concepts of flexbox](https://developer.mozilla.org/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox)
- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/), Chris Coyier для CSS Tricks
- [What the Flexbox](https://flexbox.io), Wes Bos

### Grid

- [Grid на MDN](https://developer.mozilla.org/docs/Web/CSS/CSS_Grid_Layout)
- [A Complete Guide to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/), Chris House для CSS Tricks
- [Things I’ve Learned About CSS Grid Layout](https://css-tricks.com/things-ive-learned-css-grid-layout/), Ollie Williams для CSS Tricks
- [Grid by Example](https://gridbyexample.com/examples/)

### Модульна сітка на 12 колонок

Не треба.

<details>
<summary>Чому?</summary>

[Модульні сітки](https://uk.wikipedia.org/wiki/Модульна_система_верстки) — це метод графічного дизайну,
який допомагає компонувати контент в певному чітко окресленому просторі,
наприклад, сторінці книги, газети, плакаті, тощо.

Коли почав зароджуватися веб-дизайн, різноманіття екранів не була,
та й ця сфера не могла зародитися нізвідки,
а почала базуватися на типографічному дизайні.

Модульна сітка на 12 рівних колонок історично стала найбільш гнучкою моделлю
для дизайну того, що ти поки не знаєш, як робити:
вона легко ділиться на дві, три чи чотири рівні колонки,
одну менщу й одну більшу, дві вужчі й одну широку тощо.
В результаті творчого процесу з 12-модульної сітки
утворюється макет на потрібну кількість колонок
та виділені місця для певного типу вмісту (зображення, текст, заголовки).

Процес дизайну у вебі може бути подібним.
Але це не є процесом верстки.
На варстку отримується макет із уже чітко визначеними областями контенту,
не важливо, чи для їх утворення була використана 12-модульна сітка, чи ні.
В сучасних реаліях це ускладнується ще й різноманіттям розмірів екранів:
для малих дисплеїв це може бути 1–4 модулі,
для більших — 4–12, а то й 24!
Приклад: [модульні сітки Material Design 2](https://m2.material.io/design/layout/responsive-layout-grid.html#columns-gutters-and-margins).

Як розробникам, вам не треба вдаватися в концепти мислення дизайнера,
коли ви верстаєте сторінку,
хоча корисно знати базові принципи дизайну для взаємопорозуміння з колегами.
Вам треба всього лише передавати дизайн на практиці так,
щоб він відображав замисл.
Зазвичай це доступність:
текст має бути читабельний, не надто широкий, не надто вузький,
зображення має бути чітким, розтягуватися до країв, не бути під текстом тощо.

Так в ідеальному світі, коли ви працюєте з кваліфікованими дизайнерами.
Не всі мають високу кваліфікацію, тому дивіться по ситуації.

</details>

Responsive Images
-
-	Image Formats
-	Compression
-	Responsive Images

Best Practices
-

Design Systems ?
-	Storybook

reset.css vs normalize.css vs sanitize.css
--
- [`reset.css`]() vs
- [`normalize.css`]() vs
- [`sanitize.css`]()
Interactive elements style overriding

---

1️⃣ доступность
1️⃣ лучшие практики по доступности 

---

4️⃣ Та і взагалі що повинен знати і вміти робити джун.

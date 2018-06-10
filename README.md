# Требования к PSD-макетам (lite-версия)

<b>Общее</b>

1. Формат - PSD, цветовое пространство sRGB (все постоянно об этом забывают, это важно, иначе цвета будут отличаться на экране)
2. Все величины (в том числе шрифты) измеряются в пикселях и только целых числах
3. Между объектами (например иконка и карта) допустим только режим наложения normal. Внутри объектов, которые предполагается экспортировать целиком (например баннер) — все что угодно.
4. Каждый элемент должен находиться в одном слое, названным человечески-понятным именем, а не «слой 1,2»
5. На каждую отдельную страницу должен быть отдельный PSD файл. Отображение всех страниц в одном макете приведет к использованию дикого количества оперативной памяти.
6. У файлов должно быть осмысленное название "link", "overlay", "button" и т.д.
7.  Все неиспользуемые слои нужно удалить.
8. Важно: не использоваться никакие другие режимы наложения, кроме normal. В вебе их просто нет.
9. Слои должны быть сгруппированы по блокам - "header", "reviews", "footer", блоки - идти а том порядке, в котором они будут на сайте.
10. Скрытые слои, которые нужно сверстать (разные всплывающие формы и т.д.) нужно выделить красным цветом, иначе они не будут сверстаны. Зеленым цветом выделяем слои с комментариями и стрелочками для верстальщика, если они требуются.

<b> Сетка </b>

<b> Графика </b>

Не накладывайте на векторные изображения в PSD-макетах корректирующие слои, маски, эффекты. Это приведёт к невозможности использования такой векторной графики

Должна присутствовать favicon для сайта (если ее нет, верстальщик сделает ее сам из того, что есть, но возражения приниматься не будут) в разрешении (192×192) в формате .PNG
Favicon это иконка, которая будет отображаться во владке браузера:

<b>Шрифты</b>

1. К макету должны быть приложены все шрифты, используемые в макете во всех задействованных начертаниях.
Лучше всего брать отсюда (тогда можно ограничиться ссылкой на шрифт):
https://www.google.com/fonts
http://fonts4web.ru/
https://fontstorage.com/

<b>Комплект материала для передачи верстальщику</b>

Макет в формате PSD
Стайл-гайд
Шрифты
Графика в формате SVG (иконки, логотипы, стрелочки и прочее, каждый элемент - отдельный файл)
Favicon в формате png и разрешении 192x192



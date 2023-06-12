# Landing page

Choose a design for your landing page:

- [MET landing](https://www.figma.com/file/lSR1m42L9YwzQwzzxKwHpw/THE-MET)
- [MYBIKE landing](https://www.figma.com/file/NZQAIydtHo5QkINyGLHNcq/BIKE-New-Version?node-id=0%3A1)
- [B&O](https://www.figma.com/file/DtkQmQ797hk0nI4KfMi2Uq/BOSE-New-Version?type=design&node-id=6817-212&t=ZTV6Gl8NzaWkJ4FK-0)
- [Nothing](https://www.figma.com/file/DtkQmQ797hk0nI4KfMi2Uq/BOSE-New-Version?type=design&node-id=6802-139&t=L7eKz5YKLN0m5WxR-0)

Follow the videos in this and next lessons to implement the page block by block

- Here is [the design from the video](https://www.figma.com/file/DtkQmQ797hk0nI4KfMi2Uq/BOSE-New-Version?type=design&node-id=6703-88&t=L7eKz5YKLN0m5WxR-0)
- Start writing styles in the `main.scss` file. It is be explained in the `Sass` lesson
- **DON'T** try to do it `Pixel Perfect` - implement it the most `simple` way so it looks similar;
- When done check yourself using the [CHECKLIST](./checklist.md) when finished;
- Deploy and create a Pull Request with a [DEMO LINK](https://morozit.github.io/layout_landing-page/)

# Tips & Hints

- Check `background-image: url()` to be relative to the `main.scss`. So should start with `../images`.
- If some points from the checklist are not relevant to your design, just skip it.

17. Використовуйте логотип як фавікон
18. Використовуйте цільову назву як назву сторінки
19. Усі логотипи мають бути посиланнями на верхню частину сторінки
20. Змініть колір тексту при наведенні для телефону, електронної пошти та адреси
21. Переконайтеся, що піктограми телефонів і номери телефонів є справжніми посиланнями, щоб почати дзвінок
22. Усі адреси мають бути посиланнями на певне місце на Картах Google. Потім відкрийте в новій вкладці за допомогою `target="_blank"`.
23. Збільште всі зображення при наведенні (зробіть їх посиланнями на #, якщо немає кращого варіанту)
24. Переконайтеся, що все виглядає акуратно на мобільному пристрої та без горизонтального прокручування
25. Швидкість анімації повинна бути однаковою по всій сторінці (наприклад, збільшуватися при наведенні або переміщенні блоків при прокручуванні)
26. Переконайтеся, що всі `nav__links` працюють безперебійно
27. Вимкніть прокручування сторінки під меню за допомогою наступного коду:
28. Дозволити прокручувати меню, якщо воно знаходиться вище вікна перегляду;
29. Усі поля форми повинні бути обов’язковими та мати правильний тип (`email`, `tel` тощо)
30. Заповнювачі мають давати приклади того, що слід додати, щоб зробити очікуваний формат зрозумілим
31. Сторінка не повинна перезавантажуватися під час надсилання форми, але поля мають бути очищені. Використання:

32. Зробіть нижній колонтитул липким внизу за допомогою `z-index: -1`, щоб отримати фіксований фоновий ефект.

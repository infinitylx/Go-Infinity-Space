---
title: "Code review"
date: 2013-07-08T13:20:23
---

Основною метою код ревью, на мою думку, є виявлення архітектурних помилок. Також за допомогою код ревью команда залишається в курсі хто над чим працює. Ще одним бенефітом є ознайомлення із різноманітними алгоритмами та практичними реалізаціями різних патернів для вирішення реальних проблем.

Почну із хто? Хто повинен приймати участь у перегляді коду? Відповідь щонайменше вся команда. Повинні також долучатись ті на кого можуть вплинути впроваджені зміни або виправлення.

Як? Оптимальним варіантом перегляду коду, на мою думку, є груповим. Автор розсилає усім код для поперднього ознайомлення і вказує час перегляду. Всі мають можливість ознайомитись із кодом і вже на перегляді можуть обміркувати запропонований код.

Ревью повино містити декілька обов’язкових частин. Спочатку, можливо навіть у листі із кодом на перегляд (залежить від використовуваних тулзів), автор кода повинен пояснити, яку проблему він намагається вирішити. Без цього подальший перегляд немає сенсу.

Далі, автор коду повинен пояснити, як само він хоче вирішити поставлену проблему. Ну і звісно навести код.

Далі, у чітко визначений час всі збираються і обговорюють вибраний автором шлях вирішення проблеми. Автор не зобов’язаний враховувати всі побажання.

Потім, після врахування всіх побажань, які вважає автро слушними, процедура повторюється.

Ревью можна проводити по факту або у чітко визначений день. Звісно, якщо теке дозволяє проект. Мені особиство здається, проведення у чітко визначений день більш оптимальним, оскільки дає змогу заздалегідь підготуватись та спланувати час. А одже і якість такого перегляду буде вище.

Особливо хочеться звірнути увагу на що потрібно звернути увагу в першу чергу.

 * Відповідність конверціям.
 * Назви змінних.
 * Відповідність використаних алгоритмів поставленій задачі.
 * Відповідність документації та комментарів коду.
 * Актуальність та наявність юніттестів.

Також, варто використовувати надбання сучасності у перегляді коду. Які надають змогу занотовувати коментарі до коду та вести дискусію, в  разі необхідності.

Такі сайти як [github.com](http://github.com), [bitbucket](http://bitbucket.org) та безліч інших дають змогу проводити перегляд коду.

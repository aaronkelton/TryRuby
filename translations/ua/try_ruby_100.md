---
lang:   UA
title:  Зупинись, ти здурів!)
answer: ^\d{1,}$
ok:     Розгорнути можна тільки рядки
error:  
---

Не можна розгорнути число задом наперед. Ти, звісно, можеш тримати монітор перед дзеркалом, але розгортання числа просто не має сенсу.

Ruby виведе повідомлення з помилкою. Ruby каже тобі, що не існує методу reverse для чисел.

Хіба може спробувати перетворити число 40 на рядок для початку:

    40.to_s.reverse

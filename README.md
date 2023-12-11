## <a name="up"></a> Примеры применения основных техник тест - дизайна
Ниже представлены некоторые мои примеры практического применения техник тест-дизайна при разработке тест-кейсов:

* [Тестирование по сценариям использования](#usecase)
* [Диаграмма состояний и переходов](#diagram)
* [Таблица состояний и переходов](#table_transit)
* [Доменный анализ](#domen)
* [Классы эквивалентности и анализ граничных значений](#classes)
* [Попарное тестирование](#pairwise)
* [Таблица решений](#table)
<hr>

### <a name="usecase"></a> Тестирование по сценариям использования
[Тестирование по сценариям использования.pdf](https://github.com/Elena-Belova/Test-Design/blob/88d15451b8009628751bd270717cc8433ff2008b/%D0%9F%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8C%D1%81%D0%BA%D0%B8%D0%B9%20%D1%81%D1%86%D0%B5%D0%BD%D0%B0%D1%80%D0%B8%D0%B9.pdf)
![Пользовательский сценарий](https://github.com/Elena-Belova/Test-Design/assets/148638077/24ad11f5-b330-46fc-809f-5ed70f68b503)
[Наверх](#up)
<hr>

### <a name="diagram"></a> Диаграмма состояний и переходов
**Инсталлятор приложения**
![Диаграмма состояний и переходов](https://github.com/Elena-Belova/Test-Design/assets/148638077/2a7810aa-c8d4-465d-86aa-6515f3e501e2)
**Тикеты техподдержки**
![Диаграмма состояний Тикеты](https://github.com/Elena-Belova/Test-Design/assets/148638077/dd6634af-1e6d-488d-aacf-a8ffd5c0fef8)
[Наверх](#up)
<hr>

### <a name="table_transit"></a> Таблица состояний и переходов
[Таблица переходов "Тикеты техподдержки".pdf](https://github.com/Elena-Belova/Test-Design/blob/88d15451b8009628751bd270717cc8433ff2008b/%D0%A2%D0%B0%D0%B1%D0%BB%D0%B8%D1%86%D0%B0%20%D0%BF%D0%B5%D1%80%D0%B5%D1%85%D0%BE%D0%B4%D0%BE%D0%B2%20%D0%A2%D0%B8%D0%BA%D0%B5%D1%82%D1%8B.pdf)
![Таблица переходов Тикеты](https://github.com/Elena-Belova/Test-Design/assets/148638077/74aa9ec3-3853-4528-ada5-5cfbcc73912f)
[Таблица состояний "Авторизация в онлайн-банке".pdf](https://github.com/Elena-Belova/Test-Design/blob/88d15451b8009628751bd270717cc8433ff2008b/%D0%A2%D0%B0%D0%B1%D0%BB%D0%B8%D1%86%D0%B0%20%D1%81%D0%BE%D1%81%D1%82%D0%BE%D1%8F%D0%BD%D0%B8%D0%B9%20%D0%91%D0%B0%D0%BD%D0%BA%20%D0%90%D0%B2%D1%82%D0%BE%D1%80%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F.pdf)
![Таблица состояний Банк](https://github.com/Elena-Belova/Test-Design/assets/148638077/e87fc3f0-6c9f-4ab9-809d-47dce2609cac)
[Наверх](#up)
<hr>

### <a name="domen"></a> Доменный анализ 
![Доменный анализ](https://github.com/Elena-Belova/Test-Design/assets/148638077/29f451c0-40ce-42d9-8514-08825a7b87ff)
[Доменный анализ "Модальное окно "Оплата товаров".pdf](https://github.com/Elena-Belova/Test-Design/blob/26ebe674cb5e3aa0cb1d0ae1dbd096b4efb7a67e/%D0%94%D0%BE%D0%BC%D0%B5%D0%BD%D0%BD%D1%8B%D0%B9%20%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7.pdf)

[Наверх](#up)
<hr>

### <a name="classes"></a> Классы эквивалентности и анализ граничных значений
![Классы эквивалентности Новости1](https://github.com/Elena-Belova/Test-Design/assets/148638077/6d29bc89-75e3-48f9-9524-d14bf764bb4a)
&#8594; [Проект "Модальное окно "Оплата товаров"](https://github.com/Elena-Belova/Test-Design/blob/815f3f643a1dcbdc8ffbca108a831895250febc6/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%20%D0%9C%D0%BE%D0%B4%D0%B0%D0%BB%D1%8C%D0%BD%D0%BE%D0%B5%20%D0%BE%D0%BA%D0%BD%D0%BE%20%D0%BE%D0%BF%D0%BB%D0%B0%D1%82%D1%8B.md)
![Классы эквивалентности МО Таб1](https://github.com/Elena-Belova/Test-Design/assets/148638077/479c88de-7636-4392-a2ed-5c07dcc26d17)
[Наверх](#up)
<hr>

**РЖД "Возврат электронных билетов"**
<details>
<summary>Условия</summary>
 <p><blockquote>При возврате электронного билета на поезд внутрироссийского сообщения к зачислению на банковскую карту, с которой осуществлялась оплата, причитается:<br> 
- не позднее чем за 8 часов до отправления поезда – полная стоимость проезда, состоящая из стоимости билета и стоимости плацкарты;<br>
- менее чем за 8 часов, но не позднее, чем за 2 часа до отправления поезда – стоимость билета и 50% стоимости плацкарты;<br>
- менее чем за 2 часа до отправления поезда – только стоимость билета. Стоимость плацкарты не возвращается;<br>
- при опоздании на поезд в течение 12 часов после отправления, либо вследствие болезни / несчастного случая (при наличии подтверждающих документов) в течение 5 суток с момента отправления поезда – только стоимость билета. Стоимость плацкарты не возвращается</blockquote></p>
</details>

![Классы РжД](https://github.com/Elena-Belova/Test-Design/assets/148638077/1666a39e-f149-43f9-938d-53a9bc248e4a)
<hr>

![Границы Регистрация на портале](https://github.com/Elena-Belova/Test-Design/assets/148638077/cb92d4e3-b8bd-4fa1-a5e9-bbc4cd453e24)

[Наверх](#up)

<hr>

### <a name="pairwise"></a> Pairwise
![Pairwise Фильтр Дом питомца](https://github.com/Elena-Belova/Test-Design/assets/148638077/dc8d8fe4-a092-4260-b944-4281b85820e2)
&#8594; [Проект "Создание новости".pdf](https://github.com/Elena-Belova/Test-Design/blob/26ebe674cb5e3aa0cb1d0ae1dbd096b4efb7a67e/%D0%9A%D0%BB%D0%B0%D1%81%D1%81%D1%8B%20%D0%B8%20%D0%B3%D1%80%D0%B0%D0%BD%D0%B8%D1%86%D1%8B%20(%D0%9D%D0%BE%D0%B2%D0%BE%D1%81%D1%82%D0%B8).pdf)
![Попарное Новости](https://github.com/Elena-Belova/Test-Design/assets/148638077/80a3d50c-81ae-4d21-a945-0e2a32c1dd1c)
[Наверх](#up)
<hr>

### <a name="table"></a> Таблица решений (альтернатив)
**Загрузка видеозаписи пользователем**
<details>
<summary>Условия</summary>
 <p><blockquote>1) только видео в форматах: MP4 или MOV<br>
2) размер загружаемого видео – до 10 ГБ<br>
3) разрешение может быть 1280x720 или 1920x1080</blockquote></p>
</details>

![Таблица решений1](https://github.com/Elena-Belova/Test-Design/assets/148638077/b6919396-7a0d-410c-9c91-96e59d83ff7f)

**Оформление заявки на получение кредита**
![Таблицы решений Кредит](https://github.com/Elena-Belova/Test-Design/assets/148638077/0befaa34-ed0c-4738-86f8-3eddd426cb2f)
[Наверх](#up)
<hr>

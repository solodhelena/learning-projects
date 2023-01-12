# learning-projects
Проект по А/B-тестированию

Постановка задачи
Ваша задача — провести оценку результатов A/B-теста. 
В вашем распоряжении есть датасет с действиями пользователей, техническое задание и несколько вспомогательных датасетов.

Оцените корректность проведения теста.

Проанализируйте результаты теста.

Чтобы оценить корректность проведения теста, проверьте:

пересечение тестовой аудитории с конкурирующим тестом;

совпадение теста и маркетинговых событий, другие проблемы временных границ теста.

Техническое задание

Название теста: recommender_system_test;

Группы: А (контрольная), B (новая платёжная воронка);

Дата запуска: 2020-12-07;

Дата остановки набора новых пользователей: 2020-12-21;

Дата остановки: 2021-01-04;

Аудитория: 15% новых пользователей из региона EU;

Назначение теста: тестирование изменений, связанных с внедрением улучшенной рекомендательной системы;

Ожидаемое количество участников теста: 6000.

Ожидаемый эффект: за 14 дней с момента регистрации в системе пользователи покажут улучшение каждой метрики не менее, чем на 10%:

  
конверсии в просмотр карточек товаров — событие product_page

просмотры корзины — product_cart

покупки — purchase.

Загрузите данные теста, проверьте корректность его проведения и проанализируйте полученные результаты.

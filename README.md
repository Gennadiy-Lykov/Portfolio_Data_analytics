# Портфолио: аналитик данных

## Обо мне 

Привет! Меня зовут ``{Геннадий}``, я начинающий аналитик данных.
<p>В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.
<br>

## Навыки и технологии
- Инструменты анализа данных: ``SQL``, ``Excel``: 
- Системы управления базами данных: ``PostgreSQL``

## Проекты
<p>Проект 1: Калькулятор юнит-экономики онлайн-кинотеатра</p>
<p>Задачи:<p>
<ol>
  <li>Оценить эффективность работы онлайн-кинотеатра по модели ежемесячной подписки.</li>
  <li>Посчитать юнит-экономику продукта и предложить сценарии по настройке параметров для выхода на 25% маржинальность.</li>
  <li>Собрать визуализацию, где будет показано, кто, где и в каком объеме смотрит фильмы на платформе.</li>
  <li>Собрать калькулятор юнит-экономики продукта для быстрого принятия решений.</li>
</ol>

<p>Краткое описание решения:<p>
<ol>
  <li>Определены и рассчитаны метрики поведения пользователей (просмотры, подписки).</li>
  <li>Рассчитаны бизнес-метрики (повторные оплаты, Retention, LifeTime, CAC, LTV, LTR, маржинальность.</li>
  <li>Посчитана юнит-экономика продукта и предложены сценарии по настройке параметров для выхода на 25% маржинальность.</li>
  <li>Собрана визуализация основных бизнес-показателей.</li>
  <li>Визуализированы и исследованы данные о пользователях и их поведении.</li>
</ol>

<p>Выводы (итоги):<p>
<ol>
  <li>Итог №1</li>
  <li>Итог №2</li>
</ol>
<br> 

<br> 
<p>Проект 2: Когортный анализ онлайн-кинотеатра</p>
<p>Задачи:<p>
<ol>
  <li>Оценить среднее время существования клиента (LifeTime) и среднюю прибыль с клиента (LifeTimeValue)
    после проведенеия активной рекламной компании по привлечению клиентов через социальные сети.</li>
  <li>Выяснить, есть ли зависимость между LTV и врмененем, проведенным пользователями на платформе.</li>
</ol>

<p>Краткое описание решения:<p>
  <ol>
  <li>В единую таблицу из нескольких источников-таблиц собраны данные по каждому пользователю: id, дата регистрации, время на платформе в первый месяц, флаги с активностью за каждые 30 дней, канал привлечения и стоимость привлечения пользователя.</li>
  <li>Собранные данные сведены в сводную таблицу с количеством зарегистрировавшихся на платформе пользвателей в каждый месяц с отметкой об их активности через каждые 30 дней,
суммарным и средним временем пользователей на платформе, суммарной стоимостью привлечения пользователей.</li>
  <li>Рассчитан процент оставшихся пользователей через 30, 60, 90, 120, 150, 180 дней от изначально зарегистрировавшихся пользователей по когортам.</li>
  <li>Расчитаны средние LifeTime, LifeTimeRevenue, FixedCosts, CAC, LifeTimeValue по каждой когорте.</li>
  <li>Построены графики для выявления зависимости между LTV, суммарным и среднем временем, проведенным пользователями на платформе в месяц их регистрации.</li>
</ol>

  <p>Выводы (итоги):<p>
<ol>
  <li>Итог №1</li>
  <li>Итог №2</li>
</ol>

<br>
<p>Проект 3: Моделирование изменения балансов уроков студентов в онлайн-школе с помощью SQL</p> 
<p>Задачи:<p>
<ol>
  <li>Составить SQL-запрос, который собирает данные о балансах уроков каждого студента за каждый день, а балансах уроков всех студентов за каждый день,
  об изменении количества уроков под влиянием транзакций (оплат, начислений, корректирующих списаний) и уроков (списаний с баланса по мере прохождения уроков).</li>
  <li>Проверить, всё ли в порядке с данными, составить список гипотез и вопросов по изменениям балансов уроков.</li>
</ol>

<p>Краткое описание решения:<p>
<ol>
  <li>Найдена даты первых транзакций каждого студента (начиная с этой даты будет собран баланс уроков каждого студента).</li>
  <li>Собрана таблица с уникальными датами за каждый календарный день года (дни, когда происходило изменение балансов уроков хотя бы одного студента).</li>
  <li>Найдены все даты активности каждого студента с начислением или списанием уроков после его первой транзакции.</li>
  <li>Найдены все изменения балансов, связанные с успешными транзакциями.</li>
  <li>Найден баланс студентов, который сформирован только транзакциями.</li>
  <li>Найдено количество уроков за каждый день для каждого студента.</li>
  <li>Найдена кумулятивная сумма количества пройденных уроков.</li>
  <li>Найдены балансы уроков каждого студента.</li>
  <li>В процессе анализа данных выявлено подозрительное изменение балансов у некоторых студентов (отрицательный баланс, списание по 3-4 урока в день).</li>
  <li>Найдено изменение общего количества уроков на балансах студентов.</li>
  <li>Проведена визуализация полученных данных, отмечены тенденции и закономерности в покупке и прохождении уроков.</li>
</ol>

  <p>Выводы и итоги работы по проекту:<p>
> <a href="https://drive.google.com/drive/folders/1a6LD4CgAJ0TeFYLd_eryfJD6wENd11vE?usp=sharing">Ссылка на проект</a>

## Контактная информация
- Email: GenLykovDA@yandex.ru
- LinkedIn: https://www.linkedin.com/in/username/

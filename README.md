# CI

[![Build Status](https://travis-ci.org/Aspirationtocode/ci.svg?branch=master)](https://travis-ci.org/Aspirationtocode/ci)
[![bitHound Overall Score](https://www.bithound.io/github/Aspirationtocode/ci/badges/score.svg)](https://www.bithound.io/github/Aspirationtocode/ci/badges/score.svg)

Приложение доступно здесь: http://secret-coast-74205.herokuapp.com/

### Логи ###
Heroku может передавать логи:
* приложения: На картинке те, что с app[web.1]. Показываются `console.timeEnd('render')`, `Node app is running on port 13542` и другие.
* системные: те что с `heroku[router]`.
 * `at=info` — тип сообщения
 * `method=GET` — HTTP метод
 * `path="/"` — HTTP путь
 * `host=thawing-wave-71324.herokuapp.com` — HTTP заголовок хост
 * `request_id=463f9314-a323-4f93-8a90-1f61e89fecf3` — id запроса
 * `fwd="109.252.105.212"` — заголовок X-Forwarded-For
 * `dyno=web.1` — имя контейнера, который обслуживает запрос
 * `connect=1ms` — время, затраченное за соединение с бэкендом
 * `service=5ms` — время, затраченное на передачу данных между бэкендом и клиентом
 * `status=200` — Код http ответа
 * `bytes=407` — Число переданных байтов с бэкенда на клиент

* логи api: Например, `heroku[api]: Deploy 4611dc4 by gcor.media@gmail.com`, `heroku[api]: Release v21 created by gcor.media@gmail.com`

![logs](https://psv4.vk.me/c812238/u100755398/docs/af0342829d25/Snimok_ekrana_177.png?extra=i7hXYP54NZycSnM3YcYhs7vCBE9OMkedKH0C9Pa-HWt9mWebKppy5D-GTCwoE6sSEvXyIekvb0CWVye1ZqBrwh8XRvvxFQEw-1Q5DGElhRLXum3fFrqgCjaPhQ)

### UptimeRobot ###
Сервис для мониторинга доступности ресурса по http(s), наличию ключевых слов, пингу и порту.

![uptime](https://psv4.vk.me/c812238/u100755398/docs/c0b5d3b08e56/Snimok_ekrana_178.png?extra=6Dco24DlFWUxJP914Ir9WwVHQRcXSuuFZ2kR--O_xpb91HD_DFcVfR7e8Fx0PfPZJYqX9bRw_bWk74ZPqjsLbfw4mF7ifcZu3llY7dr0ccjn1ejDKy7h4uu1bQ)

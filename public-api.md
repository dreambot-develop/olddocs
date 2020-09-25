---
description: Публичное апи у бота.
---

# Public API

{% api-method method="get" host="https://api.dreambot.ml/cmds" path="/:name" %}
{% api-method-summary %}
Получения списка команд
{% endapi-method-summary %}

{% api-method-description %}
Получить список команд бота.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name=":name" type="string" required=false %}
Имя команды
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}


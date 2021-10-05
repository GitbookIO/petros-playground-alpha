# Page 2

{% swagger method="get" path="/versions" baseUrl="https://something.com/api/v1" summary="versions" %}
{% swagger-description %}
Some description
{% endswagger-description %}

{% swagger-parameter in="path" %}

{% endswagger-parameter %}

{% swagger-response status="200: OK" description="OK" %}

{% swagger-response status="500: Internal Server Error" description="Error" %}
{% endswagger %}

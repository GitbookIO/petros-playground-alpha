# Test API method block

This is a new paragraph.

{% swagger method="get" path="/versions" baseUrl="https://api.imaging.datacommons.cancer.gov/v1" summary="versions" %}
{% swagger-description %}
Get a list of IDC data versions and per-version data model metadata, including the data sources of which each IDC data version is comprised.
{% endswagger-description %}

{% swagger-parameter in="path" %}

{% endswagger-parameter %}

{% swagger-response status="200: OK" description="A list of IDC data versions." %}

{% swagger-response status="500: Internal Server Error" description="Server error" %}
{% endswagger %}

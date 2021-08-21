---
description: This the beginning of the end!
---

# Welcome to Moud!

![Moud 23.4 in the wild](.gitbook/assets/image1b.jpg)

Hello, and welcome to the documentation for all things Moud, including but not limited to:

* Stuff
* Things
* Hints
* Tips

I wonder if I can use this for code 🤔

```typescript
const emotional_state: string = "Yup, this feels great!";

console.warn(emotional_state);
```

But like, you may be wondering about it's ability to document API endpoints:

{% api-method method="get" host="api.god.gov/" path="v3/everything" %}
{% api-method-summary %}
Get everything there ever was, or ever will be
{% endapi-method-summary %}

{% api-method-description %}
This is the fetch to fetch all fetches...
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="seedi\_id" type="string" required=false %}
If you have a Seed, this is where you add their ID to vouch for you.
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}

{% api-method-headers %}
{% api-method-parameter name="prayer\_token" type="string" required=false %}
You need to send your prayer JWT
{% endapi-method-parameter %}
{% endapi-method-headers %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```javascript
{
    "data": "crickets... 🦗🦗🦗"
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}




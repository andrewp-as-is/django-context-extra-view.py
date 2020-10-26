<!--
https://readme42.com
-->


[![](https://img.shields.io/pypi/v/django-context-extra-view.svg?maxAge=3600)](https://pypi.org/project/django-context-extra-view/)
[![](https://img.shields.io/badge/License-Unlicense-blue.svg?longCache=True)](https://unlicense.org/)
[![](https://github.com/andrewp-as-is/django-context-extra-view.py/workflows/tests42/badge.svg)](https://github.com/andrewp-as-is/django-context-extra-view.py/actions)

### Installation
```bash
$ [sudo] pip install django-context-extra-view
```

#### Examples
```python
from django_context_extra_view.views import ContextExtraMixin

class View(ContextExtraMixin,...):
    context_extra = {"my_page":{"active":True}}
```

```html
{% if my_page.active %}...{% endif %}
```

<p align="center">
    <a href="https://readme42.com/">readme42.com</a>
</p>

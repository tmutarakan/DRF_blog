# API на Django Rest Framework
____
[SPA сайт на Django Rest Framework и NuxtJS](https://stepik.org/course/82067/info)

## Описание курса

Это краш курс по созданию блога. В этом курсе вы не увидите подробный разбор каждой технологиии в отдельности. Этот курс скорее направлен на то чтобы показать как технологии интегрируются между собой.

Мы с вами сделаем:

* шаблон при помощи Bootstrap
* сайт на Django.
* API на Django Rest Framework
* Фронтенд на NuxtJS

Желательно иметь минимальные знания по Python 3, JavaScript, HTML, CSS.

### Ошибки

Для Django4:

`ImportError: cannot import name 'ugettext_lazy' from 'django.utils.translation'`

В файле `./venv/lib/python3.8/site-packages/taggit_serializer/serializers.py` замените строку 
```python
    from django.utils.translation import ugettext_lazy as _
```
на
```python
    from django.utils.translation import gettext_lazy as _
```

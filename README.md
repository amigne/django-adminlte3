# django-adminlte3
[![pypi_badge](https://badge.fury.io/py/django-adminlte3-amigne.png)](https://pypi.org/project/django-adminlte3-amigne/)
[![licence badge](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/amigne/django-adminlte3/master/LICENSE)

django-adminlte3 provides the functionality of the AdminLTE3 theme
to developers in the form of standard base templates. Optional styling for
Django's built-in admin interface is also provided.

<!--## Installation

Installation using pip:

    pip install django-adminlte3

Add to installed apps:

    INSTALLED_APPS = [
         # General use templates & template tags (should appear first)
        'adminlte3',
         # Optional: Django admin theme (must be before django.contrib.admin)
        'adminlte3_theme',

        ...
    ]

Don't forget to collect static
    
    python manage.py collectstatic -->

## Usage
The [base template] is designed to be highly customisable. Template blocks are provided to
allow you to hook in customisations as you wish

<!--### Admin Theme Usage
Install as per the above installation instructions. The django admin UI should then change as expected.-->

<!--### Documentation
Can be found at: http://django-adminlte3.readthedocs.io-->

## Versions
* v0.1.99 (March 9th, 2021)
  * Similar to release v0.1.7-alpha of `d-demirci/django-adminlte3`
    
## Credits
This project a based heavily on work by the following:
* d-demirci for [d-demirci/django-adminlte3]
* dnaextrim for [django_adminlte_x]
* beastbikes for [django-adminlte]
* adamcharnock for [django-adminlte2]


<!-- ## Screenshots
Admin Area:
* Home :![admin screenshot](https://user-images.githubusercontent.com/24219129/68544333-214e8c00-03d3-11ea-91a1-4cfb94d2b136.png)
* Model :![model screenshot](https://user-images.githubusercontent.com/24219129/68544364-77233400-03d3-11ea-97b3-350884c68f6a.png)
* Editing Model: ![model edit](https://user-images.githubusercontent.com/24219129/68544387-b6518500-03d3-11ea-9f28-27df1d996b06.png)

Site Area:
* Landing: ![site area](https://user-images.githubusercontent.com/24219129/68544298-cd43a780-03d2-11ea-8506-3abfa341a914.png) -->

[base template]: https://github.com/d-demirci/django-adminlte3/blob/master/adminlte3/templates/adminlte/base.html
[d-demirci/django-adminlte3]: https://github.com/d-demirci/django-adminlte3
[django_adminlte_x]: https://github.com/dnaextrim/django_adminlte_x
[django-adminlte]: https://github.com/beastbikes/django-adminlte/
[django-adminlte2]: https://github.com/adamcharnock/

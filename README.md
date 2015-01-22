# unnamed-future-django-translation-framework


requirements

* multi-table translation models (be re-usable app and migration friendly)
* allow any model field to be translated (not just strings)
* field level fallbacks  (will probably need de-normalisation of data)
* orderable at sql level by translated field (with fallbacks!)
* keep query counts low
* no QuerySet magic that makes stuff umnaintainable
* favor a simple api and implementation over trying to hide the fact that an application is translated

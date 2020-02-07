Changelog
=========

.. currentmodule:: flask_restx

Current
-------

- Use github actions instead of Travis (:pr:`18`)
- Register nested model wildcard fields in docs (:pr:`24`)
- Pin werkzeug version to <=0.16.1 due to incompatibilities with version 1.0.0 (:pr:`39`)

0.1.0 (2020-01-21)
------------------

- Ensure that exceptions raised in error handler, including programming errors, are logged
- Import the ABCs from 'collections.abc' instead of 'collections' by default as it is deprecated since Python3.7, and in 3.8 it will stop working. Python2.7 is still supported though.
- Fix illegal characters in JSON references to model names
- Support ``envelope`` parameter in Swagger documentation
- Fix wildcard support for fields.Nested and fields.List
- Api/Namespace individual loggers
- First flask-restx release

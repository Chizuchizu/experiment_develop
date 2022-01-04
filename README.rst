=====================
experiment_develop
=====================

How to publish in PyPI(testPyPI)
=====

::

 poetry config repositories.XXXX https://test.pypi.org/legacy/
 poetry config pypi-token.XXXX "TOKEN"
 poetry build
 poetry publish -r XXXX


参考
====

+ https://planset-study-sphinx.readthedocs.io/ja/latest/04.html
+ https://kk6.hateblo.jp/entry/2018/12/20/124151
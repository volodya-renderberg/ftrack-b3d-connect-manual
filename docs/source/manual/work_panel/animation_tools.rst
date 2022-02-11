.. _animation-tools-page:

Animation tools
===============

Функционал для работы с анимацией.

.. _animation_tools_refresh_proxy:

Refresh proxy
~~~~~~~~~~~~~

`Refresh proxy (видео) <https://youtu.be/zato5UMp3Yg>`_

* Пересоздаёт выделенный прокси с сохранением положения и анимационного экшена.
* Копирует ``child_off`` констрейн на **root** контрол и на сам прокси объект(если есть).
* При наличаи ``child_off`` констрейна:
    * функцию лучше всего производить в первом кадре, до начала анимации,
    * после выполнения функции сделать ``Set Inverse`` в самом констрейне.
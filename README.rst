=============
aiohttp-demos
=============

.. image:: https://travis-ci.org/aio-libs/aiohttp-demos.svg?branch=master
    :target: https://travis-ci.org/aio-libs/aiohttp-demos
.. image:: https://badges.gitter.im/Join%20Chat.svg
    :target: https://gitter.im/aio-libs/Lobby
    :alt: Chat on Gitter
.. image:: https://readthedocs.org/projects/aiohttp-demos/badge/?version=latest
   :target: http://aiohttp-demos.readthedocs.io/en/latest/
   :alt: Latest Read The Docs


Demos for aiohttp project.


.. contents::


URL shortener
-------------
Simple URL shortener with redis storage.

.. image:: https://raw.githubusercontent.com/aio-libs/aiohttp-demos/master/docs/_static/shorty.png


Toxic Comments Classifier 
-------------------------
UI and API for classification of offensive and toxic comments using kaggle data and simple 
logistic regression.

.. image:: https://raw.githubusercontent.com/aio-libs/aiohttp-demos/master/docs/_static/moderator.png


Twitter clone
-------------
Twitter clone with mongodb storage.

.. image:: https://raw.githubusercontent.com/aio-libs/aiohttp-demos/master/docs/_static/motortwit.png


Chat
----
Simple chat using websockets.

.. image:: https://raw.githubusercontent.com/aio-libs/aiohttp-demos/master/docs/_static/chat.png


Polls app
---------
Simple polls application with postgresql storage.

.. image:: https://raw.githubusercontent.com/aio-libs/aiohttp-demos/master/docs/_static/polls.png
    :align: center
    :width: 460px


Blog
----
Blog application with postgresql storage and redis session store.

.. image:: https://raw.githubusercontent.com/aio-libs/aiohttp-demos/master/docs/_static/blog.png
    :align: center
    :width: 460px


Contributing
------------
Things you need for local development::

    $ pip install -r requirements-dev.txt

After that - follow setup instructions from particular demo project.

To check documentation locally click the ``open file`` link from the output
of this command::

    $ make doc

To make sure everything is ok before committing::

    $ make ci


Improvement plan
----------------

Polls:

- [+] create configuration steps (venv, pip install, db initialization)
- [+] fix or recreate tests
- [~] revise `tutorial.rst`
- [+] fix urls from `aiohttp/tutorial`
- [x] setup communication channels (aio-libs gitter channel is enough)
- [~] create missing issues
- [+] add "Contributing" section
- [ ] add "What's next" section
- [ ] discuss roadmap

Ansible Role Monit
###################

|Build Status| |Ansible Galaxy| |GitHub issues| |Average time to resolve an issue| |Percentage of issues still open| |GitHub license|

:Version: 0.0.2
:Web: https://github.com/lapositiva/ansible-role-monit
:Download: https://github.com/lapositiva/ansible-role-monit
:Source: https://github.com/lapositiva/ansible-role-monit
:Keywords: ansible, monit

Ansible Role Monit

.. contents:: Table of Contents:
    :local:

How To Use
**********

Install it with the following command:

.. code:: bash

    $ ansible-galaxy install labpositiva.monit

Role Variables
==============

Here is the list of all variables and their default values:

.. list-table::
   :widths: 20 40 40
   :header-rows: 1

   * - Name
     - Default
     - Description
   * - value
     - Value
     - Value

Dependencies
============

none

Example Playbook
================

See the `examples <./examples/>`__ directory.

To run this playbook with default settings, create a basic playbook like
this:

.. code:: yaml

    - hosts: servers
      roles:
        - labpositiva.monit


Developing
**********

Add code for changes

Requirements
============

.. code-block::

   $ make setup

Setup
=====

.. code-block:: bash

  λ cat .env-template > .env
  λ make setup
  λ make build
  λ make up


Environment
===========

.. list-table::
   :widths: 50 50
   :header-rows: 1

   * - Key
     - Value
   * - Key
     - Value

Others
======

Other commands for developing are written in Makefile:

.. code-block:: bash

  λ make
    \{^_^}/ Commands
      build                Build docker container by env
      clean                clean Files compiled
      documentation        Make Documentation
      down                 remove containers docker by env
      environment          Make environment for developer
      env                  Show envs available
      install              Install with var env Dependences
      list                 List of current active services by env
      lint                 Clean files unnecesary
      test                 make test
      up                   Up application by env
      restart              Reload services
      ssh                  Connect to container
      stop                 stop containers docker by env
      setup                Install dependences initial
      verify_network       Verify network
      help                 Show help text

License
*******

MIT

Changelog
*********

Please see `CHANGELOG <CHANGELOG.md>`__ for more information what has
changed recently.

Contributing
************

Please see `CONTRIBUTING <CONTRIBUTING.md>`__ for details.

Credits
*******

Made with :heart: :coffee: and :pizza: by `labpositiva <https://github.com/labpositiva>`__.

-  `All Contributors <AUTHORS>`__

.. |Build Status| image:: https://travis-ci.org/labpositiva/ansible-role-monit.svg
   :target: https://travis-ci.org/labpositiva/ansible-role-monit
.. |Ansible Galaxy| image:: https://img.shields.io/badge/galaxy-labpositiva.monit-blue.svg
   :target: https://galaxy.ansible.com/labpositiva/monit/
.. |GitHub issues| image:: https://img.shields.io/github/issues/labpositiva/ansible-role-monit.svg
   :target: https://github.com/labpositiva/ansible-role-monit/issues
.. |Average time to resolve an issue| image:: http://isitmaintained.com/badge/resolution/labpositiva/ansible-role-monit.svg
   :target: http://isitmaintained.com/project/labpositiva/ansible-role-monit
.. |Percentage of issues still open| image:: http://isitmaintained.com/badge/open/labpositiva/ansible-role-monit.svg
   :target: http://isitmaintained.com/project/labpositiva/ansible-role-monit
.. |GitHub license| image:: https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square
   :target: LICENSE

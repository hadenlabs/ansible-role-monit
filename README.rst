Ansible Role Monit
==================

|Build Status| |Ansible Galaxy| |GitHub issues| |Average time to resolve an issue| |Percentage of issues still open| |GitHub license|

Install it with the following command:

.. code:: bash

    $ ansible-galaxy install labpositiva.monit

Requirements
------------

None

Role Variables
--------------

Here is the list of all variables and their default values:

+--------+-----------+---------------+
| Name   | Default   | Description   |
+========+===========+===============+
+--------+-----------+---------------+

Dependencies
------------

none

Example Playbook
----------------

See the `examples <./examples/>`__ directory.

To run this playbook with default settings, create a basic playbook like
this:

.. code:: yaml

    - hosts: servers
      roles:
        - labpositiva.monit

License
-------

MIT

Changelog
---------

Please see `CHANGELOG <CHANGELOG.md>`__ for more information what has
changed recently.

Contributing
------------

Please see `CONTRIBUTING <CONTRIBUTING.md>`__ for details.

Credits
-------

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

mysql
=========

Special role to install mysql and setup one database

Requirements
------------

Require **python-apt** and **python-mysqldb** library to be installed on the host

Role Variables
--------------
 - dbname - name of database to create
 - username - user which will have access to new db
 - password - password for new user

Dependencies
------------

It not depends but suggests to ansible (base) role will be used before.

Example Playbook
----------------

    - hosts: datatbase
      roles:
         - { role: mysql, dbaname: test, username: root, password: toor }

License
-------

Copyright (c) 2015 Vlad Byndych

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Author Information
------------------

If you have any questions please write [me <yojemail@gmail.com>](mailto:yojemail@gmail.com)

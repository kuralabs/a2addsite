=========
a2addsite
=========

Create a new virtual host with redirected http and a letsencrypt certificate.

Install
=======

1. Install a2addsite in your ``/usr/local/bin``.
2. Give execution permissions to it.

Requirements
============

1. Python3.
2. Apache httpd, with rewrite and ssl mods enabled.
3. letsencrypt certbot.

Usage
=====

::

   sudo a2addsite <subdomain> <domain> <admin-letsencrypt-email>

License
=======

::

   Copyright (C) 2017 KuraLabs S.R.L

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing,
   software distributed under the License is distributed on an
   "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
   KIND, either express or implied.  See the License for the
   specific language governing permissions and limitations
   under the License.

Description
===========

Shell script to allow Icinga/Nagios notification via Kannel SMS server.

Requirements
============

OS
--
* bash

Icinga/Nagios
-------------
* macros enabled  (enable_environment_macros=1)
* all contacts need a pager number
* a contact can have the following custom macros:
 _INMOKS <some sender name> (name of the SMS sender if notification type is OK)
 _INMPRS <some sender name> (name of the SMS sender if notification type is PROBLEM)

SMS server
----------
* Kannel


Configuration
==============

* SMS server configuratuion is stored in ./sms.config
* Please edit default settings on top of the script

License and Author
==================

Author:: Florian Engelmann (<engelmann@d-g-c.de>)

Copyright:: 2013 

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

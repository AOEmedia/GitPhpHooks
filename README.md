GitPhpHooks
===========

Git Hooks for PHP projects


Check php syntax on push to remote repository
---------------------------------------------

File "update".
Remote repository will reject push, if .php or .phtml file contains syntax error. Internally hook uses "php -l" command.

It is based on similar Puppet hook: http://projects.puppetlabs.com/projects/puppet/wiki/Puppet_Version_Control#Git-Update-Hook

Tested on Linux and Windows.
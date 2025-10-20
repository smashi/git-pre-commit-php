git-pre-commit-php
==================

Check whether a commit would introduce errors

Checks for

* PHP syntax errors using `php -l`
* Leftover merge conflict markers
* Twig syntax errors using `app/console twig:lint`
* Check for files with debug output (var_dump, var_export, xdewbug_break)
* Check if any of the files has `$commit = true`
* Check if somewhere the dockblock `@internal` is used
* Check for docblock syntax errors

Use this script as a pre-commit hook in Git. For automatic deployment
please put this file into `$HOME/.git_template/hooks` and `/etc/skel`.

git-pre-commit-php
==================

Check whether a commit would introduce errors

Checks for
* PHP syntax errors
* Leftover conflict markers
* Twig syntax errors

Use this script as a pre-commit hook in Git. For automatic deployment
please put this file into $HOME/.git_template/hooks and /etc/skel.

Author: Hakan Kuecuekyilamz, <hakan at lisas dot de>, 2011-10-21.

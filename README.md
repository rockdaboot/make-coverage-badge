A shell script that creates a coverage badge.svg known from Gitlab/Github.

There are no additional dependencies. Feel free to use/amend in your projects.

Usage
-----

  ./make-coverage-badge [title [percentage]]

Example
-------

  ./make-coverage-badge "fuzz-coverage" "92.30%"

This creates a badge.svg like this one:
[![fuzz coverage status](https://libidn.gitlab.io/libidn2/fuzz-coverage/badge.svg)](https://libidn.gitlab.io/libidn2/fuzz-coverage)

Research B demo
---------------

Web application that parses and interprets a log file generated by UsaProxy.

Features three experiments:
- Colors
- Images
- Cards (under construction)

Requires a UsaProxy log.txt present in the root directory.

*** UsaProxy contains a bug: it doesn't take into account that month in JavaScript's Date() is zero-based, so e.g. December shows as 00 in the next year. This application assumes this bug is fixed ***

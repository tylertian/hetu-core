+++

title = "SET SESSION"
+++

SET SESSION
===========

Synopsis
--------

``` sql
SET SESSION name = expression
SET SESSION catalog.name = expression
```

Description
-----------

Set a session property value.

Examples
--------

``` sql
SET SESSION optimize_hash_generation = true;
SET SESSION hive.optimized_reader_enabled = true;
```

See Also
--------

[reset-session](./reset-session.html), [show-session](./show-session.html)

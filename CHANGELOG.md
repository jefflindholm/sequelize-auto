# Changelog

All visible changes to this project will be documented in this file as of version `0.4.22`

## Master

### Fixes

* The defaultValue is now escape'd
* Boolean/Bit columns are now fixed for MSSQL

## [0.4.25] - 2017-03-20

### Added

* Adds `unique` support for `postgres`, `mysql`, and `mariadb`.

### Fixes

* Fixes `foreign key` and `unique` columns.

## [0.4.24] - 2017-03-20

### Added

* Adds support for `UNSIGNED` and `ZEROFILL` MySQL columns.

## [0.4.23] - 2017-03-20

### Fixed

* Adds schema support for `postgres` databases.
* Directory output is now fixed for commands containing a config file as well.
* Default port number has been added for `postgres`.
* Mssql should now properly identify `auto increment` and `foreign key` columns.

## [0.4.22] - 2017-03-20

### Fixed

* Sqlite will now properly set the `storage` option to the `database` value if no `storage` option is set.

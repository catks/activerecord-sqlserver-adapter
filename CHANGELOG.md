## v5.0.1

#### Changed

* Set `tds_version` fallback to `7.3`.

#### Fixed

* Support 2014, 2012 drop table statement.


## v5.0.0

#### Added

* Support for `supports_datetime_with_precision`.
* Support for `unprepared_statement` blocks on the connection.

#### Changed

* Major refactoring of all type objects. Especially time types.

#### Deprecated

* Support for a handful of standard Rails deprecations in 5-0-stable suite.

#### Removed

* ODBC connection mode. Not been maintained since Rails 4.0.
* View table name detection in `with_identity_insert_enabled` method for fixtures. Perf hit.

#### Fixed

* Do not output column collation in schema when same as database.

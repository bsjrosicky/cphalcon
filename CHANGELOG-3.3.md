# [3.3.0](https://github.com/phalcon/cphalcon/releases/tag/v3.3.0) (2017-XX-XX)
- Added support for `switch/case` syntax to the Volt Engine [#13107](https://github.com/phalcon/cphalcon/issues/13107)
- Added `Phalcon\Logger\Adapter\Blackhole` [#13074](https://github.com/phalcon/cphalcon/issues/13074)
- Added `Phalcon\Http\Request::hasHeader` to check if certain header exists
- Fixed `Phalcon\Mvc\Model\Query\Builder::getPhql` to correct generate PHQL in argument's array when using order DESC or ASC [#11827](https://github.com/phalcon/cphalcon/issues/11827)
- Fixed `Phalcon\Db\Dialect\Postgresql::createTable` to produce valid SQL for table definition with `BOOLEAN` types [#13132](https://github.com/phalcon/cphalcon/issues/13132)
- Fixed `Phalcon\Db\Dialect\Postgresql::_castDefault` to return correct value for `BOOLEAN` type [#13132](https://github.com/phalcon/cphalcon/issues/13132), [phalcon/phalcon-devtools#1118](https://github.com/phalcon/phalcon-devtools/issues/1118)
- Fixed `Phalcon\Mvc\Model::_doLowInsert` to correct save snapshot on creation/save identityless models [#13166](https://github.com/phalcon/cphalcon/issues/13166)
- Fixed `Phalcon\Mvc\Model::_doLowUpdate` to correctly work with `Phalcon\Db\RawValue` [#13170](https://github.com/phalcon/cphalcon/issues/13170)
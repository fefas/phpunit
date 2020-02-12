# Changes in PHPUnit 9.1

All notable changes of the PHPUnit 9.1 release series are documented in this file using the [Keep a CHANGELOG](https://keepachangelog.com/) principles.

## [9.1.0] - 2020-04-10

### Added

* Implemented [#4061](https://github.com/sebastianbergmann/phpunit/issues/4061): Implement `assertIsNotReadable()` as alternative for `assertNotIsReadable()` with a more readable name
* Implemented [#4064](https://github.com/sebastianbergmann/phpunit/issues/4064): Implement `assertIsNotWritable()` as alternative for `assertNotIsWritable()` with a more readable name
* Implemented [#4067](https://github.com/sebastianbergmann/phpunit/issues/4067): Implement `assertDirectoryDoesNotExist()` as alternative for `assertDirectoryNotExists()` with a more readable name
* Implemented [#4070](https://github.com/sebastianbergmann/phpunit/issues/4070): Implement `assertDirectoryIsNotReadable()` as alternative for `assertDirectoryNotIsReadable()` with a more readable name
* Implemented [#4073](https://github.com/sebastianbergmann/phpunit/issues/4073): Implement `assertDirectoryIsNotWritable()` as alternative for `assertDirectoryNotIsWritable()` with a more readable name
* Implemented [#4076](https://github.com/sebastianbergmann/phpunit/issues/4076): Implement `assertFileDoesNotExist()` as alternative for `assertFileNotExists()` with a more readable name
* Implemented [#4079](https://github.com/sebastianbergmann/phpunit/issues/4079): Implement `assertFileIsNotReadable()` as alternative for `assertFileNotIsReadable()` with a more readable name
* Implemented [#4082](https://github.com/sebastianbergmann/phpunit/issues/4082): Implement `assertFileIsNotWritable()` as alternative for `assertFileNotIsWritable()` with a more readable name
* Implemented [#4085](https://github.com/sebastianbergmann/phpunit/issues/4085): Implement `assertMatchesRegularExpression()` as alternative for `assertRegExp()` with a more readable name
* Implemented [#4088](https://github.com/sebastianbergmann/phpunit/issues/4088): Implement `assertDoesNotMatchRegularExpression()` as alternative for `assertNotRegExp()` with a more readable name

### Changed

* Implemented [#4039](https://github.com/sebastianbergmann/phpunit/issues/4039): Deprecate custom test suite loader
* Implemented [#4062](https://github.com/sebastianbergmann/phpunit/issues/4062): Deprecate `assertNotIsReadable()`
* Implemented [#4065](https://github.com/sebastianbergmann/phpunit/issues/4065): Deprecate `assertNotIsWritable()`
* Implemented [#4068](https://github.com/sebastianbergmann/phpunit/issues/4068): Deprecate `assertDirectoryNotExists()`
* Implemented [#4071](https://github.com/sebastianbergmann/phpunit/issues/4071): Deprecate `assertDirectoryNotIsReadable()`

[9.1.0]: https://github.com/sebastianbergmann/phpunit/compare/9.0...master
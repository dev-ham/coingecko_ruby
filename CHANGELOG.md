## 0.2.0 - 16-05-2021

### [Added]

#### Modules
 * Added `Exchanges` module to fetch exchange data.

#### Tests
 * Added `vcr` and `webmock` gems for testing.
 * Added basic unit tests for every client module.
 * Added setting for `vcr` episodes to use `:new_episodes` as the default `:record` mode.

#### Docs
 * Added `YARD` documentation (params, return values, usage, and response objects) for every method in client modules.

### [Changes]
 * Changed `get` method in `connection.rb` to build querystrings from the `options` object.
 * Changed method definitions to accept an `options` parameter to define options when making requests.

## 0.1.0 - 09-05-2021

 * Initial gem release!
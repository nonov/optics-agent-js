# Change log

### 1.1.0
* Fix an issue that introduced promises that would throw but the app could not handle.
* Support for Koa.
* Dependency updates.
  TypeScript users might have to migrate from `typed-graphql` to `@types/graphql`
  due to https://github.com/apollographql/graphql-tools/pull/249
* `shutdownGracefully` option (default true): send one last stats report on process.exit() and SIGINT.

### 1.0.4
* Dependency updates.

### 1.0.3
* Support `HTTPS_PROXY` and a proxyUrl option.

### 1.0.2
* Fix encoding issue for query variables in traces.

### 1.0.1
* Fix issue where fragments were not properly reported in stats.

### 1.0.0

Initial production release
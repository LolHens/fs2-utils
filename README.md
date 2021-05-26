# fs2-utils

[![Test Workflow](https://github.com/LolHens/fs2-utils/workflows/test/badge.svg)](https://github.com/LolHens/fs2-utils/actions?query=workflow%3Atest)
[![Release Notes](https://img.shields.io/github/release/LolHens/fs2-utils.svg?maxAge=3600)](https://github.com/LolHens/fs2-utils/releases/latest)
[![Maven Central](https://img.shields.io/maven-central/v/de.lolhens/fs2-utils_2.13)](https://search.maven.org/artifact/de.lolhens/fs2-utils_2.13)
[![Apache License 2.0](https://img.shields.io/github/license/LolHens/fs2-utils.svg?maxAge=3600)](https://www.apache.org/licenses/LICENSE-2.0)

This project provides several utility methods for [fs2](https://github.com/typelevel/fs2).

## Usage

### build.sbt

```sbt
// use this snippet for fs2 3 and the JVM
libraryDependencies += "de.lolhens" %% "fs2-utils" % "0.2.0"

libraryDependencies += "de.lolhens" %% "fs2-io-utils" % "0.2.0"

// use this snippet for fs2 3 and JS, or cross-building
libraryDependencies += "de.lolhens" %%% "fs2-utils" % "0.2.0"
```

## License

This project uses the Apache 2.0 License. See the file called LICENSE.

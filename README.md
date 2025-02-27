Cassandra Plugins for Akka Persistence
======================================

Replicated [Akka Persistence](https://doc.akka.io/docs/akka/current/scala/persistence.html) journal and snapshot store backed by [Apache Cassandra](https://cassandra.apache.org/).

For questions please use the [discuss.akka.io](https://discuss.lightbend.com/c/akka/) or [![gitter: akka/akka](https://img.shields.io/badge/gitter%3A-akka%2Fakka-blue.svg?style=flat-square)](https://gitter.im/akka/akka).

Implementation in the `main` branch is currently `1.0.x` release.


## Documentation

The current version's documentation is available at https://doc.akka.io/docs/akka-persistence-cassandra/current/.

[Snapshot documentation](https://doc.akka.io/docs/akka-persistence-cassandra/snapshot/) and [snapshot artifacts](https://oss.sonatype.org/content/repositories/snapshots/com/typesafe/akka/akka-persistence-cassandra_2.12/) are published for every successful `main` branch build.

For versions earlier than 1.0.0, check this README.md file for the corresponding release tag.


## History

This [Apache Cassandra](https://cassandra.apache.org/) plugin to Akka Persistence was initiated [originally](https://github.com/krasserm/akka-persistence-cassandra) by Martin Krasser, [@krasserm](https://github.com/krasserm) in 2014.

It moved to the [Akka](https://github.com/akka/) organisation in 2016 and the first release after that move was 0.7 in January 2016.

## Branches and versions

There are three branches of development:

* 1.0 -> `main` - current active development and stable 1.0.x patch releases
* 0.80+ (currently 0.100) -> `release-0.x`  - removed use of Cassandra Materialized Views after they were marked as not to be used in production. 
* 0.50+ (currently 0.62) -> `release-0.50`- first release under this organisation, previously under krasserm. No planned releases for this version.

## License

Akka Persistence Cassandra is licensed under the Business Source License 1.1, see LICENSE.


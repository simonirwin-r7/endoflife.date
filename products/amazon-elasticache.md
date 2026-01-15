---
title: Amazon ElastiCache
addedAt: 2026-01-15
category: service
tags: amazon database
iconSlug: amazonelasticache
permalink: /amazon-elasticache
alternate_urls:
  - /elasticache
releasePolicyLink: https://docs.aws.amazon.com/AmazonElastiCache/latest/dg/engine-versions.html
eoasColumn: Standard Support
eolColumn: Extended Support

customFields:
  - name: engineType
    display: after-release-column
    label: Engine
    description: The underlying cache engine type (Redis, Memcached, or Valkey)

releases:
  - releaseCycle: "8.2"
    releaseDate: 2025-11-01
    eoas: false
    eol: false
    latest: "8.2"
    latestReleaseDate: 2025-11-01
    engineType: valkey

  - releaseCycle: "8.1"
    releaseDate: 2025-09-01
    eoas: false
    eol: false
    latest: "8.1"
    latestReleaseDate: 2025-09-01
    engineType: valkey

  - releaseCycle: "8.0"
    releaseDate: 2025-06-01
    eoas: false
    eol: false
    latest: "8.0"
    latestReleaseDate: 2025-06-01
    engineType: valkey

  - releaseCycle: "7.2.6"
    releaseDate: 2024-11-14
    eoas: false
    eol: false
    latest: "7.2.6"
    latestReleaseDate: 2024-11-14
    engineType: valkey

  - releaseCycle: "1.6.22"
    releaseDate: 2024-03-15
    eoas: false
    eol: false
    latest: "1.6.22"
    latestReleaseDate: 2024-03-15
    engineType: memcached

  - releaseCycle: "7.1"
    releaseDate: 2023-12-01
    eoas: false
    eol: false
    latest: "7.1"
    latestReleaseDate: 2023-12-01
    engineType: redis

  - releaseCycle: "1.6.17"
    releaseDate: 2023-07-01
    eoas: false
    eol: false
    latest: "1.6.17"
    latestReleaseDate: 2023-07-01
    engineType: memcached

  - releaseCycle: "7.0"
    releaseDate: 2022-10-27
    eoas: false
    eol: false
    latest: "7.0"
    latestReleaseDate: 2022-10-27
    engineType: redis

  - releaseCycle: "1.6.12"
    releaseDate: 2022-08-01
    eoas: false
    eol: false
    latest: "1.6.12"
    latestReleaseDate: 2022-08-01
    engineType: memcached

  - releaseCycle: "1.6.6"
    releaseDate: 2021-07-08
    eoas: false
    eol: false
    latest: "1.6.6"
    latestReleaseDate: 2021-07-08
    engineType: memcached

  - releaseCycle: "6.0"
    releaseDate: 2020-05-01
    eoas: 2027-01-31
    eol: 2030-01-31
    latest: "6.0.2"
    latestReleaseDate: 2020-06-15
    engineType: redis

  - releaseCycle: "5.0"
    releaseDate: 2019-04-01
    eoas: 2026-01-31
    eol: 2029-01-31
    latest: "5.0.6"
    latestReleaseDate: 2019-10-10
    engineType: redis

  - releaseCycle: "1.5.16"
    releaseDate: 2018-05-10
    eoas: false
    eol: false
    latest: "1.5.16"
    latestReleaseDate: 2018-05-10
    engineType: memcached

  - releaseCycle: "1.5.10"
    releaseDate: 2017-11-01
    eoas: false
    eol: false
    latest: "1.5.10"
    latestReleaseDate: 2017-11-01
    engineType: memcached

  - releaseCycle: "4.0"
    releaseDate: 2017-07-14
    eoas: 2026-01-31
    eol: 2029-01-31
    latest: "4.0.10"
    latestReleaseDate: 2018-01-17
    engineType: redis

  - releaseCycle: "3.2"
    releaseDate: 2016-10-12
    eoas: 2023-07-31
    eol: 2023-07-31
    latest: "3.2.10"
    latestReleaseDate: 2016-10-12
    engineType: redis

  - releaseCycle: "1.4.34"
    releaseDate: 2016-08-01
    eoas: false
    eol: false
    latest: "1.4.34"
    latestReleaseDate: 2016-08-01
    engineType: memcached

  - releaseCycle: "1.4.33"
    releaseDate: 2016-03-01
    eoas: false
    eol: false
    latest: "1.4.33"
    latestReleaseDate: 2016-03-01
    engineType: memcached

  - releaseCycle: "1.4.24"
    releaseDate: 2015-04-01
    eoas: false
    eol: false
    latest: "1.4.24"
    latestReleaseDate: 2015-04-01
    engineType: memcached

  - releaseCycle: "2.8"
    releaseDate: 2014-03-13
    eoas: 2023-01-13
    eol: 2023-01-13
    latest: "2.8.24"
    latestReleaseDate: 2014-03-13
    engineType: redis

  - releaseCycle: "2.6"
    releaseDate: 2013-09-04
    eoas: 2023-01-13
    eol: 2023-01-13
    latest: "2.6.13"
    latestReleaseDate: 2013-09-04
    engineType: redis

  - releaseCycle: "1.4.14"
    releaseDate: 2013-09-01
    eoas: false
    eol: false
    latest: "1.4.14"
    latestReleaseDate: 2013-09-01
    engineType: memcached

  - releaseCycle: "1.4.5"
    releaseDate: 2010-04-03
    eoas: false
    eol: false
    latest: "1.4.5"
    latestReleaseDate: 2010-04-03
    engineType: memcached

---

> [Amazon ElastiCache](https://aws.amazon.com/elasticache/) is a fully managed, in-memory caching service supporting Redis, Memcached, and Valkey engines.

Amazon ElastiCache provides support for multiple versions of Redis, Memcached, and Valkey. AWS manages patching, upgrades, and maintenance of the cache engines. Each engine version receives standard support followed by extended support before end of life.

AWS typically provides several years of standard support from the release date, followed by extended support. Extended support may include additional charges. AWS recommends upgrading to newer versions before entering extended support to benefit from the latest features, performance improvements, and security patches without additional costs.

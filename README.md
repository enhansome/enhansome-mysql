# awesome-mysql with stars

A curated list of awesome MySQL free and opensource software, libraries and resources. [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 501,905 | 🐛 105 | 📅 2026-08-21

This list accepts and encourages pull requests. See [CONTRIBUTING](https://github.com/shlomi-noach/awesome-mysql/blob/master/CONTRIBUTING.md) ⭐ 2,611 | 🐛 18 | 🌐 Python | 📅 2026-08-17

### Contents

* [Awesome MySQL](#awesome-mysql)
  * [Analysis](#analysis)
  * [Backup](#backup)
  * [Benchmarking](#benchmarking)
  * [Binlog Replication](#binlog-replication)
  * [ChatOps](#chatops)
  * [Configuration](#configuration)
  * [Connectors](#connectors)
  * [Deployment](#deployment)
  * [Development](#development)
  * [GUI](#gui)
  * [HA](#ha)
  * [MCP](#mcp)
  * [Proxy](#proxy)
  * [Replication](#replication)
  * [Schema](#schema)
  * [Security](#security)
  * [Server](#server)
  * [Sharding](#sharding)
  * [Toolkits](#toolkits)

* [Resources](#resources)
  * [E-Books](#e-books)

## Analysis

*Performance, structure & data analysis tools*

* [Prometheus](https://github.com/prometheus/prometheus) ⭐ 65,932 | 🐛 882 | 🌐 Go | 📅 2026-08-31/[mysqld\_exporter](https://github.com/prometheus/mysqld_exporter) ⭐ 2,462 | 🐛 175 | 🌐 Go | 📅 2026-08-18 - Time series database for real-time monitoring and alerting.
* [MySQLTuner-perl](https://github.com/major/MySQLTuner-perl) ⭐ 9,476 | 🐛 7 | 🌐 Perl | 📅 2026-08-31 - A script that allows you to review a MySQL installation quickly and make adjustments to increase performance and stability.
* [innodb-ruby](https://github.com/jeremycole/innodb_ruby) ⭐ 1,800 | 🐛 21 | 🌐 Ruby | 📅 2026-04-28 - A parser for InnoDB file formats, in Ruby.
* [sql-tap](https://github.com/mickamy/sql-tap) ⭐ 1,586 | 🐛 0 | 🌐 Go | 📅 2026-07-07 - Real-time SQL traffic viewer.
* [Anemometer](https://github.com/box/Anemometer) ⭐ 1,392 | 🐛 60 | 🌐 JavaScript | 📅 2021-12-08 - Box SQL slow query monitor.
* [Dolphie](https://github.com/charles-001/dolphie) ⭐ 1,195 | 🐛 1 | 🌐 Python | 📅 2026-08-24 - a modern terminal tool for real-time analytics into MySQL/MariaDB & ProxySQL
* [innotop](https://github.com/innotop/innotop) ⭐ 803 | 🐛 27 | 🌐 Perl | 📅 2026-05-22 - a 'top' clone for MySQL with many features and flexibility.
* [pstop](https://github.com/sjmudd/ps-top) ⭐ 211 | 🐛 3 | 🌐 Go | 📅 2026-07-10 - a top-like program for MySQL, collecting, aggregating and displaying information from performance\_schema.
* [mysql-statsd](https://github.com/db-art/mysql-statsd) ⭐ 102 | 🐛 6 | 🌐 Python | 📅 2021-04-20 - A Python daemon to collect information from MySQL and send it via StatsD to Graphite.
* [MySQL Explain Analyzer](https://github.com/Preetam/explain-analyzer) ⭐ 98 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-12 - A web-based analyzer of `EXPLAIN FORMAT=JSON` output, providing comments, scalability analysis and permalinks for saved samples.
* [ReliaDB EXPLAIN Analyzer](https://github.com/Mughees52/mysql-explain-analyzer) ⭐ 6 | 🐛 1 | 🌐 TypeScript | 📅 2026-04-14 - a browser-based MySQL and MariaDB EXPLAIN visualizer with issue detection, index recommendations, and query rewrites. 100% client-side.
* [Wireshark](https://gitlab.com/wireshark/wireshark/) - a protocol analyzer that can decode the MySQL protocol.

## Backup

*Backup/restore/recovery tools*

* [Dumpling](https://github.com/pingcap/tidb/tree/master/dumpling) ⭐ 40,478 | 🐛 6,861 | 🌐 Go | 📅 2026-09-01 - Logical, parallel backup/dumper tool for MySQL/TiDB written in GoLang - support csv format output and integrated as library
* [Databasus](https://github.com/databasus/databasus) ⭐ 8,395 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-31 - tool for scheduled MySQL backups via web UI with external storages (local, S3, FTP, Google Drive, etc.), notifications (webhook, Discord, Slack, etc.) and team management.
* [MyDumper](https://github.com/mydumper/mydumper) ⭐ 3,217 | 🐛 60 | 🌐 C | 📅 2026-08-31 - Logical, parallel backup/dumper tool for MySQL
* [Portabase](https://github.com/Portabase/portabase) ⭐ 1,676 | 🐛 35 | 🌐 TypeScript | 📅 2026-08-27 - Agent-based platform for MySQL backups and restores with decentralized execution and centralized orchestration.
* [Percona Xtrabackup](https://github.com/percona/percona-xtrabackup) ⭐ 1,551 | 🐛 24 | 🌐 C++ | 📅 2026-08-24 - an open-source hot backup utility for MySQL - based servers that doesn’t lock your database during the backup.

## Benchmarking

*Tools to stress your servers*

* [Sysbench](https://github.com/akopytov/sysbench) ⭐ 6,784 | 🐛 217 | 🌐 C | 📅 2025-03-09 - a modular, cross-platform and multi-threaded benchmark tool.
* [HammerDB](https://github.com/TPC-Council/HammerDB) ⭐ 780 | 🐛 15 | 🌐 Tcl | 📅 2026-08-25 - An open-source database benchmark for MySQL/MariaDB and other open source and commercial databases.
* [TPCC-MySQL](https://github.com/Percona-Lab/tpcc-mysql) ⚠️ Archived (archived) - A port of the popular [TPCC](http://www.tpc.org/tpcc/) benchmark for MySQL.
* [go-tpc](https://github.com/pingcap/go-tpc) ⭐ 208 | 🐛 26 | 🌐 Go | 📅 2026-01-13 - A golang port of [TPCC](http://www.tpc.org/tpcc/) and [TPCH](http://www.tpc.org/tpch/) benchmark for MySQL.
* [iibench-mysql](https://github.com/tmcallaghan/iibench-mysql) ⭐ 47 | 🐛 3 | 🌐 Java | 📅 2017-12-04 - Java based version of the Index Insertion Benchmark for MySQL/Percona/MariaDB.

## Binlog-Replication

* [Kingbus](https://github.com/flike/kingbus) ⭐ 892 | 🐛 12 | 🌐 Go | 📅 2021-03-11 - A distributed MySQL binlog storage system built on Raft
* [DM](https://github.com/pingcap/tiflow) ⭐ 464 | 🐛 972 | 🌐 Go | 📅 2026-08-28 - A High-Availability data migration platform which supports migrating data from MySQL/MariaDB to TiDB and merging shard tables
* [mysql-ripple](https://github.com/google/mysql-ripple) ⚠️ Archived (archived) - Ripple, a server that can serve as a middleman in MySQL replication

## ChatOps

*Scripts integrated into chat rooms*

* [Hubot MySQL ChatOps](https://github.com/samlambert/hubot-mysql-chatops) ⭐ 89 | 🐛 0 | 🌐 CoffeeScript | 📅 2014-03-09

## Configuration

*MySQL sample configuration and advisors*

* [mysql-compatibility-config](https://github.com/morgo/mysql-compatibility-config) ⭐ 94 | 🐛 1 | 🌐 Shell | 📅 2017-03-02 - make MySQL configuration behave more like newer (or older) releases of MySQL.

## Connectors

*MySQL connectors for various programming languages*

* [node-mysql](https://github.com/mysqljs/mysql) ⭐ 18,617 | 🐛 175 | 🌐 JavaScript | 📅 2024-06-25 - A pure Nodejs Javascript client implementing the MySQL protocol.
* [go-sql-driver](https://github.com/go-sql-driver/mysql) ⭐ 15,273 | 🐛 69 | 🌐 Go | 📅 2026-09-01 - a lightweight and fast MySQL-Driver for Go's (golang) database/sql package.
* [PyMySQL](https://github.com/PyMySQL/PyMySQL) ⭐ 7,844 | 🐛 16 | 🌐 Python | 📅 2026-08-18 - MySQL database connector for Python.
* [mysqlclient-python](https://github.com/PyMySQL/mysqlclient) ⭐ 2,536 | 🐛 4 | 🌐 Python | 📅 2026-08-22 - MySQL database connector for Python.
* [Ruby Mysql2 gem](https://github.com/brianmario/mysql2) ⭐ 2,278 | 🐛 69 | 🌐 Ruby | 📅 2026-08-21 - MySQL driver for Ruby and Rails projects.
* [MySQL Connector/J](https://github.com/mysql/mysql-connector-j) ⭐ 1,014 | 🐛 1 | 🌐 Java | 📅 2026-07-29 - a standardized database driver for the Java platforms and development.
* [MySQL Connector/Python](https://github.com/mysql/mysql-connector-python) ⭐ 957 | 🐛 1 | 🌐 Python | 📅 2026-07-29 - a standardized database driver for Python platforms and development.
* [MySQL Connector/C++](https://github.com/mysql/mysql-connector-cpp) ⭐ 709 | 🐛 0 | 🌐 C++ | 📅 2026-07-29 - Official C/C++ driver for MySQL.
* [wtx](https://github.com/c410-f3r/wtx) ⭐ 400 | 🐛 6 | 🌐 Rust | 📅 2026-08-30 - Client for MySQL/MariaDB/Percona written in Rust
* [MariaDB Connector/J](https://github.com/mariadb-corporation/mariadb-connector-j) ⭐ 362 | 🐛 4 | 🌐 Java | 📅 2026-07-29 - LGPL-licensed MariaDB Client Library for Java Applications.
* [MySQL Connector/NET](https://github.com/mysql/mysql-connector-net) ⭐ 333 | 🐛 3 | 🌐 C# | 📅 2026-06-26 - a standardized database driver for .Net platforms and development.
* [MySQL Connector/Node.js](https://github.com/mysql/mysql-connector-nodejs) ⭐ 160 | 🐛 0 | 🌐 JavaScript | 📅 2024-10-22 - Official Node.js driver for MySQL.
* [ballerinax/mysql](https://github.com/ballerina-platform/module-ballerinax-mysql) ⭐ 111 | 🐛 5 | 🌐 Ballerina | 📅 2026-07-31 - Official Ballerina connector for MySQL.
* [MyZql](https://github.com/speed2exe/myzql) ⭐ 74 | 🐛 4 | 🌐 Zig | 📅 2026-08-19 - MySQL and MariaDB driver in native Zig.
* [DBD::mysql](https://github.com/perl5-dbi/DBD-mysql) ⭐ 67 | 🐛 75 | 🌐 Perl | 📅 2026-07-21 - MySQL driver for the Perl5 Database Interface.
* [DBD::MariaDB](https://github.com/perl5-dbi/DBD-MariaDB) ⭐ 41 | 🐛 20 | 🌐 Perl | 📅 2026-07-29 - MariaDB and MySQL driver for the Perl5 Database Interface.
* [libAttachSQL](https://github.com/libattachsql/libattachsql) ⭐ 29 | 🐛 24 | 🌐 C++ | 📅 2020-08-28 - libAttachSQL is a lightweight, non-blocking C API for MySQL servers.
* [mex-mariadb](https://github.com/markuman/mex-mariadb) ⭐ 2 | 🐛 1 | 🌐 C | 📅 2022-11-04 - MIT licensed MariaDB/MySQL Client Library for GNU Octave and Matlab.
* [MySQL C API](https://dev.mysql.com/downloads/c-api/) - Official C driver for MySQL.
* [PHP mysqlnd](https://www.php.net/manual/en/book.mysqlnd.php) - MySQL native driver for PHP.

## Deployment

*MySQL deployment tools*

* [MariaDB4j](https://github.com/MariaDB4j/MariaDB4j) ⭐ 899 | 🐛 16 | 🌐 Java | 📅 2026-07-14 - A Java launcher to run MariaDB without installation or external dependencies.

## Development

*Tools to support MySQL-related development*

* [Flywaydb](https://github.com/flyway/flyway) ⭐ 10,051 | 🐛 256 | 🌐 Java | 📅 2026-08-26 - Database migrations; Evolve your database schema easily and reliably across all your instances
* [Liquibase](https://github.com/liquibase/liquibase) ⭐ 5,601 | 🐛 254 | 🌐 Java | 📅 2026-09-01 - Source control for your database
* [Test database](https://github.com/datacharmer/test_db) ⭐ 4,437 | 🐛 2 | 🌐 PLpgSQL | 📅 2026-04-10 - A sample MySQL database with an integrated test suite, used to test applications and servers
* [SQLE](https://github.com/actiontech/sqle/blob/main/README_en.md) ⭐ 1,500 | 🐛 197 | 🌐 Go | 📅 2026-08-26 - SQLE is a SQL audit platform for DBA or developer
* [Skeema](https://github.com/skeema/skeema) ⭐ 1,379 | 🐛 15 | 🌐 Go | 📅 2026-08-31 - Declarative pure-SQL schema management system for MySQL and MariaDB, with support for sharding and external online schema change tools
* [Shift](https://github.com/square/shift) ⭐ 737 | 🐛 29 | 🌐 Ruby | 📅 2025-04-01 - An application that helps you run schema migrations on MySQL databases
* [dbsafe](https://github.com/nethalo/dbsafe) ⭐ 12 | 🐛 1 | 🌐 Go | 📅 2026-07-16 - Pre-execution safety analysis for MySQL DDL/DML operations
* [cover\_me](https://github.com/verizonconnect/cover_me) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-07-07 - code coverage tool for mysql stored procedures and functions

## GUI

*GUI frontends & applications*

* [DBeaver](https://github.com/dbeaver/dbeaver/) ⭐ 51,613 | 🐛 3,379 | 🌐 Java | 📅 2026-09-01 - A cross-platform SQL and NoSQL database client.
* [ILLA Cloud](https://github.com/illacloud/illa-builder) ⭐ 12,311 | 🐛 43 | 🌐 TypeScript | 📅 2026-05-27 - Low-code internal tool builder integrated with Mysql, can be used as GUI for Mysql.
* [mycli](https://github.com/dbcli/mycli) ⭐ 11,972 | 🐛 1 | 🌐 Python | 📅 2026-09-01 - A Terminal Client for MySQL with AutoCompletion and Syntax Highlighting.
* [phpMyAdmin](https://github.com/phpmyadmin/phpmyadmin) ⭐ 7,922 | 🐛 941 | 🌐 PHP | 📅 2026-09-01 - a free software tool written in PHP, intended to handle the administration of MySQL over the Web.
* [Adminer](https://github.com/vrana/adminer/) ⭐ 7,842 | 🐛 6 | 🌐 PHP | 📅 2026-08-31 - Database management in a single PHP file.
* [Sequel Ace](https://github.com/Sequel-Ace/Sequel-Ace) ⭐ 7,523 | 🐛 180 | 🌐 Objective-C | 📅 2026-09-01 - a Mac database management application for working with MySQL databases.
* [HeidiSQL](https://github.com/HeidiSQL/HeidiSQL) ⭐ 6,234 | 🐛 318 | 🌐 Pascal | 📅 2026-08-27 - MySQL GUI frontend for Windows.
* [TablePro](https://github.com/TableProApp/TablePro) ⭐ 5,723 | 🐛 83 | 🌐 Swift | 📅 2026-09-01 - Native macOS client for MySQL and many other databases with inline editing, SSH tunneling, and AI assistant. Free and open-source.
* [OmniDB: Web tool for database management](https://github.com/OmniDB/OmniDB) ⭐ 3,285 | 🐛 330 | 🌐 JavaScript | 📅 2023-02-01
* [pspg](https://github.com/okbob/pspg) ⭐ 2,730 | 🐛 0 | 🌐 C | 📅 2026-08-30 - provides a pager with enhanced visualization and navigation for tabular data. Originally implemented for PostgreSQL, but also supports MySQL.
* [SQLyog Community edition](https://github.com/webyog/sqlyog-community) ⭐ 2,343 | 🐛 694 | 🌐 C++ | 📅 2026-08-25 - SQLyog Community edition. For Windows, works fine under wine in Mac and Linux
* [Percona Monitoring and Management](https://github.com/percona/pmm) ⭐ 1,094 | 🐛 229 | 🌐 Go | 📅 2026-09-01 - An open-source platform for managing and monitoring MySQL performance.
* [MySQL Workbench](https://github.com/mysql/mysql-workbench) ⭐ 997 | 🐛 3 | 🌐 C++ | 📅 2026-04-23 - provides DBAs and developers an integrated tools environment for database design & modeling; SQL devleopment; database administration.
* [StackRender](https://github.com/stackrender/stackrender) ⭐ 534 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-05 - Free and open-source database schema design and SQL migration generator for MySQL.
* [LibreDB Studio](https://github.com/libredb/libredb-studio) ⭐ 391 | 🐛 8 | 🌐 TypeScript | 📅 2026-09-01 - Browser-based SQL IDE for MySQL and nine other engines, deployed as a container or Helm chart next to the database.
* [WebDB](https://github.com/WebDB-App/app) ⭐ 333 | 🐛 25 | 🌐 TypeScript | 📅 2025-06-10 – Open Source and Efficient Database IDE. Featuring Easy server connection, Modern ERD, Intelligent data generator, AI assistant, NoSQL structure manager, Time machine and Powerful query editor
* [squix](https://github.com/eduardofuncao/squix) ⭐ 268 | 🐛 12 | 🌐 Go | 📅 2026-08-31 - SQL command-line client with query management and interactive results.
* [MySQL Shell](https://github.com/mysql/mysql-shell/) ⭐ 221 | 🐛 1 | 🌐 C++ | 📅 2026-08-18 - Advanced client and code editor for MySQL that supports development and administration for the MySQL Server and MySQL InnoDB cluster (AdminAPI) with an interactive JavaScript, Python, or SQL interface.
* [Ocelot GUI](https://github.com/ocelot-inc/ocelotgui) ⭐ 64 | 🐛 2 | 🌐 C++ | 📅 2025-11-06 - GUI client for MySQL or MariaDB, including debugger.

## HA

*High availability solutions*

* [Orchestrator](https://github.com/openark/orchestrator) ⚠️ Archived (archived) - MySQL replication topology management and High Availability solution.
* [replication-manager](https://github.com/signal18/replication-manager) ⭐ 739 | 🐛 175 | 🌐 Go | 📅 2026-09-01 - a high availability solution to manage MariaDB 10.x and MySQL & Percona Server 5.7 GTID replication topologies.
* [Galera Cluster](https://github.com/codership/galera) ⭐ 498 | 🐛 254 | 🌐 C++ | 📅 2026-06-09 - a true Multimaster Cluster based on synchronous replication.
* [mha4mysql-node](https://github.com/yoshinorim/mha4mysql-node) ⭐ 408 | 🐛 14 | 🌐 Perl | 📅 2020-03-12 and [mha4mysql-manager](https://github.com/yoshinorim/mha4mysql-manager) ⭐ 1,508 | 🐛 73 | 🌐 Perl | 📅 2020-08-14 (both unmaintained) - Master High Availability Manager and tools for MySQL.
* [Percona Replication Manager](https://github.com/percona/replication-manager) ⭐ 7 | 🐛 3 | 🌐 Shell | 📅 2026-01-07 - Asynchronous MySQL replication manager agent for Pacemaker. Supports file and GTID based replication, geo-distributed clusters using booth.

## MCP

* [MCP MariaDB Server](https://github.com/MariaDB/mcp) ⭐ 199 | 🐛 28 | 🌐 Python | 📅 2026-08-10 - the official MariaDB MCP server.
* [MySQL MCP Server](https://github.com/askdba/mysql-mcp-server) ⭐ 40 | 🐛 4 | 🌐 Go | 📅 2026-06-16 - Advanced MCP server exposing MySQL via the Model Context Protocol
* [TiDB MCP Server](https://pingcap.github.io/ai/integrations/tidb-mcp-server/) - MCP Server for TiDB.

## Proxy

*Proxies to MySQL*

* [ProxySQL](https://github.com/sysown/proxysql) ⭐ 6,909 | 🐛 1,079 | 🌐 C++ | 📅 2026-09-01 - High performance proxy for MySQL.
* [MySQL Router](https://dev.mysql.com/doc/mysql-router/en/) - MySQL Router is part of InnoDB cluster, and is a lightweight middleware that provides transparent routing between your application and back-end MySQL Servers.

## Replication

*Replication related software*

* [data-diff](https://github.com/datafold/data-diff) ⚠️ Archived (archived) - Command-line tool and Python library to efficiently diff rows across two different databases.

## Schema

*Add-on schemas*

* [sys](https://github.com/mysql/mysql-sys) ⚠️ Archived (archived) - A collection of views, functions and procedures to help MySQL administrators get insight in to MySQL Database usage. See [sys schema docs](https://dev.mysql.com/doc/refman/8.4/en/sys-schema.html)
* [common\_schema](https://github.com/shlomi-noach/common_schema) ⭐ 126 | 🐛 17 | 🌐 PLpgSQL | 📅 2020-03-21 - DBA's framework for MySQL, providing a function library, views library and QueryScript interpreter.

## Security

*Tools that prevents leaking of sensitive data from database (encryption, masking and tokenization, honey-pots, etc)*

* [Acra](https://github.com/cossacklabs/acra) ⭐ 1,491 | 🐛 29 | 🌐 Go | 📅 2026-04-23 - SQL database protection suite: strong selective encryption, SQL injections prevention, intrusion detection system.
* [myanon](https://github.com/ppomes/myanon) ⭐ 126 | 🐛 0 | 🌐 C | 📅 2026-07-24 - Streaming anonymizer for MySQL dump files, reading mysqldump output from stdin and writing anonymized data to stdout. Supports deterministic hashing, fixed values, JSON field anonymization, and Python extensions.
* [myldapsync](https://github.com/6eh01der/myldapsync) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-08-25 - Synchronize MySQL or MariaDB users with users in an LDAP directory.

## Server

*MySQL server flavors*

* [TiDB](https://github.com/pingcap/tidb) ⭐ 40,478 | 🐛 6,861 | 🌐 Go | 📅 2026-09-01 - A distributed HTAP database compatible with the MySQL protocol.
* [MySQL Server & MySQL Cluster](https://github.com/mysql/mysql-server) ⭐ 12,413 | 🐛 45 | 🌐 C++ | 📅 2026-08-27 - Official Oracle's MySQL server & MySQL Cluster distribution.
* [MariaDB](https://github.com/MariaDB/server) ⭐ 8,168 | 🐛 478 | 🌐 C++ | 📅 2026-09-01 - Community developed fork of MySQL server.
* [Percona Server](https://github.com/percona/percona-server) ⭐ 1,270 | 🐛 90 | 🌐 C++ | 📅 2026-09-01 - An enhanced, drop-in MySQL replacement.
* [MyVector](https://github.com/askdba/myvector) ⭐ 27 | 🐛 1 | 🌐 C++ | 📅 2026-08-02 - Native vector search plugin for MySQL, shipped as a server plugin.

## Sharding

*Sharding solutions/frameworks*

* [Vitess](https://github.com/vitessio/vitess) ⭐ 21,283 | 🐛 1,088 | 🌐 Go | 📅 2026-09-01 - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services.
* [Jetpants](https://github.com/tumblr/jetpants) ⭐ 1,126 | 🐛 3 | 🌐 Ruby | 📅 2017-06-15 - An automation suite for managing large range sharding clusters, by Tumblr.

## Toolkits

*Toolkits, general purpose scripts*

* [sqlaxe](https://github.com/djberube/sqlaxe) ⭐ 9 | 🐛 1 | 🌐 Python | 📅 2026-08-17 - CLI tool for searching, filtering, formatting, and splitting SQL files.

- [gh-ost](https://github.com/github/gh-ost/) ⭐ 13,548 | 🐛 328 | 🌐 Go | 📅 2026-08-28 - GitHub's online schema migration for MySQL.
- [go-mysql](https://github.com/go-mysql-org/go-mysql) ⭐ 4,964 | 🐛 156 | 🌐 Go | 📅 2026-09-01 - A pure go library to handle MySQL network protocol and replication.
- [Percona Toolkit](https://github.com/percona/percona-toolkit) ⭐ 1,544 | 🐛 33 | 🌐 Perl | 📅 2026-08-31 - a collection of advanced command-line tools to perform a variety of MySQL server and system tasks that are too difficult or complex to perform manually.
- [UnDROP](https://github.com/twindb/undrop-for-innodb) ⚠️ Archived (archived) - a tool to recover data from dropped or corrupted InnoDB tables.
- [MySQL Utilities](https://github.com/mysql/mysql-utilities) ⚠️ Archived (deprecated) - a collection of command-line utilities, written in Python, that are used for maintaining and administering MySQL servers, either individually, or within Replication hierarchies.
- [Swoof](https://github.com/StirlingMarketingGroup/swoof) ⭐ 29 | 🐛 3 | 🌐 Go | 📅 2026-09-01 - Ultra fast MySQL table importer that stages swaps through temporary tables and supports file/clipboard targets.
- [sql-splitter](https://github.com/HelgeSverre/sql-splitter) ⭐ 15 | 🐛 2 | 🌐 Rust | 📅 2026-08-29 - High-performance CLI for splitting, merging, converting, validating, and sampling mysqldump files.

# Resources

*At this stage "resources" will not include websites, blogs, slides, presentation videos, etc. in fear of list size*

## e-books

*e-books as well as relevant materials on and around MySQL*

* [SQL-exercise](https://github.com/XD-DENG/SQL-exercise) ⭐ 1,530 | 🐛 8 | 📅 2023-11-11 - contains several SQL exercises, including the schema description figure, SQL code to build schema, questions and solutions in SQL. Based on wikibook [SQL Exercises](https://en.wikibooks.org/wiki/SQL_Exercises).
* [Database Systems Lecture Notes](http://spots.augusta.edu/caubert/db/ln/) - lecture notes on Database Systems (available in pdf, html, odt and markdown) including a Chapter on SQL that covers basic set-up, exercises and problems.

## Incubating

Projects that are known to be non-production and yet have either traction or substance that warrants exposure.

* [VillageSQL](https://github.com/villagesql/villagesql-server) ⭐ 176 | 🐛 260 | 🌐 C++ | 📅 2026-09-01 - A drop-in replacement for MySQL with extensions for the agentic AI era.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-01._

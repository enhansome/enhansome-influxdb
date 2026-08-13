# awesome-influxdb with stars

A curated list of awesome projects, libraries, tools, etc. related to [InfluxDB](https://www.influxdata.com/).
This list focuses on libraries, tools, etc. supporting InfluxDB version 1.0 and up.

Want to make this list better?
Take a look at our page on [contributing](CONTRIBUTING.md) and then open a pull request!

## Reference material

If you know of any particularly useful blog posts, talks, slides, etc. that belong in this list, please open a pull request!

* [Official documentation](https://docs.influxdata.com/influxdb/latest/)
* InfluxDB in IoT world. [Part 1: Introduction](https://www.easyitblog.info/2017/11/10/influxdb-and-grafana-fighting-together-with-iot-data-attack/) | [Part 2: Hosting and scaling on AWS](https://www.easyitblog.info/2017/11/14/influxdb-in-iot-world-aws-part-2/) | [Part 3: Plotting graphs using Grafana](https://www.easyitblog.info/2017/11/26/influxdb-in-iot-world-making-it-production-ready-part-3/)

## Client libraries

### Official

* [Python](https://github.com/influxdata/influxdb-python) ⚠️ Archived - Python client for InfluxDB
* [Java](https://github.com/influxdata/influxdb-java) ⭐ 1,196 | 🐛 111 | 🌐 Java | 📅 2026-03-01 - Java client for InfluxDB
* [PHP](https://github.com/influxdata/influxdb-php) ⚠️ Archived - PHP client for InfluxDB
* [Ruby](https://github.com/influxdata/influxdb-ruby) ⭐ 371 | 🐛 13 | 🌐 Ruby | 📅 2022-06-20 - Ruby client for InfluxDB
* [C#](https://github.com/influxdata/influxdb-csharp) ⚠️ Archived - A .NET library for efficiently sending points to InfluxDB
* [Go](https://github.com/influxdata/influxdb1-client) ⭐ 192 | 🐛 42 | 🌐 Go | 📅 2024-03-12 - Go client for InfluxDB 1.x
* [Rails](https://github.com/influxdata/influxdb-rails) ⚠️ Archived - Ruby on Rails bindings to automatically write metrics into InfluxDB

### Unofficial

* [node-influx](https://github.com/node-influx/node-influx) ⭐ 864 | 🐛 17 | 🌐 TypeScript | 📅 2026-05-28 - InfluxDB Node.js Client
* [InfluxDB-Client-for-Arduino](https://github.com/tobiasschuerg/InfluxDB-Client-for-Arduino) ⭐ 415 | 🐛 13 | 🌐 C++ | 📅 2026-06-09 - Arduino client for InfluxDB
* [instream](https://github.com/mneudert/instream) ⭐ 228 | 🐛 17 | 🌐 Elixir | 📅 2025-10-12 - InfluxDB driver for Elixir
* [InfluxDB.NET](https://github.com/ziyasal/InfluxDB.Net) ⭐ 163 | 🐛 23 | 🌐 C# | 📅 2022-06-22 - .NET client for InfluxDB
* [scala-influxdb-client](https://github.com/paulgoldbaum/scala-influxdb-client) ⭐ 122 | 🐛 8 | 🌐 Scala | 📅 2019-08-23 - Asynchronous InfluxDB client for Scala
* [fluxter](https://github.com/lexmag/fluxter) ⭐ 106 | 🐛 7 | 🌐 Elixir | 📅 2025-05-21 - An InfluxDB writer for Elixir
* [influxdbr](https://github.com/dleutnant/influxdbr) ⭐ 92 | 🐛 22 | 🌐 R | 📅 2024-08-09 - R library for InfluxDB
* [InfluxDB PHP SDK](https://github.com/corley/influxdb-php-sdk) ⭐ 84 | 🐛 3 | 🌐 PHP | 📅 2019-06-03 - UDP/IP or HTTP adapters for read and write data
* [capacitor](https://github.com/olauzon/capacitor) ⚠️ Archived - A Clojure client for InfluxDB
* [influxdb-haskell](https://github.com/maoe/influxdb-haskell) ⭐ 55 | 🐛 12 | 🌐 Haskell | 📅 2024-07-12 - Haskell client library for InfluxDB
* [influxdb-cpp-rest](https://github.com/d-led/influxdb-cpp-rest) ⭐ 51 | 🐛 4 | 🌐 C++ | 📅 2025-11-26 - A C++ InfluxDB client with a batching async interface
* [influent.rs](https://github.com/gobwas/influent.rs) ⚠️ Archived - InfluxDB Rust driver
* [influent](https://github.com/gobwas/influent) ⭐ 37 | 🐛 3 | 🌐 JavaScript | 📅 2015-12-23 - InfluxDB Javascript driver
* [erflux](https://github.com/gossiperl/erflux) ⭐ 29 | 🐛 1 | 🌐 Erlang | 📅 2017-03-29 - InfluxDB client for Erlang
* [cl-influxdb](https://github.com/mmaul/cl-influxdb) ⭐ 24 | 🐛 1 | 🌐 Common Lisp | 📅 2017-03-15 - Common Lisp interface to the Time Series Database InfluxDB
* [InfluxDB-Client-LabVIEW](https://github.com/johanvandenbroek/InfluxDB-Client-LabVIEW) ⭐ 24 | 🐛 3 | 🌐 LabVIEW | 📅 2020-08-21 - LabVIEW client for InfluxDB
* [node-influx-udp](https://github.com/mediocre/node-influx-udp) ⚠️ Archived - Write to InfluxDB using its UDP interface

## Collecting data into InfluxDB

### Projects

#### Dedicated

Tools whose primary or sole purpose is to feed data into InfluxDB.

* [k6](https://github.com/loadimpact/k6) ⭐ 31,248 | 🐛 776 | 🌐 Go | 📅 2026-08-12 - A modern load testing tool, using Go and JavaScript
* [Telegraf](https://github.com/influxdata/telegraf) ⭐ 17,746 | 🐛 403 | 🌐 Go | 📅 2026-08-12 - (Official) plugin-driven server agent for reporting metrics into InfluxDB
* [influxdb-logger](https://github.com/codersaur/SmartThings/tree/master/smartapps/influxdb-logger) ⭐ 318 | 🐛 55 | 🌐 Groovy | 📅 2024-04-18 - SmartApp to log [SmartThings](https://www.smartthings.com/) device attributes to an InfluxDB database
* [snmpcollector](https://github.com/toni-moreno/snmpcollector) ⭐ 307 | 🐛 44 | 🌐 Go | 📅 2023-12-18 - A full featured Generic SNMP data collector with Web Administration Interface for InfluxDB
* [vsphere-influxdb-go](https://github.com/Oxalide/vsphere-influxdb-go) ⭐ 213 | 🐛 21 | 🌐 Go | 📅 2020-04-01 - Collect VMware vSphere, vCenter and ESXi performance metrics and send them to InfluxDB
* [node-opcua-logger](https://github.com/coussej/node-opcua-logger) ⭐ 184 | 🐛 35 | 🌐 JavaScript | 📅 2022-12-08 - Collect industrial data from OPC UA Servers
* [mqforward](https://github.com/shirou/mqforward) ⭐ 81 | 🐛 6 | 🌐 Go | 📅 2025-12-02 - [MQTT](http://mqtt.org/) to influxdb forwarder
* [influxdb-sqlserver](https://github.com/zensqlmonitor/influxdb-sqlserver) ⭐ 72 | 🐛 3 | 🌐 Go | 📅 2023-11-06 - Collect Microsoft SQL Server metrics for reporting to InfluxDB and visualize them with Grafana
* [Charmander](https://github.com/att-innovate/charmander) ⭐ 67 | 🐛 4 | 🌐 Shell | 📅 2016-05-30 - Charmander is a lab environment for measuring and analyzing resource-scheduling algorithms
* [Influx-Capacitor](https://github.com/poxet/Influx-Capacitor) ⭐ 45 | 🐛 9 | 🌐 C# | 📅 2017-05-29 - Influx-Capacitor collects metrics from windows machines using Performance Counters. Data is sent to influxDB to be viewable by grafana
* [grade](https://github.com/influxdata/grade) ⭐ 43 | 🐛 0 | 🌐 Go | 📅 2020-01-20 - Track Go benchmark performance over time by storing results in InfluxDB
* [gopherwx](https://github.com/chrissnell/gopherwx) ⭐ 32 | 🐛 1 | 🌐 Go | 📅 2026-07-07 - a service that pulls live weather data from a Davis Instruments Vantage Pro2 station and stores it in InfluxDB
* [aprs2influxdb](https://github.com/FaradayRF/aprs2influxdb) ⭐ 29 | 🐛 9 | 🌐 Python | 📅 2022-08-22 - Interfaces ham radio APRS-IS servers and saves packet data into an influxdb database
* [agento](https://github.com/abrander/agento) ⚠️ Archived - Client/server collecting near realtime metrics from Linux hosts
* [tesla-streamer](https://github.com/timdorr/tesla-trip/blob/master/lib/tesla_stream_reader.rb) ⭐ 19 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-12 - Streams data from Tesla Model S to InfluxDB ([rake task](https://github.com/timdorr/tesla-trip/blob/master/lib/tasks/tesla.rake#L12-L16) ⭐ 19 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-12)
* [accelerometer2influx](https://github.com/CorpGlory/accelerometer2influx) ⭐ 18 | 🐛 2 | 🌐 Kotlin | 📅 2018-03-25 - Android application that takes the x-y-z axis metrics from your phone accelerometer and sends the data to InfluxDB.
* [mesos-influxdb-collector](https://github.com/kpacha/mesos-influxdb-collector) ⚠️ Archived - Lightweight [mesos](https://mesos.apache.org/) stats collector for InfluxDB
* [aggregateD](https://github.com/ccpgames/aggregateD) ⭐ 14 | 🐛 0 | 🌐 Go | 📅 2016-09-03 - A [dogstatsD](https://docs.datadoghq.com/guides/dogstatsd/) inspired metrics and event aggregation daemon for InfluxDB
* [Influxdb-Powershell](https://github.com/vsavornin/Influxdb-Powershell) ⚠️ Archived - Powershell script to send Windows Performance counters to an InfluxDB Server
* [ntp\_checker](https://github.com/fss1/ntp_checker) ⭐ 4 | 🐛 0 | 🌐 Perl | 📅 2018-11-28 - compares internal NTP sources and warns if the offset between servers exceeds a definable (fraction of) seconds
* [marathon-event-metrics](https://github.com/Wikia/marathon-event-metrics) ⚠️ Archived - a tool for reporting [Marathon](https://mesosphere.github.io/marathon/) events to InfluxDB
* [proc\_to\_influxdb](https://github.com/d-led/proc_to_influxdb) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2018-03-22 - Console app to observe Windows process starts and stops via InfluxDB
* [pysysinfo\_influxdb](https://github.com/nagylzs/pysysinfo_influxdb) - Periodically send system information into influxdb (uses python3 + psutil, so it also works under Windows)
* [sysinfo\_influxdb](https://github.com/novaquark/sysinfo_influxdb) - Collect and send system (linux) info to InfluxDB
* [traffic\_stats](https://traffic-control-cdn.readthedocs.io/en/latest/overview/traffic_stats.html) - Acquires and stores statistics about CDNs controlled by [Apache Traffic Control](https://trafficcontrol.apache.org/)

#### Non-dedicated

Tools that generate data that feed into multiple backends, InfluxDB included.

* [Glances](https://github.com/nicolargo/glances) ⭐ 33,325 | 🐛 105 | 🌐 Python | 📅 2026-08-08 - Glances an Eye on your system
* [cAdvisor](https://github.com/google/cadvisor) ⭐ 19,351 | 🐛 64 | 🌐 Go | 📅 2026-07-20 - Analyzes resource usage and performance characteristics of running containers
* [gatling](https://github.com/gatling/gatling) ⭐ 6,945 | 🐛 21 | 🌐 Scala | 📅 2026-07-27 - Async Scala-Akka-Netty based Stress Tool
* [Riemann](https://github.com/riemann/riemann) ⭐ 4,267 | 🐛 29 | 🌐 Clojure | 📅 2026-04-05 - A network event stream processing system, in Clojure
* [heka](https://github.com/mozilla-services/heka) ⚠️ Archived - General purpose data collection and processing tool
* [heapster](https://github.com/kubernetes-retired/heapster) ⚠️ Archived - Monitor container resource usage of a [Kubernetes](https://kubernetes.io/) cluster
* [statsite](https://github.com/statsite/statsite) ⭐ 1,817 | 🐛 28 | 🌐 C | 📅 2021-06-11 - C implementation of statsd
* [jmxtrans](https://github.com/jmxtrans/jmxtrans) ⭐ 1,702 | 🐛 138 | 🌐 Java | 📅 2022-09-05 - Effectively the missing connector between speaking to a JVM via JMX on one end and whatever logging / monitoring / graphing package that you can dream up on the other end.
* [logary](https://github.com/logary/logary) ⭐ 531 | 🐛 71 | 🌐 F# | 📅 2023-05-18 - High performance, multi-target logging, metric and health-check library for mono and .Net
* [logagent](https://github.com/sematext/logagent-js) ⭐ 391 | 🐛 42 | 🌐 JavaScript | 📅 2024-09-12 - is a modern, open-source, light-weight log shipper. Logagent includes [influxdb input plugin](https://sematext.com/docs/logagent/input-plugin-influxdb-http/) and [influxdb output plugin](https://sematext.com/docs/logagent/output-plugin-influxdb/) and many other [integrations](https://sematext.com/docs/logagent/plugins/)
* [statsd-jvm-profiler](https://github.com/etsy/statsd-jvm-profiler) ⭐ 335 | 🐛 10 | 🌐 Java | 📅 2026-01-15 - Simple JVM Profiler Using StatsD
* [cernan](https://github.com/postmates/cernan) ⭐ 314 | 🐛 31 | 🌐 Rust | 📅 2023-06-14 - A telemetry and logging aggregation server
* [Graphios](https://github.com/shawn-sterling/graphios) ⭐ 288 | 🐛 47 | 🌐 Python | 📅 2017-07-27 - A program to send nagios perf data to graphite (carbon) / statsd / librato / influxDB
* [Centreon](https://github.com/centreon/centreon) ⭐ 162 | 🐛 308 | 🌐 PHP | 📅 2026-08-12 - A network, system, applicative supervision and monitoring tool
* [metrics.sh](https://github.com/pstadler/metrics.sh) ⭐ 144 | 🐛 2 | 🌐 Shell | 📅 2019-03-11 - Collect and forward metrics using portable shell scripts
* [cloudwatch-sender](https://github.com/BBC-News/cloudwatch-sender) ⭐ 53 | 🐛 9 | 🌐 Ruby | 📅 2016-06-14 - Send metrics to InfluxDB/Graphite from [Amazon Cloudwatch](https://aws.amazon.com/cloudwatch/)
* [ioBroker](http://www.iobroker.net/) - Homeautomation / IoT Platform uses Influxdb to store [history data](https://github.com/ioBroker/ioBroker.influxdb/blob/master/README.md) ⭐ 37 | 🐛 69 | 🌐 TypeScript | 📅 2026-08-10
* [Sematext Agent](https://github.com/sematext/sematext-agent-integrations) ⭐ 13 | 🐛 6 | 📅 2024-05-30 - [Open source monitoring agent](https://sematext.com/blog/now-open-source-sematext-monitoring-agent/) to collect metrics from Solr, Elasticsearch, Cassandra, JVM, JMX, ClickHouse, MySQL, Hadoop, and more via pluggable integrations. Output via Influx Line Protocol to InfluxDB or [Sematext Cloud](https://sematext.com/cloud/)
* [crankshaftd](https://github.com/fullcontact/crankshaftd) ⚠️ Archived - Simple Go agent to ingest streaming data from [Turbine](https://github.com/Netflix/Turbine) ⚠️ Archived via SSE and push it into StatsD as a gauge or to InfluxDB
* [internet\_data\_usage](https://github.com/precurse/internet_data_usage) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2015-11-20 - Python based application to pull data plan usage for different carriers such as Telus and Koodo
* [Domoticz](https://www.domoticz.com) - Open source Home Automation System
* [Apache JMeter](https://jmeter.apache.org/usermanual/realtime-results.html) - Popular load testing tool, you can get real-time results sent to a backend through the InfluxDBBackendListenerClient which allows you to send metrics (active threads, response time ...) to an InfluxDB Backend using UDP or HTTP protocols
* [OpenHAB](https://www.openhab.org/) - A universal integration platform for all things around home automation

### Libraries

Libraries to collect data and feed into InfluxDB.

* [metrics](https://github.com/beberlei/metrics) ⭐ 322 | 🐛 11 | 🌐 PHP | 📅 2026-01-13 - (PHP) Simple library that abstracts different metrics collectors. "I find this necessary to have a consistent and simple metrics (functional) API that doesn't cause vendor lock-in"
* [go-runtime-metrics](https://github.com/tevjef/go-runtime-metrics) ⭐ 287 | 🐛 5 | 🌐 Go | 📅 2018-02-04 - Collect golang runtime Metrics, outputting to InfluxDB or through Telegraf
* [django-influxdb-metrics](https://github.com/bitlabstudio/django-influxdb-metrics) ⭐ 86 | 🐛 6 | 🌐 Python | 📅 2021-08-04 - A reusable Django app that sends metrics about your project to InfluxDB
* [lua-resty-influx](https://github.com/p0pr0ck5/lua-resty-influx) ⭐ 28 | 🐛 3 | 🌐 Perl | 📅 2020-12-16 - [OpenResty](https://openresty.org/en/) client for InfluxDB
* [pyVsphereInflux](https://github.com/fennm/pyVsphereInflux) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2016-03-01 - A library and supporting script for pulling data from [vSphere](https://www.vmware.com/products/vsphere.html) and inserting it into InfluxDB
* [crow-metrics](https://github.com/robey/crow-metrics) - small metrics collector for node servers
* [telemetry](https://github.com/arussellsaw/telemetry) - metric reporting for Go applications

#### Hooks

Hooks for other logging libraries to output to InfluxDB.

* [go-metrics-influxdb](https://github.com/vrischmann/go-metrics-influxdb) ⚠️ Archived - A reporter for the [go-metrics library](https://github.com/rcrowley/go-metrics) ⚠️ Archived which will post the metrics to InfluxDB
* [logrus\_influxdb](https://github.com/Abramovic/logrus_influxdb) ⭐ 26 | 🐛 3 | 🌐 Go | 📅 2019-12-25 - InfluxDB Hook for [Logrus](https://github.com/Sirupsen/logrus) ⭐ 25,752 | 🐛 43 | 🌐 Go | 📅 2026-08-12

### Plugins

Plugins to allow other standalone tools to send their data into InfluxDB.

* [metrics-influxdb](https://github.com/davidB/metrics-influxdb) ⚠️ Archived - A reporter for [dropwizard](https://www.dropwizard.io/0.9.1/docs/) metrics which announces measurements to an InfluxDB server
* [kafka-influxdb](https://github.com/mre/kafka-influxdb) ⭐ 218 | 🐛 15 | 🌐 Python | 📅 2022-12-08 - A [Kafka](https://kafka.apache.org/) consumer for InfluxDB written in Python
* [statsd-influxdb-backend](https://github.com/bernd/statsd-influxdb-backend) ⭐ 169 | 🐛 17 | 🌐 JavaScript | 📅 2018-05-12 - A naive InfluxDB backend for StatsD
* [fluent-plugin-influxdb](https://github.com/fangli/fluent-plugin-influxdb) ⭐ 109 | 🐛 27 | 🌐 Ruby | 📅 2024-09-27 - A buffered output plugin for [fluentd](https://www.fluentd.org/) and InfluxDB
* [logstash-output-influxdb](https://github.com/logstash-plugins/logstash-output-influxdb) ⭐ 59 | 🐛 43 | 🌐 Ruby | 📅 2026-06-16 - Community-maintained [Logstash](https://www.elastic.co/products/logstash) plugin to output metrics to InfluxDB
* [jenkinsci/influxdb-plugin](https://github.com/jenkinsci/influxdb-plugin) ⭐ 56 | 🐛 5 | 🌐 Java | 📅 2026-07-27 - [Jenkins](https://jenkins.io/index.html) plugin to send build metrics into InfluxDB
* [exometer\_influxdb](https://github.com/travelping/exometer_influxdb) ⭐ 36 | 🐛 1 | 🌐 Erlang | 📅 2020-02-12 - [Exometer](https://github.com/Feuerlabs/exometer) ⭐ 528 | 🐛 16 | 🌐 Erlang | 📅 2019-06-14 reporter for InfluxDB
* [influx-nagios-plugin](https://github.com/shaharke/influx-nagios-plugin) ⭐ 29 | 🐛 0 | 🌐 Python | 📅 2015-10-21 - [Nagios](https://www.nagios.org/) plugin for querying monitoring stats from InfluxDB
* [sensu-plugins-influxdb](https://github.com/sensu-plugins/sensu-plugins-influxdb) ⭐ 18 | 🐛 9 | 🌐 Ruby | 📅 2021-07-19 - [Sensu](https://sensu.io/) InfluxDB Plugins
* [sidekiq-influxdb](https://github.com/vassilevsky/sidekiq-influxdb) ⭐ 18 | 🐛 0 | 🌐 Ruby | 📅 2026-06-05 - A [Sidekiq](https://sidekiq.org/) middleware to send job execution metrics to InfluxDB
* [mod-influxdb](https://github.com/savoirfairelinux/mod-influxdb) ⭐ 13 | 🐛 12 | 🌐 Python | 📅 2019-05-23 - [Shinken](http://www.shinken-monitoring.org/) module for exporting data to InfluxDB
* [snap-plugin-publisher-influxdb](https://github.com/intelsdi-x/snap-plugin-publisher-influxdb) ⚠️ Archived - Publishes [snap](https://github.com/intelsdi-x/snap) ⚠️ Archived metrics to InfluxDB
* [embulk-output-influxdb](https://github.com/joker1007/embulk-output-influxdb) ⭐ 2 | 🐛 1 | 🌐 Ruby | 📅 2017-02-16 - InfluxDB output plugin for [Embulk](https://github.com/embulk/embulk) ⭐ 1,784 | 🐛 162 | 🌐 Java | 📅 2026-06-19
* [logagent influx input plugin](https://sematext.com/docs/logagent/input-plugin-influxdb-http/) - Logagent plugin to receive data via Influx Line Protocol
* [logagent InfluxDB output plugin](https://sematext.com/docs/logagent/input-plugin-influxdb-http/) - Plugin to send data via Influx Line Protocol

### Import tools

Tools to import a fixed set of data into InfluxDB.

* [nmon2influxdb](https://github.com/adejoux/nmon2influxdb) ⚠️ Archived - Import [nmon](http://nmon.sourceforge.net/pmwiki.php) file into InfluxDB
* [JMeter2InfluxDB](https://github.com/soprasteria/jmeter2influxdb) ⭐ 10 | 🐛 0 | 🌐 Java | 📅 2025-04-09 - Read JMeter results in a csv file and put results in InfluxDB after the load test
* [LoadRunner Raw Results Exporter](https://admhelp.microfocus.com/lr/en/12.60-12.62/help/WebHelp/Content/Controller/raw_results_exporter.htm) - To export scenario results (load test results) to InfluxDB

## Consuming data from InfluxDB

### Dashboards and visualization

* [grafana](https://github.com/grafana/grafana) ⭐ 76,274 | 🐛 3,370 | 🌐 TypeScript | 📅 2026-08-13 - Gorgeous metric viz, dashboards & editors for Graphite, InfluxDB & OpenTSDB
* [Chronograf](https://github.com/influxdata/chronograf) ⭐ 1,566 | 🐛 50 | 🌐 TypeScript | 📅 2026-08-11 - Official InfluxDB data visualization tool
* [facette](https://github.com/facette/facette) ⭐ 1,157 | 🐛 41 | 🌐 Go | 📅 2021-10-05 - Time series data visualization and graphing software
* [InfluxDB Studio](https://github.com/CymaticLabs/InfluxDBStudio) ⭐ 929 | 🐛 49 | 🌐 C# | 📅 2022-12-07 - InfluxDB Studio is a UI management tool, its inspiration comes from other similar SQL database management tools (use InfluxData.Net run on MS Windows)
* [ostent](https://github.com/ostrost/ostent) ⭐ 178 | 🐛 0 | 🌐 Go | 📅 2022-12-12 - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB
* [InfluxGraph](https://github.com/InfluxGraph/influxgraph) ⭐ 92 | 🐛 0 | 🌐 Python | 📅 2018-11-07 - Graphite InfluxDB storage finder for Graphite-API
* [FluxDash](https://github.com/vrecan/FluxDash) ⭐ 36 | 🐛 1 | 🌐 Go | 📅 2016-03-30 - Terminal based InfluxDB dashboard
* [DBeaver](https://dbeaver.com/databases/influxdb/) - DBeaver Universal Database Tool, DBeaver Enterprise has special extensions for InfluxDB

### Other tools

* [Morgoth](https://github.com/nathanielc/morgoth) ⭐ 280 | 🐛 15 | 🌐 Go | 📅 2022-11-14 - Metric anomaly detection
* [influx-alert](https://github.com/joshrendek/influx-alert) ⭐ 34 | 🐛 1 | 🌐 Go | 📅 2016-11-21 - A tool to query InfluxDB and send alerts based on a YAML config
* [influxdb\_google\_sheets](https://github.com/HormyAJP/influxdb_google_sheets) ⭐ 17 | 🐛 1 | 🌐 JavaScript | 📅 2025-01-13 - Google Sheets script for fetching and formatting InfluxDB data
* [hubot-influxdb-alerts](https://github.com/amwelch/hubot-influxdb-alerts) ⭐ 10 | 🐛 0 | 🌐 CoffeeScript | 📅 2015-12-17 - Create and manage alerts in your chatroom using [hubot](https://hubot.github.com/) and influxdb

## Provisioning InfluxDB

Tools, libraries, etc. to help you get InfluxDB running without installing it by hand.

* [tutum-docker-influxdb](https://github.com/tutumcloud/influxdb) ⚠️ Archived - Docker image to run an out-of-the-box InfluxDB server
* [chef-influxdb](https://github.com/bdangit/chef-influxdb) ⭐ 53 | 🐛 8 | 🌐 Ruby | 📅 2022-05-16 - Chef cookbook for InfluxDB
* [rossmcdonald/influxdb](https://github.com/rossmcdonald/influxdb) ⭐ 43 | 🐛 2 | 🌐 Jinja | 📅 2024-11-18 - Ansible role for installing, configuring, and maintaining InfluxDB
* [golja-influxdb](https://github.com/dgolja/golja-influxdb) ⭐ 19 | 🐛 25 | 🌐 Ruby | 📅 2023-09-01 - Puppet module for InfluxDB
* [influxdb-formula](https://github.com/saltstack-formulas/influxdb-formula) ⭐ 9 | 🐛 3 | 🌐 Ruby | 📅 2023-07-07 - Installs and configures the InfluxDB timeseries database
* [influxdb-release](https://github.com/pivotal-cf-experimental/influxdb-release) ⚠️ Archived - Experimental BOSH release for InfluxDB
* [puppet-telegraf](https://forge.puppet.com/datacentred/telegraf/readme) - Puppet module for Telegraf

## Queries

* [Time Series Admin](https://github.com/timeseriesadmin/timeseriesadmin) ⭐ 141 | 🐛 26 | 🌐 TypeScript | 📅 2026-08-01 - Administration panel and querying interface for InfluxDB databases
* [influxer](https://github.com/palkan/influxer) ⭐ 118 | 🐛 2 | 🌐 Ruby | 📅 2024-10-12 - InfluxDB ActiveRecord-style
* [Influxdb::Arel](https://github.com/undr/influxdb-arel) ⭐ 11 | 🐛 1 | 🌐 Ruby | 📅 2016-08-11 - Influxdb::Arel is a SQL AST manager for InfluxDB dialect. It simplifies the generation of complex SQL queries
* [dbal-influxdb](https://github.com/corley/dbal-influxdb) ⭐ 8 | 🐛 0 | 🌐 PHP | 📅 2015-07-01 - Doctrine DBAL for InfluxDB

## Hosting of InfluxDB / SaaS

* [InfluxCloud](https://cloud.influxdata.com/plan-picker) - From the creators of InfluxDB
* [Aiven](https://aiven.io/influxdb) - Provides a choice of host (AWS, Google, DigitalOcean, etc.), geographic location, and server specs
* [Scalingo](https://scalingo.com/databases/influxdb) - Provides a choice of server specs
* [HostedMetrics](https://hostedmetrics.com/product/influxdb/) - Geared towards custom application monitoring by hosting the combination of InfluxDB, Grafana, and StatsD

## Miscellaneous

Projects that don't seem to fit in any other category.

* [influx-prompt](https://github.com/RPing/influx-prompt) ⭐ 44 | 🐛 2 | 🌐 Python | 📅 2022-12-09 - An interactive command-line InfluxDB cli with auto completion
* [cleanflux](https://github.com/Transatel/cleanflux) ⭐ 32 | 🐛 1 | 🌐 Python | 📅 2022-12-26 - proxy around /query endpoint with auto retention policy selection and on the wire bug corrections
* [influx-protector](https://github.com/ve-global/influx-protector) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2017-02-21 - proxy to prevent dangerous queries getting to influxdb
* [influxdb-schema-updater](https://github.com/open-ch/influxdb-schema-updater) ⭐ 7 | 🐛 0 | 🌐 Perl | 📅 2020-03-27 - A small DevOps tool to manage the schema of an InfluxDB instance with a set of configuration files

## Other awesome lists

### Awesome lists that include links to InfluxDB

* [awesome-go](https://github.com/avelino/awesome-go) ⭐ 180,917 | 🐛 207 | 🌐 Go | 📅 2026-08-11
* [awesome-sysadmin](https://github.com/kahun/awesome-sysadmin) ⭐ 24,347 | 🐛 270 | 📅 2024-03-26
* [awesome-bigdata](https://github.com/onurakpolat/awesome-bigdata) ⭐ 14,532 | 🐛 2 | 📅 2026-07-31
* [awesome-microservices](https://github.com/mfornos/awesome-microservices) ⭐ 14,475 | 🐛 19 | 📅 2026-06-10
* [awesome-data-engineering](https://github.com/igorbarinov/awesome-data-engineering) ⭐ 8,943 | 🐛 24 | 📅 2026-07-18
* [awesome-home-assistant](https://github.com/frenck/awesome-home-assistant) ⭐ 8,325 | 🐛 18 | 🌐 Python | 📅 2026-08-07
* [awesome-db](https://github.com/numetriclabz/awesome-db) ⭐ 1,377 | 🐛 38 | 📅 2024-03-04
* [awesome-dashboard](https://github.com/obazoud/awesome-dashboard) ⭐ 1,166 | 🐛 1 | 📅 2026-08-01

### Lists of awesome lists that include awesome-influxdb

* [awesome](https://github.com/sindresorhus/awesome) ⭐ 495,052 | 🐛 100 | 📅 2026-06-30
* [lists](https://github.com/jnv/lists) ⭐ 11,413 | 🐛 20 | 📅 2026-03-23

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the authors and contributors have waived all copyright and related or neighboring rights to awesome-influxdb.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-13._

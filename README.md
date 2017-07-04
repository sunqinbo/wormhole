wormhole
========

Wormhole is dianping massive data transfer tool, it currently support data source and destination like hdfs, hive, hbase, mysql, greenplum, sqlserver, mongodb, sftp, salesforce

Project contact: yukang chen (yukang.chen@dianping.com)


Copyright and license
---------------------

Copyright 2013 DianPing, Inc.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this work except in compliance with the License. You may obtain a copy of the License in the LICENSE file, or at:

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

2012年，出于成本、稳定性与源码级别维护性的考虑，公司的Data Warehouse系统由商业的OLAP数据库转向Hadoop/Hive。2012年初，Wormhole开发完成；之后Taurus也上线部署；大量应用接入到Hadoop平台上。为了保证数据的安全性，我们开启了Hadoop的Security特性。为了提高数据的压缩率，我们将默认存储格式替换为RCFile，并开发了Hive Web供公司内部使用。2012年底，我们开始调研HBase。
![架构图](http://cms.csdnimg.cn/article/201312/18/52b14d5d3b0ed.jpg)

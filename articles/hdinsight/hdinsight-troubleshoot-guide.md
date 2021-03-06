---
title: Azure HDInsight troubleshooting guides | Microsoft Docs
description: Troubleshoot Hadoop workloads by using Azure HDInsight. Step-by-step documentation shows you how to use HDInsight to solve common problems with Hive, Spark, YARN, HBase, HDFS, and Storm.
services: hdinsight
author: arijitt
manager: arijitt
layout: LandingPage
ms.assetid:
ms.service: hdinsight
ms.tgt_pltfrm: na
ms.devlang: na
ms.topic: landing - page
ms.date: 11/2/2017
ms.author: arijitt
---


# Troubleshoot by using Azure HDInsight

| Apache workload | Top questions |
|---|---|
|![HBase](./media/hdinsight-troubleshoot-guide/HBASE.png)<br>[Troubleshoot HBase](hbase/apache-troubleshoot-hbase.md)|<br>[How do I run hbck command reports with multiple unassigned regions?](hbase/apache-troubleshoot-hbase.md#how-do-i-run-hbck-command-reports-with-multiple-unassigned-regions)<br><br>[How do I fix timeout issues when using hbck commands for region assignments?](hbase/apache-troubleshoot-hbase.md#how-do-i-fix-timeout-issues-with-hbck-commands-for-region-assignments)<br><br>[How do I force-disable HDFS safe mode on a cluster?](hbase/apache-troubleshoot-hbase.md#how-do-i-force-disable-hdfs-safe-mode-in-a-cluster)<br><br>[How do I fix JDBC or SQLLine connectivity issues with Apache Phoenix?](hbase/apache-troubleshoot-hbase.md#how-do-i-fix-jdbc-or-sqlline-connectivity-issues-with-apache-phoenix)<br><br>[What causes a master server to fail to start?](hbase/apache-troubleshoot-hbase.md#what-causes-a-master-server-to-fail-to-start)<br><br>[What causes a restart failure on a region server?](hbase/apache-troubleshoot-hbase.md#what-causes-a-restart-failure-on-a-region-server)|
|![HDFS](./media/hdinsight-troubleshoot-guide/HDFS.png)<br>[Troubleshoot HDFS](hdinsight-troubleshoot-hdfs.md)|<br>[How do I access a local HDFS from inside a cluster?](hdinsight-troubleshoot-hdfs.md#how-do-i-access-local-hdfs-from-inside-a-cluster)<br><br>[How do I force-disable HDFS safe mode on a cluster?](hdinsight-troubleshoot-hdfs.md#how-do-i-force-disable-hdfs-safe-mode-in-a-cluster)|
|![Hive](./media/hdinsight-troubleshoot-guide/HIVE.png)<br>[Troubleshoot HBase](hdinsight-troubleshoot-hive.md)|<br>[How do I export a Hive metastore and import it on another cluster?](hdinsight-troubleshoot-hive.md#how-do-i-export-a-hive-metastore-and-import-it-on-another-cluster)<br><br>[How do I locate Hive logs on a cluster?](hdinsight-troubleshoot-hive.md#how-do-i-locate-hive-logs-on-a-cluster)<br><br>[How do I launch the Hive shell with specific configurations on a cluster?](hdinsight-troubleshoot-hive.md#how-do-i-launch-the-hive-shell-with-specific-configurations-on-a-cluster)<br><br>[How do I analyze Tez DAG data on a cluster-critical path?](hdinsight-troubleshoot-hive.md#how-do-i-analyze-tez-dag-data-on-a-cluster-critical-path)<br><br>[How do I download Tez DAG data from a cluster?](hdinsight-troubleshoot-hive.md#how-do-i-download-tez-dag-data-from-a-cluster)|
|![Spark](./media/hdinsight-troubleshoot-guide/SPARK.png)<br>[Troubleshoot Spark](hdinsight-troubleshoot-SPARK.md)|<br>[How do I configure a Spark application by using Ambari on clusters?](spark/apache-troubleshoot-spark.md#how-do-i-configure-a-spark-application-by-using-ambari-on-clusters)<br><br>[How do I configure a Spark application by using a Jupyter notebook on clusters?](spark/apache-troubleshoot-spark.md#how-do-i-configure-a-spark-application-by-using-a-jupyter-notebook-on-clusters)<br><br>[How do I configure a Spark application by using Livy on clusters?](spark/apache-troubleshoot-spark.md#how-do-i-configure-a-spark-application-by-using-livy-on-clusters)<br><br>[How do I configure a Spark application by using spark-submit on clusters?](spark/apache-troubleshoot-spark.md#how-do-i-configure-a-spark-application-by-using-spark-submit-on-clusters)<br><br>[What causes a Spark application OutOfMemoryError exception?](spark/apache-troubleshoot-spark.md#what-causes-a-spark-application-outofmemoryerror-exception)|
|![Storm](./media/hdinsight-troubleshoot-guide/STORM.png)<br>[Troubleshoot Storm](hdinsight-troubleshoot-STORM.md)|<br>[How do I access the Storm UI on a cluster?](storm/apache-troubleshoot-storm.md#how-do-i-access-the-storm-ui-on-a-cluster)<br><br>[How do I transfer Storm event hub spout checkpoint information from one topology to another?](storm/apache-troubleshoot-storm.md#how-do-i-transfer-storm-event-hub-spout-checkpoint-information-from-one-topology-to-another)<br><br>[How do I locate Storm binaries on a cluster?](storm/apache-troubleshoot-storm.md#how-do-i-locate-storm-binaries-on-a-cluster)<br><br>[How do I determine the deployment topology of a Storm cluster?](storm/apache-troubleshoot-storm.md#how-do-i-determine-the-deployment-topology-of-a-storm-cluster)<br><br>[How do I locate Storm event hub spout binaries for development?](storm/apache-troubleshoot-storm.md#how-do-i-locate-storm-event-hub-spout-binaries-for-development)<br><br>[How do I locate Storm Log4J configuration files on clusters?](storm/apache-troubleshoot-storm.md#how-do-i-locate-storm-log4j-configuration-files-on-clusters)|
|![YARN](./media/hdinsight-troubleshoot-guide/YARN.png)<br>[Troubleshoot YARN](hdinsight-troubleshoot-YARN.md)|<br>[How do I create a new YARN queue on a cluster?](hdinsight-troubleshoot-yarn.md#how-do-i-create-a-new-yarn-queue-on-a-cluster)<br><br>[How do I download YARN logs from a cluster?](hdinsight-troubleshoot-yarn.md#how-do-i-download-yarn-logs-from-a-cluster)|

## HDInsight troubleshooting resources

| For information about | See these articles |
| --- | --- |
| HDInsight on Linux and optimization | - [Information about using HDInsight on Linux](hdinsight-hadoop-linux-information.md)<br>- [Hadoop memory and performance troubleshooting](hdinsight-hadoop-stack-trace-error-messages.md)<br>- [Hive query performance](https://blogs.msdn.microsoft.com/bigdatasupport/2015/08/13/troubleshooting-hive-query-performance-in-hdinsight-hadoop-cluster/) |
| Logs and dumps | - [Access Hadoop YARN application logs on Linux](hdinsight-hadoop-access-yarn-app-logs-linux.md)<br>- [Enable heap dumps for Hadoop services on Linux](hdinsight-hadoop-collect-debug-heap-dump-linux.md)<br>- [Analyze HDInsight logs](hdinsight-debug-jobs.md)|
| Errors | - [Understand and resolve WebHCat errors](hdinsight-hadoop-templeton-webhcat-debug-errors.md)<br>- [Hive settings to fix OutofMemory error](hdinsight-hadoop-hive-out-of-memory-error-oom.md) |
| Tools | - [Use Ambari Views to debug Tez jobs](hdinsight-debug-ambari-tez-view.md)<br>- [Optimize Hive queries](hdinsight-hadoop-optimize-hive-query.md) |

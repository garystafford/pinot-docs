# Table of contents

* [Introduction](README.md)

## Basics

* [Concepts](basics/concepts.md)
* [Architecture](basics/architecture.md)
* [Components](basics/components/README.md)
  * [Cluster](basics/components/cluster.md)
  * [Controller](basics/components/controller.md)
  * [Broker](basics/components/broker.md)
  * [Server](basics/components/server.md)
  * [Minion](basics/components/minion.md)
  * [Tenant](basics/components/tenant.md)
  * [Schema](basics/components/schema.md)
  * [Table](basics/components/table.md)
  * [Segment](basics/components/segment.md)
  * [Deep Store](basics/components/deep-store.md)
  * [Pinot Data Explorer](basics/components/exploring-pinot.md)
* [Getting Started](basics/getting-started/README.md)
  * [Running Pinot locally](basics/getting-started/running-pinot-locally.md)
  * [Running Pinot in Docker](basics/getting-started/running-pinot-in-docker.md)
  * [Quick Start Examples](basics/getting-started/quick-start.md)
  * [Running in Kubernetes](basics/getting-started/kubernetes-quickstart.md)
  * [Running on public clouds](basics/getting-started/public-cloud-examples/README.md)
    * [Running on Azure](basics/getting-started/public-cloud-examples/azure-quickstart.md)
    * [Running on GCP](basics/getting-started/public-cloud-examples/gcp-quickstart.md)
    * [Running on AWS](basics/getting-started/public-cloud-examples/aws-quickstart.md)
  * [Batch import example](basics/getting-started/pushing-your-data-to-pinot.md)
  * [Stream ingestion example](basics/getting-started/pushing-your-streaming-data-to-pinot.md)
  * [HDFS as Deep Storage](basics/getting-started/hdfs-as-deepstorage.md)
  * [Troubleshooting Pinot](basics/getting-started/troubleshooting-pinot.md)
  * [Frequently Asked Questions (FAQs)](basics/getting-started/frequent-questions/README.md)
    * [General](basics/getting-started/frequent-questions/genaral.md)
    * [Pinot On Kubernetes FAQ](basics/getting-started/frequent-questions/pinot-on-kubernetes-faq.md)
    * [Ingestion FAQ](basics/getting-started/frequent-questions/ingestion-faq.md)
    * [Query FAQ](basics/getting-started/frequent-questions/query-faq.md)
    * [Operations FAQ](basics/getting-started/frequent-questions/operations-faq.md)
* [Import Data](basics/data-import/README.md)
  * [From Query Console](basics/data-import/from-query-console.md)
  * [Batch Ingestion](basics/data-import/batch-ingestion/README.md)
    * [Spark](basics/data-import/batch-ingestion/spark.md)
    * [Hadoop](basics/data-import/batch-ingestion/hadoop.md)
    * [Backfill Data](basics/data-import/batch-ingestion/backfill-data.md)
    * [Dimension Table](basics/data-import/batch-ingestion/dim-table.md)
  * [Stream ingestion](basics/data-import/pinot-stream-ingestion/README.md)
    * [Apache Kafka](basics/data-import/pinot-stream-ingestion/import-from-apache-kafka.md)
    * [Amazon Kinesis](basics/data-import/pinot-stream-ingestion/amazon-kinesis.md)
    * [Apache Pulsar](basics/data-import/pinot-stream-ingestion/apache-pulsar.md)
  * [Stream Ingestion with Upsert](basics/data-import/upsert.md)
  * [Stream Ingestion with Dedup](basics/data-import/dedup.md)
  * [File Systems](basics/data-import/pinot-file-system/README.md)
    * [Amazon S3](basics/data-import/pinot-file-system/amazon-s3.md)
    * [Azure Data Lake Storage](basics/data-import/pinot-file-system/import-from-adls-azure.md)
    * [HDFS](basics/data-import/pinot-file-system/import-from-hdfs.md)
    * [Google Cloud Storage](basics/data-import/pinot-file-system/import-from-gcp.md)
  * [Input formats](basics/data-import/pinot-input-formats.md)
  * [Complex Type (Array, Map) Handling](basics/data-import/complex-type.md)
* [Indexing](basics/indexing/README.md)
  * [Forward Index](basics/indexing/forward-index.md)
  * [Inverted Index](basics/indexing/inverted-index.md)
  * [Star-Tree Index](basics/indexing/star-tree-index.md)
  * [Bloom Filter](basics/indexing/bloom-filter.md)
  * [Range Index](basics/indexing/range-index.md)
  * [Text search support](basics/indexing/text-search-support.md)
  * [JSON Index](basics/indexing/json-index.md)
  * [Geospatial](basics/indexing/geospatial-support.md)
  * [Timestamp Index](basics/indexing/timestamp-index.md)
* [Releases](basics/releases/README.md)
  * [0.10.0](basics/releases/0.10.0.md)
  * [0.9.3](basics/releases/0.9.3.md)
  * [0.9.2](basics/releases/0.9.2.md)
  * [0.9.1](basics/releases/0.9.1.md)
  * [0.9.0](basics/releases/0.9.0.md)
  * [0.8.0](basics/releases/0.8.0.md)
  * [0.7.1](basics/releases/0.7.1.md)
  * [0.6.0](basics/releases/0.6.0.md)
  * [0.5.0](basics/releases/0.5.0.md)
  * [0.4.0](basics/releases/0.4.0.md)
  * [0.3.0](basics/releases/0.3.0.md)
  * [0.2.0](basics/releases/0.2.0.md)
  * [0.1.0](basics/releases/1.0.md)
* [Recipes](basics/recipes/README.md)
  * [GitHub Events Stream](basics/recipes/github-events-stream.md)

## For Users <a href="#users" id="users"></a>

* [Query](users/user-guide-query/README.md)
  * [Querying Pinot](users/user-guide-query/querying-pinot.md)
  * [Aggregation Functions](users/user-guide-query/supported-aggregations.md)
  * [Transformation Functions](users/user-guide-query/supported-transformations.md)
  * [User-Defined Functions (UDFs)](users/user-guide-query/scalar-functions.md)
  * [Grouping Algorithm](users/user-guide-query/grouping-algorithm.md)
  * [Query Options](users/user-guide-query/query-options.md)
  * [Cardinality Estimation](users/user-guide-query/how-to-handle-unique-counting.md)
  * [Lookup UDF Join](users/user-guide-query/lookup-udf-join.md)
  * [Querying JSON data](users/user-guide-query/json-queries.md)
  * [Filtering with IdSet](users/user-guide-query/filtering-with-idset.md)
  * [Explain Plan](users/user-guide-query/explain-plan.md)
  * [GapFill Function For Time-Series Dataset](users/user-guide-query/gap-fill-functions.md)
* [APIs](users/api/README.md)
  * [Broker Query API](users/api/querying-pinot-using-standard-sql/README.md)
    * [Query Response Format](users/api/querying-pinot-using-standard-sql/response-format.md)
  * [Controller Admin API](users/api/pinot-rest-admin-interface.md)
* [External Clients](users/clients/README.md)
  * [JDBC](users/clients/jdbc.md)
  * [Java](users/clients/java.md)
  * [Python](users/clients/python.md)
  * [Golang](users/clients/golang.md)
* [Tutorials](users/tutorials/README.md)
  * [Use OSS as Deep Storage for Pinot](users/tutorials/use-oss-as-deep-storage-for-pinot.md)
  * [Ingest Parquet Files from S3 Using Spark](users/tutorials/ingest-parquet-files-from-s3-using-spark.md)
  * [Creating Pinot Segments](users/tutorials/create-pinot-segments.md)
  * [Use S3 as Deep Storage for Pinot](users/tutorials/use-s3-as-deep-store-for-pinot.md)
  * [Use S3 and Pinot in Docker](users/tutorials/use-s3-and-pinot-in-docker.md)
  * [Batch Data Ingestion In Practice](users/tutorials/batch-data-ingestion-in-practice.md)
  * [Schema Evolution](users/tutorials/schema-evolution.md)

## For Developers <a href="#developers" id="developers"></a>

* [Basics](developers/developers-and-contributors/README.md)
  * [Extending Pinot](developers/developers-and-contributors/extending-pinot/README.md)
    * [Writing Custom Aggregation Function](developers/developers-and-contributors/extending-pinot/custom-aggregation-function.md)
    * [Segment Fetchers](developers/developers-and-contributors/extending-pinot/segment-fetchers.md)
  * [Contribution Guidelines](developers/developers-and-contributors/contribution-guidelines.md)
  * [Code Setup](developers/developers-and-contributors/code-setup.md)
  * [Code Modules and Organization](developers/developers-and-contributors/code-modules-and-organization.md)
  * [Update Documentation](developers/developers-and-contributors/update-document.md)
* [Advanced](developers/advanced/README.md)
  * [Data Ingestion Overview](developers/advanced/data-ingestion.md)
  * [Ingestion Aggregations](developers/advanced/ingestion-level-aggregations.md)
  * [Ingestion Transformations](developers/advanced/ingestion-level-transformations.md)
  * [Null Value Support](developers/advanced/null-value-support.md)
  * [Advanced Pinot Setup](developers/advanced/advanced-pinot-setup.md)
* [Plugins](developers/plugin-architecture/README.md)
  * [Write Custom Plugins](developers/plugin-architecture/write-custom-plugins/README.md)
    * [Input Format Plugin](developers/plugin-architecture/write-custom-plugins/record-reader.md)
    * [Filesystem Plugin](developers/plugin-architecture/write-custom-plugins/pluggable-storage.md)
    * [Batch Segment Fetcher Plugin](developers/plugin-architecture/write-custom-plugins/write-your-batch.md)
    * [Stream Ingestion Plugin](developers/plugin-architecture/write-custom-plugins/write-your-stream.md)
* [Design Documents](developers/design-documents/README.md)
  * [Segment Writer API](developers/design-documents/segment-writer-api.md)

## For Operators <a href="#operators" id="operators"></a>

* [Deployment and Monitoring](operators/operating-pinot/README.md)
  * [Setup cluster](operators/operating-pinot/setup-cluster.md)
  * [Setup table](operators/operating-pinot/setup-table.md)
  * [Setup ingestion](operators/operating-pinot/setup-ingestion.md)
  * [Decoupling Controller from the Data Path](operators/operating-pinot/decoupling-controller-from-the-data-path.md)
  * [Segment Assignment](operators/operating-pinot/segment-assignment.md)
  * [Instance Assignment](operators/operating-pinot/instance-assignment.md)
  * [Rebalance](operators/operating-pinot/rebalance/README.md)
    * [Rebalance Servers](operators/operating-pinot/rebalance/rebalance-servers.md)
    * [Rebalance Brokers](operators/operating-pinot/rebalance/rebalance-brokers.md)
  * [Tiered Storage](operators/operating-pinot/tiered-storage.md)
  * [Pinot managed Offline flows](operators/operating-pinot/pinot-managed-offline-flows.md)
  * [Minion merge rollup task](operators/operating-pinot/minion-merge-rollup-task.md)
  * [Access Control](operators/operating-pinot/access-control.md)
  * [Monitoring](operators/operating-pinot/monitoring.md)
  * [Tuning](operators/operating-pinot/tuning/README.md)
    * [Realtime](operators/operating-pinot/tuning/realtime.md)
    * [Routing](operators/operating-pinot/tuning/routing.md)
  * [Upgrading Pinot with confidence](operators/operating-pinot/upgrading-pinot-cluster.md)
* [Command-Line Interface (CLI)](operators/cli.md)
* [Configuration Recommendation Engine](operators/configuration-recommendation-engine.md)
* [Tutorials](operators/tutorials/README.md)
  * [Authentication, Authorization, and ACLs](operators/tutorials/authentication-authorization-and-acls.md)
  * [Configuring TLS/SSL](operators/tutorials/configuring-tls-ssl.md)
  * [Build Docker Images](operators/tutorials/build-docker-images.md)
  * [Running Pinot in Production](operators/tutorials/running-pinot-in-production.md)
  * [Kubernetes Deployment](operators/tutorials/deployment-pinot-on-kubernetes.md)
  * [Amazon EKS (Kafka)](operators/tutorials/non-eks-to-eks.md)
  * [Amazon MSK (Kafka)](operators/tutorials/how-to-connect-pinot-with-amazon-managed-streaming-for-apache-kafka-amazon-msk.md)
  * [Monitor Pinot using Prometheus and Grafana](operators/tutorials/monitor-pinot-using-prometheus-and-grafana.md)
  * [Performance Optimization Configurations](operators/tutorials/performance-optimization-configurations.md)

## Configuration Reference

* [Cluster](configuration-reference/cluster.md)
* [Controller](configuration-reference/controller.md)
* [Broker](configuration-reference/broker.md)
* [Server](configuration-reference/server.md)
* [Table](configuration-reference/table.md)
* [Schema](configuration-reference/schema.md)
* [Ingestion Job Spec](configuration-reference/job-specification.md)
* [Monitoring Metrics](configuration-reference/monitoring-metrics.md)
* [Functions](configuration-reference/functions/README.md)
  * [ABS](configuration-reference/functions/abs.md)
  * [ADD](configuration-reference/functions/add.md)
  * [arrayConcatInt](configuration-reference/functions/arrayconcatint.md)
  * [arrayConcatString](configuration-reference/functions/arrayconcatstring.md)
  * [arrayContainsInt](configuration-reference/functions/arraycontainsint.md)
  * [arrayContainsString](configuration-reference/functions/arraycontainsstring.md)
  * [arrayDistinctString](configuration-reference/functions/arraydistinctstring.md)
  * [arrayDistinctInt](configuration-reference/functions/arraydistinctint.md)
  * [arrayIndexOfInt](configuration-reference/functions/arrayindexofint.md)
  * [arrayIndexOfString](configuration-reference/functions/arrayindexofstring.md)
  * [ARRAYLENGTH](configuration-reference/functions/arraylength.md)
  * [arrayRemoveInt](configuration-reference/functions/arrayremoveint.md)
  * [arrayRemoveString](configuration-reference/functions/arrayremovestring.md)
  * [arrayReverseInt](configuration-reference/functions/arrayreverseint.md)
  * [arrayReverseString](configuration-reference/functions/arrayreversestring.md)
  * [arraySliceInt](configuration-reference/functions/arraysliceint.md)
  * [arraySliceString](configuration-reference/functions/arrayslicestring.md)
  * [arraySortInt](configuration-reference/functions/arraysortint.md)
  * [arraySortString](configuration-reference/functions/arraysortstring.md)
  * [arrayUnionInt](configuration-reference/functions/arrayunionint.md)
  * [arrayUnionString](configuration-reference/functions/arrayunionstring.md)
  * [AVGMV](configuration-reference/functions/avgmv.md)
  * [ceil](configuration-reference/functions/ceil.md)
  * [CHR](configuration-reference/functions/chr.md)
  * [codepoint](configuration-reference/functions/codepoint.md)
  * [concat](configuration-reference/functions/concat.md)
  * [count](configuration-reference/functions/count.md)
  * [COUNTMV](configuration-reference/functions/countmv.md)
  * [day](configuration-reference/functions/day.md)
  * [dayOfWeek](configuration-reference/functions/dayofweek.md)
  * [dayOfYear](configuration-reference/functions/dayofyear.md)
  * [DISTINCT](configuration-reference/functions/distinct.md)
  * [DISTINCTCOUNT](configuration-reference/functions/distinctcount.md)
  * [DISTINCTCOUNTBITMAP](configuration-reference/functions/distinctcountbitmap.md)
  * [DISTINCTCOUNTBITMAPMV](configuration-reference/functions/distinctcountbitmapmv.md)
  * [DISTINCTCOUNTHLL](configuration-reference/functions/distinctcounthll.md)
  * [DISTINCTCOUNTHLLMV](configuration-reference/functions/distinctcounthllmv.md)
  * [DISTINCTCOUNTMV](configuration-reference/functions/distinctcountmv.md)
  * [DISTINCTCOUNTRAWHLL](configuration-reference/functions/distinctcountrawhll.md)
  * [DISTINCTCOUNTRAWHLLMV](configuration-reference/functions/distinctcountrawhllmv.md)
  * [DISTINCTCOUNTRAWTHETASKETCH](configuration-reference/functions/distinctcountrawthetasketch.md)
  * [DISTINCTCOUNTTHETASKETCH](configuration-reference/functions/distinctcountthetasketch.md)
  * [DIV](configuration-reference/functions/div.md)
  * [DATETIMECONVERT](configuration-reference/functions/datetimeconvert.md)
  * [DATETRUNC](configuration-reference/functions/datetrunc.md)
  * [exp](configuration-reference/functions/exp.md)
  * [FLOOR](configuration-reference/functions/floor.md)
  * [FromDateTime](configuration-reference/functions/fromdatetime.md)
  * [FromEpoch](configuration-reference/functions/fromepoch.md)
  * [FromEpochBucket](configuration-reference/functions/fromepochbucket.md)
  * [Histogram](configuration-reference/functions/histogram.md)
  * [hour](configuration-reference/functions/hour.md)
  * [JSONFORMAT](configuration-reference/functions/jsonformat.md)
  * [JSONPATH](configuration-reference/functions/jsonpath.md)
  * [JSONPATHARRAY](configuration-reference/functions/jsonpatharray.md)
  * [JSONPATHARRAYDEFAULTEMPTY](configuration-reference/functions/jsonpatharraydefaultempty.md)
  * [JSONPATHDOUBLE](configuration-reference/functions/jsonpathdouble.md)
  * [JSONPATHLONG](configuration-reference/functions/jsonpathlong.md)
  * [JSONPATHSTRING](configuration-reference/functions/jsonpathstring.md)
  * [jsonextractkey](configuration-reference/functions/jsonextractkey.md)
  * [jsonextractscalar](configuration-reference/functions/jsonextractscalar.md)
  * [length](configuration-reference/functions/length.md)
  * [ln](configuration-reference/functions/ln.md)
  * [lower](configuration-reference/functions/lower.md)
  * [lpad](configuration-reference/functions/lpad.md)
  * [ltrim](configuration-reference/functions/ltrim.md)
  * [max](configuration-reference/functions/max.md)
  * [MAXMV](configuration-reference/functions/maxmv.md)
  * [MD5](configuration-reference/functions/md5.md)
  * [millisecond](configuration-reference/functions/millisecond.md)
  * [min](configuration-reference/functions/min.md)
  * [minmaxrange](configuration-reference/functions/minmaxrange.md)
  * [MINMAXRANGEMV](configuration-reference/functions/minmaxrangemv.md)
  * [MINMV](configuration-reference/functions/minmv.md)
  * [minute](configuration-reference/functions/minute.md)
  * [MOD](configuration-reference/functions/mod.md)
  * [mode](configuration-reference/functions/mode.md)
  * [month](configuration-reference/functions/month.md)
  * [mult](configuration-reference/functions/mult.md)
  * [now](configuration-reference/functions/now.md)
  * [percentile](configuration-reference/functions/percentile.md)
  * [percentileest](configuration-reference/functions/percentileest.md)
  * [percentileestmv](configuration-reference/functions/percentileestmv.md)
  * [percentilemv](configuration-reference/functions/percentilemv.md)
  * [percentiletdigest](configuration-reference/functions/percentiletdigest.md)
  * [percentiletdigestmv](configuration-reference/functions/percentiletdigestmv.md)
  * [quarter](configuration-reference/functions/quarter.md)
  * [regexpExtract](configuration-reference/functions/regexpextract.md)
  * [regexpReplace](configuration-reference/functions/regexpreplace.md)
  * [remove](configuration-reference/functions/remove.md)
  * [replace](configuration-reference/functions/replace.md)
  * [reverse](configuration-reference/functions/reverse.md)
  * [round](configuration-reference/functions/round.md)
  * [rpad](configuration-reference/functions/rpad.md)
  * [rtrim](configuration-reference/functions/rtrim.md)
  * [second](configuration-reference/functions/second.md)
  * [SEGMENTPARTITIONEDDISTINCTCOUNT](configuration-reference/functions/segmentpartitioneddistinctcount.md)
  * [sha](configuration-reference/functions/sha.md)
  * [sha256](configuration-reference/functions/sha256.md)
  * [sha512](configuration-reference/functions/sha512.md)
  * [sqrt](configuration-reference/functions/sqrt.md)
  * [startswith](configuration-reference/functions/startswith.md)
  * [ST\_AsBinary](configuration-reference/functions/stasbinary.md)
  * [ST\_AsText](configuration-reference/functions/stastext.md)
  * [ST\_Contains](configuration-reference/functions/stcontains.md)
  * [ST\_Distance](configuration-reference/functions/stdistance.md)
  * [ST\_GeogFromText](configuration-reference/functions/stgeogfromtext.md)
  * [ST\_GeogFromWKB](configuration-reference/functions/stgeogfromwkb.md)
  * [ST\_GeometryType](configuration-reference/functions/stgeometrytype.md)
  * [ST\_GeomFromText](configuration-reference/functions/stgeomfromtext.md)
  * [ST\_GeomFromWKB](configuration-reference/functions/stgeomfromwkb.md)
  * [STPOINT](configuration-reference/functions/stpoint.md)
  * [ST\_Polygon](configuration-reference/functions/stpolygon.md)
  * [strpos](configuration-reference/functions/strpos.md)
  * [ST\_Union](configuration-reference/functions/stunion.md)
  * [SUB](configuration-reference/functions/sub.md)
  * [substr](configuration-reference/functions/substr.md)
  * [sum](configuration-reference/functions/sum.md)
  * [summv](configuration-reference/functions/summv.md)
  * [TIMECONVERT](configuration-reference/functions/timeconvert.md)
  * [timezoneHour](configuration-reference/functions/timezonehour.md)
  * [timezoneMinute](configuration-reference/functions/timezoneminute.md)
  * [ToDateTime](configuration-reference/functions/todatetime.md)
  * [ToEpoch](configuration-reference/functions/toepoch.md)
  * [ToEpochBucket](configuration-reference/functions/toepochbucket.md)
  * [ToEpochRounded](configuration-reference/functions/toepochrounded.md)
  * [TOJSONMAPSTR](configuration-reference/functions/tojsonmapstr.md)
  * [toGeometry](configuration-reference/functions/togeometry.md)
  * [toSphericalGeography](configuration-reference/functions/tosphericalgeography.md)
  * [trim](configuration-reference/functions/trim.md)
  * [upper](configuration-reference/functions/upper.md)
  * [Url](configuration-reference/functions/url.md)
  * [VALUEIN](configuration-reference/functions/valuein.md)
  * [week](configuration-reference/functions/week.md)
  * [year](configuration-reference/functions/year.md)
  * [yearOfWeek](configuration-reference/functions/yearofweek.md)

## RESOURCES <a href="#community-1" id="community-1"></a>

* [Community](community-1/community.md)
* [Team](community-1/team.md)
* [Blogs](community-1/blogs.md)
* [Presentations](community-1/blogs-and-presentations.md)
* [Videos](community-1/videos.md)

## Integrations

* [Tableau](integrations/tableau.md)
* [Trino](integrations/trino.md)
* [ThirdEye](integrations/thirdeye.md)
* [Superset](integrations/superset.md)
* [Presto](integrations/presto.md)